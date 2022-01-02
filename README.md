<h1>NewTab Academy</h1>
<h2>Projeto HTML e CSS (individual)</h2>

<p>Agora que temos um entendimento inicial sobre o funcionamento de cada linguagem, iremos demonstrar um passo a passo de desenvolvimento de um projeto que as utiliza. </p>

<p>Você verá a seguir o Fernando Duro desenvolver em tempo real esse projeto. Inclusive sem grandes edições, vai ver que mesmo um desenvolvedor com grande experiência como ele ainda precisa testar e ajustar algumas coisas conforme vai fazendo. A intenção é que você realmente acompanhe como se estivesse ali ao lado dele.</p>

<hr>

<strong>Link do projeto do curso: <a href="https://edijunior88.github.io/NewTab_Academy_Projeto_Individual/">https://edijunior88.github.io/NewTab_Academy_Projeto_Individual/</a></strong>

<hr>

![index-readme](index-readme.gif)

<hr>

<h3>Escopo do projeto individual</h3>

<p>Atualmente o mercado de trabalho está muito mais interessado em saber se você possui experiência em determinado assunto do que em quais cursos você fez. E até que você comece a criar a sua experiência profissional, trabalhando em empresas, a maneira que conseguimos provar certa experiência é desenvolvendo projetos e os apresentando ao mundo e em processos seletivos.</p>

<p>Por isso, durante a nossa jornada você vai desenvolver projetos tanto individualmente quanto em grupo.</p>

<p>Parte destes projetos foram planejados por nós, e outra parte são projetos que empresas utilizam como formas de avaliar tecnicamente um candidato para uma vaga, os famosos “testes técnicos” que vocês irão precisar resolver no futuro. Desde já, vamos nos acostumando com eles.</p>

<p>No nosso primeiro projeto, que iremos trabalhar nos módulos de HTML, CSS e Javascript, nos inspiramos no teste técnico de front-end para a empresa Via Varejo (responsável pelas Casas Bahia, Pontofrio e outras marcas).</p>

<p>E ainda adicionamos alguns itens para ficar mais divertido. 😁</p>

<p>Vamos lá?</p>

<p><strong>Obs. 1)</strong> Antes vamos deixar aqui o link do teste técnico original: <a href="https://github.com/viavarejo/frontend-test">https://github.com/viavarejo/frontend-test</a></p>
<s>
  <p><strong>Obs. 2)</strong> No módulo seguinte você vai aprender sobre JavaScript para desenvolver alguns dos requisitos abaixo, mas já vamos deixá-los aqui para entender o escopo completo do projeto. Por enquanto, você precisará fazer toda a parte de HTML e CSS.</p>
</s>

Introdução
Seu objetivo é criar uma SPA (Single Page Application) seguindo o layout que está aqui: https://www.figma.com/file/U8ojEXx2vxSK2KOvoBvHVH8y/Frontend-test?node-id=13%3A42

Obs.: Se você fizer um cadastro e login no Figma, você conseguirá ver com mais detalhes todas as telas. E para facilitar, temos imagens e docs das telas no Drive também.

No layout original, vocês vão ver que existem itens no menu sem utilidade. Vamos alterar e criar funcionalidades pra eles? 🙂

Durante o desenvolvimento portanto, vocês devem:

Alterar o link “Resumo” para “Cadastro de transações”.
Alterar o link “Dashboard” para “Limpar dados”.
Excluir o link “Configurações”.
O que sua aplicação deverá fazer
Incluir transações de compra ou venda de mercadoria.
Criar um extrato das transações incluídas. As transações deverão ser mostradas na ordem em que foram incluídas.
Mostrar o saldo final e destacar se houve lucro ou prejuízo.
A aplicação deverá ser responsiva e estar de acordo com o layout fornecido.
Persistir as transações no Local Storage.
Outros requisitos
HTML:

As opções do campo “Tipo de transação” são: Compra e Venda.
Caso não exista nenhuma transação cadastrada, adicione a mensagem “Nenhuma transação cadastrada.” na lista do Extrato.
CSS:

Testar em smartphones, tablets (modos portrait e landscape) e monitores a partir de 1024px até 1900px. (Através do inspecionar elemento no navegador)
A fonte utilizada é a Lato.
A largura máxima do conteúdo é 1100px.
JavaScript (isso será feito no próximo módulo):

Validar o formulário para que todos os campos sejam preenchidos.
Adicionar uma máscara no campo “Valor” para que apenas números sejam preenchidos e com a formatação correta. (Padrão: 10,90)
Ao adicionar uma nova transação, persistir no Local Storage e já atualizar a lista com o extrato. Atualizar também o cálculo apresentado.
Ao clicar no link “Limpar dados”, apresentar uma mensagem de confirmação e em seguida apagar as informações, atualizando a lista.
Divisão de atividades
HTML e CSS:

ATIVIDADE 1 – HTML/CSS:
Desenvolvimento completo do HTML
Início do desenvolvimento do CSS (versão mobile)
ATIVIDADE 2 – HTML/CSS:
Desenvolvimento completo do CSS (versão responsiva)
Javascript (reforçando, isso será feito no próximo módulo):

ATIVIDADE 1 – JAVASCRIPT:
Validação e máscara do formulário
ATIVIDADE 2 – JAVASCRIPT:
Registro em local storage e listagem das transações
Funcionalidade de limpar dados