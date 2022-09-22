# Comparison all major Stable Diffusion Projects
1. Since things are rapidly developing, please help to send PR to update when new features are added for each forks
1. Latest updates as of 22 Sept 2022

# Comparison of Major UI projects

| Name     | sd-webui           | AUTOMATIC1111 | invoke-AI     | cmdr2          |   |   |   |   |   |
|----------|--------------------|---------------|---------------|----------------|---|---|---|---|---|
| Alternate Name |   hlky        |       -        |   lstein       |  -     |   |   |   |   |   |
| Link     | [Github](https://github.com/sd-webui/stable-diffusion-webui) | [Github](https://github.com/AUTOMATIC1111/stable-diffusion-webui)  | [Github](https://github.com/invoke-ai/InvokeAI)        | [Github](https://github.com/cmdr2/stable-diffusion-ui)         |   |   |   |   |   |
| License         |    AGPL                |     Unknown          |      MIT         |     Unknown           |   |   |   |   |   |
| Frontend | Gradio & Streamlit | Gradio        | Custom-Server | Custom-Server  |   |   |   |   |   |
| Backend  | Python (G & S)     | Python Gradio | Python        | Python/FastAPI |   |   |   |   |   |
| Star     | 4.3k               | 3.9k          | 2.4k          | 1.4k           |   |   |   |   |   |
| OS       | W+L                | W+L           | W+L+M         | W+L            |   |   |   |   |   |
| Docker   | ✔️                | ✔️            |  ✔️(AbdBarho)           |  :x:             |   |   |   |   |   |
| T2I      | ✔️                | ✔️            | ✔️            | ✔️            |   |   |   |   |   |
| I2I      | ✔️                | ✔️            | ✔️            | ✔️            |   |   |   |   |   |
| T2V      | ✔️(dev)                | ?             | ?             | ?              |   |   |   |   |   |
| Inpainting  |     ✔️              |     ✔️          |     ✔️          |   ?             |   |   |   |   |   |
| Outpainting |      ✔️              |       ✔️        |      ?         |    ?            |   |   |   |   |   |
|          |                    |               |               |                |   |   |   |   |   |
|          |                    |               |               |                |   |   |   |   |   |


### Notes
1. OS: W = Windows, M = MacOS, L = Linux

# Other UI Projects/Notable forks
1. DreamStudio from Stability AI [Website](https://beta.dreamstudio.ai/), webapp from the Stability AI team 
1. CompVis [Github](https://github.com/CompVis/stable-diffusion), the original project with Latent Diffusion models
1. HuggingFace Diffusers [Github](https://github.com/huggingface/diffusers), backend library to run LD/SD and other models
1. Diffusionbee [Github](https://github.com/divamgupta/diffusionbee-stable-diffusion-ui), for Mac
1. AbdBarho Docker [Github](https://github.com/AbdBarho/stable-diffusion-webui-docker), docker setup for other webui (support sd-webui, AUTOMATIC1111 & invoke-AI)
1. NeonSecret [Github](https://github.com/neonsecret/stable-diffusion) & Basunjidal [Github](https://github.com/basujindal/stable-diffusion), optimized fork. (Do note that some of the changes has also been incorporated to other UI already)
1. FvsionAI [Github](https://github.com/FvsionAI/fvsion), using Vite+Vue as FrontEnd and FastAPI as backend



# Design Choices
1. Horizontal table to accomodate more feature lists
1. Sorting left to right by Github stars (updated as of 22 Sept) 