# Follow these steps to set up Stable Diffusion with ComfyUI for AI-powered image generation.

# 1️⃣ Download & Install Dependencies

Download ComfyUI from the official source. link:-(https://github.com/comfyanonymous/ComfyUI) 
Scroll to downloads and click on direct link to download
Install Stable Diffusion models from Hugging Face.

# 2️⃣ Model Setup

Download the following models: link:- (https://huggingface.co/CompVis/stable-diffusion-v-1-4-original)
SD v1.4.ckpt
SD v1.4 full EMA.ckpt
Place them in the checkpoints folder:
nginx
Copy
Edit
ComfyUI_Windows_Portable > ComfyUI > models > checkpoints  

# 3️⃣ Install FP16 Safetensors

Ensure FP16 Safetensors are installed for optimized precision. link:- (https://huggingface.co/Comfy-Org/stable-diffusion-v1-5-archive/blob/main/v1-5-pruned-emaonly-fp16.safetensors )

# 4️⃣ Enable GPU Acceleration

Run the GPU execution file to enhance performance and speed up image generation.
Once set up, you can start generating high-quality images with Stable Diffusion & ComfyUI!
