# Customization

### **Customizing Highlight Colors**

You can specify custom `colors` for positive, negative, and neutral sentiments by passing a dictionary to the `ToneTint` constructor:

```python
custom_colors = {
        "POS": "#aec867",  # Green
        "NEG": "#e8a56c",  # Red
        "NEU": "#f0e8d2",  # Yellow
}

visualizer = ToneTint(colors=custom_colors)
```

### **Adjusting Chunk Size**

You can adjust the chunk size (number of words per chunk) for more granular or broader analysis:

```python
visualizer = ToneTint(chunk_size=10)
```

### **Using a Different Model**

By default **ToneTint** uses `nlptown/bert-base-multilingual-uncased-sentiment` from [Huggingface.co](https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment) The model performs well on most sentiment analysis tasks.

You can specify a different pre-trained model, more suited to your sentiment analysis usecase:

```python
visualizer = ToneTint(model_name='distilbert/distilbert-base-uncased-finetuned-sst-2-english')
```
