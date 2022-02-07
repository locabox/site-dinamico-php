## Site Dinâmico
Um website pode processar e executar tarefas utilizando linguagens de programação que servem como instrumento para responder à requisições de usuários e funções pré-programadas, manipulando os dados de entrada e saída de forma automática. Chamamos isso de um site dinâmico!

Neste caso, linguagens de programação são responsáveis por processar informações de formulários e URLs, controlar o fluxo da aplicação, gerenciar permissões de usuários e muitas outras funcionalidades.

## Site Estático
Já, um website estático possui toda a informação que deve ser exibida incluída e, posteriormente editada, diretamente nos seu código HTML. Esse tipo de abordagem é útil para a criação de websites que não necessitam de alterações frequentes.

Como exemplo, podemos citar: currículos online, portfólios ou websites institucionais que não dependam de gerenciamento de notícias.

## Prós e contras…
O principal benefício de um site estático é a flexibilidade de adaptação do conteúdo e facilidade no seu desenvolvimento:

- O conteúdo é fácil de adaptar porque não envolve funções complexas que utilizam linguagens de programação ou conexões com banco de dados;
- Já a facilidade de desenvolvimento se dá por ser possível desenvolvê-lo apenas com conhecimentos básicos de HTML e CSS.

Por outro lado, um site dinâmico traz a possibilidade de criar aplicações mais robustas e que possuem diversas funcionalidades:

- Essa abordagem gera mais custos pela complexidade de desenvolvimento e necessidade de padronização do conteúdo exibido, tendo em vista adaptá-lo às necessidades da linguagem de programação;
- A complexidade de desenvolvimento é recompensada, uma vez que sites dinâmicos atendem a qualquer tamanho de aplicação e não dependem do conhecimento técnico em programação, por parte do usuário, para editá-lo. Ou seja, com um site dinâmico é possível implementar um gerenciador de conteúdos que possibilita o usuário administrador a realizar todas as alterações necessárias através de uma interface amigável.

## Exemplos de sites dinâmicos:
Blogs, redes sociais, portais de conteúdo, sistemas bancários, serviços de e-mail, de pagamento, lojas virtuais e até o próprio site da Becode.

Enfim, qualquer site que precisa ser dinamicamente gerenciado, caso contrário, seria inviável realizar a manutenção do conteúdo de forma manual. Imagine se a cada nova postagem, um funcionário do Facebook tivesse que incluir o HTML e o CSS para aquele novo conteúdo? Difícil, se não impossível, certo? E o que seria o Facebook, se não uma interface amigável onde você (usuário administrador de sua conta) consegue realizar todas as alterações necessárias apenas apertando botões intuitivos? Ou seja, o Facebook é uma aplicação dinâmica!

## Criando Sites Dinâmicos
Dito isso, como podemos dar o primeiro passo rumo ao desenvolvimento de sites dinâmicos?

Basicamente, existem duas formas principais:

Scripts do lado do servidor (server-side) ou;
Scripts do lado do cliente (client-side).
Neste post, vamos dar atenção à primeira forma.

Sendo assim, o que precisamos fazer primeiro é definir qual linguagem de programação iremos utilizar. Entre as opções, temos diversas tecnologias que poderiam ser utilizadas para essa finalidade, entre elas: ASP, node.js, Perl, PHP, Ruby, JavaScript e muitas outras.

Neste post, vamos utilizar o PHP.
Contudo, com estudo e experiência, você poderá escolher a melhor opção para a sua necessidade ou projeto que você estiver envolvido.

## Configurações Iniciais
Pelo fato de o PHP ser uma linguagem de servidor, os scripts precisam estar necessariamente em um servidor. Isso significa que abrir o arquivo diretamente em sua máquina não trará resultado algum.

Por isso, se faz necessário o uso de uma ferramenta para “criar” um servidor local no seu computador, possibilitando testar suas páginas web sem depender de um servidor online. Felizmente, existem diversas ferramentas que possibilitam essa prática, entre elas, podemos instalar um servidor via Xampp, Wampp, EasyPHP e Mamp.

Neste post, iremos adotar o Xampp, pois o mesmo possui versões para Windows, Linux e OS. Contudo, sinta-se à vontade para testar outras ferramentas (desde que você já conheça a ferramenta e consiga acompanhar os próximos passos).

Caso você tenha optado pelo Xampp, instale a aplicação através desse **[link](https://www.apachefriends.org/pt_br/index.html)**.
![1](https://user-images.githubusercontent.com/51889513/152848404-cfd4a626-838b-4fab-88a7-eb72ded78b00.jpg)

Após instalado, procure pelo painel de controle do software, o “Control Panel”, conforme ilustração abaixo:
![2](https://user-images.githubusercontent.com/51889513/152848456-df008d37-9ae7-4170-9868-65a76105456d.png)

Clique no botão start, ao lado de “Apache”, assim você estará iniciando o seu servidor local (conforme imagem abaixo).
![3](https://user-images.githubusercontent.com/51889513/152848528-e3e5ca5b-7c5e-45fc-a18c-93dcde1e6c7b.png)

Após, crie uma pasta para o seu projeto e insira esta pasta dentro da pasta pública do servidor local. Em nosso exemplo, iremos criar uma pasta chamada “pagina-dinamica-php”.

No xampp, a pasta pública é chamada de “htdocs”, portanto, crie uma pasta chamada “pagina-dinamica-php”, dentro de “htdocs”.

## Partindo para a o desafio
**[ETAPA 1](https://github.com/locabox/site-dinamico-php/blob/main/etapa1.md)**
