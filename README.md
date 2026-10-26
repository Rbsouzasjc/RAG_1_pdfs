# RAG_1_pdfs
um rag simples para docs
# 🔍 Sistema de Busca Semântica em Documentos (NR-20) com ChromaDB

Este projeto implementa uma solução de inteligência artificial para busca semântica inteligente e indexação de documentos complexos (utilizando como exemplo a norma regulamentadora **NR-20 - Segurança e Saúde no Trabalho com Inflamáveis e Combustíveis**) a partir de um banco de dados vetorial local (**ChromaDB**).

## 🚀 Funcionalidades
- **Extração Robusta de PDF**: Conversão automatizada de arquivos PDF complexos em blocos de texto otimizados utilizando a biblioteca `pypdf`.
- **Banco Vetorial de Alta Performance**: Armazenamento e indexação de embeddings locais usando o **ChromaDB**, garantindo velocidade e privacidade.
- **Busca Semântica Avançada**: Sistema de query capaz de retornar os trechos contextuais mais relevantes de acordo com a pergunta do usuário, e não apenas correspondências exatas por palavra-chave.
- **Segurança Pronta para Produção**: Configuração de proteção com `.gitignore` integrada para evitar o vazamento acidental do banco vetorial local (`chroma_db/`) ou de documentos sensíveis para repositórios públicos.

## 🛠️ Tecnologias Utilizadas
- **Python 3**
- **ChromaDB** (Banco de dados vetorial local)
- **pypdf** (Extração e processamento de texto de PDFs)
- **Google Colab** (Ambiente de desenvolvimento e testes interativos)

## 📂 Estrutura do Repositório
