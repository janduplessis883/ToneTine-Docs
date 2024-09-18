# Getting Started

## Installation

You can install **ToneTint** via pip:

```bash
pip install tonetint
```

Alternatively, you can clone the repository and install it manually:

```bash
git clone https://github.com/janduplessis883/tonetint_package.git
cd tonetint_package
python setup.py install
```

## Usage

### Jupyter Notebook

```python
from tonetint.sentiment_visualizer import ToneTint

# Initialize the visualizer
visualizer = ToneTint()

# Your input text
text = "I love sunny days. However, I hate the rain. The weather today is okay."

# Display the sentiment visualization in Jupyter Notebook
visualizer.display_notebook(text)
```
### Stremlit App
```python
from tonetint.sentiment_visualizer import ToneTint

# Initialize the visualizer
visualizer = ToneTint()

# Your input text
text = "I love sunny days. However, I hate the rain. The weather today is okay."

# Display the sentiment visualization in a Streamlit app
visualizer.display_streamlit(text)
```
This code will display your text with:

- **Positive sentiments** highlighted in green.
- **Negative sentiments** highlighted in red.
- **Neutral sentiments** highlighted in yellow.

Hovering over each text chunk will show a tooltip with the sentiment label and confidence score.
