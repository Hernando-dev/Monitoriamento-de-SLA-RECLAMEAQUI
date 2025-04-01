# Monitoriamento-de-SLA-RECLAMEAQUI
Bot automatizado que monitora prazos de resposta a reclamações no Reclame Aqui, enviando alertas quando há risco de violação.
sla-monitor-bot/
├── .github/
│   └── workflows/
│       └── monitor.yml        # Configuração do GitHub Actions
├── data/
│   ├── complaints.csv        # Dados históricos
│   └── model.pkl            # Modelo de ML treinado
├── src/
│   ├── scraper.py           # Coleta de dados (scraping)
│   ├── analyzer.py          # Análise de SLA
│   ├── predictor.py         # Previsão com ML
│   ├── notifier.py          # Envio de alertas
│   └── config.py            # Configurações
├── requirements.txt         # Dependências
└── README.md                # Documentação
