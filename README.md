
# A Catalog of resources for Indian language NLP



_Please suggest any other resources you may be aware of. Raise an issue to add more resources to the catalog. Put the proposed entry in the following format:_

  \[Wikipedia Dumps\]\(https://dumps.wikimedia.org/)
  
_Add a small, informative description of the dataset and provide links to any paper/article/site documenting the resource._

<!-- vscode-markdown-toc -->
* [Major Indic Language NLP Repositories](#MajorIndicLanguageNLPRepositories)
* [Text Corpora](#TextCorpora)
	* [Unicode Standard](#UnicodeStandard)
	* [Monolingual Corpus](#MonolingualCorpus)
	* [Lexical Resources](#LexicalResources)
	* [NER Corpora](#NERCorpora)
	* [Parallel Translation Corpus](#ParallelTranslationCorpus)
	* [Parallel Transliteration Corpus](#ParallelTransliterationCorpus)
	* [Textual Entailment](#TextualEntailment)
	* [Sentiment Analysis](#SentimentAnalysis)
	* [POS Tagged corpus](#POSTaggedcorpus)
	* [Chunk Corpus](#ChunkCorpus)
	* [Dependency Parse Corpus](#DependencyParseCorpus)
	* [Dialog](#Dialog)
* [Speech Corpora](#SpeechCorpora)
* [OCR Corpora](#OCRCorpora)
* [Multimodal Corpora](#MultimodalCorpora)
* [Models](#Models)
	* [Word Embeddings](#WordEmbeddings)
	* [Sentence Embeddings](#SentenceEmbeddings)
	* [Multilingual Word Embeddings](#MultilingualWordEmbeddings)
	* [SMT Models](#SMTModels)
* [Libraries](#Libraries)

<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->


## <a name='MajorIndicLanguageNLPRepositories'></a>Major Indic Language NLP Repositories

- [Technology Development for Indian Languages (TDIL)](http://tdil-dc.in)
- [Center for Indian Language Technology (CFILT)](http://www.cfilt.iitb.ac.in/)
- [Language Technologies Research Center (LTRC)](https://ltrc.iiit.ac.in/download.php)
- [Linguistic Data Consortium For Indian Languages (LDCIL)](https://data.ldcil.org)
- [University of Hyderabad - Sanskrit NLP](http://sanskrit.uohyd.ac.in/scl)

## <a name='TextCorpora'></a>Text Corpora

### <a name='UnicodeStandard'></a>Unicode Standard

- [An Introduction to Indic Scripts 
](https://www.w3.org/2002/Talks/09-ri-indic/indic-paper.pdf)
- [Unicode Standard for South Asian Scripts](http://www.unicode.org/versions/Unicode12.1.0/ch12.pdf)

### <a name='MonolingualCorpus'></a>Monolingual Corpus

- [Wikipedia Dumps](https://dumps.wikimedia.org/)
- [LDCIL Monolingual Corpus](https://data.ldcil.org)
- [Charles University Hindi Monolingual Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0023-625F-0)
- [Charles University Urdu Monolingual Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0023-65A9-5)
- [IIT Bombay Hindi Monolingual Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel/iitb_corpus_download/monolingual.hi.tgz)
- [EMILLE Corpus (multiple Indian languages)](https://www.lancaster.ac.uk/fass/projects/corpus/emille/)
- [WMT CommonCrawl Corpus](http://data.statmt.org/ngrams/raw/)
- [WMT NEWS Crawl](http://data.statmt.org/news-crawl/)
- [Janmabhumi Malayalam Corpus](https://github.com/ABHISHEKVALSAN/Malayalam-Newspaper-Article-Dataset)
- [Leipzig Corpus](http://wortschatz.uni-leipzig.de/en/download/)
- [Sanskrit Monolingual and Sandhi-split Corpus](http://sanskrit.uohyd.ac.in/Corpus/)

### <a name='LexicalResources'></a>Lexical Resources

- [IndoWordNet](http://www.cfilt.iitb.ac.in/indowordnet/)
- [IIIT-Hyderabad Word Similarity Database](https://github.com/syedsarfarazakhtar/Word-Similarity-Datasets-for-Indian-Languages): 7 Indian languages
- [Facebook Hindi Analogy Dataset](https://dl.fbaipublicfiles.com/fasttext/word-analogies/questions-words-hi.txt)

### <a name='NERCorpora'></a>NER Corpora

- [FIRE 2013 AUKBC NER Corpus](http://au-kbc.org/nlp/NER-FIRE2013)
- [FIRE 2014 AUKBC NER Corpus](http://www.au-kbc.org/nlp/NER-FIRE2014/)
- [IIT Bombay Marathi NER Corpus](http://www.cfilt.iitb.ac.in/ner/download_data.html)
- [WikiAnn NER Corpus](http://nlp.cs.rpi.edu/wikiann/) (_Noisy_)
- [a-mma NER data](https://github.com/a-mma/NER_Open_Data)

### <a name='ParallelTranslationCorpus'></a>Parallel Translation Corpus

- [Indian Language Corpora Initiative](http://sanskrit.jnu.ac.in/ilci/index.jsp): Available on TDIL portal on request
- [IIT Bombay English-Hindi Parallel Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel/)
- [OPUS corpus](http://opus.nlpl.eu/)
- [WAT 2018 Parallel Corpus](http://lotus.kuee.kyoto-u.ac.jp/WAT/indic-multilingual/index.html)
- [EILMT Corpus](http://tdil-dc.in/index.php?searchword=EILMT&searchphrase=all&option=com_search&lang=en)
- [Joshua Decoder Corpus](https://github.com/joshua-decoder/indian-parallel-corpora)
- [TED Parallel Corpus](https://github.com/ajinkyakulkarni14/TED-Multilingual-Parallel-Corpus)
- [Charles University English-Hindi Parallel Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0001-BD17-1)
- [Charles University English-Tamil Parallel Corpus](http://ufal.mff.cuni.cz/~ramasamy/parallel/html/)
- [Charles University English-Odia Parallel Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2879)
- [Charles University English-Urdu Religious Parallel Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2582)
- [WikiMatrix Corpus](https://ai.facebook.com/blog/wikimatrix)
- [FLORES dataset](https://github.com/facebookresearch/flores)

### <a name='ParallelTransliterationCorpus'></a>Parallel Transliteration Corpus

- [BrahmiNet Corpus](http://www.cfilt.iitb.ac.in/brahminet/static/download.html): 110 language pairs
- [Xlit-Crowd: Hindi-English Transliteration Corpus](https://github.com/anoopkunchukuttan/crowd-indic-transliteration-data)
- [Xlit-IITB-Par: Hindi-English Transliteration Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel/supplementary_resources/xlit-iitb-par.tgz)

### <a name='TextualEntailment'></a>Textual Entailment

- [XNLI corpus](https://github.com/facebookresearch/XNLI): Hindi and Urdu test sets and machine translated training sets (from English MultiNLI).

### <a name='SentimentAnalysis'></a>Sentiment Analysis

- [IIT Bombay movie review datasets for Hindi and Marathi](http://www.cfilt.iitb.ac.in/Sentiment_Analysis_Resources.html) 
- [IIT Patna movie review datasets for Hindi](http://www.iitp.ac.in/~ai-nlp-ml/resources.html)
- [IIIT-H LTRC Multi-domain dataset for Telugu](https://ltrc.iiit.ac.in/showfile.php?filename=downloads/sentiraama/)

### <a name='POSTaggedcorpus'></a>POS Tagged corpus

- [Indian Language Corpora Initiative](http://sanskrit.jnu.ac.in/ilci/index.jsp)
- [Universal Dependencies](https://universaldependencies.org/)
- [Code Mixed Dataset for Hindi, Bengali and Telugu, ICON 2016 shared task](https://amitavadas.com/Code-Mixing.html)

### <a name='ChunkCorpus'></a>Chunk Corpus

- [Indian Language Corpora Initiative](http://sanskrit.jnu.ac.in/ilci/index.jsp)

### <a name='DependencyParseCorpus'></a>Dependency Parse Corpus

- [IIIT Hyderabad Hindi Treebank](http://tdil-dc.in/index.php?option=com_download&task=showresourceDetails&toolid=1977&lang=en)
- [Universal Dependencies](https://universaldependencies.org/)
- [Universal Dependencies Hindi Treebank](https://github.com/UniversalDependencies/UD_Hindi-HDTB)
- [Universal Dependencies Urdu Treebank](https://github.com/UniversalDependencies/UD_Urdu-UDTB)

### <a name='Dialog'></a>Dialog
- [a-mma Indic Casual Dialogs Datasets](https://github.com/a-mma/indic_casual_dialogs_dataset)

## <a name='SpeechCorpora'></a>Speech Corpora

- [Microsoft Speech Corpus](https://msropendata.com/datasets/7230b4b1-912d-400e-be58-f84e0512985e): Speech corpus for Telugu, Tamil and Gujarati
- [IIT Madras TTS database](https://www.iitm.ac.in/donlab/tts/index.php)
- [BABEL Speech Corpus](https://en.wikipedia.org/wiki/BABEL_Speech_Corpus): includes some Indian languages

## <a name='OCRCorpora'></a>OCR Corpora

- [Kannada MNIST](https://www.kaggle.com/higgstachyon/kannada-mnist)

## <a name='MultimodalCorpora'></a>Multimodal Corpora

- [English-Hindi Visual Genome](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-2997): Images captioned in both English and Hindi. 


## <a name='Models'></a>Models

### <a name='WordEmbeddings'></a>Word Embeddings 

- [FastText CommonCrawl+Wikipedia](https://fasttext.cc/docs/en/crawl-vectors.html)
- [FastText Wikipedia](https://fasttext.cc/docs/en/pretrained-vectors.html)
- [Polyglot](https://sites.google.com/site/rmyeid/projects/polyglot) 

### <a name='SentenceEmbeddings'></a>Sentence Embeddings

- [BERT Multilingual](https://github.com/google-research/bert)

### <a name='MultilingualWordEmbeddings'></a>Multilingual Word Embeddings 

- [GeoMM](https://github.com/anoopkunchukuttan/geomm)
- [Babylon Partners](https://github.com/Babylonpartners/fastText_multilingual)

### <a name='SMTModels'></a>SMT Models

- [Shata-Anuvaadak](http://www.cfilt.iitb.ac.in/~moses/shata_anuvaadak/): 110 language pairs
- [LTRC Vanee](https://ltrc.iiit.ac.in/downloads/tools/Vaanee.tgz)


## <a name='Libraries'></a>Libraries

- [Indic NLP Library](https://github.com/anoopkunchukuttan/indic_nlp_library): Python Library for various Indian language NLP tasks like tokenization, sentece splitting, normalization, script conversion, transliteration, _etc_
- [pyiwn](https://github.com/riteshpanjwani/pyiwn): Python Interface to IndoWordNet
- [Indic-OCR] (https://indic-ocr.github.io/) : OCR for Indic Scripts
