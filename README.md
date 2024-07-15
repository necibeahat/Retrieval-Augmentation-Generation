# Retrieval Augmentation Generation (RAG)
This notebook shows a simple way to add your custom data to LLMs. This is called RAGs.  

customise your search using is a simple way to implement the retrieval augmentation generation (RAG) with a custom data. 

>> Why it is important to be ablet o add acustom data??

## Installation 

```python3 -m venv .venv source .venv/bin/activate .venv/bin/pip install -r requirements.txt ```

## Libraries
- [Pandas](https://pandas.pydata.org/): data manipulation
- [qdrant-client](https://github.com/qdrant/qdrant): vector similariy seach engine and vector database
- [Sentence Transformers](https://pypi.org/project/sentence-transformers/): framework to computer dense erctor represetnation for sentences, paragraphs and images. The models are based on transformers like BERT / RoBERTa / XLM-RoBERTa. 
- [Llamafile](https://github.com/Mozilla-Ocho/llamafile): Run LLM with a single file
- [OpenAI](https://pypi.org/project/openai/): connect to LLM from openAI

## Data 

