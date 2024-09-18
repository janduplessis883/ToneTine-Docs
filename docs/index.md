# Homepage

## What is ToneTint?
**ToneTint** is a Python package that provides an intuitive way to perform sentiment analysis on text data and visualize the results. It splits the input text into manageable chunks, analyzes each chunk using a pre-trained sentiment analysis model, and highlights the text with background colors corresponding to the sentiment. Additionally, it displays tooltips with detailed sentiment scores when hovering over each text chunk. Perfect for Jupyter Notebooks & Steamlit.

## Features

- **Sentiment Analysis**: Uses pre-trained models to analyze the sentiment of text chunks.
- **Color-Coded Visualization**: Highlights text with colors representing positive, negative, or neutral sentiments.
- **Opacity Adjustment**: Adjusts the opacity of the highlight based on the confidence score of the sentiment prediction.
- **Interactive Tooltips**: Displays sentiment labels and scores when hovering over text chunks.
- **Customizable Colors**: Allows customization of highlight colors for different sentiments.
- **Flexible Text Chunking**: Splits text into sentences and further into chunks of specified sizes for detailed analysis.


![image](docs/images/social.png)







#### Code for a specific language

Some more code with the `py` at the start:

``` py
import tensorflow as tf
def whatever()
```

#### With a title

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### With line numbers

``` py linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### Highlighting lines

``` py hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

## Icons and Emojs

:smile:

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }
