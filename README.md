# 💡 Inteligência Artificial Generativa: criando soluções reais com RAG

Repositório oficial da palestra apresentada por **José Luiz Orestes Junior** na XXII SESINFO UNIFEB (Semana de Sistemas de Informação do Centro Universitário da Fundação Educacional de Barretos).

Aqui você encontra **os slides, exemplos de código e recursos práticos** usados para demonstrar como construir soluções de **IA Generativa** utilizando **RAG (Retrieval Augmented Generation)** e **LangChain**.

---

## 🧩 Estrutura do Repositório

| Diretório | Descrição |
|------------|------------|
| `apresentacao/` | Slides e materiais visuais da palestra |
| `demo-rag/` | Códigos e notebooks utilizados no hands-on |
| `utils/` | Diagramas e arquivos de apoio (arquitetura, fluxos, exemplos) |
| `recursos/` | Links úteis e referências complementares |

---

## 🧠 Sobre o conteúdo

Nesta palestra, exploramos como a **IA Generativa** pode ser combinada a técnicas de **RAG (Retrieval Augmented Generation)** para criar soluções que utilizam **dados próprios e atualizados**.

### 🧩 O que você vai aprender:
- O que é um **LLM (Large Language Model)**  
- Por que os LLMs **precisam de RAG**  
- Como o **LangChain** facilita a integração entre LLM, embeddings e Vector DB  
- Como usar **ChromaDB** para armazenar e consultar vetores  
- Construir um **chat com documentos** em Python (hands-on)

---

## ⚙️ Tecnologias e ferramentas utilizadas

| Categoria | Ferramenta |
|------------|-------------|
| 🧠 Modelos de Linguagem | OpenAI GPT-4 / GPT-3.5 |
| 🧩 Framework de Orquestração | [LangChain](https://www.langchain.com/) |
| 🧮 Banco de Dados Vetorial | [Chroma](https://www.trychroma.com/) |
| 💻 Ambiente de Desenvolvimento | [VS Code](https://code.visualstudio.com/) |
| 📓 Execução de Códigos | [Jupyter Notebook](https://jupyter.org/) |
| 🔡 Geração de Embeddings | `text-embedding-3-small` (OpenAI API) |

---

## 🚀 Hands-on

O diretório [`demo-rag/`](demo-rag/) contém notebooks que demonstram o fluxo completo:

1. **Carregar documentos**
2. **Gerar embeddings com OpenAI**
3. **Indexar dados no Vector DB (Chroma)**
4. **Consultar dados via LangChain**
5. **Criar um chat inteligente com base no conteúdo local**

### Instalação

Clone este repositório e instale as dependências:

```bash
git clone https://github.com/seu-usuario/genai-rag-palestra.git
cd genai-rag-palestra/demo-rag
pip install -r requirements.txt
