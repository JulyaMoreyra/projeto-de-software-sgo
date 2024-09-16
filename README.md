# Sistema de Gestão das Olimpíadas (SGO)
## Descrição do Projeto
O Sistema de Gestão das Olimpíadas (SGO) foi desenvolvido para coordenar diversos aspectos das Olimpíadas.

Ele permite o gerenciamento de competições, inscrições de atletas, alocação de locais para as provas, e controle de resultados.

## Participantes do Projeto
* [Ana Flávia de Carvalho Santos](https://github.com/anaflaviacsantos)
* [Júlia Moreira Nascimento](https://github.com/JulyaMoreyra)

## Funcionalidades
* **Cadastro de Competições:** Gerencia o cadastro de competições, incluindo modalidade, data, horário, local e lista de atletas inscritos.
* **Inscrição de Atletas:** Permite que atletas de diferentes países se inscrevam em competições específicas. Um atleta pode participar de várias competições, mas só pode representar um país em cada modalidade.
* **Alocação de Locais:** Administra a alocação de locais para as competições, garantindo que não haja conflitos de horário.
* **Controle de Resultados:** Registra os resultados das competições, determinando os atletas classificados em primeiro, segundo e terceiro lugares.
* **Relatórios de Medalhas:** Gera relatórios detalhados de medalhas, mostrando o desempenho de cada país com base nas medalhas de ouro, prata e bronze conquistadas.

## Requisitos
### Requisitos Funcionais
#### RF01: Cadastro de Competições
* O sistema deve permitir o cadastro de competições pelo comitê olimpico.

#### RF02: Inscrição de Atletas
* O sistema deve permitir que os comites olímpicos nacionais se inscrevam seus atletas em competições específicas, podendo participar de várias modalidades.

#### RF03: Alocação de Locais
* O sistema deve permitir a alocação de locais para competições, garantindo que não haja conflitos de horário.

#### RF04: Registro de Resultados
* O sistema deve permitir o registro dos resultados das competições, incluindo o vencedor e os classificados em segundo e terceiro lugar.

#### RF05: Geração de Relatórios de Medalhas
* O sistema deve gerar relatórios de medalhas, exibindo o desempenho de cada país com base nas medalhas de ouro, prata e bronze conquistadas.

#### RF06: Consultar Competições e Resultados
* O sistema deve permitir a consulta de competições cadastradas e seus respectivos resultados.

### Requisitos Não Funcionais
#### RNF01: Confiabilidade
* O sistema deve garantir que os dados inseridos, como resultados e inscrições, sejam armazenados corretamente e estejam disponíveis a qualquer momento.

#### RNF02: Escalabilidade
* O sistema deve ser escalável, suportando um grande número de competições, atletas e países conforme o evento cresce.

#### RNF03: Segurança
* O sistema deve garantir que apenas usuários autorizados possam cadastrar competições, registrar resultados e gerar relatórios, implementando autenticação e controle de acesso.

#### RNF04: Disponibilidade
* O sistema deve ter uma disponibilidade de 99,9%, garantindo que os usuários possam acessar as informações sobre as competições e resultados a qualquer momento.

#### RNF05: Portabilidade
* O sistema deve ser acessível via navegadores web em dispositivos móveis e desktops, sem perda de funcionalidades

## Diagramas UML

### Diagrama de Caso de Uso
![diagrama-de-casos-de-uso](https://github.com/user-attachments/assets/74097f2e-5dd0-4f81-9f1c-d3dec3c133b6)

### Diagrama de Classes 
![Diagrama de Classe](https://github.com/user-attachments/assets/fb887e20-f8ed-4345-9268-5229ec643049)


### Diagrama de Pacotes
![Package Diagram](https://github.com/user-attachments/assets/c27e333e-cbfd-4a96-b113-4f2bf422f1a6)

### Diagrama de Componentes

### Diagrama de Implantação

