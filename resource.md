

- **Corpus**
  - plain text 
    + CC100-Marathi Dataset: [link](https://metatext.io/datasets/cc100-marathi) : this is extracted from Common crwal data 2018, and it has 12Million sentences but these are phrases or truncated sentences overall extraction quality is not good.  
    + Leipzig corpus : [link](https://wortschatz.uni-leipzig.de/en/download/Marathi) : this is text extracted from news and general websites groupd by years. it is over 1 million sentences. 
    + Marathi Wikipedia Articles [link](https://github.com/goru001/nlp-for-marathi): It has a Train set of 59.8k articles and Validation set of 25.6k articles
    + L3Cube-MahaCorpus [link](https://github.com/l3cube-pune/MarathiNLP): It is a Marathi monolingual text scraped from different internet sources. it has monolingual corpus with 24.8M sentences and 289M tokens. They also trained transformer models with this data.

  - classification data
     + L3CubeMahaSent (tweets with sentiments):[link](https://github.com/l3cube-pune/MarathiNLP) This dataset contains a total of 18,378 tweets in marathi which are classified into three classes - Positive(1), Negative(-1) and Neutral(0). All tweets are present in their original form, without any preprocessing. 
     + L3Cube-MahaHate: [link](https://github.com/l3cube-pune/MarathiNLP) This Marathi Hate Speech Detection dataset. It has 4-class and 2-class forms. The 4-class dataset (with labels hate, offensive, pofane, and not) has total of 25000 samples. the 2-class dataset (with labels hate and not) has a total of 37500 tweets.  

  - sequence labellling 
    - NER 
      + L3Cube-MahaNER [link](https://github.com/l3cube-pune/MarathiNLP): The dataset is released in IOB and non-IOB form. it has has total of 25000 sentences with 8 tags (Person, Location, Organization, Measure, Time, Date, and Designation)

- **Lexical**
  - Wordnet Marathi [link](https://www.cfilt.iitb.ac.in/wordnet/webmwn/wn.php) : it has good coverage of marathi words and its synonyms (33k concepts) and gloss, examples sentence, it also has links to other indian language concepts.

- **Tools**
  - Transformer models (pretrained)
    + L3Cube-MahaNLP [link](https://github.com/l3cube-pune/MarathiNLP) they have models MahaBert (bert), MahaRoBERTa(Roberta), MahaAlbert(Albert), MahaGPT(gpt2) models
  
  - embeddings (pretrained)
    + MahaFT: [link](https://github.com/l3cube-pune/MarathiNLP) They have MahaFT(fasttext) model  and embeddings

  - classification 
    + MahaSent [link](https://huggingface.co/l3cube-pune/MarathiSentiment) Here you will get IndicBert finetunned with sentiment of tweet
   
  - sequence labellling 
    + MahaNER [link](https://huggingface.co/l3cube-pune/marathi-ner) Here you will get a bert model tunned for  

- **Blogs**
  + It is on indian languages NLP tools in general [blog](https://www.analyticsvidhya.com/blog/2020/01/3-important-nlp-libraries-indian-languages-python/) It talks about iNLTK, Indic NLP StanfordNLP
  
- **Papers**
  + L3Cube-MahaCorpus and MahaBERT: Marathi Monolingual Corpus, Marathi BERT Language Models, and Resources by Raviraj Joshi [link](https://arxiv.org/abs/2202.01159) This is paper on experience in creating corpus and bert models for Marathi. 
  + Spread Love Not Hate: Undermining the Importance of Hateful Pre-training for Hate Speech Detection by Omkar Gokhale, Aditya Kane, Shantanu Patankar, Tanmay Chavan, Raviraj Joshi [link](https://arxiv.org/abs/2210.04267) This paper is describes training a PTM for marathi using tweets data and finetuned on supervised tweets data for hateful text (2 and 4 class) 
  + L3Cube-MahaNER: A Marathi Named Entity Recognition Dataset and BERT models by Parth Patil, Aparna Ranade, Maithili Sabane, Onkar Litake, Raviraj Joshi [link]( https://arxiv.org/pdf/2204.06029.pdf) It discussees NER dat creation and experiments with different NN models.

 
