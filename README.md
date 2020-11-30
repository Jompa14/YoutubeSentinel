# YoutubeSentinel

Em 2019 veio a público a informação de que o Youtube estava sendo usado por pedófilos que encontravam na plataforma vídeos de crianças. 
Para mais detalhes confira esta [notícia](https://mashable.com/article/youtube-wakeup-child-exploitation-explained/).

Este projeto tem como objetivo encontrar estes vídeos (muitos ainda estão no ar), com o intuito de denunciá-los.
A ideia é que através da denúncia massiva destes vídeos, o Youtube os remova de sua plataforma.
Para isso serão necessários 3 Robôs:
### **WebScrapping**
+ Web Scrapping é uma técnica para fazer um robô navegar por páginas web.
+ No nosso caso, o Robô navega entre os vídeos do Youtube.
+ Nosso alvo são as miniaturaas (capas dos vídeos).
### **Inteligência Artificial**
+ Para analizar as miniaturas temos uma IA extraída do [Teachable Machine](https://teachablemachine.withgoogle.com/).
+ A IA vai identificar se temos uma criança na miniatura ou não. Se tiver, vamos analisar se ela está em uma situação passivel de ser sexualizada.
+ Caso as duas condições anteriores sejam detectadas faremos a denúncia do vídeo.
### **Automatiza Postagens**
+ Os links dos vídeos impróprios serão postados em uma conta especial no Twitter.
+ Com o link do vídeo os usuários poderão denunciar massivamente os vídeos.
