# 5c-prompt-contracts
A minimalist, creative-friendly, token-efficient prompt design framework for LLMs (5C: Character, Cause, Constraint, Contingency, Calibration).
## Quick Start

```bash
git clone https://github.com/username/5c-prompt-contracts.git
cd 5c-prompt-contracts
pdflatex main.tex
bibtex main
metadata.yaml
```
# 5C Prompt Contracts: A Minimalist, Creative-Friendly, Token-Efficient Design Framework for Individual and SME LLM Usage

This repository contains the LaTeX source code for the research paper "5C Prompt Contracts: A Minimalist, Creative-Friendly, Token-Efficient Design Framework for Individual and SME LLM Usage".

## Purpose

This paper introduces the 5C Prompt Contract framework, a novel approach to prompt design for Large Language Models (LLMs) that emphasizes minimalism, creative flexibility, and token efficiency. It compares the 5C framework against traditional Domain-Specific Language (DSL) and Unstructured prompting methods across various LLM systems (OpenAI, Anthropic, DeepSeek, and Gemini) to demonstrate its practical advantages, especially for individual users and Small-to-Medium Enterprises (SMEs).

## Compilation Instructions

To compile this LaTeX paper, you will need a standard LaTeX distribution (e.g., TeX Live or MiKTeX) installed on your system.

1.  **Save Files:** Ensure that `main.tex` (or whatever you name the main LaTeX file), and `references.bib` (containing your BibTeX entries) are in the same directory.
2.  **Compile with `pdflatex` and `bibtex`:**
    Open your terminal or command prompt in the directory containing the files and run the following commands in sequence:
    ```bash
    pdflatex main.tex
    bibtex main
    metadata.yaml
    ```
    (Replace `main.tex` with your actual LaTeX file name if different.)

    This sequence ensures that the bibliography is correctly generated and integrated into the document, resolving all citations and references.

## Intended Submission

This paper is intended for submission to arXiv.org and can also serve as a technical showcase on platforms like Hugging Face.

[![DOI](https://zenodo.org/badge/1015604718.svg)](https://doi.org/10.5281/zenodo.15832040)

## Metadata
This repository includes a [metadata.yaml](metadata.yaml) file to facilitate integration with preprint servers, dataset/model cards, and future academic indexing platforms.

#Examples

## Example 1: 5C Prompt Contract Snippet

```plaintext
Character: A seasoned detective in a neon-soaked cyberpunk city.
Cause: Tasked with uncovering a secret society manipulating local politics.
Constraint: Must remain unbiased, avoid assuming guilt without evidence.
Contingency: If insufficient data, speculate possible scenarios but clarify uncertainty.
Calibration: Provide the output as a cinematic narrative, 2-3 paragraphs long, vivid details.
```
Example 2: 5C Prompt Contract Snippet

```plaintext
Character: A persuasive digital marketing copywriter with a witty tone.
Cause: Needs to craft a short LinkedIn post promoting a new AI productivity tool.
Constraint: Keep under 100 words, avoid buzzwords like "disrupt" or "synergy."
Contingency: If too short, provide a slightly longer version but mark it as "ALT VERSION."
Calibration: Output should be crisp, engaging, and finish with a call-to-action question.
```
Example 3: 5C Prompt Contract Snippet
```plaintext
Character: A calm, patient university professor specializing in cognitive science.
Cause: Explains the concept of "attention saturation" in large language models to a general audience.
Constraint: Avoid equations or dense jargon, use simple metaphors.
Contingency: If explanation becomes too abstract, provide a relatable real-life analogy.
Calibration: Structure output in three short paragraphs, ending with a reflective question to the reader.
```
