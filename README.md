# Paycon Processo Seletivo
<h2>Padrão da base de dados</h2>
<p>A tabela inicia na célula A4, tem as colunas descritas nos próximos itens e tem a data de extração na célula A2, que é atuzalizada quando a base for extraida</p>
<h2>Explicação da base de dados.</h2>
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
  <li><strong>Saber a quantidade de casos novos</strong> : o identificador desse caso são os status ativos sem encerramento</li>
  <li><strong>Saber a quantidade de casos que mudaram de valor</strong> : o identificador desse caso é a diferença entre a ativação e encerramento de um processo</li>
  <li><strong>Saber se o caso aumentou ou diminuiu de valor</strong> : o identificador desse caso é a diferença entre a ativação e encerramento de um processo</li>
  <li><strong>Saber quanto foi o aumento ou diminuição de valor, caso haja</strong> : o identificador desse caso é a diferença entre a ativação e encerramento de um processo</li>
</ul>
<h2>Explicação da tela</h2>
<h3>Home</h3>
<p>Clique no botão "Home" para entrar na tela Home;</p>
<p>Aqui são encontrados os KPI's do sistema.</p>
<h3>Base de Dados</h3>
<p>Clique no botão "Base de Dados" para entrar na tela Base de Dados;</p>
<p>Aqui é encontrada toda base de dados do sistema, e im filtro dinâmico para selecionar processos ativos e encerrados, essa tela é somente uma tela de visualização.</p>
<h3>Adicionar Base</h3>
<p>Clique no botão "Adicionar Base" para adicionar uma base de dados nova ao sistema;</p>
<p>Primeiramente deve-se dizer com certeza se a base está no padrão, de acordo com esse documento;</p>
<p>Após selecionar "Sim" você sera direcionado a uma tela para escolher seu arquivo em Excel;</p>
<p>Ao clicar em abrir aguarde o carregamento da base no sistema.</p>
<h3>Editar Base</h3>
<p>Clique no botão "Editar Base" para excluir alguma adição feita;</p>
<p>Primeiramente selecione a linha que contem a base que deseja excluir;</p>
<p>Após clicar duas vezes nessa linha, você deve logar no sistema como usuário (user: admin, login: admin);</p>
<p>Após logado confirme se quer mesmo apagar essa base;</p>
<p>A base será excluida do sistema</p>
<h3>Atualizações</h3>
<p>Clique no botão "Atuaizações" para entrar na tela Atuaizações;</p>
<p>Aqui é encontrado o histórico de atualizações do sistema.</p>
<h3>Relatório</h3>
<p>Clique no botão "Relatório" na página Home para enviar um email a alguem contendo o relatório de KPI's;</p>
<p>Digite o email de quem quer enviar o arquivo;</p>
<p>O arquivo é enviado.</p>
<h3>Excluir Base</h3>
<p>Clique no botão "Excluir Base" na página Atualizações ou Base para deletar todas as bases de dados no sistema;</p>
<p>Você deve logar no sistema como usuário (user: admin, login: admin);</p>
<p>Todas as bases serão deletadas</p>
<hr>
<span>Agradeço a participação no processo seletivo e fico no aguardo da minha avaliação</span>
