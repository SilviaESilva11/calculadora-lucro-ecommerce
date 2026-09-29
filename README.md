# Calculadora de Lucro e Simulação de Cenários para E-commerce

Este projeto consiste em uma ferramenta analítica interativa desenvolvida para simular e projetar o impacto financeiro de alavancas de crescimento e otimizações de conversão em um e-commerce de vestuário (focado na venda de calças).

A ferramenta utiliza dados históricos de acessos, transações, receitas e taxas de conversão segmentados por canal de origem e categoria de dispositivo (*Desktop*, *Mobile* e *Tablet*).

---

## 📊 Principais Funcionalidades

- **Ajuste de Margem de Lucro Operational:** Slider interativo para ajustar a margem bruta dos produtos (de 20% a 80%).
- **Otimização de Conversão Mobile (CRO):** Simulação de aumento na taxa de conversão em dispositivos móveis (atualmente em 2,27%).
- **Realocação de Orçamento de Mídia Pago:** Simulação da migração de tráfego de *Paid Social* para *Paid Search* (Google Ads), aproveitando a maior taxa de conversão do buscador (4,41%).
- **Aceleração de Email Marketing:** Projeção de receita marginal a partir do aumento da base e captura de leads via e-mail marketing (canal de maior conversão individual, com 6,55%).
- **Indicadores em Tempo Real (KPIs):** Atualização instantânea do Lucro Bruto Projetado, Receita Total, Número de Compras e Taxa de Conversão Global.

---

## 💻 Estrutura do Projeto

```text
CalculadoraLucroEcommerce/
├── wwwroot/
│   └── index.html          # Interface visual e lógica JavaScript da calculadora
├── Terry's Trousers Data.csv # Base de dados utilizada para calibração do modelo
└── README.md               # Documentação do projeto