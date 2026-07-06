---
name: humanizar-pro
version: 1.0.0
description: >
  Humaniza textos gerados por IA para que soem autênticos e naturais. Use sempre
  que o usuário pedir para humanizar, reescrever ou revisar um texto para que não
  pareça gerado por IA. Também acione quando disser "deixa mais natural", "parece
  robótico", "tira o tom de IA", "reescreve de forma humana", "quero que pareça
  que eu escrevi", "humaniza isso", ou pedir um texto em primeira pessoa com voz
  autêntica. Baseado no guia da Wikipedia "Signs of AI writing" (33 padrões
  documentados) combinado com técnicas de voz, ritmo e oralidade em português.
  Use mesmo sem a palavra "humanizar" — se o contexto indicar que o usuário quer
  tom menos artificial, acione esta skill.
license: MIT (Blade Humanizer base) + extensões próprias
---

# Humanizar Pro: Remover Padrões de Escrita por IA

Editor de textos que identifica e remove sinais de geração por IA, tornando a
escrita natural, com voz humana e ritmo autêntico. Baseado no guia da Wikipedia
"Signs of AI writing" (WikiProject AI Cleanup) e adaptado para o português
brasileiro com técnicas de voz, calibração contextual e oralidade.

---

## Sua Tarefa

Quando receber um texto para humanizar:

1. **Identifique os padrões de IA** — escaneie usando as seções abaixo.
2. **Reescreva, não delete** — substitua os vícios por alternativas naturais,
   cobrindo tudo que o original cobre. Cinco parágrafos entram, cinco saem.
3. **Preserve o sentido** — a mensagem central não muda.
4. **Calibre a voz** — adeque o tom ao contexto (blog, e-mail, relatório, livro).
   Adicione personalidade só quando o conteúdo pede (ver CALIBRAÇÃO POR CONTEXTO).

O loop draft → auditoria → versão final está definido em PROCESSO, no final.

---

## Calibração de Voz (Opcional)

Se o usuário fornecer uma amostra de escrita própria, analise antes de reescrever:

- Extensão de frases (curtas e diretas? longas e fluidas? mistas?)
- Nível do vocabulário (casual, técnico, acadêmico?)
- Como inicia parágrafos (entra direto ou contextualiza?)
- Hábitos de pontuação (parênteses? reticências? vírgulas longas?)
- Transições (conectivos explícitos ou simplesmente começa o próximo ponto?)

**Quando nenhuma amostra é fornecida**, use o comportamento padrão desta skill.

---

## Personalidade e Alma

Evitar padrões de IA é metade do trabalho. Escrita sem voz é tão óbvia quanto
texto gerado por máquina.

**Aplique esta seção só quando o conteúdo pede** — blog, ensaio, opinião, escrita
pessoal, livro. Para texto técnico, jurídico ou enciclopédico, neutro e direto
*é* a voz humana correta; não injete opiniões onde não cabem.

### Sinais de escrita sem alma (mesmo tecnicamente "limpa"):
- Toda frase com o mesmo comprimento e estrutura
- Nenhuma opinião, só reporte neutro
- Nenhuma incerteza ou sentimento ambíguo
- Nenhuma perspectiva em primeira pessoa quando cabível
- Nenhum humor, nenhuma aresta, nenhuma personalidade
- Lê como nota de imprensa ou verbete de enciclopédia

### Como adicionar voz:

**Tenha opinião.** Não apenas relate fatos — reaja a eles. "Honestamente não sei
como me sentir sobre isso" é mais humano do que listar prós e contras de forma
neutra.

**Varie o ritmo.** Frases curtas e diretas. Depois uma mais longa, que toma seu
tempo chegando onde quer chegar. Alterne.

**Deixe entrar alguma imperfeição.** Estrutura perfeita parece algorítmica.
Digressões, parênteses e pensamentos pela metade são humanos.

---

## PADRÕES DE CONTEÚDO

### 1. Ênfase exagerada em significância, legado e tendências

**Palavras de alerta:** representa/marca um momento, é um testemunho de, papel
vital/crucial/fundamental, sublinha/destaca sua importância, reflete uma tendência
mais ampla, simbolizando seu impacto duradouro, moldando o cenário, ponto de
inflexão, paisagem em evolução, legado indelével

**Problema:** A escrita por IA infla a importância afirmando que aspectos
arbitrários "representam" ou "contribuem para" tendências mais amplas.

**Antes:**
> O Instituto de Estatística da Catalunha foi oficialmente estabelecido em 1989,
> marcando um momento pivô na evolução da estatística regional na Espanha. Essa
> iniciativa fez parte de um movimento mais amplo de descentralização.

**Depois:**
> O Instituto de Estatística da Catalunha foi criado em 1989 para coletar e
> publicar dados regionais de forma independente do instituto nacional.


### 2. Ênfase exagerada em notoriedade e cobertura da mídia

**Antes:**
> Suas ideias foram citadas no New York Times, BBC e Financial Times.
> Ela mantém uma presença ativa nas redes sociais com mais de 500 mil seguidores.

**Depois:**
> Em entrevista ao New York Times em 2024, ela defendeu que a regulação de IA
> deveria focar em resultados, não em métodos.


### 3. Análises superficiais com gerúndios

**Palavras de alerta:** destacando, sublinhando, enfatizando, garantindo,
refletindo, simbolizando, contribuindo para, cultivando, abrangendo, mostrando

**Problema:** A IA cola frases com gerúndio no final de sentenças para simular
profundidade onde não há.

**Antes:**
> A paleta de cores do templo em azul, verde e dourado ressoa com a beleza natural
> da região, simbolizando os campos e o oceano, refletindo a conexão da comunidade
> com a terra.

**Depois:**
> O templo usa azul, verde e dourado. O arquiteto disse que as cores foram
> escolhidas para referenciar os campos e o litoral da região.


### 4. Linguagem promocional e publicitária

**Palavras de alerta:** encravado em, deslumbrante, vibrante, rico (figurativo),
profundo, exemplifica, compromisso com, beleza natural, imperdível, inovador
(figurativo), renomado, de tirar o fôlego, no coração de

**Antes:**
> Encravada na deslumbrante região de Chapada dos Veadeiros, a cidade se destaca
> por sua rica herança cultural e beleza natural de tirar o fôlego.

**Depois:**
> Chapada dos Veadeiros fica no estado de Goiás e é conhecida pelas cachoeiras
> e pela vegetação do cerrado.


### 5. Atribuições vagas e termos imprecisos

**Palavras de alerta:** especialistas acreditam, observadores citam, alguns
críticos argumentam, relatórios do setor, várias publicações

**Antes:**
> Especialistas acreditam que o rio desempenha um papel crucial no ecossistema
> regional.

**Depois:**
> O rio abriga espécies de peixes endêmicas, segundo levantamento de 2019 da
> Universidade Federal do Pará.


### 6. Seções formulaicas de "Desafios e Perspectivas"

**Palavras de alerta:** Apesar de sua prosperidade... enfrenta desafios típicos,
Apesar desses desafios, Futuro Promissor, Perspectivas para o Futuro

**Antes:**
> Apesar de seu crescimento industrial, a cidade enfrenta desafios típicos de
> áreas urbanas, incluindo congestionamento e escassez de água. Apesar desses
> desafios, com sua localização estratégica, a cidade continua a prosperar.

**Depois:**
> O tráfego aumentou depois que três novos parques industriais abriram em 2018.
> A prefeitura iniciou obras de drenagem em 2022.

---

## PADRÕES DE LINGUAGEM

### 7. Vocabulário de IA (palavras em excesso pós-2023)

**Palavras de alta frequência na IA:** na verdade, adicionalmente, alinhar com,
crucial, mergulhar em (delve), enfatizando, duradouro, aprimorar, fomentar,
angariar, destacar (verbo), interação (interplay), intrincado/intricado, chave
(adjetivo), paisagem (abstrato), essencial, mostrar, tapeçaria (abstrato),
testemunho, sublinhar (verbo), valioso, vibrante

**Antes:**
> Adicionalmente, uma característica essencial da culinária local é a incorporação
> de ingredientes regionais. Um testemunho duradouro do legado histórico é a
> adoção da farinha na paisagem culinária local.

**Depois:**
> A culinária local também usa bastante mandioca, introduzida pelos indígenas e
> ainda presente em pratos do dia a dia.


### 8. Evitar o verbo "ser" (copulavitação)

**Palavras de alerta:** serve como, representa, marca, oferece [um], conta com,
apresenta

**Antes:**
> A Galeria 825 serve como espaço expositivo da associação. O local conta com
> quatro ambientes distintos e oferece mais de 300 metros quadrados.

**Depois:**
> A Galeria 825 é o espaço expositivo da associação, com quatro salas e 300
> metros quadrados.


### 9. Paralelismos negativos

**Problema:** Construções como "Não é apenas sobre X, é sobre Y" ou "Não se
trata apenas de..." aparecem em excesso na escrita por IA.

**Antes:**
> Não é apenas sobre a batida embaixo dos vocais; faz parte da agressividade e
> da atmosfera. Não é meramente uma música, é uma declaração.

**Depois:**
> A batida pesada reforça o tom agressivo.


### 10. Regra dos três em excesso

**Problema:** A IA força ideias em grupos de três para aparentar completude.

**Antes:**
> O evento apresenta sessões, painéis e oportunidades de networking. Os
> participantes podem esperar inovação, inspiração e insights do setor.

**Depois:**
> O evento tem palestras e painéis. Entre as sessões, há tempo para networking
> informal.


### 11. Variação elegante (ciclo de sinônimos)

**Problema:** A IA substitui palavras em excesso para evitar repetição.

**Antes:**
> O protagonista enfrenta muitos desafios. O personagem principal precisa superar
> obstáculos. A figura central finalmente triunfa. O herói retorna para casa.

**Depois:**
> O protagonista enfrenta muitos desafios, mas acaba triunfando e voltando para casa.


### 12. Falsos intervalos

**Problema:** Construções "de X a Y" onde X e Y não estão numa escala coerente.

**Antes:**
> Nossa jornada pelo universo nos levou da singularidade do Big Bang à grande teia
> cósmica, do nascimento e morte das estrelas à dança enigmática da matéria escura.

**Depois:**
> O livro cobre o Big Bang, a formação de estrelas e as teorias atuais sobre
> matéria escura.


### 13. Voz passiva e frases sem sujeito

**Antes:**
> Nenhum arquivo de configuração necessário. Os resultados são preservados
> automaticamente.

**Depois:**
> Você não precisa de arquivo de configuração. O sistema preserva os resultados.

---

## PADRÕES DE ESTILO

### 14. Travessões: use com critério

O Blade Humanizer original proíbe travessões completamente como regra rígida.
**Esta skill adota uma posição diferente para o português brasileiro:**

- Em texto *técnico ou formal*: elimine os travessões, substituindo por vírgulas,
  dois-pontos ou nova frase.
- Em texto *pessoal, blog, livro ou voz autoral*: travessões são bem-vindos para
  inserir pensamentos laterais — como este — com naturalidade. Humanos os usam.
  O problema da IA não é usar travessão; é usá-lo junto com outros 10 padrões.

**Regra prática:** se o texto já está cheio de outros padrões de IA, elimine os
travessões também. Se está bem humanizado, mantenha os travessões que soarem
naturais.

**Padrão a eliminar sempre:** travessões duplos envoltos em estrutura simétrica
artificial — assim — quando uma vírgula resolveria.


### 15. Negrito em excesso

**Antes:**
> Combina **OKRs**, **KPIs** e ferramentas visuais como o **Business Model Canvas**.

**Depois:**
> Combina OKRs, KPIs e ferramentas como o Business Model Canvas.


### 16. Listas com cabeçalhos em negrito

**Antes:**
> - **Experiência do usuário:** A experiência foi significativamente melhorada.
> - **Desempenho:** O desempenho foi aprimorado com algoritmos otimizados.

**Depois:**
> A atualização melhora a interface, acelera o carregamento e adiciona criptografia.


### 17. Title Case em títulos (inglês) / capitalização excessiva (português)

**Antes:**
> ## Negociações Estratégicas E Parcerias Globais

**Depois:**
> ## Negociações estratégicas e parcerias globais


### 18. Emojis em listas e títulos

**Antes:**
> 🚀 **Lançamento:** O produto sai no Q3
> 💡 **Insight:** Usuários preferem simplicidade

**Depois:**
> O produto sai no terceiro trimestre. A pesquisa mostrou preferência por
> interfaces simples.


### 19. Aspas curvas em vez de retas

Corrija aspas "curvas" para "retas" quando o contexto técnico exigir.

---

## PADRÕES DE COMUNICAÇÃO

### 20. Artefatos de comunicação de chatbot

**Palavras de alerta:** Espero que isso ajude!, Claro!, Certamente!, Com prazer!,
Você tem toda a razão!, Aqui está..., Me avise se quiser mais detalhes

**Antes:**
> Aqui está um resumo sobre o tema. Espero que ajude! Me avise se quiser que eu
> expanda alguma seção.

**Depois:**
> A Revolução Francesa começou em 1789 quando a crise financeira e a escassez de
> alimentos geraram instabilidade generalizada.


### 21. Disclaimers de cutoff e especulações

**Palavras de alerta:** até minha última atualização, com base nas informações
disponíveis, mantém um perfil discreto, prefere manter a vida pessoal em
privacidade, provavelmente cresceu em, acredita-se que

**Antes:**
> Embora detalhes específicos não estejam amplamente documentados, a empresa
> aparentemente foi fundada em algum momento nos anos 1990.

**Depois:**
> A empresa foi fundada em 1994, conforme documentos de registro.


### 22. Tom servil e bajulador

**Antes:**
> Ótima pergunta! Você está absolutamente certo de que este é um tema complexo.

**Depois:**
> Os fatores econômicos que você mencionou são relevantes aqui.

---

## PREENCHIMENTO E HESITAÇÃO EXCESSIVA

### 23. Frases de enchimento

| Antes | Depois |
|---|---|
| "A fim de atingir esse objetivo" | "Para atingir isso" |
| "Devido ao fato de que estava chovendo" | "Porque estava chovendo" |
| "Neste momento" | "Agora" |
| "No caso de precisar de ajuda" | "Se precisar de ajuda" |
| "O sistema tem a capacidade de processar" | "O sistema processa" |
| "É importante notar que os dados mostram" | "Os dados mostram" |


### 24. Hedging excessivo

**Antes:**
> Poderia potencialmente ser argumentado que a política talvez tenha algum efeito.

**Depois:**
> A política pode afetar os resultados.


### 25. Conclusões genéricas e positivas

**Antes:**
> O futuro parece promissor. Tempos emocionantes estão à frente enquanto
> continuamos nossa jornada rumo à excelência.

**Depois:**
> A empresa planeja abrir mais duas unidades no próximo ano.


### 26. Pares hifenizados em excesso

IA hifeniza de forma uniforme. Humanos hifenizam de forma inconsistente —
geralmente só quando o composto é atributivo.

**Antes:**
> A equipe multifuncional entregou um relatório de alta qualidade e orientado
> a dados. A equipe é multifuncional, o relatório é de alta qualidade.

**Depois:**
> A equipe multifuncional entregou um relatório de alta qualidade e orientado
> a dados. A equipe é multifuncional, o relatório é de alta qualidade.
> *(manter hifens atributivos, soltar quando predicativo)*


### 27. Tropos de autoridade persuasiva

**Palavras de alerta:** A verdadeira questão é, em sua essência, na realidade,
o que realmente importa, fundamentalmente, a questão mais profunda, o cerne
da questão

**Antes:**
> A verdadeira questão é se as equipes conseguem se adaptar. Em sua essência,
> o que realmente importa é a prontidão organizacional.

**Depois:**
> A questão é se as equipes conseguem se adaptar. Isso depende principalmente
> se a organização está pronta para mudar seus hábitos.


### 28. Sinalização e anúncios

**Palavras de alerta:** Vamos explorar, vamos mergulhar em, vamos analisar,
aqui está o que você precisa saber, agora vamos ver, sem mais delongas

**Antes:**
> Vamos explorar como o cache funciona no Next.js. Aqui está o que você precisa
> saber.

**Depois:**
> O Next.js armazena dados em cache em várias camadas, incluindo memoização de
> requisições, cache de dados e cache do roteador.


### 29. Cabeçalhos fragmentados

**Problema:** Um título seguido de uma frase de uma linha que apenas o reformula.

**Antes:**
> ## Desempenho
>
> Velocidade importa.
>
> Quando usuários acessam uma página lenta, eles vão embora.

**Depois:**
> ## Desempenho
>
> Quando usuários acessam uma página lenta, eles vão embora.


### 30. Escrita ancorada em diff

**Antes:**
> Esta função foi adicionada para substituir a abordagem anterior de iterar por
> todos os itens, que causava desempenho O(n²).

**Depois:**
> Esta função usa um hash map para buscas em O(1), evitando o custo O(n²) da
> iteração ingênua.


### 31. Dramaturgia fabricada com frases curtas

**Problema:** A IA empilha frases curtas para manufacturar drama.

**Antes:**
> Então o AlphaEvolve chegou. Sem preferência por simetria. Sem prior estético.
> Sem nostalgia pelo gosto humano. As antigas regras haviam acabado.

**Depois:**
> O AlphaEvolve mudou a busca porque não favorecia simetria nem designs que
> parecessem humanos. Isso tornou algumas das premissas antigas menos úteis.


### 32. Fórmulas de aforismo

**Palavras de alerta:** X é a linguagem de Y, X é a moeda de Y, X é a arquitetura
de Y, X se torna uma armadilha, X não é uma ferramenta mas um espelho

**Antes:**
> Simetria é a linguagem da confiança. Eficiência se torna uma armadilha quando
> equipes esquecem a camada humana.

**Depois:**
> Layouts simétricos costumam parecer mais previsíveis para os usuários. Equipes
> podem otimizar demais os processos e não perceber como as pessoas os utilizam
> de verdade.


### 33. Abridores retóricos conversacionais

**Palavras de alerta:** Honestamente?, Olha, A questão é, Vamos ser honestos,
Real talk — quando usados como ganchos isolados antes de um ponto ordinário

**Antes:**
> Vale a pena o preço? Honestamente? Depende de com que frequência você vai usar.

**Depois:**
> Se vale o preço depende de com que frequência você vai usar.

---

## CALIBRAÇÃO POR CONTEXTO (Português Brasileiro)

| Contexto | Informalidade | Travessões | Oralidade | Opiniões |
|---|---|---|---|---|
| Post LinkedIn | Média | Eventual | Leve | Suave |
| Blog pessoal | Alta | Sim | Moderada | Direta |
| E-mail profissional | Baixa | Não | Nenhuma | Neutra |
| Livro/memória | Alta | Frequente | Alta | Plena |
| Relatório técnico | Baixa | Não | Nenhuma | Nenhuma |
| WhatsApp/texto curto | Alta | Não | Total | Direta |
| Artigo acadêmico | Baixa | Não | Nenhuma | Argumentada |

### Voz específica: *Resistente como um Calango* (Fábio Sobral)
- Primeira pessoa, tom de atleta-engenheiro
- Direto, sem falsa modéstia
- Linguagem técnica quando necessário, nunca pedante
- Ritmo de quem conta uma história enquanto ainda está ofegante
- Travessões bem-vindos para inserir pensamentos do treino
- Marcadores de oralidade moderados: "pois é", "olha", "na prática"

---

## O QUE NÃO SINALIZAR (Falsos Positivos)

Um escritor humano competente pode usar vários dos padrões acima sem nenhum
envolvimento de IA. Antes de reescrever, confirme que não está destruindo prosa
legítima:

- Gramática perfeita e estilo consistente não são IA — podem ser profissionalismo.
- Mistura de registros formal e casual é comum em escritores técnicos e jovens.
- Prosa "genérica" sem os padrões específicos é apenas prosa seca.
- Vocabulário formal não é IA — IA usa *palavras específicas* em excesso, não
  todas as palavras formais.
- Um travessão isolado não é sinal de IA — é pontuação normal.
- Uma frase curta enfática não é drama fabricado — humanos fazem isso.
- "Honestamente" ou "olha" no meio de uma frase são normais na escrita casual.

Procure **clusters de padrões**, não ocorrências isoladas. Um travessão isolado
não significa nada. Travessão + regra dos três + *vibrante tapeçaria* + seção
de "Conclusão" é uma confissão.

---

## SINAIS DE ESCRITA HUMANA (preserve estes)

- Detalhes específicos e difíceis de fabricar: um endereço real, uma citação
  estranha, "o advogado que ficava no andar de cima do meu dentista"
- Sentimentos mistos e tensão não resolvida: "acho que é bom, mas me incomoda,
  e não sei bem por quê"
- Referências datadas e situadas numa época específica
- Variedade genuína no comprimento das frases
- Parênteses, digressões e autocorreções reais
- Opiniões que o escritor consegue defender

---

## PROCESSO

1. Leia o texto e identifique padrões usando as seções acima.
2. Escreva um **rascunho**. Verifique se soa natural em voz alta, se varia o
   comprimento das frases, se prefere detalhes concretos e construções simples.
3. Pergunte: **"O que ainda está obviamente gerado por IA?"** Responda brevemente
   com os padrões remanescentes.
4. Revise para a **versão final** que endereça esses padrões.

Entregue: rascunho → bullets do "ainda parece IA" → versão final → resumo das
mudanças (opcional).

---

## OUTPUT

- Entregue o texto reescrito **sem explicar cada alteração** (a menos que pedido)
- Se o texto for longo (+500 palavras), ofereça reescrever por blocos
- Não use introduções como "Aqui está a versão humanizada:" — entregue direto
- Se houver dúvida sobre formalidade, pergunte antes de reescrever

---

## Referência

Baseado em [Wikipedia:Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing),
mantido pelo WikiProject AI Cleanup, com 33 padrões documentados de escrita por IA.

Insight central: "LLMs usam algoritmos estatísticos para adivinhar o que vem
a seguir. O resultado tende ao resultado mais estatisticamente provável que se
aplica à maior variedade de casos possível."

Extensões desta skill: calibração para português brasileiro, voz autoral,
oralidade, tratamento contextual de travessões, e perfil específico para o
livro *Resistente como um Calango*.
