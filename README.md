# Requirements Document for the AdmTur System

## Document Responsible
Diogo Borchhardt Beloni

## General Description of the System
The AdmTur system offers solutions for travel agency management, providing features for the daily operations of the establishment and covering prospecting, sales, and financial work.

## User Description
The system users are basically divided into three groups:
- **Manager** – Has access to all system features.
- **Attendants** – Have access to the system's customer service and sales features.
- **Financial Sector** – Has access to the system's financial records and reports features.

## Functional Requirements
1. **Package Registration**
   - **Actor:** Manager
   - **Description:** The manager periodically creates travel packages that are available to agency clients.

2. **Sales Reports**
   - **Actor:** Manager
   - **Description:** At the end of the month, the manager will issue a document that presents KPIs, sales volume, team performance, opportunity pipeline, and products sold during a specific period.

3. **Monthly Reports Issuance**
   - **Actor:** Financial Sector
   - **Description:** Monthly, the financial sector will issue a report with the company's income and expenses and pass it on to accounting.

4. **Travel Package Sales**
   - **Actor:** Attendants
   - **Description:** The product sales process is based on collecting client data, date, payment conditions, destination, lodging, and transportation. After this process, the attendant issues an electronic invoice proving the sale.

5. **Company Balance**
   - **Actor:** Manager
   - **Description:** The company balance report is created, demonstrating the company's financial data, including assets, liabilities, goods, debts, and profits.

6. **Budget Control**
   - **Actor:** Attendants
   - **Description:** Maintain budgets (add, edit, delete, search); issue a budget report for the client; make sales based on a budget allowing negotiation adjustments; and keep a history of changes in budget records, indicating the user who made the change.

## Non-Functional Requirements
1. **Internet Instability**
   - The client reports internet instability in the region; therefore, the program should run on a local network. However, the system needs some network information, such as the dollar exchange rate, so at least once a day the system should fetch this data online.

2. **Login Authentication**
   - According to the client, the system should be structured so that each employee has access to specific information, with only the manager having full system access.

## Use Cases

### Use Case 1: Sales Reports Issuance
- **Requirement Number:** RF002
- **Steps:**
  1. Start the software.
  2. User login (in this case, the user is the manager).
  3. On the software's home screen, locate the data visualization icon.
  4. Click with the left mouse button on each piece of information to be included in the sales report.
  5. After opening an information, fetch the monthly results.
  6. Enter the data found in the sales report.
  7. Repeat steps 4, 5, and 6 for each piece of information to be included in the sales report.
  8. Issue the report after data collection is complete.

### Use Case 2: Travel Package Registration
- **Requirement Number:** RF001
- **Steps:**
  1. Start the software.
  2. User login (in this case, the user is the manager).
  3. On the software's home screen, locate the registration icon.
  4. Click on the new travel package registration.
  5. Create the package.

# Documento de Requisitos para o Sistema AdmTur-Traduzido:

## Responsável pelo Documento
Diogo Borchhardt Beloni

## Descrição Geral do Sistema
O sistema AdmTur oferece soluções em administração de agência de viagens, disponibilizando funcionalidades para as operações cotidianas do estabelecimento e abrangendo o trabalho de prospecção, de vendas e também financeiro.

## Descrição dos Usuários
Os usuários do sistema se dividem basicamente em três grupos:
- **Gerente** – Têm acesso a todas as funcionalidades do sistema.
- **Atendentes** – Têm acesso às funcionalidades de atendimento e venda do sistema.
- **Setor financeiro** – Têm acesso às funcionalidades de registros e relatórios financeiros do sistema.

## Requisitos Funcionais
1. **Cadastro de pacotes**
   - **Ator:** Gerente
   - **Descrição:** O gerente monta periodicamente pacotes de viagem que ficam disponíveis a clientes da agência.

2. **Relatórios de vendas**
   - **Ator:** Gerente
   - **Descrição:** No fim do mês o gerente emitirá um documento que apresenta KPIs, volume de vendas, desempenho da equipe, pipeline de oportunidades e produtos vendidos durante um determinado período.

3. **Emissão de relatórios mensais**
   - **Ator:** Setor financeiro
   - **Descrição:** Mensalmente, o setor financeiro emitirá um relatório com as entradas e saídas de valores da empresa e repassará para a contabilidade.

4. **Vendas de pacotes de viagem**
   - **Ator:** Atendentes
   - **Descrição:** O processo de venda do produto baseia-se na coleta dos dados do cliente, data, condições de pagamento, destino, hospedagem, e transporte. Após este processo, o atendente emite uma nota fiscal eletrônica comprovando a venda.

5. **Balanço da empresa**
   - **Ator:** Gerente
   - **Descrição:** É realizado o relatório de balanceamento da empresa, demonstrando claramente os dados financeiros, incluindo ativos, passivos, bens, dívidas e lucros.

6. **Controle de orçamentos**
   - **Ator:** Atendentes
   - **Descrição:** Manter orçamentos (incluir, editar, excluir, buscar); emitir relatório de orçamento para o cliente; realizar venda com base em um orçamento permitindo ajustes de negociação; e manter histórico de alteração nos registros de orçamento, indicando o usuário que realizou a mudança.

## Requisitos Não Funcionais
1. **Instabilidade da Internet**
   - O cliente informa que há instabilidade na internet da região, portanto o programa deve rodar em rede local. No entanto, o sistema necessita de algumas informações da rede, como a cotação do dólar. Assim, ao menos uma vez ao dia o sistema deve buscar esses dados online.

2. **Autenticação por login**
   - De acordo com o fornecido pelo cliente, o sistema deve ser separado de forma que cada funcionário terá acesso a informações específicas, sendo apenas o gerente que terá acesso total ao sistema.

## Casos de Uso

### Caso de Uso 1: Emissão de Relatórios de Vendas
- **Número do requisito:** RF002
- **Passos:**
  1. Iniciar o software.
  2. Login do usuário (neste caso, o usuário é o gerente).
  3. Na tela inicial do software, localizar o ícone de visualização de dados.
  4. Clicar com o botão esquerdo do mouse sobre cada uma das informações que será incluída no relatório de vendas.
  5. Após abrir uma informação, buscar os resultados mensais.
  6. Informar os dados encontrados no relatório de vendas.
  7. Repetir os passos 4, 5 e 6 para cada informação que será apresentada no relatório de vendas.
  8. Emitir o relatório após a coleta de dados.

### Caso de Uso 2: Cadastro de Pacotes de Viagem
- **Número do requisito:** RF001
- **Passos:**
  1. Iniciar o software.
  2. Login do usuário (neste caso, o usuário é o gerente).
  3. Na tela inicial do software, localizar o ícone para realização de cadastros.
  4. Clicar sobre o cadastro de um novo pacote de viagem.
  5. Realizar a criação do pacote.
