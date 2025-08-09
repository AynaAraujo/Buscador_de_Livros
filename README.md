# 📚 Busca Inteligente de Livros com RAG

## 📌 Descrição

Este projeto implementa a técnica **RAG** (*Retrieval-Augmented Generation*) para oferecer **busca personalizada de obras literárias** em um dataset de livros.
Através de **modelos de linguagem avançados** e **busca vetorial**, o sistema retorna resultados mais relevantes e contextualizados, mesmo para consultas complexas em linguagem natural.

---

## 🚀 Tecnologias Utilizadas

* **[LlamaIndex](https://gpt-index.readthedocs.io/)** – Indexação e recuperação eficiente de informações
* **[Pandas](https://pandas.pydata.org/)** – Manipulação e análise de dados tabulares
* **[HuggingFace Transformers](https://huggingface.co/)** – Modelos de linguagem e embeddings
* **[ChromaDB](https://www.trychroma.com/)** – Banco de dados vetorial para busca semântica
* **[Gradio](https://www.gradio.app/)** – Interface web interativa para o usuário

---

## 💡 Funcionalidades

* 🔍 **Busca inteligente e personalizada** de livros a partir de consultas em linguagem natural
* 🤖 **Integração com IA** para melhorar a relevância e contexto das respostas
* 🖥 **Interface web amigável** para facilitar a interação
* 📊 Suporte a grandes volumes de dados literários

---

## ⚙️ Como Funciona

1. O dataset de livros é indexado com **LlamaIndex** e armazenado no **ChromaDB**.
2. O usuário realiza uma busca usando linguagem natural.
3. O sistema localiza os livros mais relevantes via busca vetorial.
4. Um modelo de linguagem da **HuggingFace** gera respostas contextualizadas.
5. Os resultados são exibidos em uma **interface Gradio** intuitiva.

---

## 📌 Exemplo de Uso

```bash
python app.py
```

Em seguida, acesse a interface web gerada e digite:

> "Quais livros clássicos de ficção científica têm protagonistas femininas?"

O sistema retornará uma lista de títulos com detalhes e contexto adicional.

