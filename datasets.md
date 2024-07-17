# High-Quality Datasets for Training Large Language Models

This document lists high-quality datasets suitable for training large language models, particularly those relevant to the PEER system implementation.

## Datasets

### C4 Dataset
- **Description**: Large-scale, cleaned version of Common Crawl data.
- **Source**: [TensorFlow Datasets](https://www.tensorflow.org/datasets/catalog/c4)
- **Size**: ~305 GB uncompressed.
- **Type**: Diverse web text.
- **Preprocessing**: Filtered for natural language, removed duplicates.

### GitHub Code Corpus
- **Description**: Large collection of programming code from public repositories.
- **Source**: [GitHub Archive Program](https://archiveprogram.github.com/)
- **Size**: Several terabytes.
- **Type**: Source code in various programming languages.
- **Preprocessing**: May require filtering for specific languages or quality.

### Amazon Product Data
- **Description**: Part of the fast.ai NLP datasets collection hosted on AWS. Includes both polarity and full versions of Amazon Reviews.
- **Source**: [fast.ai Datasets](https://docs.fast.ai)
- **AWS CLI Access**: `aws s3 ls --no-sign-request s3://fast-ai-nlp/`
- **Size**: Varies by dataset. Polarity dataset is 493 MB compressed.
- **Type**: Product reviews, sentiment analysis
- **Preprocessing**: May need cleaning and formatting depending on the specific use case
- **License**: Varies by dataset, check documentation for details

### Wikipedia Dump
- **Description**: Comprehensive collection of Wikipedia articles.
- **Source**: [Wikimedia Foundation](https://dumps.wikimedia.org/)
- **Size**: Over 18 GB compressed.
- **Type**: Encyclopedic text.
- **Preprocessing**: Requires parsing XML and extracting plain text.

### OpenWebText
- **Description**: Open-source replication of WebText.
- **Source**: [OpenWebText Corpus](https://github.com/jcpeterson/openwebtext)
- **Size**: ~40 GB.
- **Type**: Web content from URLs shared on Reddit.
- **Preprocessing**: Filtered for quality based on Reddit scores.

### BookCorpus
- **Description**: Dataset of free books.
- **Source**: [BookCorpus](https://yknzhu.wixsite.com/mbweb)
- **Size**: ~16 GB.
- **Type**: Full-text books.
- **Preprocessing**: May require formatting and cleaning.

### The Pile
- **Description**: Large-scale curated dataset for language modeling.
- **Source**: [EleutherAI](https://pile.eleuther.ai/)
- **Size**: 825 GB.
- **Type**: Diverse mix of 22 high-quality datasets.
- **Preprocessing**: Already cleaned and prepared for language modeling.