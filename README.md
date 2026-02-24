# Clima em Registro/SP

Página estática em HTML/CSS/JS que mostra o clima atual de **Registro/SP** com animações visuais.

## Funcionalidades

- Temperatura atual
- Sensação térmica
- Umidade
- Velocidade do vento
- Ícone e descrição do clima
- Efeitos animados (nuvens, chuva e entrada suave)

## Como executar localmente

1. Baixe/clonar este repositório.
2. Abra o arquivo `index.html` no navegador.

## Publicar no GitHub Pages

1. Envie os arquivos para um repositório no GitHub.
2. No GitHub, abra o repositório e vá em **Settings**.
3. Clique em **Pages**.
4. Em **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (ou a branch que você usa)
   - **Folder**: `/ (root)`
5. Clique em **Save**.
6. Aguarde o deploy e acesse a URL gerada pelo GitHub Pages.

## API utilizada

- [Open-Meteo Forecast API](https://open-meteo.com/)
- [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api)

## Observações

- A atualização dos dados é automática a cada 10 minutos.
- É necessário acesso à internet para consultar a API de clima.
