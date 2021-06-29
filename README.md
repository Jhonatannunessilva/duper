# Duper

Esse projeto foi feito com base no projeto do capitulo 19 do livro [Programming Elixir 1.6 - Functional |> Concurrent |> Pragmatic |> Fun](https://www.amazon.com.br/Programming-Elixir-1-6-Dave-Thomas/dp/1680502999), que tem como objetivo criar uma aplicação que irá listar todos os arquivos duplicados de um diretório.

![Imagem ilustrando o Diagrama de Sequência](./images/diagrama_de_sequencia.png)
Fonte: Imagem retirada do livro citado.

![Imagem ilustrando o Diagrama de Sequência](./images/diagrama_de_como_os_servers_estao_organizados.png)
Fonte: Imagem retirada do livro citado.

## Como Executar o Projeto

Clone o projeto, entre no diretório e então execute:

```shell
➜ mix run --no-halt
Results:

["./.elixir_ls/build/_test/lib/duper/.mix/compile.lock",
 "./.elixir_ls/build/_test/lib/dir_walker/.mix/compile.fetch",
 "./deps/dir_walker/.fetch", "./_build/dev/lib/duper/.mix/compile.lock",
 "./_build/dev/lib/dir_walker/.mix/compile.fetch"]
["./.elixir_ls/build/_test/lib/dir_walker/.mix/compile.elixir_scm",
 "./_build/dev/lib/dir_walker/.mix/compile.elixir_scm"]
...
```
