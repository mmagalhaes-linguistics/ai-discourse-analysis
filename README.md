[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21218501.svg)](https://doi.org/10.5281/zenodo.21218501)

# 🎓 Computational Discourse Analysis Laboratory
## Lisbon Summer School in Linguistics (2026)

**PhD Programme**  
**Dates:** June 29 – July 3, 2026  
**Area 3:** Grammar and Text  
**Course 2:** Critical AI Literacy for Text Production and Text Analysis  
**Instructors:** Matilde Gonçalves, Marta Fidalgo, and Miguel Magalhães (CLUNL/NOVA FCSH, Portugal)

---

### 📍 Venue
**Faculdade de Ciências Sociais e Humanas – Universidade NOVA de Lisboa**  
Avenida de Berna, 26-C  
1069-061 Lisboa – Portugal  

---

## 💻 About this Laboratory

This repository hosts the official hands-on computational suite developed for Course 2 of the *Lisbon Summer School in Linguistics*. It contains three interactive Python experiments designed to expose the architectural mechanics, strengths, and theoretical biases of modern Large Language Models (LLMs) when applied to human language, ideology, and textual traditions.

---

## 🚀 Interactive Laboratory Suite (Google Colab)

To eliminate technical friction, each experiment is fully self-contained and hosted via Google Colab. Students can launch any script with a single click—no local Python installation or hardware dependencies required.

### 🧪 Experiment 1: The Visual Mechanics of Self-Attention
*   **Theoretical Core:** Polysemy resolution and contextual tokenization.
*   **Description:** Visualizes a dynamic "X-ray" of the Portuguese BERTimbau model processing a metaphorical recipe text (*"Receita para a felicidade"*). Demonstrates how the model dynamically re-weights and differentiates the duplicate word *"forma"* based on its specific syntactic neighborhood.
*   **Launch:** [🚀 Click here to Open this Lab directly in Google Colab](https://google.com)


### 🔬 Experiment 2: The Discourse Analysis X-Ray (Euphemisms & Omissions)
*   **Theoretical Core:** The Trap of Absence and surface-level semantic biases.
*   **Description:** Utilizes a modern RoBERTa sentiment model and `transformers-interpret` to paint text tokens in green/red. Contrasts explicit conflict against highly polished corporate euphemisms, demonstrating how LLMs flatten structural violence (e.g., mass layoffs masked as *"asset optimization"*) into false positive metrics.
*   **Launch:** [🚀 Click here to Open this Lab directly in Google Colab](https://google.com)


### 📊 Experiment 3: The "Lost in the Middle" Phenomenon
*   **Theoretical Core:** Long-range textual organization and positional attenuation.
*   **Description:** Implements a classic "Needle in a Haystack" test using GPT-2. Students will witness how the model effectively retrieves data from the extreme beginning or end of a document but statistically drops critical facts (like a database password) buried in the center, generating a classic U-shaped attention drop.
*   **Launch:** [🚀 Click here to Open this Lab directly in Google Colab](https://google.com)


---

## 🧠 Theoretical Framework: The Flattening of Texts

A central theme of this laboratory is the **Discursive Flattening Effect**. While human discourse analysts focus on *singularities*—ideological tensions, historical ruptures, institutional constraints, and genre conventions—LLMs are optimized to identify *recurring regularities* across vast corpora.

### The Consequences of the Flattening Effect:
1.  **Bias Toward Consensus:** Contradictory socio-political positions become homogenized and synthesized.
2.  **Statistical Dilution:** Marginal, revolutionary, or deeply emotional human voices (e.g., personal diaries, activist manifestos) are ironed out into balanced, third-person corporate or journalistic summaries.
3.  **Vulnerability to Omission:** Interpretive conflicts and systemic struggles are polished away, creating summaries that appear comprehensive but lack the crucial friction of real-world discourse.

---

## 📝 Student Assignment & Seminar Questions

After completing all three interactive experiments during the seminar, PhD students are expected to submit a short analytical report answering the following questions:

1.  **Regarding Experiment 1:** How did the higher layers (9–11) of the model differ from the lower layers (0–3) when evaluating the word *"forma"*? What does this imply about the model's capacity to decode poetic metaphors vs. mechanical grammar?
2.  **Regarding Experiment 2:** Explain why the model attributed a highly positive score to the corporate restructuring text. How does this demonstrate the "Trap of Absence" in computational text analysis?
3.  **Regarding Experiment 3:** Relate the "Lost in the Middle" phenomenon to modern political public relations (PR) strategies. How can the "sandwich method" be used to systematically camouflage controversial data from automated AI oversight?

