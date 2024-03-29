# Summarizer Chat Bot

Model: facebook/bart-large-cnn 

-->[Documentation](https://huggingface.co/facebook/bart-large-cnn)

-->[Link to Model @ Hugging face spaces](https://huggingface.co/spaces/sajadahmadi/summarizer_chatbot)

**Model description**

BART is a transformer encoder-encoder (seq2seq) model with a bidirectional (BERT-like) encoder and an autoregressive (GPT-like) decoder. BART is pre-trained by (1) corrupting text with an arbitrary noising function, and (2) learning a model to reconstruct the original text.

BART is particularly effective when fine-tuned for text generation (e.g. summarization, translation) but also works well for comprehension tasks (e.g. text classification, question answering). This particular checkpoint has been fine-tuned on CNN Daily Mail, a large collection of text-summary pairs.

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
