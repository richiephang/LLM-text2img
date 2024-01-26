# LLM-text2img
A project that explores how to use LLMs and text-to-image models for prompt-based content generation.

## Online models from HuggingFace used:
* Large Language Model (LLM): [Falcon-7B-Instruct](https://huggingface.co/tiiuae/falcon-7b-instruct)
* Text to Image Generation Model: [Stable Diffusion v2-1](https://huggingface.co/stabilityai/stable-diffusion-2-1)
<br><br><br>
## Story and Story Image Generator
1. Enter a simple story title and generate a story using Falcon-7B-Instruct.
2. Use the generated story as input and generate a prompt for the story image using Falcon-7B-Instruct.
3. Use the generated prompt as input and generate the story image using Stable Diffusion v2-1.

![image](https://github.com/richiephang/LLM-text2img/assets/76896343/3f3fce09-9373-4166-8e49-404c603eb71d)
<br><br><br>
## Recipe Generator
1. Provide a list of ingredients and generate a recipe using Falcon-7B-Instruct.
2. Use the generated recipe as input and generate a prompt for the dish image using Falcon-7B-Instruct.
3. Use the generatedd prompt as input and generate the dish image using Stable Diffusion v2-1.

![image](https://github.com/richiephang/LLM-text2img/assets/76896343/b21e1931-5858-4228-af49-eda4a7082a9d)
<br><br><br>
## Findings in writing a working prompt:
1. Providing sufficient examples in the prompt is important.
2. Specify word limits can reduce chances of incomplete result from LLM
3. Break down the prompt in steps if necesary.
