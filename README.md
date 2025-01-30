# ListaDeTarefas

Uma aplicação web simples para gerenciar tarefas, com funcionalidades de login, adição de tarefas e organização por data, local ou usuário.

## Funcionalidades

- **Sistema de Login**: Os usuários podem fazer login com um nome de usuário para identificar quem adicionou cada tarefa.
- **Adição de Tarefas**: Adicione tarefas com um título e um local.
- **Organização de Tarefas**: As tarefas podem ser organizadas por:
  - Data de criação
  - Local
  - Usuário que adicionou
- **Persistência de Dados**: As tarefas são salvas no `localStorage` do navegador, permitindo que permaneçam disponíveis mesmo após atualizar a página.

## Como Usar

1. **Login**:
   - Insira um nome de usuário no campo de login e clique em "Entrar".
   
2. **Adicionar Tarefas**:
   - Após o login, insira o nome da tarefa e o local nos campos correspondentes.
   - Clique em "Adicionar" para incluir a tarefa na lista.

3. **Organizar Tarefas**:
   - Use o menu dropdown para selecionar o critério de ordenação (Data, Local ou Usuário).
   - A lista de tarefas será automaticamente reorganizada conforme o critério selecionado.

4. **Visualizar Tarefas**:
   - As tarefas são exibidas em uma lista, mostrando o título, local, usuário que adicionou e a data de criação.

## Tecnologias Utilizadas

- **HTML**: Estrutura da página.
- **CSS**: Estilização e layout.
- **JavaScript**: Lógica de front-end e interatividade.
- **LocalStorage**: Armazenamento local das tarefas.

## Como Executar Localmente

Clone este repositório:
https://github.com/PedroSMorais/ListaDeTarefas.git
