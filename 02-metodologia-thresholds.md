---
title: Metodologia e Thresholds
---

[English](02-methodology-thresholds.html) | [Português](02-metodologia-thresholds.html)

# Metodologia: Foco em Fraquezas e o Método de Thresholds

## Por que focar nas suas fraquezas (método Viscose, por robinwobin)

O Viscose Benchmark foi montado pra que cada cenário represente o tipo de treino que você precisa se for fraco naquela área. Não é aleatório.

O benchmark não é sua rotina diária inteira. A ideia é jogar todos os cenários uma vez, estabelecer uma pontuação base em cada um, e depois focar quase só nos cenários onde você tirou a pior nota. Eliminar fraquezas assim é uma das formas mais comprovadas de evoluir, não importa seu nível atual.

## O Método de Thresholds (por Escalate / VT Matty)

Medir sua evolução só pelo PB é um erro. PB é fácil de adulterar por coisas que não têm nada a ver com sua habilidade real: noite mal dormida, alimentação, ou pura sorte no posicionamento dos alvos numa run. Ele não reflete seu raw aim de verdade, nem sua capacidade de traduzir isso pro jogo.

### O que é Threshold?

É o valor que você consegue alcançar todo santo dia, com esforço e técnica correta. Não é sua melhor run possível. É sua run consistente.

### A analogia com a academia

Pensa no Threshold como uma série de musculação levada perto da falha técnica, RPE alto.

Fazer reps no piloto automático, sem carga, equivale a bater pontuações fáceis demais, sem desafio real. Forçar um peso exagerado que quebra sua postura só pra dizer que levantou equivale a um PB de sorte com técnica horrível. O Threshold fica no meio: é a faixa onde você treina no limite da sua capacidade, mantendo forma, controle biomecânico e tensão corretos, sem a execução desmoronar.

### Exemplo prático

Em 5 tentativas você tirou 1000, 970, 890, 900 e 980 pontos. Seu PB é 1000. Seu Threshold é 970, porque esse é o valor que exige técnica e atenção constante pra bater de novo.

### Como aplicar isso na rotina

Nas playlists, só avança pra próxima task depois de bater o Threshold definido pra ela. Se você está passando muito rápido pelas tasks, menos de 15 minutos na playlist inteira, repete ela e aumenta o Threshold: sinal de que está fácil demais pro seu nível.

E o Threshold só sobe quando sua consistência real melhora de verdade. Nunca por causa de uma run de sorte isolada.

---

## Fundamentos de Psicofísica Visuomotora e Controle Motor

### 1. Lei de Fitts e o Trade-Off Velocidade-Precisão

Na psicofísica do apontamento humano (Paul Fitts, 1954), o tempo de movimento ($MT$) necessário para adquirir um alvo depende da razão entre a distância até o alvo ($A$) e a largura útil do alvo ($W$):

$$MT = a + b \log_2\left(\frac{2A}{W}\right)$$

O termo logarítmico define o **Índice de Dificuldade ($ID$)**: alvos mais distantes ou menores exigem mais bits de informação motora processados pelo sistema nervoso. Para avaliar a dispersão real dos tiros de um jogador ao longo de uma sessão, utiliza-se o **Índice de Dificuldade Efetivo de Crossman ($ID_e$)**:

$$ID_e = \log_2\left(\frac{A_e}{W_e} + 1\right), \quad \text{onde } W_e = 4,133 \times SD_x$$

Aqui, $W_e$ representa a largura efetiva baseada no desvio-padrão ($SD_x$) dos pontos de impacto, e $ID = \log_2(2d/e)$ quantifica a relação direta entre distância ($d$) e margem de erro ($e$). O Método de Thresholds atua reduzindo o desvio-padrão motor ($SD_x$), comprimindo a dispersão de cliques dentro da hitbox sem sacrificar o tempo de aquisição ($MT$).

### 2. Ruído Dependente de Sinal (Signal-Dependent Noise)

Estudos clássicos de neurociência motora (Harris & Wolpert, 1998) demonstram que o comando neural enviado aos músculos sofre de **Ruído Dependente de Sinal**: a variabilidade da força muscular ($\sigma_v$) cresce proporcionalmente à magnitude do comando motor somada ao ruído basal ($\sigma_0$).

- Quando você tenta mover o mouse com força máxima descontrolada (*rushar o tiro* ou aplicar *death grip*), o ruído neuromotor explode, fazendo o cursor passar do alvo ou tremer na frenagem.
- A trajetória ótima que minimiza a variância final do ponto de impacto exige **suavidade cinemática** (minimização do *jerk*, a derivada da aceleração), aplicando tensão fásica apenas no impulso inicial e relaxando imediatamente na desaceleração.

### 3. Cinemática Bifásica do Flick e Hipometria Conservadora

Todo *flick* de alto nível é composto por duas fases neurofisiológicas distintas:

1. **Fase 1 — Impulso Balístico Primário (*Open-Loop*):** Movimento rápido executado pelos grandes grupos musculares (ombro/antebraço) que leva o cursor até a vizinhança do alvo. Por ocorrer em janela temporal inferior ao tempo de reação visual, não sofre correção visual durante o voo.
2. **Fase 2 — Microajuste Secundário (*Closed-Loop*):** Correção fina executada por punho e dedos, guiada pelo feedback visual foveal para alinhar o retículo exatamente sobre o alvo antes do clique.

**A Descoberta da Hipometria Conservadora (*Under-Flicking* vs. *Over-Flicking*):**
Pesquisas biomecânicas comparando tarefas de alvos largos (*Gridshot*) com tarefas de precisão extrema (*Sixshot*) revelam uma mudança deliberada de estratégia ($p = 0,88$ de consistência em jogadores treinados):
- Em alvos pequenos (*Sixshot* / *headshots* em jogos táticos), jogadores de elite adotam uma estratégia conservadora de **hipometria (*under-flicking*)**, aterrissando o impulso balístico ligeiramente **aquém** do alvo.
- Isso ocorre porque emendar o microajuste na **mesma direção** do movimento primário economiza dezenas de milissegundos em comparação ao **over-flicking** (ultrapassar o alvo, vencer a inércia até parar totalmente e inverter os músculos antagonistas no sentido oposto).

### 4. Os 3 Estágios do Aprendizado Motor e o Mito da "Memória Muscular" Fixa

A ideia popular de que os músculos "decoram uma distância fixa em centímetros" e que alterar a sensibilidade "apaga a memória muscular" é cientificamente falsa (Krakauer et al.). Mesmo mantendo a mesma sensibilidade no jogo, o coeficiente de atrito do mousepad muda diariamente conforme a umidade do ar, a temperatura da pele, o suor e o desgaste dos *skates* de PTFE.

O cérebro armazena um **Programa Motor Generalizado (GMP)** capaz de recalibrar parâmetros de escala rapidamente. Essa consolidação ocorre em três estágios:

| Estágio | Janela Temporal | Características Neurocognitivas |
|---|---|---|
| **1. Cognitivo** | Dias 1 a 7 | Alto esforço consciente, movimentos fragmentados, grande variância de pontuação e necessidade de atenção visual constante. |
| **2. Associativo** | Semanas 2 a 8 | Refinamento da coordenação entre fase balística e microajuste, redução drástica da tensão muscular parasitária e estabilização do Threshold. |
| **3. Autônomo** | Meses 2+ | Execução subcortical automatizada com custo atencional mínimo, liberando 100% da memória de trabalho para leitura tática in-game. |

---

[← Voltar ao índice](./index.pt-BR.html)
