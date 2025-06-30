# Análise de Sentimento e Opiniões com Azure AI Language Studio

Este documento apresenta a análise de sentimento e mineração de opiniões realizada no Azure AI Language Studio para o texto em português: "O produto que recebi veio com defeito. A descrição é diferente do produto que recebi, a qualidade do produto deixa a desejar e gostaria de saber como proceder para troca."

---

## 📊 Análise de Sentimento Geral

* **Sentimento do Documento:** Misto ⚖️
* **Confiança:**
    * **Positivo:** ✅ 30.00%
    * **Neutro:** 😐 4.00%
    * **Negativo:** 🔴 65.00%

---

## 📝 Análise de Sentimento e Mineração de Opiniões por Sentença

A segunda sentença do texto foi detalhada na análise.

* **Texto Original:** "O produto que recebi veio com defeito. A descrição é diferente do produto que recebi, a qualidade do produto deixa a desejar e gostaria de saber como proceder para troca."

### Sentença 2:
* **Sentimento da Sentença:** Negativo 👎 (100% de confiança ⭐)

#### Mineração de Opiniões (Targets e Avaliações):
* **Target:** produto 🎯
    * **Avaliações:**
        * "defeito" 📝 (Negativo 🔴, 100.00% de confiança ⭐)
        * "deixar a desejar" 📝 (Negativo 🔴)
* **Target:** descrição 🎯
    * **Avaliações:**
        * "diferente" 📝 (Negativo 🔴)

---

## 🛠️ Detalhes do Recurso Utilizado

A análise foi realizada usando os seguintes detalhes do recurso Azure AI Language Studio:

* **Serviço de Linguagem:** LaboratorioPcomALang
* **Região:** 📍 eastus
* **Endpoint do Idioma:** 🔗 `https://laboratoriopcomalang.cognitiveservices.azure.com/`
