<br id="topo">
 
<h1 align="center">Projeto IA - Terceira entrega</h1>

<p align="center">
    <a href="#mvp">MVP</a> | 
    <a href="#backlog">Backlog Sprint</a> |
    <a href="#DOR">DOR</a> |
    <a href="#dados">Dados para IA</a> |
    <a href="#entrega">Entrega(DOD)</a>
</p>
<span id="mvp">
 
<h1> :dart: MVP </h1>
<p align="justify">O MVP da terceira entrega foi o aprimoramento da IA de monitoramento do fluxo de entrada e saída de pessoas para garantir que diferentes cenários possíveis sejam cobertos, além da inclusão do cadastro de áreas (departamentos) e filtros mais precisos para a dashboard do sistema.</p>

<span id="backlog">

## 📃 Backlog da Sprint

| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito |
| :----: | :-------- | :-------- | :----: | :---: | :----: |
| 06 | Média | COMO usuário, QUERO filtros de período que me permitam analisar os dados de acesso nas RedZones de forma flexível, como por dia, semana, mês ou período personalizado, PARA QUE eu possa realizar análises detalhadas conforme necessário. | 50 | 03 | RF-3 |
| 07 | Média | COMO administrador, QUERO QUE o sistema possua cadastro, listagem e edição de áreas restritas, vinculando com suas respectivas RedZones PARA QUE seja possível criar uma divisão dentro do sistema, possibilitando a existência de diferentes níveis de acessos. | 60 | 03 | RF-6 | 
| 08 | Média | COMO gerente de segurança, QUERO QUE a inteligência artificial seja aprimorada para cubrir diferentes cenários de interação de pessoas, PARA QUE o monitoramento correto do fluxo de pessoas de uma RedZone esteja eficaz. | 70 | 03 | RF-5 |

<span id="DOR"> 
  
## 📌 DOR

<p align="justify">

  ### 📄 User stories e Critérios de aceitação

US #6: COMO usuário, QUERO filtros de período que me permitam analisar os dados de acesso nas RedZones de forma flexível, como por dia, semana, mês ou período personalizado, PARA QUE eu possa realizar análises detalhadas conforme necessário.

Critérios de aceitação:

- O sistema deve fornecer filtros de período para análise dos dados de acesso nas RedZones.
- Os filtros de período devem permitir que o usuário selecione intervalos temporais flexíveis, como por dia, semana, mês ou um período personalizado.
- O sistema deve ser capaz de filtrar os dados de acesso de acordo com o período selecionado pelo usuário.

US #7 COMO administrador, QUERO QUE o sistema possua cadastro, listagem e edição de áreas restritas, vinculando com suas respectivas RedZones PARA QUE seja possível criar uma divisão dentro do sistema, possibilitando a existência de diferentes níveis de acessos.

Critérios de aceitação:

- O sistema deve permitir que o administrador realize o cadastro de áreas restritas, fornecendo informações como nome, descrição e outras informações relevantes.
- O sistema deve fornecer uma lista de todas as áreas restritas cadastradas, permitindo que o administrador visualize e gerencie essas informações.
- O administrador deve ser capaz de editar as informações de áreas restritas previamente cadastradas, possibilitando a atualização de dados conforme necessário.
- O administrador deve ser capaz de excluir/desativar áreas restritas e suas respectivas RedZones.
- Para cada área restrita cadastrada, o sistema deve permitir a definição e o cadastramento de RedZones específicas associadas a essa área.

US #8 COMO gerente de segurança, QUERO QUE a inteligência artificial seja aprimorada para cubrir diferentes cenários de interação de pessoas, PARA QUE o monitoramento correto do fluxo de pessoas de uma RedZone esteja eficaz.

Critérios de aceitação:

- A IA deve ser testada nos seguintes cenários de teste: a) Pessoas paradas na porta, mas que não entrem na área; b) Caso a aplicação seja encerrada, garantir que consiga entender quem está dentro da área; c) Garantir que diferentes angulações consigam detectar corretamente o fluxo.
- Após os testes, a IA deve ser ajustada para que os cenários descritos acima estejam ocorrendo de forma correta e sem problemas.

 ### 🖥️ Protótipo navegável

> [Link para protótipo no figma](https://www.figma.com/proto/7pXrAvYbVSbmm7yi5WDiXM/API-6---Altave?type=design&scaling=min-zoom&page-id=0%3A1&node-id=12-102&starting-point-node-id=12%3A102&show-proto-sidebar=1)

### 📋 Modelo de Entidade-Relacionamento (MER)

![MER](https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/cb337968-a467-434b-8155-25043f0733c9)
  
</p>

<br />

<span id="dados">

## :floppy_disk: Dados para IA

<p align="justify">
 
 Na entrega dessa sprint, optamos por treinar um modelo de dados para aplicar em nossa aplicação de IA. Para isso utilizamos uma base de dados pública gratuíta fornecida pelo RoboFlow, focada em track de pessoas. Essa base está disponível no seguinte [link](https://universe.roboflow.com/leo-ueno/people-detection-o4rdr/dataset/8). O treinamento foi feito utilizando a biblioteca [YOLO](https://docs.ultralytics.com/pt), que fornece métodos para, a partir de uma base de dados, treinar um modelo de detecção de objetos/pessoas. O código abaixo é para exemplificar uma forma de realizar tal treinamento:

 ```python
from ultralytics import YOLO

model = YOLO()

results = model.train(data='data.yaml', epochs=5, imgsz=640, deterministic=True)
```

Ao realizar o treinamento, obtivemos os seguintes resultados:

 ![results](https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/037dc928-8b6f-4fb9-a949-6d7911889083)

Além do treinamento, também entregamos nessa sprint vídeos exemplificando como a aplicação desenvolvida está se comportando em cenários diferentes dos utilizados nas entregas anteriores. Dessa vez trabalhamos com diferente angulação e posicionamento de câmera, além de um cenário em que a pessoa fica parada na entrada (porta), mas não entra de fato na área. Esses vídeos estão disponíveis abaixo:


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
