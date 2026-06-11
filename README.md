
<h1>DOCUMENTAÇÃO DE IMPLANTAÇÃO – PORTFOLIOHUB</h1>
<p><strong>Estudante:</strong> Nathan de Andrade Silva</p>
<p><strong>Curso:</strong> Engenharia de Software – Bootcamp I</p>
<p><strong>Data de Entrega:</strong> 14/06/2026</p>

<hr>

<h2>1. Planejamento da Implantação</h2>
<p>A implantação do PortfolioHUB foi realizada utilizando uma abordagem ágil, dividida em sprints diárias para garantir o cumprimento dos prazos e requisitos. O Google Gemini foi configurado como assistente, validando cada tomada de decisão técnica.</p>

<h2>2. Estrutura do Projeto e Integração com GitHub</h2>
<p>O ambiente foi versionado no GitHub sob um repositório dedicado. A integração consome a API oficial do GitHub para buscar repositórios públicos em tempo real, eliminando a necessidade de atualização manual do portfólio.</p>

<table border="1" cellpadding="5" cellspacing="0" style="border-collapse: collapse; width: 100%;">
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th>Componente</th>
      <th>Tecnologia / Recurso</th>
      <th>Função no Projeto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Frontend</strong></td>
      <td>HTML5, CSS3, JavaScript</td>
      <td>Interface visual responsiva e interativa.</td>
    </tr>
    <tr>
      <td><strong>Integração</strong></td>
      <td>Fetch API / GitHub REST API</td>
      <td>Consumo automatizado dos dados de projetos.</td>
    </tr>
    <tr>
      <td><strong>Controle de Versão</strong></td>
      <td>Git & GitHub</td>
      <td>Gerenciamento de código e histórico de alterações.</td>
    </tr>
  </tbody>
</table>

<br>

<h2>3. Gestão de Usuários e Segurança</h2>
<p>Seguindo as orientações de segurança validadas pelo Gemini, foram implementadas as seguintes práticas no ecossistema do projeto:</p>
<ul>
  <li><strong>Proteção de Branch:</strong> Bloqueio de commits diretos na branch <code>main</code>, exigindo Pull Request com revisão.</li>
  <li><strong>Análise de Vulnerabilidades:</strong> Ativação do GitHub Dependabot para monitoramento ativo de dependências inseguras.</li>
  <li><strong>Higiene de Credenciais:</strong> Inclusão de arquivos de configuração local e variáveis de ambiente no <code>.gitignore</code>.</li>
</ul>

<h2>4. Fluxo de Trabalho e Práticas de Colaboração</h2>
<p>Adotou-se o modelo simplificado de Git Flow:</p>
<ol>
  <li><code>main</code>: Branch protegida, contendo o código homologado em produção.</li>
  <li><code>feature/*</code>: Branches temporárias criadas para o desenvolvimento de novos componentes visuais ou lógicos.</li>
</ol>

