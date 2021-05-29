<h1>Habilidades</h1>

<p>Neste projeto fui capaz de: </p>
<ul>
	<li>Utilizar os seletores (queries) da React-Testing-Library em testes automatizados.<li>
	<li>Simular eventos com a React-Testing-Library em testes automatizados.<li>
	<li>Testar fluxos lógicos assíncronos com a React-Testing-Library.<li>
	<li>Escrever testes que permitam a refatoração da estrutura dos componentes da aplicação sem necessidade de serem alterados.<li>
	<li>Criar mocks de APIs utilizando fetch.<li>
	<li>Testar inputs.<li>
</ul>

<h1>Instruções para rodar o projeto</h1>
<ol> Clone o repositório.
	<li>Clone o repositório.
	<ul><li>git clone git@github.com:brunobastosfer/ProjectTestRTL.git</li></ul>
	<ul><li>Entre na pasta do repositório que você acabou de clonar</li></ul>
	</li>
	<li>Instale as dependências
	<ul><li>Rode o comando: npm install</li</ul>
</ol>

<h1>Descrição</h1>
<p>
Esse testa contra com a presença de um STRYKER, a ideia dele é quebrar o código e depois rodar os testes para verificar se ele resolve os problemas que ocorreram. O stryker gera 'mutantes', e o teste deve matar todos eles! Caso algum mutante sobreviva, significa que o teste tem algum problema.
</p>

<h1>Rodando o teste</h1>
<ul>
	<li>use o comando npm test 'nomedoteste'</li>
	<li>rode o comando: npx stryker run ./stryker/nomeDoArquivo.conf.json .Para rodar o stryker!</li>
</ul>

<h1>NÃO ESQUEÇA !</h1>
<p>Lint é uma ferramente que utilizo para seguir padrão de código, utilizar o comando para verificar possíveis problemas. Comando: npm run lint | npm run lint:styles <p>
