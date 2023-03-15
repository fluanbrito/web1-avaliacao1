## 🧾 Descrição

Avaliação 1 de Desenvolvimento WEB I - 13/03/2023

- **Q1:**  O código é uma página HTML com um formulário de senha que possui uma caixa de entrada de senha e um botão de login. Ele também inclui um script JavaScript que verifica se a senha digitada é "senha123" e adiciona uma classe CSS "yellow-bg" à caixa de senha se a senha tiver pelo menos um número e tiver um comprimento mínimo de seis caracteres. Além disso, o script JavaScript também adiciona um manipulador de eventos para o evento "keyup" na caixa de senha que chama a função "checkPasswordStrength()" sempre que uma tecla é pressionada na caixa de senha.

- **Q2:** Página HTML que contém um campo de texto em que o usuário pode digitar e um contador de caracteres que atualiza em tempo real conforme o usuário digita. O CSS da página alinha o conteúdo no centro e define estilos para a fonte, tamanho e cor do texto. O JavaScript define uma função que é chamada quando o usuário digita no campo de texto e atualiza o valor do contador de caracteres exibido na página.

- **Q3:** Página HTML com um título, estilo CSS e JavaScript embutido. A página apresenta um controle deslizante (slider) que permite ao usuário ajustar o tamanho das imagens apresentadas na página. O valor do controle deslizante é exibido em um elemento de texto ao lado do controle deslizante. O código JavaScript vincula um evento de entrada (input) ao controle deslizante para atualizar o tamanho das imagens em tempo real à medida que o usuário move o controle deslizante. As imagens são exibidas em um contêiner e possuem uma sombra e um formato arredondado.

<h1>

## ⚙️ Estrutura

## Q1

### Q1.html
- A estrutura do código começa com a declaração do tipo de documento HTML ```<!DOCTYPE html>```, seguido pela tag ```<html>```, que envolve todo o conteúdo da página. Em seguida, há uma seção ```<head>```, que contém informações de metadados, como o título da página e a folha de estilo CSS incorporada.

- A seção ```<body>``` contém o conteúdo visível da página, incluindo uma caixa de senha ```<div>``` que contém um campo de entrada de senha ```<input>``` e um botão de envio ```<button>```.

- O script JavaScript é incluído na página com a tag ```<script>``` no final da seção ```<body>```. Ele contém duas funções: checkPassword() verifica se a senha inserida corresponde à senha correta, e checkPasswordStrength() verifica se a senha inserida atende a requisitos mínimos de força da senha.

<h1>

## Q2

### Q2.html

- O cabeçalho da página contém o título e o conjunto de caracteres usados. O corpo da página possui uma div para exibir o contador de caracteres e uma textarea para inserção de texto.

- O CSS é usado para definir a aparência dos elementos da página, incluindo fonte, cor de fundo e tamanho da caixa de texto.

- O script JavaScript é responsável por atualizar o contador de caracteres conforme o usuário digita no campo de texto. Ele obtém o elemento da caixa de texto e a div do contador de caracteres usando seus respectivos IDs e, em seguida, atualiza o texto dentro da div com o comprimento do texto na caixa de texto. A função countCharacters() é chamada sempre que o usuário digita no campo de texto, usando o evento onkeyup.

<h1>

## Q3

### Q3.html

- O código HTML define a estrutura básica da página, com uma seção head e uma seção body. Na seção head, é definido o título da página e um estilo CSS embutido. No body, há um cabeçalho h1, um container com um elemento input range e um valor associado, e um container com duas imagens.

- O estilo CSS é responsável por dar estilo à página. Ele define o tipo de fonte, a cor do texto, o alinhamento do texto, a cor de fundo e outros elementos visuais. Ele também define as propriedades do input range e das imagens, como tamanho, margem, borda e sombreamento.

- O código JavaScript é responsável por fazer as imagens mudarem de tamanho conforme o usuário move o slider. Ele primeiro pega o elemento input range e as imagens usando o método document.querySelector e document.querySelectorAll, respectivamente. Depois, adiciona um evento listener para o input range que atualiza o tamanho das imagens quando o usuário muda o valor do range. 
- O evento listener atualiza o tamanho das imagens definindo suas propriedades width e height em relação ao valor do range. Ele também atualiza o valor exibido abaixo do range com o valor atual do range. 

### 1.png
- Imagem de exemplo.
### 2.png
- Imagem de exemplo.
<h1>

## ✅ Resultado (Preview)
<br>

## Q1
![Q1](https://i.imgur.com/ogRuIT9.png)

<br>

## Q2
![Q2](https://i.imgur.com/P1UGqVQ.png)

<br>

## Q3
![Q3](https://i.imgur.com/N98RASV.png)

<br>

## 💻 Autor

- [@Luan Ferreira](https://github.com/fluanbrito)

<h1>

## 🚀 Sobre mim
Sou um grande entusiasta e apaixonado por tecnologia, empreendedorismo e inovação. Hoje, estou a cursar o curso de Sistema de Informação pelo Instituto Federal, faço uso profissionalmente de ferramentas e me aprofundo em temas como Marketing, Machine Learning AWS, Metodologias ágeis, Gestão de Projetos, Programação Web, Administração de Sistemas, Redes de computadores, entre outros.
