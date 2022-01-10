<script context="module">
	export const prerender = true;
</script>

<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneTwo;
    let two, twoOne, twoTwo, twoThree;
    let three;
    let four;
    let five, fiveOne, fiveTwo;
    let six, sixOne, sixTwo, sixThree, sixFour, sixFive, sixFiveOne, sixFiveTwo;
    let seven, sevenOne, sevenTwo, sevenThree, sevenFour, sevenFive, sevenSix;
    let eight, eightOne, eightOneOne, eightOneTwo;
    let nine, nineOne, nineTwo, nineThree;
    let ten, tenOne, tenTwo, tenThree;
    let eleven, elevenOne, elevenTwo, elevenThree;
    let twelve, twelveOne, twelveTwo, twelveThree, twelveFour;
    let thirteen, thirteenOne, thirteenTwo, thirteenThree, thirteenFour, thirteenFive, thirteenSix, thirteenSeven;
    let fourteen, fourteenOne, fourteenTwo, fourteenTwoOne;
    let fifteen;
    let sixteen, sixteenOne, sixteenTwo;	

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">LEGENDS LEAGUE CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>1: Comissários permanentes (o núcleo duro)</h3>
	
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneOne)}>A. Composição</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneTwo)}>B. Comunicação</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>2: Comissário rotativo (o núcleo mole)</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoOne)}>A. Termo</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoTwo)}>B. Escolha</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoThree)}>C. Atual</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>3: Plataforma</h3>
        
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>4: Inscrição</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>5: Premiação</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>A. Vencedor</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(fiveTwo)}>B. Pior time</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>6: Estrutura dos times</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixOne)}>A. Ataque</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>B. Defesa</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixThree)}>C. Banco/IR/TS</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(sixFour)}>D. IR</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(sixFive)}>E. Taxi</h4>
	    <h5 class="noUnderscore clickable" on:click={() => goToSection(sixFiveOne)}>1. Elegibilidade</h5>
	    <h5 class="noUnderscore clickable" on:click={() => goToSection(sixFiveTwo)}>2. Deadline</h5>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>7: Datas importantes</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOne)}>A. Temporada</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenTwo)}>B. Pré-temporada</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenThree)}>C. Draft da Primeira Liga</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(sevenFour)}>D. Primeiro deadline de cortes</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(sevenFive)}>E. Segundo deadline de cortes</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(sevenSix)}>F. Limite para livre trânsito na TS</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(eight)}>8: Bacia</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightOne)}>A. Waiver</h4>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(eightOneOne)}>1. Ranking</h5>
	    <h5 class="noUnderscore clickable" on:click={() => goToSection(eightOneTwo)}>2. Período</h5>
	
    <h3 class="noUnderscore clickable" on:click={() => goToSection(nine)}>9: Trocas</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineOne)}>A. Revisão</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(nineTwo)}>A. Deadline</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(ten)}>10: Divisões</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(tenOne)}>A. Composição</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(tenTwo)}>B. Critério de desempate</h4>
	
    <h3 class="noUnderscore clickable" on:click={() => goToSection(eleven)}>11: Playoffs</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(elevenOne)}>A. Classificação</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(elevenTwo)}>B. Calendário</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(elevenThree)}>C. Toilet Bowl</h4>
	
    <h3 class="noUnderscore clickable" on:click={() => goToSection(twelve)}>12: Draft</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twelveOne)}>A. Pré-draft</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(twelveTwo)}>B. Ordem 2020-22</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(twelveThree)}>C. Ordem 2023+</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(twelveFour)}>D. Composição</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(twelveFive)}>E. Rodadas</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(twelveSix)}>F. Data</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(thirteen)}>13: Scoring</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(thirteenOne)}>A. Passing</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(thirteenTwo)}>B. Rushing</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(thirteenThree)}>C. Receiving</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(thirteenFour)}>D. Special Teams</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(thirteenFive)}>E. MISC</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(thirteenSix)}>F. Bonus</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(thirteenSeven)}>G. IDP</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(fourteen)}>14: Penalidades</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourteenOne)}>A. Negligência</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(fourteenTwo)}>B. Tanking</h4>
	    <h5 class="noUnderscore clickable" on:click={() => goToSection(fourteenTwoOne)}>1. Exemplos</h5>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(fifteen)}>15: Mudança de dono</h3>
	
    <h3 class="noUnderscore clickable" on:click={() => goToSection(sixteen)}>16: Novas regras e mudanças</h3>
	
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixteenOne)}>A. Responsabilidade</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(sixteenTwo)}>B. Participação</h4>
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>1 Comissários permanentes (o núcleo duro)</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>A. Composição</h3>
    
    <p>Os comissários permanentes são responsáveis por tomar as decisões finais sobre qualquer aspecto da liga. São eles:</p>
    
    <p class="underscore">Contato</p>
    <ul>
        <li>Eduardo “Pitoco” Scopel - +1 (706) 461-4532</li>
        <li>João “JN” Neto - +55 (41) 9927-6666</li>
        <li>Pippo - +55 (41) 8853-6770</li>
        <li>Diogo “Preto” Valente - +1 (832) 997-7658</li>
    </ul>
    
    <h3 class="subSectionHeading" bind:this={oneTwo}>B. Comunicação</h3>
	
    <p>Os comissários permanentes são responsáveis por tomar as decisões finais sobre qualquer aspecto da liga. São eles:</p>
    
    
    <h2 class="sectionHeading" bind:this={two}>2 Comissário rotativo (o núcleo mole)</h2>
    
    <h3 bind:this={twoOne}>A. Termo</h3>
    <p>O comissário rotativo muda anualmente e é responsável por auxiliar o núcleo duro em quaisquer decisões sobre a liga.</p>

    <h3 bind:this={twoTwo}>B. Escolha</h3>
    <p>A escolha do comissário rotativo é feita pelo núcleo duro, e um membro não pode ser escolhido por dois anos consecutivos. A ideia é que todos os membros tenham a oportunidade de participar pelo menos uma vez antes de repetir. Voluntários terão preferência.</p>
    
    <h3 bind:this={twoThree}>C. Atual</h3>
    <p>O comissário rotativo de 2021 é o Alexandre "Braza".</p>
    
    <h2 class="sectionHeading" bind:this={three}>3 Plataforma</h2>

    <p>A plataforma que acolhe a liga é a “Sleeper”.</p>
    
    <h2 class="sectionHeading" bind:this={four}>4 Inscrição</h2>
    
    <p>A taxa de inscrição é gratuita.</p>

	
    <h2 class="sectionHeading" bind:this={five}>5 Premiação</h2>
    
    <h3 bind:this={fiveOne}>A. Vencedor</h3>
    <p>Um troféu de campeão pode ser comprado ao final de cada ano e enviado ao vencedor da liga. Os custos são divididos entre os membros da liga, excluindo o dono do time vencedor.</p>
    <h3 bind:this={fiveTwo}>B. Pior Time</h3>
    <p>Um troféu de pior time (toilet bowl) pode ser comprado ao final de cada ano e enviado ao vencedor da liga. Os custos são divididos entre os membros da liga.</p>


    <h2 class="sectionHeading" bind:this={six}>6 Estrutura dos times</h2>
    
    <h3 bind:this={sixOne}>A. Ataque</h3>
    <ul>
        <li>QB</li>
        <li>RB</li>
        <li>RB</li>
        <li>WR</li>
	<li>WR</li>
	<li>TE</li>
	<li>W/R/T</li>
	<li>W/R/T</li>
    </ul>
  
    <h3 bind:this={sixTwo}>B. Defesa</h3>

    <ul>
        <li>DL</li>
        <li>LB</li>
        <li>DB</li>
    </ul>

	
    <h3 bind:this={sixThree}>C. Banco/IR/TS</h3>
    <ul>
        <li>9 banco</li>
        <li>2 IR</li>
        <li>3 TS</li>
    </ul>
	
    <h3 bind:this={sixFour}>D. IR</h3>
	<p>Jogadores na IR, DNR, COVID19 ou suspended são elegíveis para a IR.</p>
	
    <h3 bind:this={sixFive}>E. TS</h3>
	<h4 bind:this={sixFiveOne}1. Elegibilidade</h4>
	<p>Apenas rookies são elegíveis para a TS.</p>
	<h4 bind:this={sixFiveTwo}2. Deadline</h4>
	<p>Jogadores só podem ser adicionados à TS até o início da temporada regular.</p>
	<p>Nós iremos acompanhar como essa mudança vai afetar os times e a bacia ao longo da temporada. Uma possível consequência é a mudança dos tamanhos do draft (possível redução) e do banco/IR/TS (possível expansão) para a temporada de 2023. Qualquer mudança nesse sentido será definida até a semana 5 de 2022.</p>

    <h2 class="sectionHeading" bind:this={seven}>7 Datas importantes</h2>
    
    <h3 bind:this={sevenOne}>A. Temporada</h3>
    <p>Entre as semanas 1 e 18 da temporada regular da NFL.</p>

    <h3 bind:this={sevenTwo}>B. Pré-temporada</h3>
    <p>Entre o Super Bowl da temporada X e a semana 1 da temporada regular X+1.</p>
    
    <h3 bind:this={sevenThree}>C. Draft da Primeira Liga</h3>
    <p>Entre o draft da NFL e o primeiro jogo de pré-temporada da NFL.</p>
    
    <h3 bind:this={sevenFour}>D. Primeiro deadline de cortes</h3>
    <p>Véspera do draft da Primeira Liga. Cada time deve ter um máximo de 21 jogadores em seus rosters, com os slots de TS e IR vazio.</p>

    <h3 bind:this={sevenFive}>E. Segundo deadline de cortes</h3>
    <p>Após o draft da Primeira Liga cada time deve ter em torno de 26 jogadores em seus rosters. Até o início da pré-temporada da NFL este número deve ser reduzido para 21 jogadores no roster ativo, com a possibilidade de 2 jogadores na IR e 3 no TS.</p>

    <h3 bind:this={sevenSix}>F. Limite para livre trânsito na TS</h3>
    <p>Primeira semana da temporada regular da NFL.</p>
	
	
    <h2 class="sectionHeading" bind:this={eight}>8 Bacia</h2>
    
    <h3 bind:this={eightOne}>A. Waiver</h3>
    <p>Free Agent Acquisition Budget (FAAB). Cada time recebe $100 ao final de cada ano e só adiciona um jogador se oferecer um valor superior aos demais times. Em caso de empate, o jogador vai para o time com prioridade no ranking de waiver.</p>

	<h4 bind:this={eightOneOne}1. Ranking</h4>
	<p>O ranking de waiver é inversamente proporcional ao desempenho na semana anterior. Uma vez que um jogador é adicionado a um time, este time cai para o final do ranking de waiver.</p>
	<h4 bind:this={eightOneTwo}2. Período</h4>
	<p>Waiver semanal: Todos os jogadores da bacia estão sujeitos a waiver, que resolve toda quarta-feira 00:05 (BRT). Durante os outros dias, a bacia fica aberta. Entre o final da temporada e o draft da Primeira Liga, a bacia fica fechada.</p>

    <h2 class="sectionHeading" bind:this={nine}>9 Trocas</h2>
    
    <h3 bind:this={nineOne}>A. Revisão</h3>
    <p>Os núcleos duro e mole revisam todas as trocas com a maior brevidade possível. Em havendo conflito de interesse os participantes dos núcleos duro e mole não podem se manifestar. Ktc é recomendado para equilibrar trocas.</p>
	
    <h3 bind:this={nineTwo}>B. Deadline</h3>
    <p>Semana 13 da temporada regular, reabrindo na pré-temporada (logo após o final da temporada).</p>
	
    <h2 class="sectionHeading" bind:this={ten}>10 Divisões</h2>
    
    <h3 bind:this={tenOne}>A. Composição</h3>
    <p>A liga é composta por 3 divisões com 4 times cada:</p>
	
    <ul>
        <li>Divisão Aaron Hernandez: JN, Bird, Pippo, Felpa</li>
        <li>Divisão Vick cachorrão: Scopel, Ronaldo, Preto, Dede</li>
        <li>Divisão Ray Rice: Hildo, Eric, Alexandre, Henk</li>
    </ul>
	
    <p>Obs: Com o objetivo de manter o equilíbrio da Liga, os componentes das divisões podem ser alterados pelos núcleos duro e mole, levando em conta a opinião dos demais membros da liga.</>

    <h3 bind:this={tenTwo}>B. Critérios de desempate</h3>
    <p>O critério de desempate é o número de pontos marcados.</p>


    <h2 class="sectionHeading" bind:this={eleven}>11 Playoffs</h2>
    
    <h3 bind:this={elevenOne}>A. Classificação</h3>
    <p>6 times classificam para os playoffs. Os 3 campeões de divisão e os 3 não campeões com maior número de vitórias.</p>
    <h3 bind:this={elevenTwo}>B. Calendário</h3>
    <p>Os playoffs são jogados nas semanas 15, 16 e 17 da temporada regular da NFL.</p>
    <h3 bind:this={elevenThree}>C. Toilet Bowl</h3>
    <p>os times que não se classificarem para os playoffs jogam o Toilet Bowl. Neste torneio, cada time joga para evitar jogar, ou seja quem perder avança.</p>

    <h2 class="sectionHeading" bind:this={twelve}>12 Draft</h2>
    
    <h3 bind:this={twelveOne}>A. Pré-draft</h3>
    <p>Antes do draft cada time deve ter até 21 jogadores em seus rosters, e seus slots de IR e TS devem estar limpos. O núcleo duro se reserva o direito de alterar os rosters dos times caso estas condições não sejam cumpridas até a véspera do draft.</p>
    <h3 bind:this={twelveTwo}>B. Ordem 2020-22</h3>
    <p>A ordem do draft de 2022 é Standard e é inversa à classificação dos times no ano anterior. A classificação pré-playoffs é o que vale para os times que não se classificarem. A classificação pós-playoffs é o que vale para os times que se classificarem.</p>
    <h3 bind:this={twelveThree}>C. Ordem 2023+</h3>
    <p>Em 2023 a ordem do draft respeitará os seguintes grupos:</p>
    <ul>
	    <li>Picks 1-6: times não classificados, rankeados por Max PF</li>
	    <li>Picks 7-8: times eliminados na semana 15, rankeados por Max PF</li>
	    <li>Picks 9-10: times eliminados na semana 16, rankeados por Max PF</li>
	    <li>Pick 11: vice-campeão da liga</li>
	    <li>Pick 12: campeão da liga</li>
    </ul>
    <h3 bind:this={twelveFour}>D. Composição</h3>
    <p>O draft é composto por todos os jogadores da bacia, incluindo calouros da NFL.</p>
    <h3 bind:this={twelveFive}>E. Rodadas</h3>
    <p>O draft de 2022 terá 5 rodadas.</p>
    <h3 bind:this={twelveSix}>F. Data</h3>
    <p>O início do draft de 2022 será definido em 2022, mas obrigatoriamente será após o draft da NFL e antes da pré-temporada da NFL.</p>


    <h2 class="sectionHeading" bind:this={thirteen}>13 Scoring</h2>
    
    <h3 bind:this={thirteenOne}>A. Passing</h3>
        <ul>
	    <li>Passing Yards: +0.04 per yard (25 yards = 1 point)</li>
	    <li>Passing TD: +4</li>
	    <li>2-Pt Conversion: +2</li>
	    <li>Pass Intercepted: -2</li>
	    <li>Pick 6 Thrown: -2</li>
	    <li>QB Sacked: -0.50</li>
	    <li>40+ Yard Completion Bonus: +0.5</li>
	    <li>40+ Yard Pass TD Bonus: +0.5</li>
        </ul>

    <h3 bind:this={thirteenTwo}>B. Rushing</h3>
        <ul>
	    <li>Rushing Yards: +0.1 per yard (10 yards = 1 point)</li>
	    <li>Rushing TD: +6</li>
	    <li>2-Pt Conversion: +2</li>
	    <li>40+ Yard Rush Bonus: +0.5</li>
	    <li>40+ Yard Rush TD Bonus: +0.5</li>
        </ul>

    <h3 bind:this={thirteenThree}>C. Receiving</h3>
        <ul>
		<li>Reception (0-9 yd): +0.1</li>
		<li>Reception (10-19 yd): +0.2</li>
		<li>Reception (20-29 yd): +0.3</li>
		<li>Reception (30-39 yd): +0.4</li>
		<li>Receiving Yards: +0.1 per yard (10 yards = 1 point)</li>
		<li>Receiving TD: +6</li>
		<li>2-Pt Conversion: +2</li>
		<li>40+ Yard Reception Bonus: +0.5</li>
		<li>40+ Yard Reception TD Bonus: +0.5</li>
        </ul>

    <h3 bind:this={thirteenFour}>D. Special Teams</h3>
        <ul>
		<li>Special Teams TD: +6</li>
		<li>Special Teams Forced Fumble: +1</li>
		<li>Special Teams Fumble Recovery: +1</li>
		<li>Kick/Punt Return Yards: +0.04 per yard (25 yards = 1 point)</li>
        </ul>

    <h3 bind:this={thirteenFive}>E. Misc</h3>
        <ul>
		<li>Fumble: -1</li>
		<li>Fumble Lost: -1</li>
        </ul>

    <h3 bind:this={thirteenSix}>F. Bonus</h3>
        <ul>
		<li>300-399 Yard Passing Game: +1</li>
		<li>400+ Yard Passing Game: +2</li>
		<li>100-199 Combined Rush + Rec Yards: +1</li>
		<li>200+ Combined Rush + Rec Yards: +2</li>
        </ul>
	
    <h3 bind:this={thirteenSeven}>G. IDP</h3>
        <ul>
		<li>IDP TD: +6</li>
		<li>Sack: +2.5</li>
		<li>Hit on QB: +0.5</li>
		<li>Tackle: +0.5</li>
		<li>Tackle For Loss: +0.5</li>
		<li>Blocked Punt, PAT or FG: +2</li>
		<li>Interception: +4</li>
		<li>Fumble Recovery: +2.5</li>
		<li>Forced Fumble: +2.5</li>
		<li>Safety: +4</li>
		<li>Pass Defended: +1</li>
        </ul>

    <h2 class="sectionHeading" bind:this={fourteen}>14 Penalidades</h2>
    
    <h3 bind:this={fourteenOne}>A. Negligência</h3>
    <p>Escalar jogador na IR/SUS/DNR/BYE/OUT/COV:</p>
        <ul>
		<li>1x: perda de 50% do budget OU melhor escolha de R1 no próximo draft, caso o time tenha budget inferior a mediana dos budgets de todos os times</li>
		<li>2x: perda de 100% do budget E 2 melhores escolhas de R1 nos próximos drafts</li>
		<li>3x: suspensão até o final da temporada</li>
		<li>Reincidência: expulsão</li>
        </ul>
     <p>Os jogadores têm direito a defesa antes da penalidade entrar em efeito.</p>

    <h3 bind:this={fourteenTwo}>B. Tanking</h3>
    <p>O jogador que praticar tanking (perder jogos de propósito para melhorar a posição no draft) perderá todas as suas escolhas no draft e será suspenso até o final da temporada. Caso um jogador faça tanking em mais de uma temporada ele será excluído da liga.</p>

    <h4 bind:this={fourteenTwoOne}>1. Exemplos</h3>
    <p>Alguns exemplos do que configura tanking:</p>
        <ul>
		<li>Não escalar jogadores antes de uma partida repetidamente</li>
		<li>Escalar jogadores obviamente piores com o objetivo de pontuar menos</li>
		<li>Escalar jogadores na IR/suspenso/DNR/bye repetidamente</li>
		<li>Fazer trocas claramente desequilibradas para acumular escolhas no draft ou budget</li>
        </ul>

    <h2 class="sectionHeading" bind:this={fifteen}>15 Mudança de dono</h2>
    <p>Caso um jogador não tenha mais interesse ou seja excluído da liga seu time será administrado pelos núcleos duro e mole até o final da temporada corrente, e um novo dono será encontrado durante a pré-temporada. Este novo dono deve ser conhecido de pelo menos 1 membro da liga.</p>

    <h2 class="sectionHeading" bind:this={sixteen}>16 Novas regras e mudanças</h2>
    
    <h3 bind:this={sixteenOne}>A. Responsabilidade</h3>
    <p>Os núcleos duro e mole são responsáveis por executar qualquer mudança, inclusão e/ou remoção de regras. No entanto, qualquer modificação será discutida entre todos os membros da liga antes de ser executada. Em caso de discordância, uma votação entre todos os membros deve ser a opção preferida para resolução.</p>
    <h3 bind:this={sixteenTwo}>B. Participação</h3>
    <p>Qualquer membro da liga pode propor mudança, inclusão e/ou remoção de regras.</p>

</div>
