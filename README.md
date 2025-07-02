# 📞 Análise de Evasão de Clientes (Churn) - Telecom X

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📋 Visão Geral

Este projeto apresenta uma análise completa de evasão de clientes (churn) para a empresa de telecomunicações **Telecom X**, utilizando técnicas de ciência de dados para identificar padrões comportamentais e fatores de risco que contribuem para o cancelamento de serviços.

### 🎯 Problema de Negócio

A Telecom X enfrenta um alto índice de evasão de clientes, impactando diretamente sua receita e crescimento. Sem clareza sobre as causas principais do churn, a empresa necessita de insights baseados em dados para:

- Identificar perfis de clientes com maior risco de cancelamento
- Desenvolver estratégias de retenção direcionadas
- Otimizar a experiência do cliente nos momentos críticos
- Subsidiar a criação de modelos preditivos

## 🔍 Metodologia

O projeto segue uma abordagem estruturada de análise de dados:

### 1. **Extração de Dados (Extract)**
- Coleta de dados de clientes via API
- Validação da integridade dos dados recebidos

### 2. **Transformação e Limpeza (Transform)**
- Tratamento de valores ausentes
- Normalização de formatos
- Criação de variáveis derivadas
- Validação de consistência

### 3. **Análise Exploratória (Analyze)**
- Análise univariada e bivariada
- Identificação de padrões e correlações
- Segmentação de clientes
- Visualizações interativas

### 4. **Insights e Recomendações (Report)**
- Síntese dos principais achados
- Recomendações estratégicas
- Próximos passos para implementação

## 📊 Principais Descobertas

### 🚨 Fatores Críticos de Churn

#### 💰 **Tipo de Contrato - Principal Indicador**
- **Contratos mensais** apresentam taxa de churn **3x superior** aos anuais
- Clientes sem compromisso de longo prazo representam **65%** dos cancelamentos
- **Recomendação**: Implementar incentivos para migração para contratos anuais

#### ⏱️ **Tempo de Permanência - Período Crítico**
- **72%** dos cancelamentos ocorrem nos primeiros **18 meses**
- Pico de evasão entre **6-12 meses** de relacionamento
- **Recomendação**: Programa de onboarding estendido e acompanhamento proativo

#### 📈 **Outros Fatores Relevantes**
- Clientes com múltiplos serviços têm **40% menos** probabilidade de cancelar
- Métodos de pagamento automático reduzem churn em **25%**
- Atendimento ao cliente nos primeiros 90 dias é **crítico**

## 🛠️ Tecnologias Utilizadas

### **Linguagens e Ferramentas**
- **Python 3.8+** - Linguagem principal
- **Jupyter Notebook** - Ambiente de desenvolvimento
- **Git** - Controle de versão

### **Bibliotecas Principais**
```python
pandas>=1.3.0          # Manipulação de dados
numpy>=1.20.0           # Computação numérica
matplotlib>=3.4.0       # Visualizações básicas
seaborn>=0.11.0         # Visualizações estatísticas
requests>=2.25.0        # Requisições HTTP
plotly>=5.0.0           # Visualizações interativas (opcional)
```

## 📂 Estrutura do Projeto

```
📦 TELECOMX/
├── 📓 TelecomX_BR.ipynb          # Notebook principal com análise completa
└── 📖 README.md                   # Este arquivo
```

## 🚀 Como Executar

### **Pré-requisitos**
- Python 3.8 ou superior instalado
- Git (opcional, para clonar o repositório)
- Jupyter Notebook ou JupyterLab

### **Instalação Rápida**

1. **Clone o repositório:**
```bash
git clone https://github.com/AlexandreCalmonJr/TelecomX_oracle_challenge_2.git
cd TelecomX_oracle_challenge_2
```

2. **Inicie o Jupyter:**
```bash
jupyter notebook
```

3. **Execute o notebook:**
- Abra `TelecomX_BR.ipynb`
- Execute as células sequencialmente (`Shift + Enter`)
- Aguarde o processamento completo (~5-10 minutos)

### **Instalação Manual das Bibliotecas**
```bash
pip install pandas numpy matplotlib seaborn requests plotly
```

## 📈 Resultados Esperados

Após a execução completa, você terá:

- ✅ **Análise exploratória completa** dos dados de clientes
- ✅ **Visualizações interativas** dos padrões de churn
- ✅ **Relatório executivo** com insights principais
- ✅ **Recomendações estratégicas** baseadas em dados
- ✅ **Base preparada** para modelos preditivos

## 🎯 Próximos Passos

### **Implementação Imediata**
1. **Programa de Retenção Proativa** para clientes de 6-18 meses
2. **Campanha de Migração** para contratos anuais com incentivos
3. **Melhoria do Onboarding** nos primeiros 90 dias

### **Desenvolvimento Futuro**
1. **Modelo Preditivo** de churn usando Machine Learning
2. **Dashboard em Tempo Real** para monitoramento
3. **Testes A/B** das estratégias de retenção
4. **Integração com CRM** para ações automatizadas

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📞 Contato

**Desenvolvido por**: Alexandre Calmon
- 📧 Email: alexandrecalmonjunior@gmail.com
- 💼 LinkedIn: [Alexandre Calmon](https://linkedin.com/in/alexandre-calmon)
- 🐙 GitHub: [@AlexandreCalmonJr](https://github.com/AlexandreCalmonJr)