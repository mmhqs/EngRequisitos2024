# Trabalho final

Disciplina: Engenharia de Requisitos

## Integrantes do grupo:
- David Leong Ho
- Erica Alves dos Santos
- Joana Iuna de Morais
- Luís Miguel Souza Almeida
- Mariana Almeida Henriques
- Victor Augusto Nascimento
- Vinicius Gabriel Romie Vieira

## Introdução
No presente trabalho, será apresentada a primeira entrega do trabalho final da disciplina de Engenharia de Requisitos, ministrada pela professora Michelle Hanne.

## Processos de negócios
Os processos de negócios apresentados no problema são:
1. Cadastrar Pessoa Física ou Organização Não-Governamental (ONG)
2. Criar Projeto Social
3. Realizar ação ou evento social

Para cada um destes processos foi realizada a modelagem BPNM, que está apresentada no diretório [Processos de negócio](https://github.com/mmhqs/EngRequisitos2024/tree/d46c1e8c4e97c88a7c1d65622497d415330823c7/docs/Processos%20de%20neg%C3%B3cio) no presente repositório.

## Visão geral de requisitos
A visão geral dos requisitos está apresentada no diretório [Documento de visão](https://github.com/mmhqs/EngRequisitos2024/tree/29a904a920492e1e7a74ea849d950ea8c435d2c7/docs/Documento%20de%20vis%C3%A3o) no presente repositório.

## *Backlog* de Requisitos - *User Stories* em *Cards*
As histórias de usuário (*user stories*) foram criadas para representar o backlog dos requisitos priorizados. Foram definidas 19 histórias de usuário, que são apresentadas a seguir.

### Cadastro

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntário,<br>Eu quero ser capaz de adicionar meus dados básicos no aplicativo,<br>Para efetuar o cadastro. | - Validar a existência dos dados cadastrados.<br>- Verificar a formatação dos dados. |

### Login

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntário,<br>Eu quero ser capaz de efetuar login,<br>Para utilizar as funcionalidades do aplicativo. | - Possuir cadastro. |

### Alterar Foto de Perfil

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntário,<br>Eu quero poder editar minha foto de perfil,<br>Para otimizar meu perfil. | - Possuir cadastro. |

### Alterar Senha - Necessário

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntário,<br>Eu quero poder alterar minha senha,<br>Para melhorar a segurança da minha conta. | - Possuir cadastro.<br>- Possuir acesso ao email. |

### Alterar Senha - Esqueceu a Senha

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntário,<br>Eu quero poder alterar minha senha,<br>Para entrar no aplicativo caso eu a esqueça. | - Possuir cadastro.<br>- Possuir acesso ao email. |

### Cadastro de Projetos

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntário,<br>Eu quero poder cadastrar um novo projeto social com os dados básicos (nome, descrição, data início, data fim, status e endereço completo),<br>Para facilitar a busca e cadastro de voluntários para o projeto. | - Possuir cadastro.<br>- Validar dados de cadastro. |

### Gerenciar Projetos

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntário,<br>Eu quero poder alterar ou excluir o projeto criado,<br>Para que eu possa manter as informações sempre atualizadas e remover projetos que não são mais relevantes ou que foram concluídos. | - Possuir projeto pré cadastrado.<br>- Apenas voluntários responsáveis pelo projeto podem gerenciá-lo. |

### Convidar Voluntários

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntário,<br>Eu quero ser capaz de enviar links por e-mails e/ou WhatsApp,<br>Para convidar pessoas externas ou pré cadastradas a participarem do projeto. | - Possuir projeto pré cadastrado.<br>- Verificação de e-mail e telefones. |

### Inserir Eventos nos Projetos

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntário,<br>Eu quero inserir eventos dentro de projetos que estão com status ativo,<br>Para organizar e promover ações específicas, como distribuição de brinquedos em comunidades carentes, e associar voluntários a esses eventos de forma eficiente. | - Possuir projeto pré cadastrado.<br>- Validar datas e horários do evento. |

### Inserir Fotos dos Eventos

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntário,<br>Eu quero inserir fotos dos eventos,<br>Para gerar um histórico e um portfólio detalhado de cada Projeto Social cadastrado. | - Possuir evento pré cadastrado. |

### Conversar com Participantes

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntário,<br>Eu quero poder conversar com outros voluntários do projeto,<br>Para socializar e trocar ideias que podem incrementar o projeto. | - Todos na conversa devem participar do mesmo projeto. |

### Filtrar por habilidades e valores

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntária,<br>quero poder pesquisar por trabalhos sociais que se alinhem com minhas habilidades e valores éticos,<br>para encontrar oportunidades relevantes para meu trabalho voluntário. | - O sistema deve permitir filtrar as habilidades e interesses do usuário.<br>- Os resultados da pesquisa devem ser relevantes para os filtros escolhidos. |

### Lista de trabalhos sociais disponíveis

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntária,<br>quero poder visualizar detalhes completos de trabalhos sociais listados, incluindo informações sobre a organização, localização e descrição do trabalho,<br>para tomar decisões informadas sobre onde me voluntariar. | - As informações apresentadas devem ser claras e concisas.<br>- As informações sobre a organização devem ser precisas e atualizadas. |

### Filtrar por categoria

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntária,<br>quero poder filtrar os trabalhos sociais por localização geográfica, tipo de trabalho e requisitos específicos,<br>para encontrar oportunidades que se adequem melhor às minhas necessidades e preferências. | - Os filtros devem ser intuitivos e fáceis de usar.<br>- Os resultados da filtragem devem ser precisos e atualizados. |

### Lista das organizações cadastradas e suas atividades

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntária,<br>quero poder entrar em contato com as organizações listadas diretamente através do aplicativo,<br>para expressar meu interesse em me voluntariar ou obter mais informações sobre suas atividades. | - O sistema deve fornecer opções para entrar em contato, como e-mail ou formulário de contato.<br>- As informações de contato das organizações devem ser precisas e atualizadas. |

### Critério de avaliação e feedback

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como voluntária,<br>quero poder revisar e classificar as organizações e trabalhos sociais listados com base em minha experiência pessoal,<br>para ajudar outros voluntários a tomar decisões informadas. | - O sistema deve permitir que Sandra deixe feedback e avaliações para as organizações e oportunidades de trabalho social. |

### Cadastro de ONG no Aplicativo

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como representante da ONG Terra,<br>Eu quero poder cadastrar os dados básicos da minha organização no aplicativo, incluindo nome da ONG, telefone, e-mail, endereço completo e senha,<br>Para ter acesso às funcionalidades disponíveis e interagir com os voluntários. | - Os campos obrigatórios para o cadastro são: nome da ONG, telefone, e-mail, endereço completo e senha.<br>- O sistema deve permitir a inclusão de uma senha segura, com no mínimo 8 caracteres.<br>- O e-mail fornecido deve ser válido e único, não podendo ser utilizado por outra ONG cadastrada no aplicativo.<br>- O telefone deve ser válido e conter apenas números, com um formato aceitável.<br>- O endereço completo deve ser inserido corretamente, contendo rua, número, bairro, cidade e estado. |

### Edição de Perfil

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como representante da ONG Terra,<br>Eu quero poder editar a foto de perfil da minha organização no aplicativo,<br>Para atualizar nossa imagem e representação visual. | - A ONG deve ter a opção de selecionar uma imagem da galeria de fotos do dispositivo ou tirar uma nova foto para ser utilizada como foto de perfil.<br>- O sistema deve permitir o ajuste e recorte da imagem para garantir uma exibição adequada no aplicativo.<br>- As alterações na foto de perfil devem ser refletidas imediatamente após a conclusão do processo de edição.<br>- O tamanho da imagem de perfil deve ser limitado para garantir uma boa experiência de usuário e economia de espaço de armazenamento.<br>- A ONG deve receber uma confirmação visual após a atualização bem-sucedida da foto de perfil. |

### Divulgação de Vagas de Trabalho Voluntário

| **User Story** | **Critérios de Aceite** |
| --- | --- |
| Como representante da ONG Terra,<br>Eu quero poder divulgar vagas de trabalho voluntário no aplicativo,<br>Para atrair interessados em contribuir com nossas atividades. | - A ONG deve ter a capacidade de cadastrar vagas de trabalho voluntário no sistema, incluindo título, descrição da vaga, requisitos necessários e informações de contato.<br>- As vagas cadastradas devem ser exibidas em uma seção específica do aplicativo, separadas por categorias, como tipo de atividade, período de voluntariado, etc.<br>- Os voluntários interessados devem poder visualizar as vagas disponíveis e obter informações detalhadas sobre cada uma.<br>- A ONG deve receber notificações sobre novas candidaturas para as vagas divulgadas, incluindo informações de contato dos interessados.<br>- Após o preenchimento das vagas, a ONG deve ter a opção de remover ou desativar a divulgação da vaga no aplicativo.<br>- O sistema deve permitir a atualização e edição das informações das vagas de trabalho voluntário, caso necessário.<br>- As vagas divulgadas devem ser exibidas de forma clara e organizada no aplicativo, facilitando a visualização e compreensão por parte dos voluntários em potencial. |

