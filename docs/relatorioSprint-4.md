<br id="topo">
 
<h1 align="center">Projeto IA - Quarta entrega</h1>

<p align="center">
    <a href="#mvp">MVP</a> | 
    <a href="#backlog">Backlog Sprint</a> |
    <a href="#DOR">DOR</a> |
    <a href="#dados">Dados para IA</a> |
    <a href="#entrega">Entrega(DOD)</a>
</p>
<span id="mvp">
 
<h1> :dart: MVP </h1>
<p align="justify">O MVP da última entrega é a inclusão de usuários no sistema, permitindo que haja um sistema de autenticação eficaz e também diferentes níveis de permissão. Além disso, uma documentação sobre o funcionamento total do sistema e instalação será entregue.</p>

<span id="backlog">

## 📃 Backlog da Sprint

| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito |
| :----: | :-------- | :-------- | :----: | :---: | :----: |
| 09 | Média | COMO administrador, QUERO QUE o sistema possua cadastro, listagem e edição de usuários, PARA QUE tenha a possibilidade de multiplos acessos  ao sistema. | 50 | 04 | RF-6 |
| 10 | Média | COMO administrador, QUERO QUE o sistema possua divisão de cargos de permissão, PARA QUE seja possível controlar o acesso a interface e a ações de cada usuário. | 40 | 04 | RF-6 |
| 11 | Baixa | COMO usuário, QUERO um processo de autenticação seguro PARA QUE eu possa acessar o sistema de forma protegida. | 40 | 04 | RF-1 |
| 12 | Baixa | COMO usuário, QUERO ter acesso a um manual detalhado que explique todas as funcionalidades e recursos do sistema, PARA QUE eu possa utilizá-lo de forma eficaz e aproveitar ao máximo suas capacidades. | 20 | 04 | RNF-1 |
| 13 | Baixa | COMO usuário, QUERO um guia passo a passo que me oriente na instalação e configuração do sistema, PARA QUE eu possa implantá-lo facilmente em meu ambiente de trabalho. | 20 | 04 | RNF-3 |

<span id="DOR"> 
  
## 📌 DOR

<p align="justify">

  ### 📄 User stories e Critérios de aceitação

US #9: COMO administrador, QUERO QUE o sistema possua cadastro, listagem e edição de usuários, PARA QUE tenha a possibilidade de multiplos acessos  ao sistema.

Critérios de aceitação:

- O sistema deve permitir que o administrador realize o cadastro de novos usuários, fornecendo informações como nome, e-mail e nível de acesso. 
- Ao cadastrar um usuário, o sistema deve enviar um e-mail com uma senha gerada a partir de caracteres aleatórios para que ela possa se autenticar.
- Os usuários cadastrados devem ser listados de forma clara e organizada, permitindo que o administrador visualize todas as contas de usuário registradas no sistema.
- O administrador deve ser capaz de editar as informações de usuários previamente cadastrados, possibilitando a atualização de dados conforme necessário.
- O administrador deve receber feedback imediato sobre o sucesso ou falha das operações de cadastro, listagem e edição de usuários.
- O sistema deve fornecer uma interface para que o usuário, após estar autenticado, possa trocar/atualizar sua senha.
- O sistema deve permitir que um usuário possa excluir/desativar outro usuário.
- O sistema deve bloquear a tentativa de um usuário tentar se excluir/desativar.


US #10 COMO administrador, QUERO QUE o sistema possua divisão de cargos de permissão, PARA QUE seja possível controlar o acesso a interface e a ações de cada usuário.

Critérios de aceitação:

- O sistema deve suportar diferentes níveis de acesso para os usuários, como administrador, gerente de segurança e segurança.
- O administrador deve ser capaz de realizar todas as operações de cadastros no sistema, além de ter acesso a todas as áreas e redzones.
- O gerente de segurança deve ser capaz de ter acesso as áreas vinculadas a ele e suas respectivas redzones, além de poder cadastrar seguranças e os vincular a determinadas redzones.
- O segurança deve ser capaz de ter acesso as redzones vinculadas, podendo visualizar as informações disponibilizadas

US #11 COMO usuário, QUERO um processo de autenticação seguro PARA QUE eu possa acessar o sistema de forma protegida.

Critérios de aceitação:

- O sistema deve fornecer um formulário de login seguro, onde os usuários possam inserir suas credenciais de acesso.
- As credenciais de acesso dos usuários, como e-mail e senha, devem ser armazenadas de forma segura no banco de dados do sistema.
- O sistema deve implementar um processo de autenticação robusto e seguro, utilizando técnicas como criptografia de senha e tokens de sessão.
- Os usuários devem ter a opção de recuperar suas senhas em caso de esquecimento, utilizando o e-mail cadastrado.
- O sistema deve solicitar que o usuário esteja autenticado no sistema para realizar as operações no sistema.

US #12 COMO usuário, QUERO ter acesso a um manual detalhado que explique todas as funcionalidades e recursos do sistema, PARA QUE eu possa utilizá-lo de forma eficaz e aproveitar ao máximo suas capacidades.

Critérios de aceitação:

- O sistema deve fornecer um manual detalhado que explique todas as funcionalidades e recursos disponíveis.
- O manual deve ser acessível aos usuários a partir da interface do sistema, com fácil localização e navegação.
- O manual deve ser organizado de forma clara e estruturada, dividido em seções ou categorias que abordem diferentes aspectos do sistema.
- Cada funcionalidade ou recurso do sistema deve ter uma seção dedicada no manual, contendo uma descrição detalhada de como utilizá-lo e quais são suas finalidades.
- O manual deve incluir instruções passo a passo, capturas de tela e exemplos práticos sempre que possível, para auxiliar os usuários na compreensão e utilização do sistema.
- Deve ser fornecida uma introdução geral que apresente uma visão geral do sistema, seus principais objetivos e benefícios.
- O manual deve estar disponível em um formato facilmente acessível e legível, como PDF.
- O manual deve conter informações sobre o funcionamento da IA, detalhando o Data Understanding/Preparation/Modeling e demais características utilizadas pela biblioteca YOLO.

US #13 COMO usuário, QUERO um guia passo a passo que me oriente na instalação e configuração do sistema, PARA QUE eu possa implantá-lo facilmente em meu ambiente de trabalho.

Critérios de aceitação:

- O guia deve estar disponível em um formato facilmente acessível e legível. 
- O guia deve ser organizado de forma clara e estruturada, dividido em seções ou etapas que abordem cada parte do processo de instalação e configuração.
- Devem ser fornecidas capturas de tela ou vídeos ilustrativos sempre que possível, para auxiliar os usuários na compreensão e execução das etapas do guia.

 ### 🖥️ Protótipo navegável

> [Link para protótipo no figma](https://www.figma.com/proto/7pXrAvYbVSbmm7yi5WDiXM/API-6---Altave?type=design&scaling=min-zoom&page-id=0%3A1&node-id=12-102&starting-point-node-id=12%3A102&show-proto-sidebar=1)

### 📋 Modelo de Entidade-Relacionamento (MER)

![mer](https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/efebc6d8-5353-437d-8ada-22e362263dec)
  
</p>

<br />

<span id="dados">

## :floppy_disk: Detalhes da IA

<p align="justify">
 
O projeto entregue possui uma IA (inteligência artifical) com o objetivo de monitorar e identificar a entrada e saída de pessoas em uma determinada área restrita (chamada de redzone). Essa aplicação foi desenvolvida com a biblioteca [YOLO](https://docs.ultralytics.com/pt), que é altamente utilizada como um modelo de detecção de objetos e pessoas em imagens/vídeos em tempo real. Escolhemos utilizar essa biblioteca por conta de sua detecção feita em tempo real, analisando a imagem inteira de uma vez só, o que garante a eficácia necessária para atingirmos o objetivo do projeto.

Utililizamos o YOLO para treinar uma base de dados pública fornecida pelo [RoboFlow](https://universe.roboflow.com/leo-ueno/people-detection-o4rdr/dataset/8), que foi escolhida por conta de sua diversidade de cenários, que possui diversas situações e ambientes que facilitam o treinamento para cenários distintos, como diferentes angulações, iluminação e contextos, também a escolhemos por possuir um formato compátivel com o YOLO, facilitando o processo de integração com a biblioteca.

Ao realizar o treinamento, obtivemos os seguintes resultados:

 ![results](https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/037dc928-8b6f-4fb9-a949-6d7911889083)

Para garantirmos que o monitoramento está adequado para o projeto, gravamos e utilizamos os seguintes cenários para simular sua eficácia em ambientes que emulam o objetivo do projeto.

. Cenário genérico em que uma pessoa entra na sala restrita:

https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/3aeb1aee-2075-48ac-a9ff-db2c56b10683

. Cenário em que uma pessoa entrada na sala restrita, mas vindo de costas/lado:

https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/6e101563-2040-424b-9b53-89830b959504

. Cenário em que a pessoa entra na sala restrita, mas gravado em diferente angulação dos vídeos anteriores:

https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/1d845636-c53b-48eb-b913-9b92db1df9a7

. Cenário na qual a pessoa passa pela porta (entrada) mas não entra na sala restrita:

https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/3ab33dc5-2e9f-46d1-ad47-5437b785e57d

Com os cenários ilustrados acima, obtivemos os seguintes resultados de eficácia de nossa aplicação:

![acuracia_cenarios](https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/84529855-d9cc-4c0a-a235-c4d13fae93b1)

</p>

<br />

<span id="entrega">
 
## 👩‍💻 Entrega

<p align="center">

https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/4c4bc248-2616-4223-a8d7-1e7209b8bb07

</p>


<br>

→ [Voltar ao topo](#topo)

<div align='center' height='70'>
  
![Logo Fatec](https://github.com/thaleskerber/Projeto-Integrador-4-Semestre/assets/26208169/c5407beb-d912-41da-afbb-13b054a55885)

<h5 align="center"> Projeto Integrador - Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal </h5>
</div>
