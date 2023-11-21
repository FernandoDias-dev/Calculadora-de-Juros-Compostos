# Calculadora-de-Juros-Compostos

Documentação do Projeto: Calculadora de Juros Compostos
Este projeto consiste em uma Calculadora de Juros Compostos desenvolvida utilizando HTML, CSS e JavaScript. O objetivo é permitir que o usuário calcule o montante final após um período de investimento, levando em consideração o valor inicial, a taxa de juros mensal e o tempo de rendimento.

Estrutura do Projeto
HTML (index.html)
<!DOCTYPE html>: Declaração do tipo de documento.
<head>: Contém metadados, como a codificação do documento, a viewport e o link para a folha de estilos.
<body>: Corpo da página, onde estão localizados os elementos visíveis para o usuário.
<main>: Contém o conteúdo principal da aplicação.
<div id="calculator">: A área da calculadora, com campos de entrada e botão de cálculo.
<h2>: Título da calculadora.
<div id="input_box">: Contém os campos de entrada para valor inicial, taxa de juros e tempo de rendimento.
<div id="result">: Exibe o resultado do cálculo.
<span id="total">: Mostra o resultado em formato monetário.
CSS (style.css)
@import: Importa a fonte Poppins do Google Fonts.
:root: Define variáveis, como o gradiente linear utilizado.
*: Estilização global para remoção de margens e preenchimento padrão.
#container: Estilo para o contêiner principal da página.
#calculator: Estilo para a área da calculadora, incluindo fundo, sombra e espaçamento.
#calculator h2 e #calculator h2::before: Estilo para o título da calculadora e uma linha decorativa.
#input_box e .input-field: Estilos para os campos de entrada.
#result e #total: Estilos para a exibição do resultado.
#calculate: Estilo para o botão de cálculo.
@media screen and (min-width: 768px): Media query para ajustar o tamanho máximo da calculadora em telas maiores.
JavaScript (script.js)
document.getElementById("calculate").addEventListener("click", ...): Adiciona um ouvinte de evento para o botão de cálculo.
Cálculo: Obtém os valores dos campos de entrada, realiza o cálculo de juros compostos e exibe o resultado formatado na tela.
Responsividade
O projeto é responsivo, adaptando-se a diferentes tamanhos de tela. Isso é alcançado por meio de unidades relativas no CSS e da utilização de uma media query para ajustar o layout em telas maiores.

Como Utilizar
Abra o arquivo index.html em um navegador da web.
Insira o valor inicial, a taxa de juros mensal e o tempo de rendimento nos campos correspondentes.
Clique no botão "Calcular" para obter o resultado dos juros compostos.
Sinta-se à vontade para explorar, modificar e contribuir para aprimorar este projeto!
 
