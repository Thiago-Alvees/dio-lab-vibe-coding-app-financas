
## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

O desafio é criar o conceito do seu próprio App de Finanças com IA, aplicando o jeito Vibe de programar, guiando ferramentas como o Copilot e o Lovable com prompts claros e criativos. Transforme suas ideias em um projeto real e construa um portfólio que destaque suas habilidades para o mercado!

> [!IMPORTANT]
> **Não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Criação do PRD (Product Requirements Document)

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
PRD – Aplicativo de Recomendação de Ações e FIIs
Título do Projeto: Aplicativo de análise de Ações e FIIs
Descrição:
Quero criar um aplicativo que ajude iniciantes a decidir em quais ações ou fundos imobiliários investir. O app deve mostrar se o preço está atrativo e calcular indicadores financeiros básicos (P/L, P/VP e Dividend Yield). Além disso, deve permitir salvar favoritos e exibir uma lista com as Top 5 recomendações.

Objetivo
Facilitar a tomada de decisão de investimento para iniciantes, com recomendações automáticas e linguagem simples.

Público-Alvo
• 	Pessoas que querem começar a investir sem complicação.
• 	Iniciantes no mercado financeiro.

Funcionalidades do MVP
1. 	Pesquisar ativos (ações e FIIs) pelo código.
2. 	Classificação automática com base nos cálculos:
• 	P/L (Preço/Lucro) = Preço ÷ Lucro por ação.
• 	P/VP (Preço/Valor Patrimonial) = Preço ÷ Valor Patrimonial por ação.
• 	Dividend Yield = Dividendos ÷ Preço × 100.
3. 	Favoritos: salvar ativos preferidos.
4. 	Top 5 recomendações: lista dos ativos mais atrativos.
5. 	Visualização simples de gráficos para tendência de preço.

Fórmulas de Cálculo
• 	P/L = Preço ÷ Lucro por ação.
• 	P/VP = Preço ÷ Valor Patrimonial por ação.
• 	Dividend Yield = Dividendos ÷ Preço × 100.
Para FIIs:
• 	P/VP = Preço da cota ÷ Valor Patrimonial por cota.
• 	Dividend Yield = Dividendos ÷ Preço da cota × 100.

Recursos Técnicos (gratuitos)
• 	API de dados financeiros: Yahoo Finance API ou Alpha Vantage.
• 	Banco de dados: Firebase ou Supabase.
• 	Front-end: React Native (mobile) ou Flutter.
• 	Back-end: Node.js ou Python (FastAPI).
• 	Hospedagem: Vercel ou Netlify.

Telas do MVP
• 	Tela de Pesquisa: campo de busca + resultado com preço atual e indicadores.
• 	Tela de Classificação: mostra P/L, P/VP e Dividend Yield com cores (verde = atrativo, amarelo = neutro, vermelho = caro).
• 	Tela de Favoritos: lista personalizada.
• 	Tela de Top 5: ranking dos ativos mais atrativos.
• 	Tela de Gráficos: tendência de preço simplificada.

```

### 2. Prompts utilizados no Lovable

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

```txt
Quero criar um aplicativo que ajude iniciantes a decidir em quais ações ou fundos imobiliários investir. O app deve mostrar se o preço está atrativo e calcular indicadores financeiros básicos (P/L, P/VP e Dividend Yield). 

Objetivo
Facilitar a tomada de decisão de investimento para iniciantes, com recomendações automáticas e linguagem simples.

Funcionalidades do MVP
1. 	Pesquisar ativos (ações e FIIs) pelo código.
2. 	Classificação automática com base nos cálculos:
• 	P/L (Preço/Lucro) = Preço ÷ Lucro por ação.
• 	P/VP (Preço/Valor Patrimonial) = Preço ÷ Valor Patrimonial por ação.
• 	Dividend Yield = Dividendos ÷ Preço × 100.
3. 	Favoritos: salvar ativos preferidos.
4. 	Top 5 recomendações: lista dos ativos mais atrativos.
5. 	Visualização simples de gráficos para tendência de preço.

Fórmulas de Cálculo
• 	P/L = Preço ÷ Lucro por ação.
• 	P/VP = Preço ÷ Valor Patrimonial por ação.
• 	Dividend Yield = Dividendos ÷ Preço × 100.
Para FIIs:
• 	P/VP = Preço da cota ÷ Valor Patrimonial por cota.
• 	Dividend Yield = Dividendos ÷ Preço da cota × 100.

Recursos Técnicos (gratuitos)
• 	API de dados financeiros:Alpha Vantage.
• 	Banco de dados:Supabase.
• 	Front-end: React Native.
• 	Back-end:Python (FastAPI).

Telas do MVP
• 	Tela de Pesquisa: campo de busca + resultado com preço atual e indicadores.
• 	Tela de Classificação: mostra P/L, P/VP e Dividend Yield com cores (verde = atrativo, amarelo = neutro, vermelho = caro).
• 	Tela de Favoritos: lista personalizada.
• 	Tela de Top 5: ranking dos ativos mais atrativos.
• 	Tela de Gráficos: tendência de preço simplificada.

```

### 3. Resultado Final
## Tela inicial 
<img width="1528" height="943" alt="image" src="https://github.com/user-attachments/assets/ef4782e6-2a53-4ac6-acfb-37f711d6e726" />
## Visão do ativo Selecionado
<img width="1423" height="938" alt="image" src="https://github.com/user-attachments/assets/542ac127-fb2a-42fa-bd0c-8e27072b10db" />
<img width="1503" height="936" alt="image" src="https://github.com/user-attachments/assets/07a4d3f7-08f8-4a4a-bc91-937b25dda4bc" />
## Link do projeto publicado, explore o quanto desejar!
https://preview--fii-finder-plus.lovable.app/
 
## 💬 Conclusão

Utilizar o conceito de Vibe Coding foi uma experiência bastante interessante. A ideia de simplesmente descrever o que eu precisava e ver o sistema gerar um MVP funcional é realmente incrível. Durante o desenvolvimento, consegui explorar ferramentas como o Copilot e o ChatGPT para a construção do prompt, e utilizei o Lovable para dar vida à aplicação.
No Lovable, enfrentei alguns desafios, principalmente para verificar se todas as informações que eu havia solicitado estavam implementadas corretamente e entender por que não era possível buscar outros ativos além dos já disponibilizados inicialmente. Apesar dessas dificuldades, a experiência foi enriquecedora.
Em resumo, aprendi que os conceitos de engenharia de prompt são fundamentais para otimizar o tempo de trabalho e alcançar resultados mais próximos do esperado. Tenho certeza de que, com prática e aprimoramento contínuo, poderei evoluir ainda mais nesse processo e seguir me desenvolvendo.

