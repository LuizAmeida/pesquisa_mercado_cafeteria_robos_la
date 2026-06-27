# Pesquisa de Mercado para Cafeteria com Garçons Robôs em Los Angeles

> Projeto de análise de dados do mercado de restaurantes em Los Angeles para recomendar o tipo de estabelecimento mais apropriado, o número ideal de assentos e avaliar a viabilidade de desenvolver uma rede de cafeterias com garçons robôs.

---

## 🎯 Objetivo do Projeto

Analisar os dados de restaurantes em Los Angeles para:

- Identificar os tipos de estabelecimentos existentes
- Avaliar a proporção de redes vs. estabelecimentos independentes
- Determinar qual tipo de estabelecimento é típico para redes
- Analisar as características das redes (assentos)
- Calcular a média de assentos por tipo de restaurante
- Identificar as ruas com maior concentração de restaurantes
- Gerar recomendações práticas para investidores

---

## 📊 Resultados Obtidos

### 1. Tipos de Estabelecimentos

| Tipo | Quantidade | Percentual |
|------|------------|------------|
| Restaurant | 7.255 | 75,2% |
| Fast Food | 1.066 | 11,0% |
| Cafe | 435 | 4,5% |
| Pizza | 320 | 3,3% |
| Bar | 292 | 3,0% |
| Bakery | 283 | 2,9% |
| Outros | 0 | 0% |
| **Total** | **9.651** | **100%** |

**Descoberta:** O mercado é dominado por "Restaurant" (75,2%). Cafeterias representam apenas 4,5% do mercado → oportunidade!

---

### 2. Redes vs. Independentes

| Categoria | Quantidade | Percentual |
|-----------|------------|------------|
| Independentes | 5.972 | 61,9% |
| Redes | 3.676 | 38,1% |
| **Total** | **9.651** | **100%** |

**Proporção:** 1 rede para cada 1,6 independentes

**Descoberta:** Mercado equilibrado com espaço para novas redes.

---

### 3. Tipos Mais Comuns em Redes

| Tipo | Quantidade | % das Redes |
|------|------------|-------------|
| Restaurant | 2.292 | 62,4% |
| Fast Food | 605 | 16,5% |
| Bakery | 283 | 7,7% |
| Cafe | 266 | 7,2% |
| Pizza | 153 | 4,2% |
| Bar | 77 | 2,1% |

**Descoberta:** Cafeterias em rede representam 7,2% das redes → modelo validado!

---

### 4. Características das Redes (Assentos)

| Métrica | Redes | Independentes |
|---------|-------|---------------|
| Média de assentos | 40 | 46 |
| Mediana | 35 | 40 |
| Mínimo | 1 | 1 |
| Máximo | 200 | 229 |

**Descoberta:** Redes têm estabelecimentos MENORES que os independentes (40 vs 46 assentos).

---

### 5. Média de Assentos por Tipo

| Tipo | Média de Assentos |
|------|-------------------|
| Restaurant | 48 |
| Bar | 45 |
| Fast Food | 32 |
| Pizza | 28 |
| Cafe | 25 |
| Bakery | 22 |

**Descoberta:** Restaurant tem a maior média (48 assentos). Cafe tem média de 25 assentos.

---

### 6. Top 10 Ruas com Mais Restaurantes

| Posição | Rua | Restaurantes |
|:---:|-----|:---:|
| 1º | W SUNSET BLVD | 296 |
| 2º | W PICO BLVD | 288 |
| 3º | HOLLYWOOD BLVD | 167 |
| 4º | WILSHIRE BLVD | 161 |
| 5º | S VERMONT AVE | 148 |
| 6º | SANTA MONICA BLVD | 146 |
| 7º | W 3RD ST | 145 |
| 8º | BEVERLY BLVD | 135 |
| 9º | S FIGUEROA ST | 134 |
| 10º | S WESTERN AVE | 128 |

**Descoberta:** W SUNSET BLVD é a rua com maior fluxo de restaurantes em LA.

---

### 7. Ruas com Apenas 1 Restaurante

| Métrica | Valor |
|---------|-------|
| Número de ruas | 2.445 |
| Percentual do total | 79,5% |

**Descoberta:** A maioria das ruas tem apenas 1 restaurante → oportunidades em locais inexplorados.

---

## 📊 Resumo dos Insights

| Métrica | Insight |
|---------|---------|
| Mercado de cafeterias | 4,5% do mercado (oportunidade) |
| Redes vs. Independentes | 38,1% são redes (mercado equilibrado) |
| Cafe em redes | 266 estabelecimentos (7,2% das redes) |
| Assentos - Redes | Média de 40 assentos |
| Assentos - Cafe | Média de 25 assentos |
| Maior média de assentos | Restaurant (48 assentos) |
| Rua com mais restaurantes | W SUNSET BLVD (296) |
| Ruas com 1 restaurante | 2.445 ruas (79,5%) |
| Tipo recomendado | Coffee Shop / Cafeteria |
| Assentos recomendados | 40 assentos |
| Localização recomendada | W SUNSET BLVD |
| Viabilidade de rede | SIM (mercado valida) |

---

## 🛠️ Ferramentas Utilizadas

- **Python 3**
- **Bibliotecas:**
  - `pandas` — manipulação e análise de dados
  - `matplotlib` — visualização de dados
  - `seaborn` — visualização estatística

---

## 📚 O que Aprendi

- **Análise de mercado:** identificação de oportunidades em segmentos subexplorados
- **Segmentação por tipo:** compreensão da distribuição de estabelecimentos
- **Análise de redes:** características e padrões de expansão
- **Distribuição geográfica:** identificação de ruas com maior concentração
- **Recomendação de negócio:** tradução de dados em decisões práticas para investidores

---

## 🚀 Como Executar o Projeto

```bash
# Clone o repositório
git clone https://github.com/LuizAlmeida/pesquisa_mercado_cafeteria_robos_la

# Navegue até a pasta do projeto
cd pesquisa_mercado_cafeteria_robos_la

# Execute o notebook (recomendado: Google Colab ou Jupyter Notebook)
````


## Requisitos:
- Python 3.x instalado
- Jupyter Notebook (opcional) ou Google Colab (recomendado)
- Bibliotecas: pip install pandas matplotlib seaborn


## 🔍 Metodologia
O projeto seguiu uma abordagem estruturada em 8 passos:


## Passo 1: Carregar e Preparar os Dados
- Leitura do arquivo rest_data_us_upd.csv
- Padronização de colunas
- Verificação de valores ausentes e duplicados
- Extração do nome da rua a partir do endereço

## Passo 2: Proporção de Tipos de Estabelecimentos
- Contagem e percentual por tipo
- Gráfico de barras

Análise específica de cafeterias

## Passo 3: Proporção de Redes vs. Independentes
- Contagem e percentual
- Gráfico de pizza

## Passo 4: Tipo Típico para Redes
- Filtragem apenas de redes
- Identificação dos tipos mais comuns
- Análise de cafeterias em redes

## Passo 5: Características das Redes (Assentos)
- Estatísticas comparativas (média, mediana, min, max)
- Boxplot comparativo
- Resposta à pergunta sobre padrão de redes

## Passo 6: Média de Assentos por Tipo
- Cálculo da média por tipo
- Gráfico de barras
- Identificação do tipo com maior média

## Passo 7: Distribuição por Ruas
- Identificação das top 10 ruas
- Contagem de ruas com apenas 1 restaurante
- Boxplot das top 5 ruas

## Passo 8: Conclusão e Recomendações
- Consolidação de todos os achados
- Recomendações para investidores
- Plano de expansão sugerido


## 💡 Recomendações para Investidores
| Aspecto |	Recomendação |
| :--- | :--- |
| Tipo |	Coffee Shop / Cafeteria |
| Assentos |	40 assentos |
| Localização |	W SUNSET BLVD |
| Estratégia |	Começar com 1 unidade, expandir para rede (5-7 unidades em 5 anos) |
| Diferencial |	Garçons robôs → justifica capacidade acima da média (40 vs 25 da média de cafes) |


## Justificativas
- Tipo (Coffee Shop / Cafeteria):
> Segmento com apenas 4,5% do mercado (pouca concorrência direta)
> Modelo de rede já existe (266 cafeterias em rede em LA)
> Perfeito para o conceito de garçons robôs

- Assentos (40 assentos):
> Acima da média de cafeterias (25 assentos) → diferencial
> Abaixo de restaurantes (48 assentos) → não competir diretamente
> Alinhado com o padrão de redes (40 assentos em média)

- Localização (W SUNSET BLVD):
> Maior fluxo de LA (296 restaurantes)
> Perfil variado de estabelecimentos
> Melhor custo-benefício


## 📁 Estrutura do Projeto
````
📁 pesquisa_mercado_cafeteria_robos_la/
├── 📁 datasets/
│   └── rest_data_us_upd.csv
├── 📁 notebooks/
│   └── Projeto_Sprint_10.ipynb
├── 📁 presentations/
│   └── apresentacao_investidores.pdf
├── README.md
└── requirements.txt
````


## 📌 Contato
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/luizmarques84)
- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/LuizAlmeida)


## ⭐ Este projeto faz parte do meu Bootcamp em Análise de Dados na TripleTen.





