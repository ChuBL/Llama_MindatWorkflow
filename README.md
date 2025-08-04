# Llama_MindatWorkflow

Fine-tuning code and models for automating geoscience data analysis workflows using Llama 3.1.

## Resources

**Fine-tuned Model:** [llama_3.1_instruct_8b_openmindat](https://ollama.com/gene21d4/llama_3.1_instruct_8b_openmindat)

**Training Dataset:** [![Hugging Face Dataset](https://img.shields.io/badge/HuggingFace-Dataset-blue)](https://huggingface.co/datasets/gene21d4/test_mindat_workflow)

**Synthetic Dataset Generation:** [alpaca_for_kg](https://github.com/ChuBL/alpaca_for_kg)

## **LLaMA 3.1 Instruct 8B OpenMindat**

This model is hosted on [**Ollama**](https://ollama.com/gene21d4/llama_3.1_instruct_8b_openmindat) and is designed for AI-driven geoscience workflows, optimized for OpenMindat applications.

---

### **Model Overview**

| **Attribute**   | **Details**        |
|------------------|--------------------|
| **Size**        | 4.9 GB             |
| **Architecture**| `llama`            |
| **Parameters**  | 8.03B              |
| **Quantization**| Q4_K_M             |

---

### 🚀 **How to Use the Model**

Make sure you have Ollama installed. Then run:

```bash
ollama run gene21d4/llama_3.1_instruct_8b_openmindat
```


## Citation

If you use this code in your research, please cite our work:

```bibtex
@misc{zhang2024fine,
  title={Fine-Tuning Small and Open {LLMs} to Automate Geoscience Data Analysis Workflows: A Scalable Approach},
  author={Zhang, Jiyin and Li, Wenjia and Que, Xiang and Chen, Weilin and Li, Chenhao and Ma, Xiaogang},
  howpublished={Available at SSRN},
  note={SSRN 5065689},
  year={2024},
  month={December},
  doi={10.2139/ssrn.5065689},
  keywords={Open LLM, Fine tuning, Mindat, Data analytics, Data science}
}
```

**Paper:** [Fine-Tuning Small and Open LLMs to Automate Geoscience Data Analysis Workflows: A Scalable Approach](https://doi.org/10.2139/ssrn.5065689)