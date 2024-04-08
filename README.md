**Objective:**

The aim of this endeavor is to construct deep neural network architectures tailored for tasks in Natural Language Processing (NLP) utilizing PyTorch. The project delineates into two main segments:

**Classification Task:**
This phase entails the retrieval of textual data from Arabic websites, preprocessing the gathered data, and the subsequent training of classification models employing RNN, Bidirectional RNN, GRU, and LSTM architectures. Additionally, it encompasses text generation using the Transformer model:

**Part 1: Classification Task**

1. **Data Collection:**
   Textual data is acquired from Arabic websites through scraping mechanisms such as Scrapy or BeautifulSoup. Each extracted text is assigned a relevance score, spanning from 0 to 10.

2. **Preprocessing:**
   Establish an NLP pipeline comprising tokenization, stemming, lemmatization, stop words elimination, and discretization.

3. **Model Training:**
   Conduct model training utilizing RNN, Bidirectional RNN, GRU, and LSTM architectures, alongside hyperparameter optimization to attain optimal performance.

4. **Evaluation:**
   Assess the models employing standard metrics as well as supplementary ones like BLEU score.

**Part 2: Transformer (Text Generation)**

1. **GPT2 Fine-Tuning:**
   Deploy pytorch-transformers to incorporate and fine-tune the GPT2 pre-trained model on a tailored dataset for text generation purposes.

2. **Text Generation:**
   Generate new textual passages grounded on provided sentences leveraging the fine-tuned GPT2 model.

**Files Included:**
- `data_scraper.py`: Housing the code for data scraping from Arabic websites.
- `preprocessing.py`: Implementing the NLP preprocessing pipeline.
- `classification_models.py`: Defining RNN, Bidirectional RNN, GRU, and LSTM models for the classification task.
- `evaluation_metrics.py`: Evaluating models using standard metrics and BLEU score.
- `transformer_finetuning.py`: Fine-tuning the GPT2 model for text generation.
- `text_generation.py`: Generating paragraphs based on input sentences using the fine-tuned GPT2 model.

**Usage:**
Clone the repository, install necessary libraries via `pip install -r requirements.txt`, and execute the scripts sequentially or as required, adjusting parameters as deemed necessary.

**Results:**
Results and performance metrics are stored in respective output files or presented in the console. Elaborate analysis and interpretation of the outcomes can be found within the corresponding sections of the code or accompanying documentation.
