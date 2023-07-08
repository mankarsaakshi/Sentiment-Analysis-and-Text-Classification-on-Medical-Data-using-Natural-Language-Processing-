# Sentiment-Analysis-and-Text-Classification-on-Medical-Data-using-Natural-Language-Processing-

The project "Sentiment Analysis and Text Classification on Medical Data using Natural Language Processing" focuses on developing a system that can automatically analyze the sentiment or emotion expressed in unstructured textual data, of medical discharge summary.

To accomplish this, the project utilizes three key components: Stanza Core NLP, SentiWordNet, and the Pattern library.

1. Stanza Core NLP: Stanza is a powerful Python library for natural language processing (NLP). It provides a wide range of NLP tools, including tokenization, part-of-speech tagging, dependency parsing, and named entity recognition. In this project, Stanza is employed to preprocess the unstructured text, breaking it down into meaningful units, such as sentences or words, and performing essential linguistic analysis.

2. SentiWordNet: SentiWordNet is a lexical resource that assigns sentiment scores to words based on their semantic properties. It contains a vast database of words along with their associated sentiment scores, indicating the degree of positivity, negativity, or neutrality. By leveraging SentiWordNet, the sentiment analysis system can assign sentiment scores to words in the text, allowing for a quantitative assessment of sentiment in the given data.

3. Pattern library: The Pattern library is a Python library that offers a wide range of NLP functionalities, including sentiment analysis. It provides pre-trained sentiment analysis models that can be used to classify text as positive, negative, or neutral. By incorporating the Pattern library, the sentiment analysis system can employ a machine learning-based approach to determine sentiment based on patterns and contextual information in the text.

The project workflow involves several steps. First, the unstructured text data is preprocessed, which includes tasks like tokenization, part-of-speech tagging, and parsing. Then, the sentiment scores of individual words are retrieved from SentiWordNet. These scores are combined and weighted to calculate an overall sentiment score for each sentence or document.

In addition, the sentiment analysis system can leverage the Pattern library's pre-trained models to enhance the sentiment classification process. These models employ machine learning techniques to classify text into positive, negative, or neutral sentiment categories.

By utilizing Stanza Core NLP, SentiWordNet, and the Pattern library, this project aims to provide a comprehensive sentiment analysis solution for unstructured textual data. The combined power of these tools allows for a more accurate and nuanced understanding of sentiment, enabling focused applications in medical area .
