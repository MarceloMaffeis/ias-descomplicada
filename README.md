# 💡 IA Descomplicada: Do Básico ao Streamlit com Exemplos do Cotidiano

> **Plataforma Educacional Aberta de Inteligência Artificial**  
> *Recurso Educacional Aberto (REA) sob Licença MIT — Desenvolvido por Marcelo Maffeis*

---

## 🎯 Sobre o Projeto

O **IA Descomplicada** é um laboratório interativo desenvolvido em Python e [Streamlit](https://streamlit.io/) que desmistifica a Inteligência Artificial, o Aprendizado de Máquina (*Machine Learning*), o Processamento de Linguagem Natural (*PLN*), a Visão Computacional e as IAs Generativas (*RAG / LLMs*), utilizando analogias simples e dados práticos do dia a dia.

Cada módulo apresenta:
1. **Simulador Interativo em Tempo Real:** Gráficos, métricas e controles dinâmicos.
2. **Entendimento Passo a Passo:** Analogias do mundo real e conceitos teóricos sem jargões indecifráveis.
3. **Código Python Linha por Linha:** Sintaxe comentada com links diretos para a documentação oficial.

---

## 🧰 Módulos Disponíveis

| Módulo | Algoritmo / Técnica | Aplicação Prática | Biblioteca Principal |
| :--- | :--- | :--- | :--- |
| **0. Kit de Bibliotecas** | Visão Geral do Ecossistema | O kit de ferramentas essencial do desenvolvedor de IA | `numpy`, `pandas`, `sklearn`, `streamlit` |
| **1. Regressão Linear** | Regressão Linear Simples | Previsão de vendas de sorvetes conforme a temperatura | `sklearn.linear_model.LinearRegression` |
| **2. Classificação** | Árvores de Decisão (*Decision Tree*) | Separador automático de frutas por peso e textura | `sklearn.tree.DecisionTreeClassifier` |
| **3. Clusterização** | K-Means Clustering | Descoberta de perfis de compras em supermercados | `sklearn.cluster.KMeans` |
| **4. Deep Learning** | Perceptron Multicamadas (*MLP*) | Previsão de notas escolares via horas de estudo e sono | `sklearn.neural_network.MLPRegressor` |
| **5. PLN / Sentimentos** | Tokenização e Léxico de Sentimentos | Classificação de avaliações de pedidos de delivery | Processamento léxico em Python |
| **6. Visão Computacional** | Matrizes de Pixels e Filtros | Inspeção visual e controle de conformidade industrial | `numpy`, `plotly` / `opencv` |
| **7. Chatbot com RAG** | LLM + Recuperação Ancorada | Chatbot corporativo com manuais técnicos via Google Gemini | `requests` / API Google Gemini |

---

## 🚀 Como Executar Localmente

### 1. Pré-requisitos
* Python 3.10 ou superior instalado no seu sistema.
* Git instalado.

### 2. Instalação e Execução

```bash
# 1. Clone o repositório
git clone https://github.com/MarceloMaffeis/ias-descomplicada.git
cd ias-descomplicada

# 2. (Opcional, porém recomendado) Crie e ative um ambiente virtual
python -m venv .venv

# No Windows (PowerShell):
.venv\Scripts\Activate.ps1
# No Linux/macOS:
source .venv/bin/activate

# 3. Instale as dependências
pip install -r requirements.txt

# 4. Inicie a aplicação Streamlit
streamlit run app.py
```

Acesse no seu navegador em `http://localhost:8501`.

---

## ⚖️ Licença, Diretrizes de Uso & Blindagem Jurídica

### 1. Licença MIT (Código Aberto)
Este projeto está sob a **[Licença MIT](LICENSE)**. Você tem total permissão para:
* Utilizar, copiar, modificar, mesclar e distribuir o código-fonte;
* **Criar soluções comerciais ou acadêmicas:** Alunos e desenvolvedores têm total liberdade para utilizar os conhecimentos, códigos e arquiteturas deste repositório como base para desenvolver seus próprios aplicativos, produtos ou serviços monetizados.

### 2. Diretrizes de Uso da Plataforma Hospedada (Anti-Framing)
* **Acesso Público Gratuito:** O objetivo desta aplicação pública é democratizar o acesso à educação tecnológica de forma 100% gratuita.
* **Proibição de Encapsulamento Abusivo (*iFrames* / *Clickjacking*):** É terminantemente vedado o embutimento desta instância hospedada pública em *iframes* ou portais pagos de terceiros com o objetivo de comercializar ou cobrar assinaturas pelo acesso a este ambiente público. Qualquer cobrança de acesso a esta instância constitui prática desautorizada e abusiva perante os usuários.

### 3. Isenção Legal de Responsabilidade (*Disclaimer / AS IS*)
* O software é fornecido **"NO ESTADO EM QUE SE ENCONTRA" (*AS IS*)**, sem garantias expressas ou implícitas de qualquer natureza, incluindo, sem limitação, garantias de comercialização, adequação a fins específicos ou precisão de modelos matemáticos.
* Em nenhuma circunstância o autor ou colaboradores serão responsabilizados por quaisquer danos diretos, indiretos, incidentais ou lucros cessantes decorrentes do uso ou da impossibilidade de uso das ferramentas e simulações aqui apresentadas.
* As simulações possuem finalidade estritamente pedagógica e acadêmica.
