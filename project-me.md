# Definindo Layout

![[layout.gif]]
Acho que farei este layout de responsividade
já que nunca fiz isso antes. pode ser uma boa tentativa.

vamos começar fazendo o básico, vou usar display grid ( quem diria, eu acho mais fácil manter o display grid do que o flex)

- [x] Procurar layout ✅ 2024-01-23
- [x] Fazer o layout básico ✅ 2024-01-23
finalizado o layout padrão, eu aproveitei para brincar um pouco com o media, e tive que dar uma olhada breve na internet sobre como usar ele, pelo que eu entendi, o ***media*** se refere a um argumento geral, do tipo "okay, com o que estamos lidando aqui?" ai temos algumas opções que desconheço mas duas que entendi até agora, a primeria sendo ***screen*** que se expressa na tela do dispositivo em que se o página e o ***print*** que ao meu ver tem haver com impressão.. não sei necessita de mais pesquisa..

mas indo ao direto ponto que eu preciso é, ***screen***, onde aplica-se a regra de proporção da tela, em que podemos trabalhar o layout do site e adaptar ou deixar responsivo de acordo com o tamanho da tela de um dispositivo.. simplificando usando o screen podemos adaptar o site para tamanhos de telas de monitores, celulares e computador entre outros.

como fazer? simples usando o comando 
``` css
@media screen (max-with="pixels ou tamanho da tela horizontal do dispostivo"){
aqui aplicamos as regras do css normalmente como estivessemos escrevendo regras de css basicas, então podemos manipular as regras e deixar responsivo nosso site de acordo com necessidade do projeto.
}
```

apesar de ter entendido este conceito de forma leve, preciso ainda aprender novos jeitos mais "bonitos" de fazer algumas coisas no css para deixar além de responsivo, site atrativo.... sinceramente não sei não.