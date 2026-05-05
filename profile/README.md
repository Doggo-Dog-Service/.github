# Projeto Integrador - Modelo

*Doggo - Dog Service*

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

O **Doggo - Dog Service** é uma plataforma para a contratação, registro e monitoramento legal de serviços relacionados à cachorros, como o Dog Walking, Dog Sitter e Dog Boarding.

Professor: [Marco André Mendes](github.com/marcoandre)

Equipe:
- [André Ricardo Schultz](https://github.com/AndreRicardoSc)
- [Johann Matthies e Borges](https://github.com/Johann5731)
- [Luiz Roberto de Melo Correia Junior](https://github.com/Luizinx-1412)

Links do projeto:
(*Coloque aqui os links para a documentação do projeto e os repositórios e plubicação do backend e frontend.*)
-   [Documentação (esse documento)](github.com/marcoandre/pi-modelo)
-   Backend: [Repositório](https://github.com/Doggo-Dog-Service/doggo-backend) e [Publicação]()
-   Frontend: [Repositório](https://github.com/Doggo-Dog-Service/doggo-frontend) e [Publicação]()

# 1. Desenvolvimento

**1.1 Modelo de Sistema**

**Prestação de Serviço:** Sistema onde o usuário pode contratar serviços de um profissional ou empresa.

**1.2 Descrição do Sistema**

O Doggo - Dog Service é uma plataforma de serviços para cachorro que engloba três tipos de serviço:
- **Dog Walking** (Passeadores): profissionais contratados para passear com os cachorros, garantindo exercícios físicos, socialização e estimulação mental. Esse serviço é essencial para tutores com a rotina agitada. 
- **Dog Sitter** (Babás): profissionais contratados para cuidar do pet por um tempo definido na própria casa do tutor. Esse serviço é essencial para tutores que não conseguem se manter por muito tempo em casa. 
- **Dog boarding** (Moradia): o profissional oferece a própria casa por tempo determinado para cuidar do seu pet, garantindo o bem estar e condições confortáveis à ele. Esse serviço é essencial para tutores que desejam hospedar o pet, sem perder a privacidade da própria moradia contratando um Dog Sitter. 

O sistema terá agendamento de horários e registro para os três tipos de serviço. Em especial ao Dog Walking, terá serviço para passeios rápidos (semelhante ao sistema do Uber), que oferecerá localização em tempo real entre profissional e cliente, e o registro desses passeios.

O sistema irá filtrar as localização do profissionais para entregar ao cliente serviços perto de sua área.

**1.3 Motivo da Escolha**

Um dos integrantes da equipe teve contato com uma pessoa que trabalha na área de Dog Walking. A partir disso pensamos em deesenvolver esse sistema, não só para essa pessoa, mas para todos os que trabalham com a área ou com alguma que englobe o Dog Service (serviços para cachorros).
****
# 2. Situação Problema

**A Empresa**

O mercado de pet no Brasil é um dos maiores do mundo e vem crescendo muito ao longo dos anos, aumentando o número de tutores que consideram o seus pets como membro da família. Dentro desse contexto, muitas pessoas, na maioria autônomas, vêm trabalhando com serviços de pet como o Dog Walking e não há nenhuma plataforma que faça o registro desses serviços. Pensando nisso, surge a Doggo - Dog Service, uma empresa de prestação de serviços voltados exclusivamente para cães, fundada em 2026 na região Norte de Santa Catarina. A empresa conta atualmente com três funcionários, fundadores da empresa, que possuem um único foco: transformar os passeios do seu pet com tecnologia, tornando-os mais seguros, confiáveis e gerando empregos tanto para quem já atua na área de Dog Walking, como para quem ainda é novato.

**O Problema**

Atualmente, toda a operação de serviços relacionada a pets, principalmente o Dog Walking, é feita de forma descentralizada. Os tutores que desejam contratar um serviço geralmente têm que seguire esses passos:
- Entrar em contato com o prestador do serviço pessoalmente via Whatsapp ou qualquer outro meio;
- Esperar uma resposta para poder ver os horários e preços disponíveis;
- Escolher um horário;
- Esperar novamente a confirmação.

Esse ciclo gera repetitividade e retarda o serviço. Fazendo com que muitas vezes o cliente nem consiga concluir o agendamento do serviço ou se depare com preços inacessíveis e acabe desistindo, gerando prejuízo de tempo tanto para o tutor, tanto para o prestador.

Em outra análise, a empresa viu a falta de um software que registre o serviço do início ao fim. Como o processo de contratação dos serviços geralmente é muito pessoal, deixando muitas vezes o cliente inseguro em relação ao serviço. Em uma contratação de serviço, como o próprio nome retrata, existe um contrato, mas levando em conta que o pet não consegue dar um feedback de como foi o serviço, não se tem um registro legal das ações ocorridas durante o serviço.

**A Solução**

Com isso a Dog - Dog Service irá oferecer tudo isso em um único software. O site da Doggo terá como objetivo a união de vários prestadores de serviço para que os clientes possam contratá-los, incluindo Dog Walkers, Dog Sitters e prestadores de Dog Boarding. Para a solução dos problemas citados, o sistema contará com:
- Preço de cada prestador claro e direto;
- Agenda disponível para o cliente solicitar ao prestador, reduzindo o processo de contratação;
- Chat direto entre cliente e prestador;
- Pagamento feito e registrado através do software;
- Diário de serviço: uma aba com fotos e descrição de como foi o serviço e como o pet estava naquele momento;
- Rastreamento em tempo real do serviço ( somente no Dog Walking );
- Acesso ao histórico de serviços para cliente e prestador de maneira clara e segura.

# 3. Descrição da proposta

A proposta do software **Doggo - Dog Service** vem com intuito de otimizar e segurar o processo de contratação de serviços relacionados ao mercado de pet. 

**Para o cliente**, o sistema contará com:
- **Procura de serviços em áreas próximas**: parte da aplicação que permitirá filtrar os serviços pela área mais próxima do cliente; 
- **Localização em tempo real**: para o serviço de Dog Walking, o cliente conseguirá acessar a localização em tempo real de onde o pretador está;
- **Diário de serviço**: será uma aba do sistema onde o cliente conseguirá ver como o pet estava no momento do serviço e acessar tudo o que foi feito com o pet (responsabilidade do prestador em atualizar esses dados);
- **Rota de passeios registrada**: após um passeio (Dog Walking), ficará registrado cada local em que o passeador esteve, formando um desenho da rota no mapa;
- **Cadastro de pets**: para uma busca de prestadores mais específica de acordo com os pets adicionados pelo cliente;
- **Preço dos serviços de maneira transparente**: No perfil de cada prestador, ficará exibido os preços e pacotes de promoção de seus serviços;
- **Agenda dos prestadores disponível para solicitar serviço**: o cliente poderá solicitar agendamento clicando nos horários vagos disponibilizados pelo prestador;
- **Serviço de passeios rápidos (para Dog Walking)**: o cliente poderá chamar um passeador que estará em modo de passeio rápido, priorizando os que estiverem mais próximos;
- **Contratção direta pelo sistema (sem aplicativos de terceiros)**: todo o processo de contratação e pagamento dos serviços ocorrerá pela plataforma, sem a necessidade de apps terceiros;
- **Reembolso**: caso o serviço não tenha sido realizado ou o prestador violar algum termo de política de uso, o cliente poderá abrir um processo de reembolso pelo serviço.

**Para o prestador**, o sistema contará com:
- **Diário de serviço**: o prestador terá a responsabilidade de atualizar o diário do serviço, colocando fotos do pet ou imagens dele.
- **Preços customizáveis**: o prestador poderá modificar quando quiser o seu perfil com preços e pacotes promocionais; 
- **Integração com agenda personalizada**: o prestador terá acesso à uma agenda semanal que irá personalizar com os dias e horários disponíveis para trabalho, quando algum cliente for marcado, esse calendário será atualizado com esse serviço agendado; 
- **Solicitações de agendamento dos clientes**: Quando um cliente solicitar um serviço pela agenda, virá uma soliciação para aceitar esse serviço; 
- **Grupos de fidelidade**: o prestador terá direito a um grupo de fidelidade dos clientes, onde o horário semanal terá prioridade para eles, além de poder lançar pacotes promocionais exclusivos; 
- **Pagamento antecipado do serviço**: o prestador receberá o dinheiro antes do serviço ser executado para evitar golpes;

O software contará com quatro tipos de usuário, sendo eles:
- Cliente (cliente);
- Walker (prestador);
- Sitter (prestador);
- Boarding (prestador);
  
# 4. Modelagem de Dados

**4.1 Diagrama**

![Diagrama de Caso de Uso](/images/imagem-modelagem-dados.png "Diagrama de Caso de Uso")

**4.2 Entidades do Sistema**

O sistema é composto pelas seguintes entidades principais:

**Usuário (user)**

Representa qualquer pessoa no sistema (cliente ou prestador).

**Atributos**

- id (PK)
- usename
- email
- password
- cpf
- full_name
- phone

---

**Papel (role)**

Define o tipo de usuário (ex: cliente, prestador, admin).

**Atributos**

- id (PK)
- name

---

**Usuário-papel (user_has_role)**

Tabela associativa entre usuário e papel.

**Atributos**

- id (PK)
- user_id (FK)
- role_id (FK)

**Relacionamento:**

- Usuário - Papel (N:M)

---

**Pet (pet)**

Representa os pets cadastrados pelos usuários.

**Atributos**

- id (PK)
- user_id (FK)
- name
- breed
- size
- weight
- temperament
- special_needs
- vaccination_status
- created_at

**Relacionamento:**

- Usuário - Pet (1:N)

---

**Tipo de Serviço (service_type)**

Define os tipos de serviços disponíveis (passeio, cuidador, hospedagem).

**Atributos**

- id (PK)
- name
- description

---

**Serviço do Prestador (provider_service)**

Serviços oferecidos por um prestador.

**Atributos:**

- id (PK)
- service_type_id (FK)
- user_id (FK)
- price_per_hour
- price_per_day
- activity_area_km
- description
- created_at

**Relacionamentos:**

- Usuário (prestador) - Serviço (1:N)
- Tipo de Serviço - Serviço do Prestador (1:N)

---

**Serviço (service)**

Representa um agendamento realizado.

**Atributos:**

- id (PK)
- pet_id (FK)
- user_id (FK) → cliente
- provider_service_id (FK)
- service_type_id (FK)
- start_datetime
- end_datetime
- status
- total_price
- created_at

**Relacionamentos:**

- Serviço - Pet (1:N)
- Serviço - Usuário (cliente) (1:N)
- Serviço - Pet (1:N)

---

**Pagamento (payment)**

Registra o pagamento de um serviço.

**Atributos:**

- id (PK)
- service_id (FK)
- amount
- status
- payment_method
- transaction_id
- paid_at
- created_at

**Relacionamento:**

- Serviço - Pagamento (1:1)

---

**Taxa da Plataforma (platform_fee)**

Define a comissão da plataforma sobre o pagamento.

- id (PK)
- payment_id (FK)
- amount
- percentage
- created_at

**Relacionamentos:**

- Pagamento - Taxa da Plataforma (1:1)

---

**Repasse (payout)**

Valor transferido ao prestador.

**Atributos:**

- id (PK)
- service_id (FK)
- provider_service_id (FK)
- amount
- status
- payment_method
- payment_id
- scheduled_at
- paid_at
- created_at

**Relacionamento:**

- Serviço - Repasse (1:1)

# 5. Regras de negócio

**RN01 - Cadastro de Usuário:** O sistema deve bloquear o registro de usuários com mesmo email, cpf ou telefone.

**RN02 - Associação Obrigatória de Perfil**: O sistema deve cadastrar sempre o usuário em algum perfil: cliente ou provedor.

**RN03 - Cadastro de Pet Vinculado:** O sistema deve cadastrar sempre um pet associado à um dono, esse dono somente poderá ser um cliente.

**RN04 - Agendamentos com Dados Obrigatórios:** O sistema deve exigir para agendar: um pet e um serviço cadastrado pelo provedor.

**RN05 - Validação de Datas do Serviço:** O sistema deve verificar se o horário e data de término de um serviço é posterior à data de início.

**RN06 - Cálculo do Valor dos Serviços:** O sistema deve calcular automaticamente o valor de um serviço com base na duração e nos preços definidos pelo prestador.

**RN07 - Pagamento Vinculado ao Serviço:** O sistema deve registrar um pagamento obrigatóriamente associado à um serviço.

**RN08 - Confirmação do Pagamento:** O sistema deve concluir o agendamento somente após o pagamento do serviço.

**RN09 - Geração Automática da Taxa da Plataforma:** O sistema deve gerar automáticamente uma taxa baseada num percentual definido.

**RN10 - Cálculo do Repasse ao Prestador:** O sistema deve repassar o valor do serviço com o desconto da taxa da plataforma automaticamente.

**RN11 - Controle de Status de Serviço:** O sistema deve seguir apenas os seguintes status: pendente, confirmado, em andamento, concluído e cancelado.

**RN12 - Restrição de Alteração pós Pagamento:** O sistema deve restringir alterações no serviço após pagamento.

**RN13 - Integridade do Histórico:** O sistema deve manter os serviços, pagamentos e repasses de dinheiro. Esses dados nunca devem ser excluídos permanentemente.

# 6. Requisitos funcionais

**6.1 Entradas**

**RF01 - Cadastro de Usuários:** O sistema deve permitir o cadastro de novos usuários no sistema, possibilitando o acesso à plataforma DOGGO, seja como cliente ou prestador de serviços.

- Dados necessários: username, email, password, cpf, full_name, phone.
- Usuários: visitantes.

**RF02 - Cadastro de Papéis de Usuário:** O sistema deve permitir a definição de papéis (roles) para os usuários, como cliente ou prestador, possibilitando controle de permissões no sistema.

- Dados necessários: name.
- Usuários: administrador.

**RF03 - Associação de Usuário a Papel:** O sistema deve permitir vincular um usuário a um papel, definindo seu nível de acesso dentro da plataforma.

- Dados necessários: user_id, role_id.
- Usuários: administrador.

**RF04 - Cadastro de Pets:** O sistema deve permitir que usuários registrem seus pets para utilização nos serviços oferecidos na plataforma.

- Dados necessários: user_id, name, breed, size, weight, temperament, special_needs, vaccination_status.
- Usuários: cliente.

**RF05 - Cadastro de Tipos de Serviço:** O sistema deve permitir o cadastro dos tipos de serviços disponíveis na plataforma (ex: passeio, hospedagem).

- Dados necessários: name, description.
- Usuários: adminitrador.

**RF06 - Cadastro de Serviços do Prestador:** O sistema deve permitir que prestadores cadastrem os serviços que oferecem, incluindo preços e área de atuação.

- Dados necessários: user_id, service_type_id, price_per_hour, price_per_day, activity_area_km, description.
- Usuários: prestador.

**6.2 Processos**

**RF07 - Autenticação de Usuário:** O sistema deve permitir que o usuário acesse o sistema mediante validação de suas credenciais, garantindo segurança no acesso.

- Dados necessários: email, password.
- Usuários: todos os usuários.

**RF08 - Agendamento de Serviço:** O sistema deve permitir que um cliente solicite um serviço com base na disponibilidade de um prestador, vinculando pet, horário e tipo de serviço.

- Dados necessários: pet_id, user_id, provider_service_id, service_type_id, start_datetime, end_datetime.
- Usuários: cliente.

**RF09 - Cálculo do Valor do Serviço:** O sistema deve calcular automaticamente o valor total do serviço com base no tempo contratado e nos preços definidos pelo prestador.

- Dados necessários: price_per_hour, price_per_day, start_datetime, end_datetime.
- Usuários: nenhum (sistema).

**RF10 - Processamento de Pagamento:** O sistema deve registrar e processar o pagamento de um serviço, garantindo que a transação seja associada ao serviço contratado.

- Dados necessários: service_id, amount, payment_method, transaction_id.
- Usuários: cliente.

**RF11 - Cálculo da Taxa da Plataforma:** O sistema deve calcular a taxa da plataforma com base em um percentual definido sobre o valor do serviço pago.

- Dados necessários: payment_id, amount, percentage.
- Usuários: nenhum (sistema).

**RF12 - Geração de Repasse ao Prestador:** O sistema deve gerar o valor a ser repassado ao prestador, descontando a taxa da plataforma.

- Dados necessários: service_id, provider_service_id, amount.
- Usuários: nenhum (sistema).

**RF13 - Atualização de Status do Serviço:** O sistema deve permitir a atualização do status do serviço (pendente, confirmado, concluído, cancelado).

- Dados necessários: service_id, status.
- Usuários: cliente, prestador.

**6.3 Sáidas**

**RF14 - Listagem de Serviços Disponíveis:** O sistema deve exibir os serviços disponíveis na plataforma, permitindo que clientes visualizem opções de prestadores.

- Dados necessários: service_type, price, description, provider.
- Usuários: cliente.

**RF15 - Histórico de Serviços do Usuário:** O sistema deve exibir o histórico de serviços realizados por um usuário, incluindo detalhes de cada serviço.

- Dados necessários: service_id, pet, provider, status, total_price, datas.
- Usuários: cliente, prestador.

**RF16 - Relatório de Pagamentos:** O sistema deve permitir a visualização dos pagamentos realizados na plataforma, incluindo status e valores.

- Dados necessários: payment_id, service_id, amount, status, payment_method.
- Usuários: administrador, cliente e prestador.

**RF17 - Relatório de Taxas da Plataforma:** O sistema deve exibir as taxas geradas pela plataforma sobre os serviços realizados.

- Dados necessários: platform_fee_id, service_id, amount, percentage.
- Usuários: administrador.

**RF18 - Relatório de Repasses aos Prestadores:** O sistema deve exibir os valores repassados aos prestadores, incluindo status e datas de pagamento.

- Dados necessários: payout_id, service_id, amount, status, paid_at.
- Usuários: administrador, prestador.

# 7. Requisitos não funcionais

**RNF01 - Navegadores Homologados:** O sistema deve ser compatível com os navegadores Google Chrome, Mozilla Firefox e Microsoft Edge em suas versões mais recentes.

**RNF02 - Responsividade:** O sistema deve possuir interface responsiva, usando a arquitetura mobile first e adaptando-se para telas de computadores

**RNF03 - Usabilidade:** O sistema deve conter uma interface intuitiva e direta, permitindo ações mais fáceis.

**RNF04 - Autenticação:** O sistema deve exigir a autenticação dos usuários para acessar as funcionalidades.

**RNF05 - Criptografia de Dados:** O sistema deve armazenar as senhas do usuário de maneira criptografada.

**RNF06 - Grupos de Acesso:** O sistema deve conter controles de acesso  baseados em papéis que limitarão as funcionalidades do usuário no sistema.

**RNF07 - Integridade dos Dados:** O sistema deve garantir consistência dos dados, especialmente de operações financeiras, como pagamentos e repasses de valor.

**RNF08 - Arquitetura do Sistema:** O sistema deve ser desenvolvido na arquitetura baseada em API REST.

**RNF09 - Tecnologias:** O sistema deve ser desenvolvido utilizando: Django com DRF, Vue js, Tailwindcss e MySql.

**RNF10 - Manutenção:** O sistema deve ser desenvolvido em um padrão de pastas e arquivos para facilitar manutenção e escalabilidade.

# 8. Diagrama de Caso de Uso

**8.1 Introdução**

O diagrama de caso de uso é uma ferramenta de modelagem que descreve o comportamento de um sistema a partir da perspectiva do usuário. Ele é usado para capturar os requisitos funcionais de um sistema.

- Especificam a visão externa do sistema.
- Descrevem como o sistema é percebido por seus usuários.
- Descrevem as interações entre os usuários e o sistema.

![Diagrama de Caso de Uso](img/dcu1.png "Diagrama de Caso de Uso")

**Os casos de uso:**
- Descrevem como os **usuários interagem com o sistema** (as funcionalidades do sistema)
- Facilitam a **organização dos requisitos** de um sistema.
- Dão uma **visão externa** do sistema
- O conjunto de casos de uso deve ser capaz de comunicar a **funcionalidade** e o **comportamento** do sistema para o cliente.
- Descrevem **o que** o sistema faz, mas **não** especificam **como** isso deve ser feito.

**8.2 Elementos do diagrama de caso de uso**

8.2.1 **Atores**

- Representam os papéis desempenhados por **elementos externos** ao sistema
  - Ex: humano (usuário), dispositivo de hardware ou outro sistema (cliente)
- Elementos que **interagem** com o sistema

Notação:

![Atores Notação](img/dcu_atores_notacao.png "Atores Notação")

**Exemplo: Loja de CDs**

**Identificando os atores**
- Uma loja de CDs possui discos para venda. Um cliente pode comprar uma quantidade ilimitada de discos para isto ele deve se dirigir à loja.
- A loja possui um **atendente** cuja função é atender os clientes durante a venda dos discos. A loja também possui um **gerente** cuja função é administrar o estoque para que não faltem discos. Além disso é ele quem dá folga ao atendente, ou seja, ele também atende os clientes durante a venda dos discos.

![Identificando os atores](img/dcu_identificando_atores.png "Identificando os atores")

**E o cliente?**
- Não é ator pois ele **não interage** com o sistema!

**8.2.2 Casos de uso**

- Representam **funcionalidades** do sistema (requisitos funcionais).
- São iniciados por **atores** ou por outros casos de uso.

> **Dica**: nomeie os casos de uso com **verbos** no **infinitivo**.

Notação:

![Casos de uso Notação](img/dcu_casos_de_uso_notacao.png "Casos de uso Notação")

**Exemplo: Loja de CDs**

**Identificando os casos de uso**

- Uma loja de CDs possui discos para venda. Um cliente pode comprar uma quantidade ilimitada de discos para isto ele deve se dirigir à loja. A loja possui um atendente cuja função é atender os clientes durante a **venda dos discos**.
- A loja também possui um gerente cuja função é **administrar o estoque** para que não faltem discos. Além disso é ele quem dá folga ao atendente, ou seja, ele também atende os clientes durante a **venda dos discos**.

![Identificando os casos de uso](img/dcu_identificando_casos_de_uso.png "Identificando os casos de uso")

**8.2.3 Relacionamentos**

**8.2.3.1 Relacionamento de associação**

- Indica que um ator **participa** de um caso de uso, ou seja, o ator **interage** (comunica-se) com o caso de uso.
- É representado por uma **linha sólida**.
- Um ator pode se relacionar com **um ou mais casos de uso**.

> Dicas:
> - Não use setas nas linhas de associação.
> - Associações não representam fluxo de informação.

![Relacionamento de associação](img/dcu_relacionamento_de_associacao.png "Relacionamento de associação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de associação**

- Uma loja de CDs possui discos para venda. Um cliente pode comprar uma quantidade ilimitada de discos para isto ele deve se dirigir à loja. A loja possui um _atendente_ cuja função é atender os clientes durante a **venda dos discos**.
- A loja também possui um _gerente_ cuja função é **administrar o estoque** para que não faltem discos. Além disso é ele quem dá folga ao _atendente_, ou seja, ele também atende os clientes durante a **venda dos discos**.

![Identificando os relacionamentos de associação](img/dcu_identificando_relacionamentos_de_associacao.png "Identificando os relacionamentos de associação")

**8.2.3.2 Relacionamento de generalização/especialização**

**Generalização de atores**

- Quando dois ou mais atores podem se **comunicar com o mesmo conjunto de casos de uso**.
- Indica que um ator **herda** as características de outro ator.
– Um filho (herdeiro) pode se comunicar com todos os casos de uso que seu pai se comunica.

> **Dica:** coloque os herdeiros **embaixo**.

**Notação:**

![Relacionamento de generalização/especialização de atores - notação](img/dcu_relacionamento_de_generalizacao_especializacao_notacao_de_atores.png "Relacionamento de generalização/especialização de atores - notação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de generalização/especialização de atores**

![Identificando os relacionamentos de generalização/especialização de atores](img/dcu_identificando_relacionamentos_de_generalizacao_especializacao_de_atores.png "Identificando os relacionamentos de generalização/especialização de atores")

**Generalização de casos de uso**

– O caso de uso filho herda o comportamento e o significado do caso de uso pai.
– O caso de uso filho pode incluir ou sobrescrever o comportamento do caso de uso pai.
– O caso de uso filho pode substituir o caso de uso pai em qualquer lugar que ele apareça.

> **Dica:** deve ser aplicada quando uma condição resulta na definição de
diversos fluxos alternativos.

Notação:

![Relacionamento de generalização/especialização de casos de uso - notação](img/dcu_relacionamento_de_generalizacao_especializacao_notacao_de_casos_de_uso.png "Relacionamento de generalização/especialização de casos de uso - notação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de generalização/especialização de casos de uso**

**Novos requisitos:**

- As vendas podem ser **à vista** ou **a prazo**. Em ambos os casos o estoque é
atualizado e uma nota fiscal, entregue ao consumidor.
- No caso de uma **venda à vista**, clientes cadastrados na loja e que compram mais de 5 CDs de uma só vez ganham um desconto de 1% para cada ano de cadastro.
- No caso de uma **venda a prazo**, ela pode ser parcelada em 2 pagamentos com um
acréscimo de 20%. As vendas a prazo podem ser pagas no **cartão** ou no **boleto**.
  - Para pagamento com **boleto**, são gerados boletos bancários que são entregues ao cliente e armazenados no sistema para lançamento posterior no caixa.
  - Para pagamento com **cartão**, os clientes com mais de 10 anos de cadastro na loja ganham o mesmo desconto das compras à vista.

![Identificando os relacionamentos de generalização/especialização de casos de uso](img/dcu_identificando_relacionamentos_de_generalizacao_especializacao_de_casos_de_uso.png "Identificando os relacionamentos de generalização/especialização de casos de uso")

**Identificando mais relacionamentos de generalização/especialização de casos de uso**

![Identificando mais relacionamentos de generalização/especialização de casos de uso](img/dcu_identificando_mais_relacionamentos_de_generalizacao_especializacao_de_casos_de_uso.png "Identificando mais relacionamentos de generalização/especialização de casos de uso")

**8.2.3.3 Relacionamento de dependência**

**Extensão**

- Representa uma variação/extensão do comportamento do caso de uso base.
- O caso de uso estendido só é executado sob certas circunstâncias.
- Separa partes obrigatórias de partes opcionais.
  - Partes obrigatórias: caso de uso base.
  - Partes opcionais: caso de uso estendido.
- Fatorar comportamentos variantes do sistema (podendo reusar este comportamento
em outros casos de uso).

**Notação:**

![Relacionamento de dependência (extensão) - notação](img/dcu_relacionamento_de_dependencia_extensao_notacao.png "Relacionamento de dependência (extensão) - notação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de dependência (extensão)**

**Novos requisitos:**
- No caso de uma venda à vista, clientes cadastrados na loja e que compram mais
de 5 CDs de uma só vez ganham um **desconto** de 1% para cada ano de cadastro.
- No caso de uma venda a prazo...
  - ...Para pagamento com cartão, os clientes com mais de 10 anos de cadastro na loja ganham o mesmo **desconto** das compras à vista.

![Identificando os relacionamentos de dependência (extensão)](img/dcu_identificando_relacionamentos_de_dependencia_extensao.png "Identificando os relacionamentos de dependência (extensão)")

**Inclusão**

- Evita repetição ao fatorar uma atividade
comum a dois ou mais casos de uso.
- Um caso de uso pode incluir vários casos de uso.

**Notação:**

![Relacionamento de dependência (inclusão) - notação](img/dcu_relacionamento_de_dependencia_inclusao_notacao.png "Relacionamento de dependência (inclusão) - notação")

**Exemplo: Loja de CDs**

**Novos requisitos:**
Para efetuar vendas ou administrar estoque, atendentes e gerentes terão que **validar** suas respectivas senhas de
acesso ao sistema.

![Identificando os relacionamentos de dependência (inclusão)](img/dcu_identificando_relacionamentos_de_dependencia_inclusao.png "Identificando os relacionamentos de dependência (inclusão)")

**8.2.4 Fronteira do sistema**

- Elemento opcional (mas essencial para um bom
entendimento).
- Serve para definir a área de atuação do sistema, ou seja, seus limites.

**Identificando a fronteira do sistema**

![Identificando a fronteira do sistema](img/dcu_identificando_a_fronteira_do_sistema.png "Identificando a fronteira do sistema")

---
