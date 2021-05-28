Os tres tipos de objetos no git

- Blob - metadados, tipo do objeto, tamanho, \0 e conteudo do arquivo.
- Tree - armazena e aponta para tipos de blob e commit diferentes.
- Commit - objeto que junta tudo, da sentido ao que esta fazendo.







Comandos git

- git init - inicializa um repositorio git na pasta em questao
- git commit - ???
- git commit -m - (msg) para adicionar comentario.
- git edge - ???
- git status - mostrar status dos objetos
- mv - comando de mover objetos
- git add * - adiciona todos os objetos para staged para depois fazer commit
- git add nomeArquivo - adiciona um objeto especifico
- git add . - adiciona todas as modificacoes ao repositorio
- cd - comando para entrar em objetos. ex: "cd receitas/"
- cd .. - comando para voltar um nivel. ex: "cd receitas/receitas doces" ~ cd .. "cd receitas/"
- sha1 - key aleatoria




				Tracked
	
	Untracked	Unmodified	Modified	Staged
	    |		     |		    | 		    |
	    |Adiciona arquivo ----------------------------->|	
	    |		     |Edit arq ---->|		    |
	    |		     |		    |"Stage" arq -->|
	    |<---- Remove arq|		    |		    |
	    |	             |<---------------------- Commit|


	Servidor
	   |
	Remote Repository.

Ambiente de desenvolvimento
	   | 
    Working Directory;
      Staging Area;
    Local Repository.