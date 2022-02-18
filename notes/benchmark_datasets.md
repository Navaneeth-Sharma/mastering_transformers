# Benchmark Datasets for NLP

1. GLUE
    - Single-sentence tasks
    - CoLA: The Corpus of Linguistic Acceptability dataset.
    - SST-2: The Stanford Sentiment Treebank dataset.
    - Similarity and paraphrase tasks
    - MRPC: The Microsoft Research Paraphrase Corpus
    - QQP: The Quora Question Pairs dataset.
    - STS-B: The Semantic Textual Similarity Benchmark
    - Inference tasks
    - MNLI: The Multi-Genre Natural Language Inference
    - QNLI: Question Natural Language Inference dataset.
    - RTE: The Recognizing Textual Entailment dataset.
    - WNLI: The Winograd Natural Language Inference

2. SuperGLUE
   - Like Glue, SuperGLUE is a new benchmark styled with a new set of more difficult language-understanding tasks and offers a public leaderboard of around currently eight language tasks, drawing on existing data, associated with a single-number performance metric like that of GLUE. The motivation behind it is that as of writing this book, the current state-of-the-art GLUE Score (90.8) surpasses human performance (87.1). Thus, SuperGLUE provides a more challenging and diverse task toward general-purpose, language-understanding

3. XTREME
   - In recent years, NLP researchers have increasingly focused on learning general-purpose representations rather than a single task that can be applied to many related tasks. Another way of building a general-purpose language model is by using multilingual tasks. It has been observed that recent multilingual models such as Multilingual BERT (mBERT) and XLM-R pretrained on massive amounts of multilingual corpora have performed better when transferring them to other languages. Thus, the main advantage here is that cross-lingual generalization enables us to build successful NLP applications in resource-poor languages through zero-shot cross-lingual transfer.

4. XGLUE
   - XGLUE is another cross-lingual benchmark to evaluate and improve the performance of cross-lingual pretrained models for Natural Language Understanding (NLU) and Natural Language Generation (NLG). It originally consisted of 11 tasks over 19 languages. The main difference from XTREME is that the training data is only available in English for each task.

5. SQuAD
   - SQuAD is a widely used QA dataset in the NLP field. It provides a set of QA pairs to benchmark the reading comprehension capabilities of NLP models. It consists of a list of questions, a reading passage, and an answer annotated by crowdworkers on a set of Wikipedia articles. The answer to the question is a span of text from the reading passage.

Find more datasets at Hugging face [repo](https://github.com/huggingface/datasets/tree/master/datasets).
