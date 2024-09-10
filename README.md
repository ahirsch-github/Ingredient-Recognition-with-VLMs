# Ingredient Recognition with Vision-Language Models
This repository contains the code for the master thesis "Identifikation von Lebensmitteln in Fotos von Mahlzeiten mit Transformern" (engl. "Identification of Ingredients in Pictures of Food with Transformers") by Anja Hirsch at HTW Berlin.

## Fine-Tuning Vision-Language Model

A primary objective of this thesis is to assess the efficacy of fine-tuning Vision-Language models for ingredient recognition. Given their proven success in various applications, these models seem promising for food identification. Their extensive pre-existing knowledge potentially requires fewer adjustments compared to pure Vision Transformer models. The fine-tuning experiments utilize Google's Vision-Language model [PaliGemma](https://ai.google.dev/gemma/docs/paligemma), with implementation details available in the notebook `fine_tuning_paligemma.ipynb`.

## Prompting Vision-Language Model
An alternative approach explores prompting Vision-Language models, leveraging their versatility to tackle new tasks without specific training. This research evaluates both zero-shot and few-shot prompting techniques for ingredient recognition. The Vision-Language model [GPT-4o mini](https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/) is employed for this purpose. Results and implementation are presented in the notebook `prompting_gpt4o.ipynb`.
