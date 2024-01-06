# Data_extraction_llm
Leveraging Large language models (LLM), extract information from the documents.

This project utilizes the Mistral-7B quantized model, a powerful large language model (LLM), to effectively extract key information from diverse documents.

# installation
```python
!pip3 install --upgrade auto-gptq
!pip3 install --upgrade transformers optimum
!pip install paddlepaddle-gpu
!pip install paddleocr
```
# Note : 

Quantized gptq model runs only in GPU environment . Use ggml or gguf versions for cpu based inference.

![One_01_08_new_1](https://github.com/kavinsharaj/Data_extraction_llm/assets/88884470/186fd227-937a-4dd7-a90a-763e0c84b2e5)
# Output
{
  "invoice": {
    "invoice_number": "4172",
    "client_id": "335",
    "date": "03/27/2003"
  }
}
