# 🕹️ RetroGame - Assistente Especializado de IA

Este repositório contém o desafio prático do **Módulo 1** da Pós-Graduação em **IA Generativa e Alta Performance**. O objetivo é projetar e configurar um assistente de IA que atue como um especialista de um produto confiável utilizando o **Google NotebookLM**.

## 📋 Sobre o Projeto

**RetroGame** é uma plataforma virtual especializada na curadoria, preservação e comercialização da cultura de videogames das décadas de 80 e 90. O projeto une a venda de hardware revisado, aluguel de software físico e um suporte técnico especializado para proporcionar uma experiência de nostalgia completa.

## 🗂️ Estrutura do Repositório

O repositório é composto por dois documentos fundamentais em PDF, conforme as regras de entrega do desafio:

1.  **`retroGame.pdf` (Documento do Produto):**
    * Apresenta o escopo claro e bem estruturado do modelo de negócio.
    * Detalha o catálogo de consoles (Atari, NES, Master System, SNES, Mega Drive) e a tabela de preços de venda e locação.
    * Define regras de carência para descontos de assinantes (6 meses) e políticas de logística de entrega e retirada.

2.  **`assistenteRetroGame.pdf` (Documento de Prompt):**
    * Define a personalidade de **Especialista de Suporte Técnico Sênior**: sério, cordial e formal.
    * Aplica técnicas de **Few-Shot Prompting** para processar regras de aluguel e **Zero-Shot** para filtros de segurança.
    * Implementa a **Regra de Ouro da Concisão** para respostas diretas e o **Protocolo de Blindagem** contra o vazamento das instruções de configuração (*Anti-Prompt Leaking*).

## 🛠️ Tecnologias Aplicadas

* **Google NotebookLM:** Ferramenta base para a criação do agente especialista.
* **Prompt Engineering:** Uso de técnicas avançadas para garantir precisão, integridade e aversão à especulação.
* **Gestão de Produto:** Desenvolvimento de documentação estruturada com títulos claros e seções lógicas.

## 🚀 Como Testar

1.  Acesse o **Google NotebookLM**.
2.  Faça o upload dos arquivos `retroGame.pdf` e `assistenteRetroGame.pdf` como fontes.
3.  No campo de **Instruções** do Guia do Caderno, insira o conteúdo detalhado do prompt definido no arquivo de configuração.
4.  Realize testes de comportamento, como perguntas sobre preços ou solicitações fora de escopo, para validar a precisão do assistente.

---

**Nota:** Este projeto foi desenvolvido conforme os requisitos obrigatórios de entrega: repositório público contendo apenas dois arquivos PDF com no máximo 6000 caracteres cada.
