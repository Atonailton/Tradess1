# Entrerium - Robô de Análise de Criptomoedas

**Entrerium** é um robô de trade desenvolvido em HTML que realiza análise técnica de criptomoedas utilizando dados das APIs da Binance, TAAPI.io e TradingView. Ele combina RSI, MACD, Volume, sentimento de mercado e Smart Money Concepts para fornecer sinais precisos de compra, venda ou espera, com atualizações automáticas a cada 20 segundos.

## Funcionalidades

- **Análise Técnica Completa**:
  - RSI (Índice de Força Relativa)
  - MACD (Convergência/Divergência de Médias Móveis)
  - Volume de mercado
  - Sentimento de mercado (Alternative.me)
  - Reconhecimento de figuras gráficas (padrões de candle)
  - Smart Money Concept (movimentos institucionais)

- **Sinais Automatizados**:
  - Sugestão de compra, venda ou espera
  - Cálculo de lucro potencial
  - Cor prevista do próximo candle (verde/vermelho)
  - Atualização automática a cada 20 segundos

- **Outros Recursos**:
  - Inserção de valor disponível para cálculo de possíveis lucros
  - Mural de operações com sinais anteriores
  - Interface responsiva para desktop e mobile
  - Gráfico do TradingView embutido

## Tecnologias Utilizadas

- HTML5
- JavaScript puro (sem frameworks)
- APIs:
  - [Binance](https://binance-docs.github.io/apidocs/)
  - [TAAPI.io](https://taapi.io/)
  - [CoinGecko](https://www.coingecko.com/)
  - [Alternative.me - Fear & Greed Index](https://alternative.me/crypto/fear-and-greed-index/)
  - [TradingView Widget](https://www.tradingview.com/widget/)

## Como Usar

1. Clone este repositório ou extraia os arquivos do `.zip`.
2. Faça upload para sua conta no [Vercel](https://vercel.com/) ou abra o `index.html` diretamente no navegador.
3. Insira suas **chaves de API** (TAAPI.io e Binance) no local indicado no código (caso deseje dados reais).
4. Use os botões e insira os dados para visualizar os sinais de entrada e saída com lucro potencial.

## Requisitos

- Conexão com a internet (para consumo das APIs)
- Navegador moderno (Chrome, Firefox, Edge, etc.)

## Licença

Este projeto está sob a licença MIT. Sinta-se livre para modificar e melhorar conforme necessário.

---

**Desenvolvido por [Seu Nome ou Nome do Projeto]**
