
# Entrerium - Robô Cripto

**Entrerium** é um robô de análise de criptomoedas que exibe gráficos interativos com dados do Bitcoin em tempo real, utilizando a API do CoinGecko. Ele combina visualização com análise técnica em um painel moderno e responsivo.

## Funcionalidades

- Exibição de gráfico candlestick do Bitcoin (BTC)
- Obtenção automática dos dados da API CoinGecko (OHLC)
- Visualização com Chart.js + plugin financeiro
- Interface responsiva com TailwindCSS
- Mensagens de carregamento e erro personalizadas

## Tecnologias Utilizadas

- HTML5
- JavaScript ES6+
- Tailwind CSS
- Chart.js 4 com plugins:
  - `chartjs-chart-financial`
  - `chartjs-plugin-annotation`
  - `chartjs-adapter-moment`
- API pública CoinGecko

## Como usar

1. Basta abrir o arquivo `index.html` em qualquer navegador moderno.
2. O gráfico irá carregar automaticamente os candles do BTC/USD das últimas 24 horas.

## API Utilizada

- **CoinGecko OHLC Endpoint:**
  ```
  https://api.coingecko.com/api/v3/coins/bitcoin/ohlc?vs_currency=usd&days=1
  ```

## Pré-requisitos

- Conexão com a internet (para carregar dependências e dados do gráfico)
- Navegador compatível com ES6

## Exemplo

![Captura de tela do gráfico](https://via.placeholder.com/800x400.png?text=Entrerium+Candlestick+Chart)

## Licença

Este projeto é de uso pessoal. Você pode modificar, estudar ou integrar como quiser.
