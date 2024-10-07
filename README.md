<h1 align="center"> AWS Step Functions </h1>

<h2> Uma breve introdução sobre a AWs Step Functions </h2>

<p> Você pode criar fluxos de trabalho visuais para organizar tarefas, automatizar processos, orquestrar microsserviços e aprendizado de máquina. Basicamente, ele junta várias funções da AWS e outras ferramentas pra criar apps importantes. </p>
<p> Usando o Step Functions, você combina funções do AWS Lambda e outros serviços para construir aplicativos robustos. Ele usa uma linguagem visual chamada Amazon States Language (ASL) para definir "máquinas de estado", que são compostas por etapas. Essas etapas podem incluir chamadas para outros serviços da AWS, APIs ou até atividades externas. </p>

<h2> Sobre preços </h2>

<h3> Nível gratuito </h3>
<p1> 4.000 transições de estado por mês. O nível gratuito do Step Functions não expira automaticamente ao final do período de 12 meses do nível gratuito da AWS e fica disponível indefinidamente para os nossos clientes novos e atuais. </p>

<h3> Transições de estado </h3>
<p>USD 0,000025 por transição de estado deste ponto em diante.
USD 0,025 por 1.000 transições de estado.

Com o AWS Step Functions, você paga pelo número de transições de estado usadas por mês. São cobradas as transições de estado que excedem o nível gratuito. Veja a tabela de definição de preço de transições de estado para obter mais detalhes. 

Se você incluir nova tentativa de processamento em caso de erro em qualquer etapa do fluxo de trabalho, a nova tentativa será cobrada como uma transição de estado adicional.
</p>

<h3>Express Workflows</h3>
<p>
Com o Step Functions Express Workflows, você paga somente pelo que usa. Você é cobrado com base no número de solicitações de seu fluxo de trabalho e sua duração.

O Step Functions Express Workflows conta uma solicitação toda vez que começa a executar um fluxo de trabalho e você é cobrado pelo número total de solicitações em todos os seus fluxos de trabalho. Isso inclui testes no console.

A duração é calculada com base no início da execução do seu fluxo de trabalho e vai até a conclusão ou o encerramento dele de outra maneira. O valor é arredondado para os 100 ms mais próximos e a quantidade de memória usada na execução do seu fluxo de trabalho é faturada em blocos de 64 MB.

O consumo de memória tem como base o tamanho de uma definição de fluxo de trabalho, o uso de estados Map ou Parallel, além do tamanho dos dados de execução (carga). Os exemplos 3 e 4 de definição de preço mostram como estimar a utilização de memória. </p>
