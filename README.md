<h2>To-do List - Angular 16</h2>

<p>Este projeto é uma aplicação de lista de tarefas (To-do List) desenvolvida com <strong>Angular 16</strong>. Ele demonstra o uso de novos conceitos e recursos introduzidos nesta versão, como <strong>signals</strong>, <strong>mutate</strong> e a injeção de dependências via função <strong>inject</strong>. A aplicação permite que os usuários criem, visualizem, concluam e removam tarefas, com as informações persistidas no LocalStorage.</p>

<p>Você pode acessar a aplicação em <a href="https://todo-list-v-16.vercel.app/" target="_blank">https://todo-list-v-16.vercel.app/</a>.</p>

<h3>Funcionalidades Principais:</h3>
<ul>
  <li><strong>Criação de tarefas</strong>: Os usuários podem adicionar tarefas com título e descrição através de um formulário reativo.</li>
  <li><strong>Gerenciamento de tarefas</strong>: As tarefas são separadas em abas de "Em andamento" e "Concluídas", utilizando o <code>mat-tab-group</code>.</li>
  <li><strong>Persistência de dados</strong>: As tarefas são salvas no LocalStorage para garantir que os dados permaneçam após o recarregamento da página.</li>
  <li><strong>Modal de criação</strong>: Utiliza o <code>MatDialog</code> para exibir um formulário em modal, onde os usuários podem adicionar novas tarefas.</li>
</ul>

<h3>Conceitos e Tecnologias Utilizadas:</h3>
<ul>
  <li><strong>Signals</strong>: Utilizado para gerenciar o estado das tarefas de forma reativa e eficiente. O serviço <code>TodoSignalsService</code> utiliza signals para rastrear e atualizar o estado da lista de tarefas.</li>
  <li><strong>Mutate</strong>: A função <code>mutate</code> é usada para modificar o estado do signal diretamente, como ao adicionar, remover ou marcar tarefas como concluídas.</li>
  <li><strong>Injeção de Dependências com Inject</strong>: O projeto utiliza o novo método <code>inject()</code> para injetar dependências diretamente dentro de componentes e serviços.</li>
  <li><strong>Angular Material</strong>: A interface do usuário é construída com componentes do Angular Material, como botões, formulários, cards e diálogos.</li>
</ul>

<h3>Como Executar:</h3>
<ol>
  <li>Instale as dependências do projeto:
    <pre><code>npm install</code></pre>
  </li>
  <li>Execute o servidor de desenvolvimento:
    <pre><code>ng serve</code></pre>
  </li>
  <li>Acesse a aplicação em <code>http://localhost:4200</code>.</li>
</ol>
