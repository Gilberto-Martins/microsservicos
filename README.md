# microsservicos
Introdução a microsserviços com .NET

##

<h2>Monolitos</h2>
<p>
    Monolítica é um sistema único, não dividido, que roda em um único processo, uma aplicação de software em que diferentes componentes estão ligados a um <br> único programa dentro de uma única plataforma.
</p>

<h3>Desfios da arquitetura monolítica</h3>
<ul>
    <li>Aumento da complexidade e tamanho ao longo do tempo</li>
    <li>Alta dependência de componentes de código</li>
    <li>Escalabilidade do sistema é limitada</li>
    <li>Falata de flexibilidade</li>
    <li>Dificuldade para colocar alterações em produção</li>
</ul>

<h3>Escalabilidade</h3>
<p>
    Escalabilidade de softwares significa aumentar as funcionalidades de um software, aumentar o consumo de memória, de processos, atender demandas de alta<br> exigência de processamento e possivelmente concorrência de acesso. Desenvolver um software escalável significa também planejar seu crescimento.<br> É preciso estar de olho no momento exato de alocar mais recursos para não ser atropelado por um aumento de demanda,<br> gerando a perda de qualidade do sistema.
</p>

<h3>Escalabilidade Vertical</h3>
<p>
    Escalonamento vertical é botar mais capacidade de memória (principal e/ou de massa) e processamento. Ou seja, é comprar um hardware mais poderoso para dar<br> conta do recado.<br><br>
    Em alguns casos basta criar mais processos/threads que está fazendo o scaling up, desde que o hardware já suporte esse aumento. Há casos que separar o<br> banco de dados em vários dispositivos de armazenamento já seja uma escala vertical, novamente é escalar na mesma máquina.<br><br>
    O investimento é basicamente em hardware. Comprando mais processador. memória e armazenamento já tem uma capacidade aumentada.<br><br>
    Em alguns casos é mais questão de fazer uma simples configuração para alcançar o que o hardware único já suporta.<br><br>
    Também pode ser otimizar a aplicação para que ela desempenhe melhor e atenda mais do que fazia antes.
</p>

<h3>Escalabilidade Horizontal</h3>
<p>
    Escalonamento horizontal é colocar mais computadores para dar conta do recado. Claro que eles adicionam mais capacidade de processamento e memória também,<br> na soma total.<br><br>
    É muito mais complexo fazer um escalonamento horizontal tanto do ponto de vista de gerenciamento quanto do ponto de vista de programação, ainda que<br> existam ferramentas para facilitar. Não é só colocar os computadores, eles precisam "se falar" de forma consistente e adequada. Na verdade isso é<br> considerado o problemas mais difícil de resolver na computação.<br><br>
    Por incrível que pareça pode ser mais barato que o vertical, pelo menos no custo da aquisição da infraestrutura já que é possível adquirir hardware mais<br> simples e mais comum que costuma ser mais barato pela escala de produção. Claro que o custo de gerenciamento e desenvolvimento pode mudar<br> o custo total.<br><br>
    Fora os casos que o vertical não comportaria a necessidade, afinal essa estratégia tem um limite que em tese o horizontal não tem, o horizontal tem a<br> vantagem de ser mais tolerante a falhas, ou pelo menos ser mais fácil ter a operação de volta em caso de alguma falha.
</p>

<h3>Micro Serviços</h3>
<p>
    Microsserviços são uma abordagem arquitetônica e organizacional do desenvolvimento de software na qual o software consiste em pequenos serviços<br> independentes que se comunicam usando APIs bem definidas. Esses serviços pertencem a pequenas equipes autossuficientes.<br><br>
    As arquiteturas de microsserviços facilitam a escalabilidade e agilizam o desenvolvimento de aplicativos, habilitando a inovação e acelerando o tempo de<br> introdução de novos recursos no mercado.
</p>
