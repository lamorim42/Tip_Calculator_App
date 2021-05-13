# Tip_Calculator_App
Nesse projeto trabalhamos um pouco mais a interação entre a MainActivity e layout construido com o activity_main.xml. Alem disso usamos o viewBinding para fazer as chamadas de elementos da UI diretamente pelo id sem precisar do método findViewById().
O Tip_Calculator é um app onde o usuario irá calcular a gorjeta com base no valor do serviço e como ele avaliou o serviço.

## Imagens do App:
<img src= "https://github.com/luishads/Tip_Calculator_App/blob/UI_Improve_main/TipCalculator_photo04.png" width="285px" height="500px"/> 


<h1>activity_main.xml</h1>
Esse layout apresenta vários elementos, são eles:
<ul>
  <li>EditText</li>
  <li>TextView</li>
  <li>RadioGroup</li>
  <li>RadioButton</li>
  <li>Switch</li>
  <li>Button</li>
</ul>

Veja em detalhes no arquivo <a href = "https://github.com/luishads/Tip_Calculator_App/blob/master/app/src/main/res/layout/activity_main.xml" target="_blank">activity_main.xml</a>.
Nesse layout podemos perceber muito bem definido o conceito de ViewGroup. <a href ="https://web.digitalinnovation.one/articles/entendendo-viewgoup-e-activity-com-o-app-dice_roller?back=%2Farticles&page=1&order=oldest">Veja mais sobre ViewGroup aqui</a>.

<h3>EditText</h3>
É onde o usuário coloca a informação do valor do serviço.

<h3>RadioGroup & RadioButton's</h3>
É onde o usuário avalia o serviço em incrível, bom ou ok.

<h3>Switch</h3>
É uma opção que o usuário tem de arredondar a conta.

<h1>MainActivity</h1>
Aqui é onde a "mágica" acontece. É onde está todo o comportamento do app, é onde está a lógica para o cálculo da gorjeta.
E é onde usamos o recurso viewBinding. Veja em detalhes no arquivo <a href = "https://github.com/luishads/Tip_Calculator_App/blob/master/app/src/main/java/com/example/tipcalculator/MainActivity.kt" target="_blank">MainActivity.kt</a>.
