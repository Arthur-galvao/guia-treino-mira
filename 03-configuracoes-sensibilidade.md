---
title: Configurações e Sensibilidade
---

[English](03-settings-sensitivity.html) | [Português](03-configuracoes-sensibilidade.html)

# Configurações e Medidas (por @robinwobin_)

## Configurações e erros comuns

- Vídeo de configurações da Viscose: https://www.youtube.com/watch?v=QSS-zJb4lsY
- Vídeo sobre erros comuns no treino de mira: https://www.youtube.com/watch?v=VARQNEdQYbw

## Onde jogar e como progredir de dificuldade

Se você é iniciante, começa pelo "Viscose Entry Benchmarks". Intermediário ou avançado, começa direto pelo "Viscose Benchmarks S2". Pra acompanhar tudo, usa o Rastreador Web Benchmark (Raw Input).

Quando subir de dificuldade? Só depois de alcançar o segundo ranque mais alto e completar o terceiro mais alto. E só começa a incorporar cenários mais difíceis quando estiver, no mínimo, 4 ranques abaixo do máximo nos cenários fáceis.

- Vídeo: Viscose Benchmark - https://www.youtube.com/watch?v=KwCzQmSx-p0

## O que é cm/360?

cm/360 é quantos centímetros você move o mouse fisicamente pra dar uma volta completa de 360° no jogo. Muda a escala de sensibilidade do KovaaK's pra cm/360: assim dá pra comunicar e ajustar sua sensibilidade com precisão em qualquer jogo, não só no KovaaK's.

- Conversor de sensibilidade: https://kovaaks.com/kovaaks/cm360-converter

## Sensibilidade por tipo de cenário

Trocar a sensibilidade dependendo do cenário ajuda a desenvolver um controle de mouse mais completo e trabalha diferentes grupos musculares de forma equilibrada, em vez de treinar sempre do mesmo jeito.

### Voltaic Benchmark, categorias

| Categoria | Sensibilidade recomendada (cm/360) |
|---|---|
| Dynamic Clicking | 44 |
| Static Clicking | 64 |
| Linear Clicking | 54 |
| Precise Tracking | 44 |
| Reactive Tracking | 30 |
| Control Tracking | 38 |
| Speed Switching | 40 |
| Evasive Switching | 44 |
| Stability Switching | 54 |

### Viscose Benchmark, categorias

| Categoria | Subcategoria | Sensibilidade recomendada (cm/360) |
|---|---|---|
| Control Tracking | Arm | 34 |
| Control Tracking | Wrist | 44 |
| Control Tracking | Fingertip | 40 |
| Control Tracking | Blending | 44 |
| Reactive Tracking | Control | 34 |
| Reactive Tracking | Speed | 28 |
| Reactive Tracking | Reading | 30 |
| Flick Tech | Speed | 45 |
| Flick Tech | Stability | 55 |
| Flick Tech | Micro | 65 |
| Flick Tech | Post-Flick | 44 |
| Click Timing | Reading | 45 |
| Click Timing | Precision | 60 |
| Click Timing | Stability | 50 |

---

## eDPI, Calibração de Base e Prática Variável vs. Competitiva

### 1. O que é eDPI e a Faixa Competitiva de Referência

Enquanto o `cm/360` mede o deslocamento físico universal no mousepad, o **eDPI (Effective Dots Per Inch)** quantifica a sensibilidade efetiva dentro de um motor de jogo específico:

$$\text{eDPI} = \text{DPI do Mouse} \times \text{Sensibilidade no Jogo}$$

- **Referência Competitiva (Valorant):** A média dos atletas profissionais situa-se entre **250 e 280 eDPI** (equivalente a `0,31–0,35` em `800 DPI`, ou aproximadamente **46 a 52 cm/360°**).
- **Calibração da Base Física (~60 cm/360° a 800 DPI):** Uma regra prática biomecânica para Tactical FPS é calibrar sua sensibilidade de modo que uma varredura confortável da borda esquerda à borda direita da sua área útil de mousepad (~30 cm) produza um giro de **180°** no jogo (~60 cm/360°).

### 2. Prática Variável (Randomizador) vs. Familiaridade Pré-Competitiva

- **No Aim Trainer (Prática Variável / Reconsolidação):** Alternar a sensibilidade por categoria (conforme as tabelas acima) ou utilizar um randomizador de sensibilidade dentro de um envelope controlado ($\pm 10\%$ a $\pm 25\%$) força a reconsolidação do Programa Motor Generalizado (Wymbs, Bastian & Celnik, 2016), refinando a independência entre dedos, punho e antebraço.
- **No Jogo Competitivo (Estabilidade de Longo Prazo):** Para campeonatos e filas ranqueadas de alto nível, mantenha uma sensibilidade base fixa no seu FPS principal por pelo menos **3 semanas consecutivas** antes de avaliar sua eficácia. Caso precise ajustá-la, aplique incrementos graduais de **5% a 10%**, evitando mudanças radicais na véspera de partidas oficiais.

---

## Tribologia de Mousepads e Bases de Poron

O desempenho em microajustes e rastreamento contínuo depende diretamente da **tribologia** (ciência do atrito e lubrificação entre superfícies em contato) entre os *skates* de PTFE/vidro do mouse e o tecido ou superfície rígida do mousepad:

1. **Atrito Estático ($\mu_s$):** Força necessária para iniciar o movimento do mouse a partir do repouso. Um atrito estático excessivamente alto causa o efeito de *stick-slip* (o mouse "gruda" e salta ao tentar fazer microajustes de 1 a 2 pixels em *Static/Micro* ou *Smooth Tracking*).
2. **Atrito Dinâmico ($\mu_k$):** Resistência sentida enquanto o mouse já está deslizando em velocidade contínua. Define a fluidez no *Tracking*.
3. **Poder de Parada (*Stopping Power*):** Capacidade combinada da superfície e da espuma de base em dissipar a energia cinética ao final de um *flick* explosivo.

### Dureza da Base de Uretano Celular (Poron)

Mousepads de alta performance (como a linha Artisan e equivalentes) utilizam bases de **Poron** em três densidades que alteram diretamente a biomecânica:

| Densidade da Base | Comportamento Mecânico | Indicação Principal |
|---|---|---|
| **MID (Firme)** | Espuma densa que quase não afunda sob pressão vertical. Mantém razão entre atrito estático e dinâmico 100% previsível e constante. | *Tracking* reativo/preciso e jogadores que mantêm mão leve sem tensionar verticalmente. |
| **SOFT (Equilibrada)** | Permite leve compressão sob os dedos. Oferece deslize livre quando a mão está relaxada e ganho progressivo de *stopping power* ao pressionar o mouse na frenagem. | Versatilidade total (*All-Rounder* para Click Timing, Switching e Tracking). |
| **XSOFT (Extra Macia)** | Alta deformação elástica. Afundar os dedos ou o mouse no pad freia o cursor instantaneamente, mas pune severamente quem sofre de *death grip* (tensão vertical involuntária trava o deslize). | *Static/Tac-FPS* com necessidade extrema de frenagem, exigindo controle rigoroso de tensão. |

---

## Ergonomia Clínica (Protocolo 1HP) e Interferência do Treino de Força

De acordo com a medicina esportiva aplicada aos esports (**1HP — Dr. Matthew Hwu**):

1. **Alinhamento Articular Neutro:** Ajuste a altura da cadeira e da mesa para que o cotovelo forme um ângulo de aproximadamente **90°**, com o antebraço apoiado de forma estável e o punho em posição neutra (sem extensão dorsal excessiva nem desvio ulnar pronunciado).
2. **Tensão Fásica vs. Tensão Tônica (*Death Grip*):** A contração muscular para acelerar ou parar o mouse deve ser **fásica** (dura frações de segundo e relaxa imediatamente). Manter os flexores dos dedos e do carpo contraídos continuamente durante toda a run (*death grip*) comprime o túnel do carpo, acelera a fadiga periférica, amplifica o ruído motor e leva a tendinopatias por esforço repetitivo.
3. **Interferência Aguda da Academia (Treino de Força Pesado):** Sessões intensas de musculação (especialmente exercícios de puxada, barra fixa, levantamento terra e roscas que exigem pegada isométrica máxima) induzem fadiga aguda do sistema nervoso central e tremores neuromusculares nos membros superiores por várias horas. **Regra prática:** sempre execute seu treino de mira de alta precisão e suas partidas ranqueadas **antes** do treino pesado de membros superiores na academia, ou respeite uma janela de recuperação de pelo menos 4 a 6 horas.

---

[← Voltar ao índice](./index.pt-BR.html)
