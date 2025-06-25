---

# 📁 Projeto: Reconhecimento de Texto com Azure AI Vision

> Este projeto foi desenvolvido como parte do laboratório **"Read text in Vision Studio"** para conslusão do curso da empresa DIO, disponível no módulo [MS Learn - Fundamentos de IA](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html). O objetivo é utilizar o serviço Azure AI Vision para extrair texto de imagens por meio da funcionalidade OCR (Optical Character Recognition) usando o **Vision Studio**.

---

## 🎯 Objetivo

Demonstrar a capacidade do Azure AI Vision em identificar e extrair texto de diferentes tipos de imagens, utilizando Optical Character Recognition (OCR), sem escrever código.

---

## 🛠️ Tecnologias Utilizadas

- **Azure AI Services**
- **Azure AI Vision Studio**
- OCR (Reconhecimento Óptico de Caracteres)

---

## 📦 Estrutura do Projeto

- Pasta Inputs: Imagem "borrão" com várias anotações.
- Pasta Outputs: print da extração de texto da imagem.

--- 

## 🔍 Processo Realizado

1. **Criação do recurso Azure AI Services**:
   - Foi criado um recurso do tipo *Azure AI Services* no portal do Azure.
   - Configurações utilizadas: região, grupo de recursos, nome único e camada Standard S0.

2. **Conexão com Vision Studio**:
   - Acessamos o [Vision Studio](https://portal.vision.cognitive.azure.com).
   - Conectamos o recurso criado ao Vision Studio como recurso padrão.

3. **Extração de texto com OCR**:
   - A imagem "borrão" foi carregada no Vision Studio:
   - Para a imagem, o serviço retornou:
     - Texto extraído organizado por linhas e palavras.
     - Localização das palavras através de caixas delimitadoras (*bounding boxes*).

4. **Armazenamento dos resultados**:
   - O resultado foi printado e colocado na pasta `outputs`.

---

## 💡 Insights e Aprendizados

- ✅ O Azure AI Vision consegue extrair texto tanto de documentos digitais quanto de imagens com caligrafia, embora com variação de precisão.
- 🧠 É possível integrar esses dados extraídos em sistemas automatizados, como leitura de recibos, análise de formulários e até tradução automática.
- 📊 A estrutura hierárquica de saída (regiões → linhas → palavras) facilita a manipulação dos dados em aplicações reais.
- 🚀 Mesmo sem programação, é possível testar e validar cenários complexos com apenas alguns cliques.


---

## 🙌 Créditos

Este projeto foi baseado no conteúdo do treinamento gratuito da Microsoft Learn:
🔗 [MS Learn - Read text in images with Azure AI Vision](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)

---
