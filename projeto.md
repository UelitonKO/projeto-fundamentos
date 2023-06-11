<img src='/img/logo.png' alt='logo da empresa' width='50px' heidth='50px'/>

# *Paradisee*

# PROJETO DE SOFTWARE

## *Stakeholders*
|Alana Tarcila Martins Alves|Gerente de Projeto|alanaimportant@gmail.com|
|Daiany Kelly Campos Silva||Designer de Inteface com o Usuário|daiihkel@gmail.com|
|Diego Vinicius Daniel da Silva|Analista de Teste|diegoviny000@gmail.com|
|João Pedro Pires e Macedo|Testador de Software|joaopedropiresemacedo2006@gmail.com|
|Uéliton Pereira Novais|Programador|elrockimportant@gmail.com|

# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [ESCOPO DO PROJETO](#escopo-do-projeto)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
  * [CONVENÇÕES, TERMOS E ABRIVEAÇÕES][def]
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
  * [VIABILIDADE TÉCNICA](#viabilidade-técnica)
  * [VIABILIDADE ECONÔMICA](#viabilidade-econômica)
  * [VIABILIDADE ORGANIZACIONAL](#viabilidade-organizacional)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | Paradisee |
| GERENTE DO PROJETO | Alana Tarcila Martins Alves |
| PRINCIPAL OBJETIVO | Oferecer uma forma de entreternimento através de diferentes midias que poderão ser abertas e utilizadas por qualquer tipo de público. |
| BENEFÍCIOS ESPERADOS |* ;<br/>* Promover o entreternimento para diversas idades;<br/>* Melhorar o intelectual com filmes e livros educacionais disponiveis;<br/>* Redução de acessos indevidos em sites improprios para isso;<br/>* Deixar os usuarios constantemente atualizados das novidades. |
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2023 - 07/12/2023 |

[ [INÍCIO](#Paradisee) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se à todos envolvidos nesse projeto. O objetivo do projeto **Paradisee** é ser um banco de informações sobre diversos tipos de entretenimentos como filmes e livros, contendo seus autores, nacionalidade, data de criação, locais onde podem ser acessados, entre outras informações.

## CONCEPÇÃO DO SISTEMA


Foram usados métodos para que pudessem ser obtidos os requisitos do sistema: 
* Reunião: 
  * Os envolvidos no projeto debateram para decidir qual tipo de projeto era mais agradável a todos;
* Consulta com especialista: 
  * Wagner, docente do curso técnico em informática na disciplina de Fundamentos e Analise de Sistemas que orientou na concepção do projeto inicial devido sua experiência em trabalhar na área; 
* Pesquisa: 
  * Afim de entender melhor sobre o projeto e sua acessibilidade, os envolvidos fizeram pesquisas sobre o assunto.



## CONVENÇÕES, TERMOS E ABREVIAÇÕES

Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são aceitos a seguir:

* Conteúdo: Quando citado no conteúdo do projeto, diz respeito a filmes, séries, livros, jogos, músicas e canais.
* Cultura pop: Conteúdo principalmente de entretenimento que ficou popular ou ganhou espaço no seu meio.
* Login: Crie ou inicie uma sessão em sites ou aplicativos.
* Logout: encerrar uma sessão.
* Streaming: Tecnologia que permite consumir vídeos e áudios pela internet sem a necessidade de baixar os mesmos.

[ [INÍCIO](#Paradisee) ]

# DESCRIÇÃO GERAL

## ESCOPO DO PROJETO

### NO ESCOPO

O projeto consiste na construção de um site interativo *(Paradisee)*, que possiblite o entretenimento do usuario de forma simples e pratica. O projeto visa proporcionar ao usuario uma forma de se divertir sem ter que sair de sua casa, e que possa ser utilizada por todos conforme sua faixa etaria. 
O escopo do **site** pode ser consultado nos [requisitos do software](#requisitos-do-software)

### FORA DO ESCOPO

Não fazem parte do escopo do projeto:

* Treinamento de instalação, configuração, administração e  utilização do sistema;
* Escolha de um tema do projeto;
* Consumo dos conteúdos apresentados pelo site.



## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Realizam as tarefas comuns a todos os usuários, tal como: logar e enviar mensagens. Todos demais usuários estendem as funcionalidades do UsuárioPadrão|
|**Administrador:**|Responsáveis pelo gerenciamento das entidades pertinentes ao site e pela alocação de outros administradores.|

## Abrangência e sistemas similares

### Abrangência:

O sistema irá conter ferramentas para construção de um plano de aulas que esteja de acordo com os objetivos e metodologia de uma turma ministrda peloa professor. O professor através de ferramentas (como Chat, Fórum, Base de Documentos) irá montar o programa desta disciplina que deverá ser seguido pelo aluno usuário do sistema. O professor terá a liberdade de criar atividades (textos e questionários) e determinar prazos a serem cumpridos pelos alunos. Serão armazenadas as resoluções dos alunos para serem corrigidas pelo professor posteriormente, gerando estatísticas do desempenho de cada aluno e da turma. O sistema também irá prover o gerenciamento das entidades que compõem a instituição e os usuários do sistema.

Dentre as ferramentas de comunicação do sistema existirão as assíncronas, como Chat, onde poderão ser feitas reuniões, discussões, explicações conjuntas ou qualquer outra atividade de comunicação. O Fórum consiste na ferramenta síncrona usada para os mesmos fins do Chat.

Das ferramentas de planejamento podemos citar:

* **Avaliações e Exercícios:** serão criadas tarefas a serem entregues pelos alunos nos determinados prazos;

* **Anúncios:** espaço para criação de avisos e informes aos alunos de uma determinada turma;

* **Manipulação de Arquivos:** haverá um diretório onde podem ser acumulados arquivos de diversos tipos pelos usuários;

* **Planejamento de Aulas:** planejamento de uma aula estruturada com leituras e exercícios.

### Sistemas similares:

No cenário atual da universidade se encontra um sistema que é responsável por realizar tal tarefa, denominado Virtus, porém o sistema não atende todas as necessidades, não sendo considerado satisfatório pela maioria dos usuários.

No cenário nacional encontram-se três sistemas que se destacam:

**AulaNet:** é um ambiente de software baseado na Web, desenvolvido no Laboratório de Engenharia de Software - LES - do Departamento de Informática da PUC-Rio, para administração, criação, manutenção e participação em cursos à distância.
WebAula: é um produto formado por soluções integradas de gerenciamento de aprendizagem, conhecimento e conteúdos on-line, resultado de uma joint venture entre as empresas Zargon e Poliedro.

**TelEduc:** é um ambiente para a criação, participação e administração de cursos na Web. Ele foi concebido tendo como alvo o processo de formação de professores para informática educativa, baseado na metodologia de formação contextualizada desenvolvida por pesquisadores do Nied (Núcleo de Informática Aplicada à Educação) da Unicamp.

No cenário internacional os sistemas de maior porte são:

**WebCT:** O WebCT é um programa que possibilita a criação de ambientes educacionais na Internet, desenvolvido pela University of British Columbia - Canadá. Ele permite a colocação do conteúdo de um curso na Internet pelo professor e, em seguida, o cadastro os alunos que participarão daquele curso. O objetivo principal é possibilitar a interação entre tais sujeitos através de ferramentas de trabalho em grupo, tais como: fóruns de discussão, chat, palestras on-line, além de facilitar a comunicação professor-aluno, através da publicação de notas e gabaritos de avaliações.

**Blackboard:** é um sistema de autoria extremamente amigável, desenvolvido para ser utilizado por educadores e profissionais interessados em aplicar as novas tecnologias interativas da rede na educação, contribuindo para a metodologia de ensino presencial e potencializando o processo de ensino e aprendizagem a distância.

## Suposições e dependências
O sistema necessita de um servidor web para sua hospedagem.

Os usuários devem utilizar um computador com a seguinte configuração mínima:

* Processador Dual Core 2GHz ou superior
* 2Gb de memória RAM
* 5Gb de armazenamento em disco
* Para uso do sistema é preciso ter instalado o Java SE versão 8 e o MySql versão 8.0.28.

# ESTUDO DE VIABILIDADE

Uma vez definidos a necessidade para o sistema e seus requisitos de negócio, é possível compreender melhor o projeto do sistema proposto para elaborar o estudo de viabilidade com os seguintes destaques:

## Viabilidade Técnica
Os colaboradores da empresa contratante possuem bastante experiência com aplicações desta natureza, os analistas também estão familiarizados com esta área de aplicação comercial, porém o sistema utiliza uma tecnologia nova, com a qual os analistas e programadores não estão familiarizados. No que se refere ao tamanho do sistema, trata-se de um projeto de médio porte, com baixo nível de complexidade, que não será integrado a outros sistemas, limitando-se a atender a demanda da escola no que se refere à EaD, que, atualmente possui 1.000 alunos matriculados. Conclui-se que o projeto possui viabilidade técnica, em virtude dos baixos riscos identificados.

## Viabilidade Econômica

Foi realizada uma análise de custo-benefício, e, mesmo com estimativas conservadoras do retorno sobre o investimento e dos benefícios totais, este projeto é viável economicamente. Após a implantação, espera-se uma melhoria na qualidade dos serviços prestados e aumento da capacidade de vagas da unidade escolar.

## Viabilidade Organizacional

Do ponto de vista organizacional, este projeto apresenta baixo risco. Os diretores e coordenadores da instituição demonstram forte interesse no projeto. Espera-se que os professores e alunos aprovem a implantação do sistema, visto que atualmente a escola não possui uma ferramenta específica para o controle das informações, o que está provocando enormes transtornos para a instituição.


[ [INÍCIO](#paradisee) ]

# Metodologia Adotada no Desenvolvimento


[ [INÍCIO](#paradisee) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001 |Cadastro de usuário |Este caso de uso serve para que o usuário possa cadastrar-se ao sistema. |
|RF-020 |E-mail de confirmação |Este caso de uso serve para que o sistema envie um e-mail de confirmação de cadastro ao usuário. |
|RF-002 |Efetuar login |Este caso de uso serve para que o usuário possa conectar-se ao sistema. |
|RF-003 |Recuperar senha |Este caso de uso serve para que o usuário possa recuperar sua senha ao esquecê-la. |
|RF-004 |Tela de buscas |Este caso de uso serve para que o usuário possa buscar as formas de entretenimento por titulos, autores, diretores, atores, etc. |
|RF-005 |Histórico de buscas |Este caso de uso serve para que o usuário tenha acesso ao seu histórico de pesquisas. |
|RF-006 |Controle de idade |Este caso de uso serve para que o usuário receba indicações conforme sua idade. |
|RF-007 |Solicitação de conteúdo |Este caso de uso serve para que o usuário possa solicitar o conteúdo que ele deseja ver no site, que não está disponível. |
|RF-008 |Lista de favoritos |Este caso de uso serve para que o usuário consiga criar uma lista de favoritos. |
|RF-009 |Estabilidade |Este caso de uso serve para que o sistema seja capaz de aumentar ou diminuir conforme o necessário. |
|RF-010 |Confiabilidade |Este caso de uso serve para que o sistema seja confiavel e atenda aos requisistos do usuários. |
|RF-011 |Conteúdo |Este caso de uso serve para que o sistema seja capaz de identificar e salvar conteúdos. |
|RF-012 |Comentário |Este caso de uso serve para que o usuário tenha a opção de interagir dentro do site. |
|RF-013 |Notificação |Este caso de uso serve para que o sistema envie notificações de atualização de conteúdo ao usuário. |
|RF-014 | |Este caso de uso serve para que o usuário receba indicações conforme sua idade. |
|RF-015 | |Este caso de uso serve para que o usuário receba indicações conforme sua idade. |
|RF-016 | |Este caso de uso serve para que o usuário receba indicações conforme sua idade. |
|RF-017 | |Este caso de uso serve para que o usuário receba indicações conforme sua idade. |
|RF-018 | |Este caso de uso serve para que o usuário receba indicações conforme sua idade. |
|RF-019 | |Este caso de uso serve para que o usuário receba indicações conforme sua idade. |



## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 |Atuação |O sistema deve ser capaz de lidar com o número necessário de usuários sem qualquer degradação no desempenho. |
|RNF-002 |Disponibilidade |O sistema deve estar disponível quando necessário. |
|RNF-003 |Manutenção |O sistema deve ser fácil de manter e atualizar. |
|RNF-004 |Portabilidade |O sistema deve ser capaz de rodar em diferentes plataformas com alterações mínimas. |
|RNF-005 |Usabilidade |O sistema deve ser fácil de usar e entender. |
|RNF-006 |Publicidade |possivel a integração de anúncios futuros. |
|RNF-007 |Deletar dados do usuários |O sistema deve ser capaz de deletar dados próprios de usuário. |
|RNF-008 |Interoperabilidade |O sistema deverá se comunicar com o SQL Server. |
|RNF-009 |Integração |O sistema integra com outra aplicação. |
|RNF-010 |interação de usuário |O sistema deve permitir a interação do usuário. |

[ [INÍCIO](#paradisee) ]


# Prototipagem

[Protótipo criado no FIGMA em 2022 por estudantes](https://www.figma.com/file/iNC7wyX9zP7Kmn3BhiCFGf/Fals6Hood-(Prot%C3%B3tipo-criado-por-estudantes-em-2022)?node-id=0%3A1&t=B16hgeZP3MSURCCa-1)

![Imagem do Protótipo](/img/home.png)

[ [INÍCIO](#paradisee) ]


# Diagrama de Casos de Uso


![Diagrama de Casos de Uso](/img/use_case_placas.png)

## Descrição / Especificação dos Casos de Uso

### UC-01 - Cadastrar Professor

|UC-01 - Cadastrar Professor|           
|:---|
|**Descrição/Objetivo:** Permite a inclusão de novos professores no Sistema|
|**Atores: Administrador**|
|**Pré-condições:** O usuário precisa estar cadastrado e logado|
|**Pós-condições:** Será apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário seleciona a opção cadastrar professor|
|2. Os dados do professor são inseridos|
|3. O usuário clica em salvar|
|4. Um novo ID é gerado |
|5. É apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Campo obrigatório não preenchido** |
|1. Uma mensagem será apresentada para o usuário, informando que existe(m) campos obrigatórios que não foram preenchidos |
|2. O cursor será posicionado no primeiro campo obrigatório que não foi preenchido |
|**A2: Data de nascimento inválida** |
|1. Uma mensagem será apresentada para o usuário, informando que a data informáda não é válida|
|2. O cursor será posicionado para o campo data|


## Matriz de Rastreabilidade


| REQUISITO |UC-01|UC-02|UC-03|UC-04|UC-05|UC-06|UC-07|UC-08|UC-09| UC-10|     
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|RF-001|X| | | | | | | | | |
|RF-002| |X| |X| | | | | | |

[ [INÍCIO](#paradisee) ]

# Diagrama de Classes

[ [INÍCIO](#paradisee) ]

# Diagrama de Sequências

[ [INÍCIO](#paradisee) ]

# Diagrama de Atividades


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)

[def]: #convenções-termos-e-abreviações