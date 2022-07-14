# Paycon Processo Seletivo
<h2>Explicação da base de dados</h2>
<h3>Base 1</h3>
<h4>Data de extração:</h4>
<p>Quando for extraido para o arquivo "Indicadores" atualizar essa data</p>
<h4>Colunas:</h4>
<ul>
  <li><strong>ID</strong> (integer): Id do processo que foi cadastrado ou editado</li>
  <li><strong>Processo</strong> (string): Texto que identifica algumas caracteristicas do projeto, único por projeto</li>
  <li><strong>Status</strong> (string): Texto que identifica se o processo está ATIVO ou ENCERRADO</li>
  <li><strong>Valor do processo</strong> (currency): Valor monetário que representa o valor do processo quando foi cadastrado ou editado</li>
</ul>
<h3>Base 2</h3>
<h4>Data de extração:</h4>
<p>Quando for extraido para o arquivo "Indicadores" atualizar essa data</p>
<h4>Colunas:</h4>
<ul>
  <li><strong>ID</strong> (integer): Id do processo que foi cadastrado ou editado</li>
  <li><strong>Processo</strong> (string): Texto que identifica algumas caracteristicas do projeto, único por projeto</li>
  <li><strong>Status</strong> (string): Texto que identifica se o processo está ATIVO ou ENCERRADO</li>
  <li><strong>Valor do processo</strong> (currency): Valor monetário que representa o valor do processo quando foi cadastrado ou editado</li>
</ul>
<h2>Requisitos desenvolvidos</h2>
<ul>
  <li><strong>Saber a quantidade de casos que foram excluídos</strong>: o identificador desse caso é o valor monetário nulo com status encerrado e sem ativação</li>
  <li><strong>Saber a quantidade de casos novos</strong> :o identificador desse caso são os status ativos sem encerramento</li>
  <li><strong>Saber a quantidade de casos que mudaram de valor</strong> :o identificador desse caso é a diferença entre a ativação e encerramento de um processo</li>
  <li><strong>Saber se o caso aumentou ou diminuiu de valor</strong> :o identificador desse caso é a diferença entre a ativação e encerramento de um processo</li>
  <li><strong>Saber quanto foi o aumento ou diminuição de valor, caso haja</strong> :o identificador desse caso é a diferença entre a ativação e encerramento de um processo</li>
</ul>
