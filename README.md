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

## 🚀 Como Ver os Dados no Momento (Sem Esperar)
O GA4 demora 24-48h a processar relatórios finais, mas podes ver tudo agora:

1. **Relatório de Tempo Real:** No menu esquerdo, vai a **Relatórios > Tempo Real**. Mostra atividade dos últimos 30 minutos.
2. **DebugView (O Melhor para Testes):**
    - Como eu ativei o `debug_mode: true` no código, podes ir a **Admin > DebugView**.
    - Aqui os eventos aparecem **segundo a segundo** numa cronologia vertical. É o ideal para validares se o teu clique no botão disparou o evento correto.