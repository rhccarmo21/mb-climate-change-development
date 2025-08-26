# 🌍 Climate Change & Development Analysis

[![Python](https://img.shields.io/badge/Python-3.8%252B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Completed-success)]()
[![GitHub](https://img.shields.io/badge/GitHub-rhccarmo21-%2523121011)](https://github.com/rhccarmo21)

Análise completa da relação entre desenvolvimento econômico e mudanças climáticas usando dados do Banco Mundial e Our World in Data.

[![Download Projeto Completo](https://img.shields.io/badge/Download-Projeto_Completo-%25230099ff?style=for-the-badge&logo=github)](mb-climate-change-development-main.zip)

---

## 🎯 Sobre o Projeto
Este projeto investiga a complexa relação entre desenvolvimento econômico (PIB per capita) e emissões de gases de efeito estufa, respondendo à questão central:

> "Como o desenvolvimento econômico de um país está relacionado com sua trajetória de emissões e vulnerabilidade climática?"

## 📊 Principais Resultados

### 🔍 Descobertas Chave
- **Correlação PIB-Emissões:** 0.75-0.85  
- **Ponto de inflexão:** ~$30,000 USD per capita  
- **Desigualdade:** Países ricos emitem 8-12x mais per capita  
- **Eficiência:** Intensidade de carbono diminui apenas 1-2% ao ano  

### 🎯 Recomendações Estratégicas
- **Países em desenvolvimento:** Crescimento verde desde o início  
- **Países desenvolvidos:** Acelerar transição energética  
- **Todos os países:** Adotar intensidade de carbono como KPI  
- **Cooperação global:** Mecanismos de justiça climática  

## 🛠️ Tecnologias Utilizadas
- **Python 3.8+** com Jupyter Notebook  
- **Pandas & NumPy** - Manipulação de dados  
- **Matplotlib & Seaborn** - Visualizações  
- **Scipy** - Análises estatísticas  
- **APIs:** Banco Mundial e Our World in Data  

## 📁 Estrutura do Projeto

```
mb-climate-change-development-main/
│
├── notebooks/
│   └── analysis_main.ipynb          # Análise principal completa
│
├── scripts/
│   ├── data_collection.py           # Coleta de dados das APIs
│   └── setup_environment.sh         # Configuração do ambiente
│
├── data/
│   ├── raw/                         # Dados brutos das APIs
│   └── processed/                   # Dados processados
│
├── figures/                         # Visualizações geradas
│   ├── curva_kuznets.png
│   ├── relacao_principal_pib_co2.png
│   └── tendencia_intensidade.png
│
├── reports/
│   ├── RELATORIO_EXECUTIVO_ANALISE_ESTRATEGICA.md
│   └── relatorio_final.md
│
├── requirements.txt                 # Dependências do projeto
├── setup_environment.sh             # Script de configuração
└── README.md                         # Documentação completa
```

## 🚀 Como Usar após Download

1️⃣ Extraia o arquivo ZIP:
```bash
unzip mb-climate-change-development-main.zip
cd mb-climate-change-development-main
```

2️⃣ Configure o ambiente (Linux/Mac):
```bash
chmod +x setup_environment.sh
./setup_environment.sh
```

3️⃣ Ou configure manualmente:
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python -m ipykernel install --user --name=climate-env --display-name "Python (Climate Analysis)"
```

4️⃣ Execute a análise:
```bash
source venv/bin/activate
jupyter notebook notebooks/analysis_main.ipynb
```

## 📋 Conteúdo do Projeto
- Gráficos de dispersão PIB vs CO2  
- Curva de Kuznets Ambiental  
- Tendências temporais de eficiência  
- Comparativos entre grupos de renda  
- Análises de outliers e padrões  

## 🎯 Para quem é este projeto
- **Estudantes:** Aprenda análise de dados com Python e métodos estatísticos  
- **Analistas de Dados:** Estrutura replicável para projetos socioambientais  
- **Gestores Públicos:** Insights para políticas climáticas e planejamento sustentável  

## 🌐 Dados Utilizados
- **Banco Mundial:** Indicadores econômicos e sociais  
- **Our World in Data:** Dados climáticos e de emissões  
- **Período:** 1990-2020  
- **Variáveis:** PIB per capita, CO2 per capita, Intensidade de carbono, População  

## 🤝 Como Contribuir
- Faça um **Fork** do projeto: [GitHub](https://github.com/rhccarmo21/mb-climate-change-development)  
- Sugira melhorias via **Issues**  
- Envie **Pull Requests** com novas funcionalidades  

## 📝 Licença
MIT License

## 👥 Autor
Ricardo da Cunha - [rhccarmo21](https://github.com/rhccarmo21)

---

<div align="center">
🌍 Projeto para entender o planeta e construir um futuro melhor  
⭐ Deixe uma estrela no GitHub  
</div>
