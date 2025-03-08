# text-to-image-generation-comparison
This repository belongs to comparing the results of generated image using Stable difussion (vesrion 3.5 large) and deepseek (version R1).
# Text to Image Generation Using Stable Diffusion and Deepseek
<p align="justify"> Text-to-image model is a machine learning model which takes an input natural language description and produces an image matching that description.
In this the models are evaluated an RTX3090ti on the available datasets on the Hugging face. </p>

# Requirements 
1. lingua-language-detector
2. torch == 2.4.1
3. torchvision
8. flash-attn
9. xformers
10. trl
11. peft
12. accelerate
13. bitsandbytes
# Results (Left:Stable Diffusion, Right: Deepseek)
1. Make a bold Facebook advertisement for a flash sale using bright red and white colors. Keep the design minimal but impactful with large bold text in a modern Times New Roman font.
<p align="center">
  <img src="https://github.com/user-attachments/assets/22a68abf-296c-4e26-917e-b198be7eede3" width="350" title="Stable Diffusion">
  <img src="https://github.com/user-attachments/assets/696ac8b0-a318-4ecb-879e-b8c0afffa7b1" width="350" title="Deep Seek">
</p>

2. Generate an image with an aerial view of a coastal town capturing the contrast between the vibrant blue ocean and soft pastel colors of the rooftop. The overall scene should feel peaceful and bright.
<p align="center">
  <img src="https://github.com/user-attachments/assets/926beee4-e891-40b7-abc3-9a354ba6d408" width="350" title="Stable Diffusion">
  <img src="https://github.com/user-attachments/assets/6328b061-bbfc-4c05-b80b-a09185bbc09e" width="350" title="Deep Seek">
</p>
