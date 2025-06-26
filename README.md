# Sistema de Gerenciamento de Tarefas (Full Stack)

Um sistema completo de gerenciamento de tarefas desenvolvido para demonstrar habilidades em desenvolvimento Full Stack, com backend em Java Spring Boot e frontend em React.js, utilizando MongoDB para persistência de dados. O layout foi inspirado no Trello, com funcionalidades de notificação e alternância de tema (claro/escuro).

## Funcionalidades

* **Criação de Tarefas:** Adicione novas tarefas com título, descrição, data e horário de vencimento.
* **Visualização de Tarefas:** Exiba todas as tarefas em um formato de "cartões" intuitivo.
* **Edição de Tarefas:** Modifique título, descrição, data, horário e status de conclusão.
* **Exclusão de Tarefas:** Remova tarefas da lista com confirmação personalizada.
* **Status de Conclusão:** Marque tarefas como concluídas ou pendentes.
* **Notificações do Navegador:** Habilite notificações para tarefas com data e hora específicas.
* **Alternância de Tema:** Alterne entre os temas claro e escuro para uma experiência visual personalizada.
* **Animações:** Animações sutis na adição de tarefas e outras interações.
* **Pop-ups Informativos:** Mensagens de sucesso/erro e confirmação de exclusão personalizadas.

## Tecnologias Utilizadas

### Backend (Java)
* **Java 17+**
* **Spring Boot**: Framework para construção de aplicações Java robustas.
* **Spring Data MongoDB**: Integração simplificada com o banco de dados MongoDB.
* **Apache Maven**: Ferramenta de automação e gerenciamento de projetos.
* **Lombok**: Para reduzir boilerplate code (getters/setters).

### Frontend (React.js)
* **React.js**: Biblioteca JavaScript para construção de interfaces de usuário.
* **Node.js / npm**: Ambiente de execução e gerenciador de pacotes.
* **Axios**: Cliente HTTP para requisições à API.
* **CSS Modules**: Para estilização localmente escopada.
* **Context API**: Para gerenciamento de estado global (Tema, Notificações, Modal de Confirmação).
* **Lucide React**: Biblioteca de ícones moderna e personalizável.

### Banco de Dados
* **MongoDB**: Banco de dados NoSQL baseado em documentos.

## Como Rodar o Projeto Localmente

Para ter este projeto em execução na sua máquina, siga os passos abaixo:

### Pré-requisitos

Certifique-se de ter instalado:
* [**JDK 17 ou superior**](https://www.oracle.com/java/technologies/downloads/)
* [**Node.js e npm**](https://nodejs.org/en/download/)
* [**Apache Maven**](https://maven.apache.org/download.cgi) (opcional, o projeto inclui `mvnw` que o gerencia)
* [**MongoDB Community Server**](https://www.mongodb.com/try/download/community) (e certifique-se de que o serviço está rodando)
* [**Git**](https://git-scm.com/downloads)

### 1. Clonar o Repositório

```bash
git clone [https://github.com/DaviSCR05/reimagined-fortnight](https://github.com/DaviSCR05/reimagined-fortnight)
cd task-management-system