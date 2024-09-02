# Ingredient Recognition with Vision-Language Models
This repository contains the code for the master thesis "Identifikation von Lebensmitteln in Fotos von Mahlzeiten mit Transformern" (engl. "Identification of Ingredients in Pictures of Food with Transformers") by Anja Hirsch at the HTW Berlin.

## Fine-Tuning of Vision-Language Models
One of the main goals of this thesis is to evaluate the effectiveness of fine-tuning Vision-Language models for the task of ingredient recognition. Vision-Language models have already proven their effectiveness in numerous application areas and could therefore also be suitable for the field of food identification. These models already have extensive prior knowledge, which is why potentially fewer adjustments are required than with pure Vision Transformer models. For the Fine-tuning experiments Google's Vision-Language model [PaliGemma](https://ai.google.dev/gemma/docs/paligemma) is used.

The implementation can be found in the notebook `fine_tuning_paligemma.ipynb`.

## Prompting of Vision-Language Models
Another approach is the prompting of a Vision-Language model. This approach takes advantage of the versatility of these models, which can be applied to new tasks even without specific training due to their broad knowledge base. In this context, both zero-shot prompting techniques and few-shot prompting are evaluated as potential methods for ingredient recognition. For this purpose, the Vision-Language model GPT-4o mini is used.

Results and implementation are presented in the notebook `prompting_gpt4o.ipynb`.