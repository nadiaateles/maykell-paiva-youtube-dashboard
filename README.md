# Dashboard YouTube - Maykell Paiva

Painel estático com as métricas do canal do YouTube de Maykell Paiva, gerado a partir da YouTube Data API + Analytics API.

Não contém nenhuma credencial - só dados agregados já públicos no próprio YouTube (visualizações, inscritos, fonte de tráfego, vídeos mais vistos).

## Como atualizar os dados

Os dados são um retrato de um momento (snapshot), não ao vivo. Pra atualizar:

1. Rodar `gerar_dados_dashboard.py` (fica em `MAYKELL/Sistema de Produção/youtube-api/`, fora deste repositório)
2. Copiar o `dashboard_data.json` gerado pra dentro desta pasta
3. Colar o conteúdo dentro da tag `<script id="dashboard-data" type="application/json">` em `index.html`
4. Commit + push

Publicado via GitHub Pages.
