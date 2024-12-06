This repository contains three Jupyter notebooks implementing diverse AI functionalities:

1. Copy of Assignment 3: A notebook for solving a minimum distance problem.
2. SimpleQ&AChatbot: A LoRA-based chatbot for question answering.
3. StableDiffusionImageToImage: A notebook leveraging Stable Diffusion to modify images based on prompt instructions.

Table of Contents  

- [Installation] 
- [File Descriptions]
- [Usage]
- [License]


 Installation  

1. Clone the repository:  
   ```bash  
   git clone <repository_url>  
   cd <repository_folder>  
   ```  

2. Install the required Python libraries:  
   ```bash  
   pip install -r requirements.txt  
   ```  

3. For Stable Diffusion:
   - Ensure you have the required model weights (e.g., `.ckpt` or `.safetensors`) placed in the appropriate directory.
   - A compatible GPU and the `diffusers` library are strongly recommended for running Stable Diffusion.


 File Descriptions  

1. Copy of Assignment 3 (Minimum Distance Calculation)  
Purpose:  
This notebook provides a solution to a minimum distance problem, potentially related to optimization or computational geometry.  

Features:  
- Input dataset handling  
- Calculation of minimum distances between points  
- Visualization of results (if applicable)  

Prerequisites:  
- Basic Python and Jupyter Notebook environment  


 2. SimpleQ&AChatbot  
Purpose:  
This notebook implements a LoRA-based (Low-Rank Adaptation) chatbot designed for question-answering tasks.  

Features:  
- Fine-tuning of a pre-trained language model with LoRA  
- Ability to answer questions based on given input  
- Simple and customizable architecture  

Prerequisites:  
- A base language model (e.g., GPT, LLaMA, or similar)  
- Datasets for fine-tuning  


3. StableDiffusionImageToImage  
Purpose  
This notebook uses the Stable Diffusion model to modify an uploaded image based on a provided prompt.  

Features:  
- Accepts image uploads and textual prompts  
- Processes images using the Stable Diffusion Image-to-Image pipeline  
- Outputs modified images that align with the prompt instructions  

Prerequisites:  
- Stable Diffusion weights/models (downloadable from Hugging Face or other sources)  
- High-performance GPU  


 Usage  

General Instructions  
1. Open the desired notebook in a Jupyter environment:  
   ```bash  
   jupyter notebook <notebook_name>.ipynb  
   ```  

2. Follow the step-by-step instructions in each notebook to input data, run the code, and view results.  

 Example Commands  

For Copy of Assignment 3:  
- Load your dataset into the notebook.  
- Execute the cells to calculate the minimum distances.  

For SimpleQ&AChatbot:  
- Ensure you have the pre-trained language model.  
- Run the fine-tuning process (if needed).  
- Interact with the chatbot by inputting questions in the provided interface.  

For StableDiffusionImageToImage:  
- Upload an image in the designated cell.  
- Provide a textual prompt describing the desired changes.  
- Execute the notebook to generate the modified image.  

 License  

This repository is open-sourced under the MIT License. See the [LICENSE](LICENSE) file for details.  

