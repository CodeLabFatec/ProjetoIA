<br id="topo">
 
<h1 align="center">Projeto IA - Segunda entrega</h1>

<p align="center">
    <a href="#mvp">MVP</a> | 
    <a href="#backlog">Backlog Sprint</a> |
    <a href="#DOR">DOR</a> |
    <a href="#dados">Dados para IA</a> |
    <a href="#entrega">Entrega(DOD)</a>
</p>
<span id="mvp">
 
<h1> :dart: MVP </h1>
<p align="justify">O MVP da segunda entrega foi o desenvolvimento das telas de Dashboard para visualização de gráficos e indicadores, juntamente com o cadastro, edição e listagem de RedZones para classificar os dados de E/S por RedZone.</p>

<span id="backlog">

## 📃 Backlog da Sprint

| Rank | Prioridade | User Story | Estimativa | Sprint | Requisito |
| :----: | :-------- | :-------- | :----: | :---: | :----: |
| 03 | Média | COMO administrador, QUERO QUE o sistema possua cadastro, listagem e edição de RedZones, PARA QUE seja possível criar uma divisão dentro do sistema, permitindo que haja análises de IA salvando informações específicas para cada RedZone. | 80 | 02 | RF-6 |
| 04 | Média | COMO usuário, QUERO um dashboard que exiba os principais indicadores de acesso nas RedZones por períodos específicos, PARA QUE eu possa visualizar facilmente o desempenho do sistema ao longo do tempo. | 70 | 02 | RF-2 |
| 05 | Média | COMO usuário, QUERO a capacidade de gerar relatórios personalizados com base nos dados de acesso nas RedZones PARA QUE eu possa compartilhar informações relevantes com outras partes interessadas. | 60 | 02 | RF-4 |


<span id="DOR"> 
  
## 📌 DOR

<p align="justify">

  ### 📄 User stories e Critérios de aceitação

US #3: COMO administrador, QUERO QUE o sistema possua cadastro, listagem e edição de RedZones, PARA QUE seja possível criar uma divisão dentro do sistema, permitindo que haja análises de IA salvando informações específicas para cada RedZone.

Critérios de aceitação:

- O sistema deve permitir que o administrador realize o cadastro de áreas restritas, fornecendo informações como nome, descrição e outras informações relevantes.

- O sistema deve fornecer uma lista de todas as redzones, permitindo que o administrador visualize e gerencie essas informações.

- O administrador deve ser capaz de editar as informações de redzones previamente cadastradas, possibilitando a atualização de dados conforme necessário.

- Cada RedZone deve ser identificada por um nome único e uma descrição que a diferencie das demais.

- Os dados de entrada e saída de pessoas coletados e analisados pela IA devem ser salvos de forma associada às RedZones correspondentes.


US #4 COMO usuário, QUERO a capacidade de gerar relatórios personalizados com base nos dados de acesso nas RedZones PARA QUE eu possa compartilhar informações relevantes com outras partes interessadas.

Critérios de aceitação:

- Os usuários devem poder selecionar os parâmetros e critérios específicos para a geração do relatório, como intervalo de datas, RedZones específicas, tipos de eventos, entre outros.
  
- Os usuários devem poder exportar os relatórios em formatos comuns, como PDF ou Excel, para compartilhamento com outras partes interessadas.

US #5 COMO usuário, QUERO um dashboard que exiba os principais indicadores de acesso nas RedZones por períodos específicos, PARA QUE eu possa visualizar facilmente o desempenho do sistema ao longo do tempo.

Critérios de aceitação:

- O sistema deve fornecer um dashboard que exiba os principais indicadores de acesso nas RedZones.
- Os indicadores de acesso devem incluir, pelo menos, o número total de entradas e saídas de pessoas em cada RedZone.
- O sistema deve fornecer gráficos ou visualizações visuais para representar os dados de acesso de forma intuitiva e compreensível.

 ### 🖥️ Protótipo navegável

> [Link para protótipo no figma](https://www.figma.com/proto/7pXrAvYbVSbmm7yi5WDiXM/API-6---Altave?type=design&scaling=min-zoom&page-id=0%3A1&node-id=12-102&starting-point-node-id=12%3A102&show-proto-sidebar=1)

### 📋 Modelo de Entidade-Relacionamento (MER)

![DER](https://github.com/CodeLabFatec/ProjetoIA/assets/26208169/f60a3205-2171-41ed-b34f-ed71dfbd6175)
  
</p>

<br />

<span id="dados">

## :floppy_disk: Dados para IA

<p align="justify">
 
 Para essa entrega, os dados que utilizados para construção da IA que monitora o fluxo de entrada e pessoas de uma determinada área restrita estão disponíveis na biblioteca [YOLO](https://docs.ultralytics.com/pt), em que utilizados como uma facilitadora devido a sua excelência em detecção de objetos e pessoas em tempo real.

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
