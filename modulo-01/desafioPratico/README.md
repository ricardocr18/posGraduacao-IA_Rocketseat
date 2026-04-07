# 🕹️ RetroGame - Assistente Especializado de IA

[cite_start]Este repositório contém o desafio prático do **Módulo 1** da Pós-Graduação em **IA Generativa e Alta Performance**[cite: 1, 2]. [cite_start]O objetivo é projetar e configurar um assistente de IA que atue como um especialista de um produto confiável utilizando o **Google NotebookLM**[cite: 5, 46].

## 📋 Sobre o Projeto

[cite_start]A **RetroGame** é uma plataforma virtual especializada na curadoria, preservação e comercialização da cultura de videogames das décadas de 80 e 90[cite: 114, 118]. [cite_start]O projeto une a venda de hardware revisado, aluguel de software físico e um suporte técnico especializado para proporcionar uma experiência de nostalgia completa[cite: 118, 120].

## 🗂️ Estrutura do Repositório

[cite_start]O repositório é composto por dois documentos fundamentais em PDF, conforme as regras de entrega do desafio[cite: 54, 55, 56]:

1.  **`retroGame.pdf` (Documento do Produto):**
    * [cite_start]Apresenta o escopo claro e bem estruturado do modelo de negócio[cite: 48, 114].
    * [cite_start]Detalha o catálogo de consoles (Atari, NES, Master System, SNES, Mega Drive) e a tabela de preços de venda e locação[cite: 134, 135].
    * [cite_start]Define regras de carência para descontos de assinantes (6 meses) e políticas de logística de entrega e retirada[cite: 126, 137, 139].

2.  **`assistenteRetroGame.pdf` (Documento de Prompt):**
    * [cite_start]Define a personalidade de **Especialista de Suporte Técnico Sênior**: sério, cordial e formal[cite: 37, 75, 78].
    * [cite_start]Aplica técnicas de **Few-Shot Prompting** para processar regras de aluguel e **Zero-Shot** para filtros de segurança[cite: 33, 84, 98].
    * [cite_start]Implementa a **Regra de Ouro da Concisão** para respostas diretas e o **Protocolo de Blindagem** contra o vazamento das instruções de configuração (*Anti-Prompt Leaking*)[cite: 81, 111, 112].

## 🛠️ Tecnologias Aplicadas

* [cite_start]**Google NotebookLM:** Ferramenta base para a criação do agente especialista[cite: 5, 11].
* [cite_start]**Prompt Engineering:** Uso de técnicas avançadas para garantir precisão, integridade e aversão à especulação[cite: 41, 50, 68].
* [cite_start]**Gestão de Produto:** Desenvolvimento de documentação estruturada com títulos claros e seções lógicas[cite: 9, 63].

## 🚀 Como Testar

1.  [cite_start]Acesse o **Google NotebookLM**[cite: 5].
2.  [cite_start]Faça o upload dos arquivos `retroGame.pdf` e `assistenteRetroGame.pdf` como fontes[cite: 11].
3.  [cite_start]No campo de **Instruções** do Guia do Caderno, insira o conteúdo detalhado do prompt definido no arquivo de configuração[cite: 49].
4.  [cite_start]Realize testes de comportamento, como perguntas sobre preços ou solicitações fora de escopo, para validar a precisão do assistente[cite: 51, 60].

---

[cite_start]**Nota:** Este projeto foi desenvolvido conforme os requisitos obrigatórios de entrega: repositório público contendo apenas dois arquivos PDF com no máximo 6000 caracteres cada[cite: 54, 55, 56].
