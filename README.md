# FCT NOVA - Analytics Lab

Website simples desenhado para aprender e testar funcionalidades do **Google Analytics 4 (GA4)**.

## Funcionalidades para Testar

### 1. Aquisição de Tráfego (Traffic Acquisition)
Usa a secção **"Simulador de Tráfego"** para recarregar a página com parâmetros UTM e simular diferentes origens:
- **Facebook (Social):** `utm_medium=social`
- **Google Ads (Paid):** `utm_medium=cpc`
- **Newsletter (Email):** `utm_medium=email`

### 2. Conversão de Leads (Leads)
- **Formulário Principal:** Pede informações e escolhe o motivo (segmentação).
- **Newsletter:** Uma conversão secundária no footer.

### 3. Envolvimento (Engagement)
- **Vídeo:** Reproduz o vídeo para disparar eventos de `video_start`, `video_progress`, etc.
- **Botões:** O botão "Simular Candidatura" e downloads de PDF são rastreados.
- **Search:** Usa a barra de pesquisa para testar o `view_search_results`.