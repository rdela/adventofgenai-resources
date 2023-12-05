# 🚀 Resources: Your Gateway to GenAI Mastery! 🌟

Hello, AI Adventurers! Ready to navigate the exciting world of Generative AI with Intel's advanced tech? Here's everything you need to ace the hackathon:

1. **Intel Developer Cloud: Your AI Powerhouse**
   - 🌐 Step into the [Intel Developer Cloud](https://cloud.intel.com) (IDC), register for free, and access a realm where Intel Xeons CPUs and GPUs amplify your code's potential. Discover GenAI notebooks in 'GenAI Essentials' on your home page @IDC  – A set of curated notebooks for Stable Diffusion, LLM inference and Finetuning on Intel!

   ![Intel Developer Cloud](https://github.com/adventofgenai/resources/assets/786476/ddcfd550-1be4-4227-abbc-8cc6b630e102)

2. **GenAI GitHub Repository: Your AI Compass**
   - 🧭 Explore [rahulunair/genAI](https://github.com/rahulunair/genAI) for key insights on GenAI applications - Stable diffusion, LLM inference, finetuning and code generation with Intel GPUs. If you find the notebooks useful, consider leaving a star or spark a discussion with an issue!

3. **Magic of Prompt Engineering**:
   - Explore generative art techniques with [Stable Diffusion Prompt Book](https://openart.ai/promptbook), a resource for diverse prompt ideas and creative exploration in AI art.

4. **Intel Extension for PyTorch (XPUs):**
   - 🔥 Check if XPU is ready:
     ```python
     import torch
     import intel_extension_for_pytorch
     print(f"torch.xpu.is_available()")
     ```
   - 📚 Dive deeper at [Intel XPU Tutorials](https://intel.github.io/intel-extension-for-pytorch/xpu/latest/tutorials/examples.html)

5. **BigDL & LLMs: Unleash AI Magic**
   - 🧙‍♂️ Experience LLM inference in 4-bit with [BigDL LLM Inference](https://github.com/intel-analytics/BigDL/blob/main/python/llm/example/GPU/HF-Transformers-AutoModels/Model/llama2/generate.py#L58)

6. **Detect Your AI Resources: The Discovery Commands**
   - 🔍 Uncover Intel GPUs and CPUs:
     ```bash
     echo "Intel GPUs:"
     xpu-smi  discovery 2> /dev/null
     echo "Intel Xeon CPU:"
     lscpu | grep "Model name"
     xpu-smi dump -m 18
     ```

7. **Craft Your Custom Conda Environment**
   - 🧪 Mix your perfect environment:
     ```bash
     conda clone pytorch-gpu <new_name>
     conda activate new_name
     conda install ipykernel
     ipykernel install <>
     conda install ...
     ```

8. **Python Package Installation: Effortlessly**
   - 📦 Streamline your installations:
     ```python
     import sys
     import site
     from pathlib import Path
     !echo "Installing..."
     !{sys.executable} -m pip cache purge > /dev/null
     !{sys.executable} -m pip install --pre <python_package_name>
     !echo "Installation Complete."
     ```

9. **Prediction Guard: Safeguard Your LLM Predictions**
   - 🛡️ Explore [Prediction Guard Documentation](https://docs.predictionguard.com)

10. **Mastery in Retrieval Augmented Generation**
   - 🎓 Learn from [LangChain](https://python.langchain.com/docs/use_cases/question_answering/) and [Llama-index](https://docs.llamaindex.ai/en/stable/getting_started/concepts.html)

11. **Building LLM Applications: The Ultimate Guide**
    - 📘 Deep dive into [Llama-index Docs](https://docs.llamaindex.ai/en/stable/understanding/understanding.html)

12. **Vector Databases: Exploring with LanceDB**
    - 🗂️ Engage with [LanceDB VectorDB Recipes](https://github.com/lancedb/vectordb-recipes/blob/main/examples/multimodal_search/main.ipynb)

# Contributing to GenAI 🤝

**Share Your Genius:**
- Got an innovative idea or an improvement? We're all ears! 🌟
- Fork the repository, push your changes, and open a pull request.
- Remember, every bit of contribution helps us sail further in the ocean of AI!

# Reporting Issues 🐛

**Spot Something Amiss?**
- Stumbled upon a bug or facing a challenge? Let us help! 🛠️
- Create an issue in the [GitHub repository](https://github.com/adventofgenai/genAI/issues) with a detailed description.
- Your keen eye helps us refine the experience for everyone!

