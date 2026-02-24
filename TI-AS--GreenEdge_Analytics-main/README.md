# ⚡ Dashboard de Monitoramento Energético (Eficiência de Data Centers)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Power BI](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

Um sistema completo de monitoramento e análise de eficiência energética para Data Centers, focado em reduzir custos operacionais e desperdícios através de métricas globais como **PUE** (Power Usage Effectiveness).

---

## 🎯 Minhas Contribuições (Destaques Técnicos)

Como desenvolvedor neste projeto, meu foco esteve na **performance, confiabilidade e análise de dados**, garantindo que o sistema suportasse o processamento em larga escala sem perder a fluidez:

* **Motor de Alertas (RF03):** Fui responsável pelo desenvolvimento da lógica que identifica e alerta os gestores em caso de quedas abruptas no desempenho dos servidores ou irregularidades energéticas.
* **Análise de Tendências (RF05):** Estruturei as ferramentas e lógicas de análise histórica, permitindo que o sistema cruze dados sequenciais para prever tendências de consumo ao longo do tempo.
* **Otimização e Escalabilidade (RNF04):** Atuei fortemente na otimização do código (Backend e Frontend) e na revisão da arquitetura, assegurando que o tempo de resposta do dashboard não fosse impactado por grandes volumes de dados processados.

### 📐 Arquitetura do Sistema e Fluxo de Dados
```mermaid
graph LR
    A[Frontend Web<br>HTML / JS Puro] -->|Envio de Planilhas<br>API REST| B(Backend Python<br>Flask / Pandas)
    B -->|ETL e Processamento| C[(Data Warehouse<br>Excel)]
    C -->|Script PowerShell<br>Automação| D[Dashboard Power BI<br>Análise DAX]