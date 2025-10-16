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

## 🧭 Links úteis  

| Tema | Link |
|------|------|
| 🎨 Criar apresentações visuais | [Gamma.app](https://gamma.app) |
| 🤖 ChatGPT | [https://chat.openai.com](https://chat.openai.com) |
| 🧩 LangChain | [https://www.langchain.com/](https://www.langchain.com/) |
| 🧱 ChromaDB | [https://www.trychroma.com/](https://www.trychroma.com/) |
| 📓 Jupyter Notebook | [https://jupyter.org/](https://jupyter.org/) |
| 💻 VS Code | [https://code.visualstudio.com/](https://code.visualstudio.com/) |
| 🔐 Variáveis de ambiente (.env) | [python-dotenv](https://pypi.org/project/python-dotenv/) |
| 📚 Documentação OpenAI API | [https://platform.openai.com/docs](https://platform.openai.com/docs) |
| 🌐 Exemplos oficiais LangChain | [https://github.com/langchain-ai/langchain](https://github.com/langchain-ai/langchain) |

---

### 📖 Referências e Leituras Recomendadas

- 🧮 **Gerando embeddings e vectorstore para os seus LLMs** — *por Diogo Santos*  
  [https://www.linkedin.com/pulse/gerando-embeddings-e-vectorstore-para-os-seus-llms-diogo-santos-q6chf/](https://www.linkedin.com/pulse/gerando-embeddings-e-vectorstore-para-os-seus-llms-diogo-santos-q6chf/)
  
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
```

---
## 💬 Contato  

📧 **José Luiz Orestes Junior**  
💼 [LinkedIn](https://www.linkedin.com/in/jose-luiz-orestes-junior-bab0556a/)  
🏢 *Senior Engineering Manager | AWS Certified Solutions Architect | PSM I | Management 3.0*  


---

⭐ *Se este conteúdo te ajudou, deixe uma estrela no repositório e compartilhe com colegas!*

