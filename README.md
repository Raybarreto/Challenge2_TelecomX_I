# 📊 TelecomX - Análise de Evasão de Clientes (Churn)
Este projeto realiza uma análise exploratória de dados (EDA) com foco na evasão de clientes (churn) de uma empresa fictícia de telecomunicações, TelecomX. O objetivo é identificar padrões e variáveis que contribuem para a saída de clientes.

## 📁 Estrutura do Projeto
* Extração e carregamento de dados
* Tratamento de inconsistências
* Padronização e engenharia de atributos
* Análise descritiva
* Visualizações estatísticas
* Correlação de variáveis

## ✅ Requisitos e Instalação
Certifique-se de que você possui o **Python 3.7+ instalado**. Utilize o pip para instalar os pacotes necessários listados abaixo:

### 📄 Para executar este projeto, você precisará das seguintes bibliotecas Python:
* `requests`
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn` 

Você pode instalar todas as dependências de uma vez usando pip:

```
pip install requests pandas numpy matplotlib seaborn
```

## ▶️ Como Executar
1. Clone o repositório:
    
```
git clone https://github.com/Raybarreto/Challenge2_Telecom.git
cd Challenge2_Telecom
```

2. Execute o script principal:

    
```
python Telecom_BR.ipynb
```

Certifique-se de estar em um ambiente virtual.

## 🌐 Fonte de Dados
Os dados utilizados são carregados diretamente de um arquivo JSON hospedado no GitHub:

```
https://raw.githubusercontent.com/ingridcristh/challenge2-data-science/refs/heads/main/TelecomX_Data.json
```

## 🔍 Funcionalidades e Etapas
1. Limpeza de Dados
    * Conversão de colunas para tipos apropriados.
    * Tratamento de valores ausentes `(NaN)`.
    * Remoção de duplicatas.
      
2. Transformações
    * Mapeamento de variáveis categóricas para binárias.
    * Criação de novas variáveis como:
        ◦ Contas_diarias: cobrança média diária.
        ◦ Numero_servicos: total de serviços contratados.
      
3. Análise Exploratória
    * Distribuições de churn.
    * Comparações por gênero, idade, contrato, faturamento etc.
    * Visualizações com `Seaborn e Matplotlib`.
    * Cálculo da matriz de correlação.
      
4. Insights
    * Clientes com menos tempo de serviço tendem a evadir mais.
    * Certos métodos de pagamento estão mais associados à evasão.
    * A quantidade de serviços contratados impacta diretamente o churn.

## 📉 Visualizações
O script gera visualizações como:
* Histogramas de churn
* Gráficos de barras para variáveis categóricas
* Gráficos de densidade para variáveis numéricas
* Heatmap de correlação
* Boxplots comparando variáveis com churn

As imagens são exibidas automaticamente via `matplotlib.pyplot.show()`.

## ❗ Possíveis Problemas e Soluções
|   Problema   |   Solução  |
| :----------  | :--------: |
|ModuleNotFoundError para bibliotecas | Instale com `pip install <nome_do_pacote>` |
|Ambiente virtual não configurado | Use `python -m venv venv` e ative com `source venv/bin/activate ou venv\Scripts\activate` |
|Problemas ao carregar dados | Verifique a URL ou conexão com a internet |
|Gráficos não exibem | Certifique-se de que não está executando via terminal sem suporte gráfico (como SSH) |

## 🧠 Requisitos para Uso e Expansão
* Python básico/intermediário
* Conhecimentos de EDA
* Familiaridade com bibliotecas: `pandas, numpy, seaborn, matplotlib`

## 📬 Contato
Para dúvidas ou sugestões:
- Raylaine Barreto
- E-mail: raylainebarreto@outlook.com
- [LinkedIn](https://www.linkedin.com/in/raylaine-barreto)

