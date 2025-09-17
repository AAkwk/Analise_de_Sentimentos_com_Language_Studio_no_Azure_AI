# Desafio do Bootcamp Suzano Python Developer
## Resumo "Análise de Sentimentos com Language Studio no Azure AI".
### 📋 Visão Geral do Desafio
Este repositório documenta minha jornada completa de aprendizado e prática com os serviços de IA da Azure, focando especificamente no **Azure Speech Studio e Language Studio**. Através de exploração hands-on, pude compreender profundamente as capacidades de processamento de linguagem natural, análise de sentimentos, reconhecimento de fala e criação de sistemas de perguntas e respostas.
### 🎯 Objetivos Alcançados
#### ✅ Análise de Texto com Language Studio
- Análise de Sentimento: Avaliação de polaridade (positivo/negativo) com pontuação de confiança

- Reconhecimento de Entidades: Identificação de elementos como localizações, pessoas, organizações

- Extração de Frases-Chave: Detecção dos termos mais relevantes no texto

- Detecção de Idioma: Reconhecimento automático do idioma do texto

#### ✅ Processamento de Fala com Speech Studio
- Conversão de Fala em Texto: Transcrição de áudio para formato textual

- Conversão de Texto em Fala: Geração de áudio a partir de texto

- Seleção de Idiomas e Vozes: Suporte a múltiplos idiomas e variantes de voz

#### ✅ Configuração de Recursos na Azure
- Criação do recurso Language Service com personalizações
- Configuração do resource group **LABAI-900**
- Utilização do tier **Free F0** para experimentação

### 🔍 Análises Realizadas
#### 1️⃣ Análise de Sentimento
**Texto**: "Passei férias maravilhosas na França."
- **Resultados**:

- **Idioma**: Português

- **Sentimento**: Positivo (0.88)

- **Frases-chave**: "férias maravilhosas"

- **Entidades**: França (Localização)

#### 2️⃣ Análise de Review de Hotel
**Texto**: "Tired hotel with poor service"
**Resultados**:

- **Sentimento**: Negativo (98% de confiança)

- **Opiniões Mineradas**:

  | **Alvo** | **Avaliação** | **Sentimento** | **Confiança** |
  |----------|---------------|----------------|---------------|
  | `hotel`  | `tired`       | Negativo       | 99%           |
  | `service`| `poor`        | Negativo       | 99%           |


#### 3️⃣ Conversão de Fala em Texto

**Arquivo**: WhatAICanDo.m4a (18 segundos)

**Transcrição**:
"AI enables us to build amazing software that can improve healthcare, enable people to overcome physical disadvantages, empower smart infrastructure"

### 🔍 Evidências de Aprendizado
#### 📸 Capturas de Tela Incluídas:
1 - **Configuração do Language Service** - Criação do recurso "Idiomalanguage"

2 - **Análise de Sentimento** - Resultados detalhados da mineração de opiniões

3 - **Interface do Speech Studio** - Upload e processamento de arquivo de áudio

4 - **Recursos do Bot Service** - Opções de configuração e integração

5 - **Seleção de Idiomas** - Suporte multilíngue para processamento

### 📁 Estrutura do Repositório

    /
    ├── 📄 README.md (este arquivo)
    ├── 📁 images/
         ├── 🖼️ configuracao-language-service.png
         ├── 🖼️ analise-sentimento-resultados.png
         ├── 🖼️ speech-studio-interface.png
         ├── 🖼️ bot-service-configuracao.png
         └── 🖼️ selecao-idiomas.png
   




### 🙌 Conclusão
Através deste desafio, adquiri experiência prática valiosa com as ferramentas de IA da Azure, consolidando conhecimentos em processamento de linguagem natural e reconhecimento de fala. As habilidades desenvolvidas são diretamente aplicáveis em cenários reais de negócio, desde atendimento ao cliente automatizado até análise de sentimentos em redes sociais.



