# Projeto Flexbox

Projeto para exemplificar utilização de flex box. Utilizando conceitos de display, justify content e responsividade.

## Tela

row
justify-content trabalha no eixo x
align-tems trabalha no eixo y

column
justify-content trabalha no eixo y
align-tems trabalha no eixo x

Visite a <a href="https://github.com/Daruedo/Flexbox/wiki" target="_blank">wiki</a>!


Quando colocamos display: flex em um elemento, o navegador passa a considerar esse elemento como um flex container, ou seja, cria todo aquele comportamento que vimos anteriormente no curso, os filhos ficam um do lado do outro e podemos aplicar propriedades para espaçá-los.

Os filhos de um flex container por sua vez também ganham um nome, são chamados de flex items.

Quando utilizamos flexbox temos que ficar atentos em quem colocamos as propriedades de espaçamento e distribuição do flex. Por exemplo, existem algumas propriedades que devem ser aplicadas à flex container e outras que devem ser aplicadas nos flex items.

container:

display: flex
flex-direction
justify-content
flex-wrap
flex-flow
align-items
align-content
flex item:

order
flex-grow
flex-shrink
flex-basis
flex
align-self