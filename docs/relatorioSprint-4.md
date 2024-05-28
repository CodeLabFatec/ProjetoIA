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

  
</p>

<br />

<span id="dados">

## :floppy_disk: Dados para IA

<p align="justify">
 
 Na entrega da sprint anterior, treinamos um modelo de dados para aplicar em nossa aplicação de IA. Para isso utilizamos uma base de dados pública gratuíta fornecida pelo RoboFlow, focada em track de pessoas. Essa base está disponível no seguinte [link](https://universe.roboflow.com/leo-ueno/people-detection-o4rdr/dataset/8). O treinamento foi feito utilizando a biblioteca [YOLO](https://docs.ultralytics.com/pt), que fornece métodos para, a partir de uma base de dados, treinar um modelo de detecção de objetos/pessoas. O código abaixo é para exemplificar uma forma de realizar tal treinamento:

 ```python
from ultralytics import YOLO

model = YOLO()

results = model.train(data='data.yaml', epochs=5, imgsz=640, deterministic=True)
```

Ao realizar o treinamento, obtivemos os seguintes resultados:

 ![results](https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/037dc928-8b6f-4fb9-a949-6d7911889083)

Além do treinamento, também entregamos na sprint anterior vídeos exemplificando como a aplicação desenvolvida está se comportando em cenários diferentes dos utilizados nas entregas anteriores. Dessa vez trabalhamos com diferente angulação e posicionamento de câmera, além de um cenário em que a pessoa fica parada na entrada (porta), mas não entra de fato na área. Esses vídeos estão disponíveis abaixo:


https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/1d845636-c53b-48eb-b913-9b92db1df9a7


https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/3ab33dc5-2e9f-46d1-ad47-5437b785e57d


</p>

<br />

<span id="entrega">
 
## 👩‍💻 Entrega

<p align="center">



</p>


<br>

→ [Voltar ao topo](#topo)

<div align='center' height='70'>
  
![Logo Fatec](https://github.com/thaleskerber/Projeto-Integrador-4-Semestre/assets/26208169/c5407beb-d912-41da-afbb-13b054a55885)

<h5 align="center"> Projeto Integrador - Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal </h5>
</div>
