
# Sistema de Controle de Curativos | UBS Cidade Satélite

Um sistema web simples e de página única para o gerenciamento de pacientes e controle de procedimentos de curativos na Unidade Básica de Saúde (UBS) Cidade Satélite. A aplicação é totalmente client-side, utilizando o armazenamento local do navegador para persistir os dados, garantindo privacidade e funcionamento offline.

## ✅ Funcionalidades Principais

  * **Autenticação Segura:** Tela de login para proteger o acesso aos dados dos pacientes. As senhas são verificadas usando hash (SHA-256), garantindo que a senha original nunca seja exposta no código.
  * **Níveis de Permissão:**
      * **Administrador (`admin`):** Acesso total ao sistema, incluindo a capacidade de adicionar, editar e excluir pacientes e seus respectivos atendimentos.
      * **Enfermagem (`enfermagem`):** Acesso para as operações do dia a dia. Pode adicionar novos pacientes e registrar/editar atendimentos, mas não tem permissão para excluir registros.
  * **Gerenciamento de Pacientes (CRUD):**
      * Adicionar novos pacientes com informações detalhadas.
      * Listar todos os pacientes cadastrados.
      * Buscar pacientes em tempo real por nome ou número do Cartão SUS.
      * Editar informações de pacientes existentes.
  * **Prontuário Individual:**
      * Visualizar detalhes completos do paciente e da lesão.
      * Adicionar um histórico de atendimentos (procedimentos) com data e agendamento de retorno.
  * **Relatórios para Impressão:**
      * Gerar e imprimir um prontuário detalhado para um paciente específico.
      * Gerar e imprimir uma lista geral de todos os pacientes cadastrados, organizada em ordem alfabética.
  * **Persistência de Dados:** Todas as informações são salvas localmente no navegador (`localStorage`), permitindo que os dados não se percam ao fechar a página.

## 💻 Tecnologias Utilizadas

  * **HTML5:** Estrutura da página.
  * **CSS3:** Estilização, layout e responsividade.
  * **Bootstrap 4.5:** Framework CSS para componentes de UI (modais, botões, etc.).
  * **JavaScript (Vanilla):** Toda a lógica da aplicação, manipulação de dados e interatividade.
  * **jQuery:** Utilizado como dependência do Bootstrap para o funcionamento dos modais.
  * **Web Crypto API:** Para a geração segura do hash de senhas.

## 🚀 Como Executar o Sistema

Este sistema não requer instalação de servidores ou dependências complexas.

1.  Salve o código principal em um arquivo com a extensão `.html` (por exemplo, `index.html`).
2.  Abra este arquivo em um navegador de internet moderno (Google Chrome, Firefox, Microsoft Edge, etc.).
3.  Pronto\! O sistema já estará funcionando.

**Importante:** Como os dados são salvos no `localStorage` do navegador, cada navegador ou computador terá sua própria base de dados isolada.

## 👨‍💻 Autor

Desenvolvido por **ANTONIEL SOUSA**.

## 📄 Licença

Este projeto é de código aberto e pode ser modificado e distribuído livremente.
