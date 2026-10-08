# simplerag
一个简洁有效的工程化RAG项目

基于LinearRAG工程改造而来，主要改动：

1、仅使用段落-词进行图建模；
2、将本地存储修改为工程化的图数据库存储与向量数据库存储；
3、增强高并发下的项目能力。


```bash
pip install -r requirements.txt
```

**Step 2: Download Spacy language model**

```bash
python -m spacy download en_core_web_trf/zh_core_web_md

```
