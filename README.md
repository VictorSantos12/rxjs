<div align="center">
  <img src="https://user-images.githubusercontent.com/61476935/115932575-9432b200-a463-11eb-802d-5a056f7dbb85.png">
</div>
<br>
<img src="https://img.shields.io/static/v1?label=JavaScript&message=Library&color=pink&style=for-the-badge&logo=JavaScript"/>


O RxJS é uma biblioteca de composição de programas assíncronos e baseados em eventos usando sequências de observables. Ela fornece um
núcleo chamado de Observable, e receptores (Observer, Schedulers, Subjects), além de operadores inspirados em métodos comuns a vetores
(map, filter, reduce, every, etc), os quais permitem tratar eventos assíncronos como collections. O ReactiveX combina o Observer Pattern
o Interator Pattern e Programação Funcional com collections para preencher a necessidade por um método de gerenciamento de sequências de
eventos ideal

Os conceitos fundamentais em RxJS, cujas funções são prover o gerenciamento de eventos assícronos são: 

<ul>
  <li>
    <strong>Observable:</strong> representa a ideia de uma coleção de valores ou futuros eventos invocáveis
  </li>
  <li>
    <strong>Observer:</strong> é uma coleção de callbacks que sabem como tratar valores entregues pelo Observable
  </li>
  <li>
    <strong>Subscription:</strong> representa a execução de um Observable, sendo primariamente inútil para o cancelamento de execução
  </li>
  <li>
    <strong>Operators:</strong> são funções puras que permitem um estilo de programação funcional para lidar com collections, com operações
    como map, filter, concat, reduce, etc.
  </li>
  <li>
    <strong>Subject:</strong> é o equivalente a um EventEmitter, sendo o único meio de emitir um valor ou evento para muilplos Observers
  </li>
  <li>
    <strong>Schedulers:</strong> são dispatchers centralizados para controlar a simultaneidade, permitindo coordenar quando o processamento
    acontece, por exemplo, setTimeout ou requestAnimationFrame ou outros.
  </li>
</ul>

<h1>
  Observer Pattern
</h1>

O padrão de desenvolvimento Observer define que um objeto central chamado de <strong>Subject</strong> mantenha uma lista de
suas dependências, estas chamadas de <strong>Observers</strong>, as notificando automaticamente caso aja qualquer mudança de
estado

<div align="center">
  <img width="80%" src="https://user-images.githubusercontent.com/61476935/116111712-4a2d1480-a68d-11eb-937f-d55d8433563c.png">
</div>

<h1>
  Iterator Pattern
</h1>

<h1>
  Functional Programming
</h1>


 
