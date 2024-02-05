# Gamer_Project 🎮
Você foi convidado para desenvolver uma aplicação web que terá
o intuito de efetuar a organização de competições de e-sports.
Um dos fatores importantes para o desempenho dos jogadores é seu estado físico,
pensando nisso solicitamos que efetue também a criação de um dispositivo que
alerte os jogadores que estão a mais de 2 horas sentados ininterruptamente a se
movimentarem e fazerem uma pausa.

## Projeto integrado à estrutura MVC
O **Modelo-Visão-Controlador** (MVC) é um padrão de arquitetura de software amplamente utilizado na criação de aplicativos de software, especialmente em desenvolvimento web. Ele separa o aplicativo em três componentes principais, cada um com uma responsabilidade específica.
##
**Aqui estão os conceitos-chave do padrão MVC:**

**• Modelo (Model):**

O Modelo representa a **camada de dados** e regras de negócios do aplicativo.
Ele é responsável por acessar, manipular e armazenar os dados do aplicativo.
Os modelos contêm a lógica que define como os dados são recuperados e atualizados no banco de dados ou em qualquer outra fonte de dados.
**Eles não estão cientes da interface do usuário ou da lógica de apresentação.**

**• Visão (View):**

A Visão é responsável pela apresentação da **interface do usuário.**
Ela exibe os dados do Modelo aos usuários e permite que eles interajam com o aplicativo.
**As Views geralmente são passivas e não contêm lógica de negócios significativa;** em vez disso, elas refletem o estado atual do Modelo.
Uma aplicação pode ter várias Views para apresentar os dados de diferentes maneiras.

**• Controlador (Controller):**

O Controlador atua como um **intermediário entre o Modelo e a Visão.**
Ele recebe entradas do usuário **(como cliques em botões ou requisições HTTP)** e coordena as ações apropriadas no Modelo ou na Visão.
A lógica de controle reside no Controlador, o que significa que ele decide como responder a eventos ou ações do usuário.
**O Controlador não realiza operações de manipulação de dados diretamente, deixando essa responsabilidade para o Modelo.**
##
O MVC é amplamente usado em **frameworks de desenvolvimento web**, como o **ASP.NET MVC (para .NET)**, o **Ruby on Rails (para Ruby)**, o **Django (para Python)** e outros, mas também pode ser aplicado em aplicativos de desktop e móveis. É uma abordagem sólida para criar aplicativos organizados e de fácil manutenção.


