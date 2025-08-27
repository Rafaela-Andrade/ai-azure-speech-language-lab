# Azure AI – Speech & Language Labs (DIO)

## 🎯 Objetivo
Esse repositório foi criado para documentar a prática com as ferramentas **Azure AI Speech** e **Azure AI Language**, seguindo o desafio proposto no curso da DIO.  
A ideia foi experimentar na prática como funcionam a transcrição de fala e a análise de linguagem natural, registrando os resultados e insights que podem ser aplicados em projetos reais.

## 🧩 O que foi feito
- Testei o **Speech Playground** para transcrever um áudio de exemplo (`WhatAICanDo.m4a`).
- Usei o **Language Playground** para:
  - Extrair **Named Entities** (entidades nomeadas).
  - Identificar **Key Phrases** (frases-chave).
  - Gerar **Summarization** (resumos de texto).
- Fiz capturas de tela de cada etapa e registrei observações.

## 🛠️ Ferramentas e Material de Apoio
- [Azure AI Foundry](https://ai.azure.com)
- Playgrounds de Speech e Language
- Documentação e labs oficiais:
  - [Lab Speech](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)
  - [Lab Language](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)

## 🚀 Passo a passo resumido
1. Criei um **Project** no Azure AI Foundry em uma região suportada.
2. No **Speech Playground**, rodei a transcrição em tempo real do áudio de exemplo.
3. No **Language Playground**, testei:
   - Named Entities com um review negativo de hotel.
   - Key Phrases com um review positivo de hotel.
   - Summarization com um review de hotel mais longo e crítico.
4. Capturei telas de cada resultado e organizei na pasta `/images`.

## 🖼️ Evidências
- Transcrição (Speech): ![speech-transcription](images/speech-transcription.png)
- Named Entities: ![language-entities](images/language-entities.png)
- Key Phrases: ![language-keyphrases](images/language-keyphrases.png)
- Summarization: ![language-summary](images/language-summary.png)

## 📌 Resultados e Insights
- **Speech**: a transcrição foi rápida e próxima do áudio original. Notei que a pontuação e algumas palavras podem variar conforme a qualidade do áudio.
- **Named Entities**: identificou corretamente nomes e categorias, mas alguns detalhes poderiam ser refinados (ex.: confundiu algumas palavras comuns com entidades).
- **Key Phrases**: destacou bem os pontos principais do texto, facilitando enxergar a mensagem sem ler o review inteiro.
- **Summarization**: conseguiu condensar o conteúdo e manter o sentido geral. Achei útil para cenários em que é preciso lidar com grandes volumes de texto.
- **Limitações**: percebi que idioma, sotaque e qualidade do áudio/texto influenciam muito nos resultados.
- **Aplicações práticas**: atendimento ao cliente, análise de reviews, suporte inteligente e monitoramento de redes sociais.

## ♻️ Observação
Depois dos testes, é importante excluir o resource group no portal do Azure para não gerar custos desnecessários.

---

👩🏻‍💻 Feito por **Rafaela Andrade Santos** – Desafio DIO | AI Azure
