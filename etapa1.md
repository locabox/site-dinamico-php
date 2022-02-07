# Etapa 1

## Criar uma Página Estática
Feito as configurações iniciais, é necessário criar uma página estática HTML chamada “index.html”. Para criar este arquivo, utilize um editor de texto de sua preferência (Sublime, Notepad ++, entre outros). O importante é lembrar de salvar o arquivo com a extensão .html.

Lembrando, este arquivo deve estar contido dentro da pasta pública do servidor como uma pasta para o seu projeto  
**(se for Xampp, o nome da pasta pública é “htdocs”)**.

> Feito isso, sempre que você acessar a sua página pelo seu navegador, digitando “http://localhost/pagina-dinamica-php”, o arquivo “index.html” que você acabou de criar será lido automaticamente.

Em seguida, para efeitos de visualização da página, podemos adicionar um estilo básico em nosso documento HTML. Com isso, teremos uma página visualmente mais atraente e organizada.

Entretanto, como o foco não é explorar estilos CSS, utilizaremos uma biblioteca pronta que possui a estilização já desenvolvida e só precisaremos incluir as classes da biblioteca em nosso HTML. Faremos isso com o Bootstrap:

Adicione essa linha de codigo entre as tags head e /head:
~~~php
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css" integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn" crossorigin="anonymous">
~~~

e antes do /body acrescente:
~~~php
<script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.min.js" integrity="sha384-VHvPCCyXqtD5DqJeNxl2dtTyhF78xXNXdkwX1CZeRusQfRKp+tA7hAShOK/B/fQ2" crossorigin="anonymous"></script>
~~~

## Integrar o PHP com HTML
Antes de tudo, você deve modificar o nome do nosso arquivo de **index.html** para **index.php**.

Assim, faremos com que o servidor reconheça que estamos trabalhando com a linguagem PHP e, portanto, consiga interpretar os scripts criados para serem executados. O servidor continuará executando o arquivo index.php em primeiro lugar, quando acessado http://localhost/pagina-dinamica-php.

Com esta pequena modificação **(de .html para .php)**, agora é possível escrever scripts .php e, assim, manipular os elementos HTML de acordo com a necessidade. Além disso, podemos criar e imprimir variáveis, fazer repetições, verificações de verdadeiro e falso e outras rotinas de programação.

Para criar um script PHP, devemos usar os delimitadores <?php para abrir e ?> para fechar

## Agora mãos a obra
- Contudo que foi explicado anteriormente, contrua um formulário onde você possa receber o nome de um produto.
- Em seguida imprima na tela o nome desse produto com personalizações que dezejar incluindo a cor vermelha para o texto.

## Concluiu essa etapa? siga para a proxima:
**[ETAPA 2](https://github.com/locabox/site-dinamico-php/blob/main/etapa2.md)**
