# Text Summarization Tool

This project implements a simple text summarization tool using Python and the `spaCy` library. The tool takes a large paragraph as input and generates a concise summary by extracting the most important sentences based on keyword frequency.

## Features
- **Text Summarization**: Summarizes large paragraphs into concise sentences.
- **Customizable Summary Length**: Allows users to specify the number of sentences in the summary.
- **Efficient and Lightweight**: Uses `spaCy` for natural language processing, ensuring fast and accurate results.

## Installation

To use this tool, you need to install the required Python libraries. Follow the steps below:

1. **Install spaCy**:
   ```bash
   pip install spacy
   ```

2. **Download the spaCy English Model**:
   ```bash
   python -m spacy download en_core_web_sm
   ```

3. **Clone this Repository**:
   ```bash
   git clone https://github.com/Daniyal-DS/Text-Summarization-Tool
   cd text-summarization-tool
   ```

## Usage

### Running the Tool
1. Open the Jupyter Notebook file `Text_Summarization_Tool.ipynb`.
2. Run the cells in the notebook to load the summarization function.
3. Use the `summarize_text` function to summarize your text.

Example:
```python
text = """
Artificial intelligence (AI) is intelligence demonstrated by machines, in contrast to the natural intelligence displayed by humans and animals. Leading AI textbooks define the field as the study of "intelligent agents": any device that perceives its environment and takes actions that maximize its chance of successfully achieving its goals. Colloquially, the term "artificial intelligence" is often used to describe machines (or computers) that mimic "cognitive" functions that humans associate with the human mind, such as "learning" and "problem-solving". As machines become increasingly capable, tasks considered to require "intelligence" are often removed from the definition of AI, a phenomenon known as the AI effect. A quip in Tesler's Theorem says "AI is whatever hasn't been done yet." For instance, optical character recognition is frequently excluded from things considered to be AI, having become a routine technology.
"""

summary = summarize_text(text, summary_length=2)
print("Summary:\n", summary)
```

### Output
The tool will output a summary of the input text:
```plaintext
Summary:
Artificial intelligence (AI) is intelligence demonstrated by machines, in contrast to the natural intelligence displayed by humans and animals. Leading AI textbooks define the field as the study of "intelligent agents": any device that perceives its environment and takes actions that maximize its chance of successfully achieving its goals.
```

## Code Structure
- `Text_Summarization_Tool.ipynb`: Jupyter Notebook containing the implementation of the text summarization tool.
- `README.md`: This file, providing an overview of the project and instructions for use.

## Dependencies
- Python 3.x
- `spaCy` library
- `en_core_web_sm` spaCy model

## Contributing
If you'd like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push them to your fork.
4. Submit a pull request with a detailed description of your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thanks to the `spaCy` team for providing an excellent NLP library.
- Inspired by various text summarization techniques and tutorials.

## Contact
For any questions or feedback, feel free to reach out:
- **Daniyal Haider**
- **Email**: haiderdaniyal095@gmail.com
- **GitHub**: [Daniyal-DS](https://github.com/Daniyal-DS)
```
