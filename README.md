<h1>Redes-M6-FP01-14648-Desenvolvimento de Interface Web para Inventário de Computadores (PHP + SQL)</h1>

<h2>Identificação</h2>
<p>Nome:</p>
<p>Turma:  2ºI</p>
<p>Disciplina: REDES – M6 – Programação de Sistemas de Informação</p>  
<p>Curso: GPSI – 2.º Ano </p> 

<h2>Objetivo do Projeto</h2>
<p>O Objetivo deste projeto foi a criação de uma base de dados SQL com um site criado a partir da linguagem de programação PHP. A Base de dados deste projeto tem como objetivo a organização dos computadores respectivos de cada sala, exibindo uma lista deles.
</p>
<p>Este Programa também permite a visualização das especificações de Hardware e Software de cada computador individual.</p>

<h2>Estrutura do Projeto</h2>
<p>Este Projeto tem duas partes principais, ambas baseadas no site do InfinityFree. A Base de dados SQL e o Site PHP.</p>
<p>A Base de dados e os seus dados são geridos e guardados num servidor da InfinityFree com recurso php-myadmin.net. Esta Base de Dados tem 4 tabelas: Computadores, Salas, Software e Computador_Software.</p>
<p>As 4 tabelas têm multiplos atributos além das Primary Keys, que pode ser vistos abaixo:</p>
<details>
  <summary>Tabelas</summary>
  <details>
    <summary>Computadores</summary>
    <ul>
      <li>ID_Computador (PK)</li>
      <li>Nome_Computador</li>
      <li>Processador</li>
      <li>RAM</li>
      <li>Armazenamento</li>
      <li>Placa_Grafica</li>
      <li>Sistema_Operativo</li>
      <li>ID_Sala(FK)</li>
    </ul>
  </details>
  <details>
    <summary>Salas</summary>
    <ul>
      <li>ID_Sala (PK)</li>
      <li>Nome_Salas</li>
      <li>Localização</li>
    </ul>
    
  </details>
  <details>
    <summary>Software</summary>
    <ul>
      <li>ID_Software (PK)</li>
      <li>Nome_Software</li>
      <li>Versão</li>
    </ul>
    
  </details>
   <details>
    <summary>Software_Computadores</summary>
    <ul>
      <li>ID_Computador (FK)</li>
      <li>ID_Software (FK)</li>
    </ul>
  </details>
</details>
<p>As 4 tabelas utilizam as suas Primary Keys respectivas para conectar as informações entre elas, como por exemplo, o Software esteja no Computador correto, o Computador na Sala Correta, Etc...</p>


