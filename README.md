# Projeto Aplicado I: Análise Exploratória de Preços e Cesta Básica (Curitiba)

## 📌 Identificação 
* **Disciplina**: Projeto Aplicado I
* **Instituição**: Universidade Presbiteriana Mackenzie
* **Grupo**: 9
* **Integrantes**: Jennifer Lins Baia da Silva (10756227) e 
Nilton Cesar Marques dos Santos (10733175)

---

## 🏢 A Empresa-Alvo: Prefeitura de Curitiba (Programa Clique Economia)
O **Clique Economia** é um serviço de utilidade pública mantido pela Prefeitura de Curitiba. Trata-se de uma plataforma governamental voltada à transparência que monitora e disponibiliza os valores de gêneros alimentícios e itens de primeira necessidade praticados no varejo local .

* **Abrangência**: Município de Curitiba, cobrindo os preços praticados por diversas redes de supermercados da região .
* **Transparência de Dados**: O programa coleta e centraliza as informações no portal de dados abertos da cidade, auxiliando o cidadão na pesquisa de preços para gerar economia doméstica .
* **Inteligência de Mercado**: A base permite a formulação de análises avançadas sobre a inflação local de alimentos, mapeamento de competitividade do varejo e entendimento do custo de vida urbano .

---

## 🎯 O Projeto 
Este projeto tem como objetivo realizar uma exploração profunda e extrair *insights* estratégicos sobre a flutuação de preços nos supermercados da capital paranaense, utilizando técnicas de Ciência de Dados para simular o custo da cesta básica e entender as discrepâncias de valores entre diferentes redes .

### Conexão com ODS (UNESCO) 
Este estudo está alinhado ao **ODS 2: Fome Zero e Agricultura Sustentável**, contribuindo para o monitoramento do acesso econômico e da segurança alimentar da população . Adicionalmente, tangencia o **ODS 10: Redução das Desigualdades**, auxiliando na compreensão das assimetrias de preços e poder de compra de acordo com a rede varejista e a localização .

---

## 📊 Dataset 
Os dados utilizados foram extraídos do dataset [Clique Economia Dados (Curitiba)](https://www.kaggle.com/datasets/paulogladson/clickeconomiadados?resource=download) via Kaggle . O conjunto de dados compreende registros de preços regulares, promoções e valores de atacado de milhares de produtos coletados nas redes supermercadistas do município .

### Dicionário de Dados (Metadata)
| Variável | Descrição |
| :--- | :--- |
| `data_pesquisa` | Data em que a coleta de preços foi realizada no estabelecimento. |
| `id_empresa` | Identificador único da filial ou estabelecimento comercial. |
| `rede` | Nome da rede de supermercados (ex: Fuchspan). |
| `codigo_categoria` | Identificador da categoria à qual o produto pertence. |
| `id_produto` | Código de barras (geralmente padrão EAN-13) do produto. |
| `descricao` | Nome e características do produto (marca, peso, volume). |
| `preco_regular` | Preço padrão de venda do produto no varejo. |
| `preco_atacado` | Preço reduzido aplicado para compras em grande volume. |
| `preco_atacado_qtd` | Quantidade mínima de itens exigida para ativar o preço de atacado. |
| `preco_promocao` | Preço do produto quando está em oferta temporária. |
| `preco_fidelidade` | Preço exclusivo para clientes do programa de vantagens/fidelidade. |

---

## 📁 Estrutura do Repositório 
* `/dataset`: Contém os arquivos CSV extraídos do Kaggle referentes aos registros de preços .
* `/docs`: Documentação do projeto e PDFs das etapas de entrega .
* `/scripts`: Scripts Python com a rotina de limpeza e gráficos da Análise Exploratória (EDA).

---

## 🛠️ Tecnologias Utilizadas 
* **Linguagem**: Python 
* **Bibliotecas Principais**: Pandas 
* **Ambiente**: Jupyter Notebook / Google Colab 
