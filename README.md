# Natural Language Processing and Machine Learning

Slides with thanks to: Rob Gaizauskas (U Sheffield), Lucia Specia (Imperial), Noah Smith (U Washington), Chris Manning and the CS224n staffers (Stanford), GATE, Manuel Ciosici, Philipp Koehn, Jay Alammar, and many others - credits given on slides

# Info

This is a computer science course, expecting some knowledge of machine learning and good programming skills.

Telegram link: https://t.me/joinchat/C82SK3gg29NmOGJi

## Assessment

Three assignments; they are worth 30%, 30% and 40% of the final grade.

## Reading

* [Manning and Schutze](https://www.cs.vassar.edu/~cs366/docs/Manning_Schuetze_StatisticalNLP.pdf)


# Week 1


* Introduction to the course [slides](1a - admin, intro.odp)
* Outline of NLP [slides](1b - nlp outline.pdf)
* What is NLP - challenges [slides](1d - what is nlp - challenges and brief tour.pdf)
* Levels of linguistics [slides](1e - levels of linguistics, syntax phonology etc.pdf)
* Intro to ML [slides](intro_to_ml.pdf)
  * ex. 2_1: https://gist.github.com/leondz/06495f7a505117c30ab31e4c98f02ded
  * ex. 2_2: https://gist.github.com/leondz/9a5b95b0f3a3d18fa957e406d1dda207
  * ex. 2_3: https://gist.github.com/leondz/a31f9a2b0dc8bd5c21e66df428ab14b8
* Perceptrons, [slides](6a-nnets and dl.pdf), [notebook](https://colab.research.google.com/drive/1eELLPBIZEkS7UYiPjfPaqdESLHS6uYk6)

* Tokenization [slides 1f](1f - tokenization.pdf), [slides 1g](1g - tokenization approaches.pdf)
<!-- * Exercise 1: sentiment classifier [slides](2c - ngrams exercise (movie reviews).pdf), [notebook](reviews.ipynb) -->
* Word embeddings [slides stanford](http://web.stanford.edu/class/cs224n/slides/cs224n-2019-lecture01-wordvecs1.pdf), [notes stanford](http://web.stanford.edu/class/cs224n/readings/cs224n-2019-notes01-wordvecs1.pdf), [slides yoav](https://www.slideshare.net/mlreview/yoav-goldberg-word-embeddings-what-how-and-whither) 
* Lexical semantics [slides](3a - lexical semantics.pdf)


* Word similarity [slides](3c - word similarity.pdf)
* Part of Speech tagging [slides](2d - pos tags.pdf), [extra slides](4d-markov.pdf) 

* Backpropagation, [slides](6c-multilayer.pdf)
* LSTM [slides](11a-lstm.pdf)
* Backpropagation and word encoding, [slides](lstm2.pdf), 

* Word embeddings [slides](9b-embeddings.pdf)
* Language models and smoothing [slides](smoothing.pdf)


* [Assignment 1](assn1-hmm-emb.pdf): HMM Tagger -or- Embedding induction

# Week 2

* Statistical machine translation [slides](10c-smt.pdf)
* Sequence to sequence [slides](14-seq2seq.pdf)
* Neural machine translation with attention [slides](nmt.pdf)
* Autoencoding [slides](autoenc.pdf)

* Neural language modelling [slides](neural-lm.pdf)
* Dialogue [slides](10a.pdf)
* Assignment: [Sequence-to-sequence prediction](assignment%20seq2seq.pdf)

# Week 3

* Energy efficient NLP [slides](http://www.derczynski.com/greenai.pdf)

Reading:
* Sequence-to-sequence learning with Neural Machine translation [blog](https://www.analyticsvidhya.com/blog/2019/01/neural-machine-translation-keras/), attention [blog](https://towardsdatascience.com/light-on-math-ml-attention-with-keras-dc8dbc1fad39)

* Autoencoding [page](https://blog.keras.io/building-autoencoders-in-keras.html), [AE notebook](https://colab.research.google.com/drive/1P1n8LEIzKZSrlvIWx3YdwdNkgFu9facK), [Denoising AE notebook](https://colab.research.google.com/drive/1erwsMQvq3nqjIcK5rHxeWWWBBPZSKtxC)
* Autoencoding for text [exercise](autoenc-exercise.pdf)


* Illustrated Transformer [post](http://jalammar.github.io/illustrated-transformer/), [tensor2tensor notebook](https://colab.research.google.com/github/tensorflow/tensor2tensor/blob/master/tensor2tensor/notebooks/hello_t2t.ipynb)
* Annotated Transformer [post](https://nlp.seas.harvard.edu/2018/04/03/attention.html)


# Week 3


* CRFsuite: a brief tour [slides](4e-crfsuite.pdf), [data](4f.tar.gz)
* Named entity recognition [slides](8c.pdf). Examples from [displaCy](https://explosion.ai/demos/displacy-ent)

* Gradient descent [slides](12-gd.pdf)

* Advanced clustering, word clustering [slides](clustering_slides.pdf)




* Course recap
* Transfer learning tutorial [NAACL slides](https://docs.google.com/presentation/d/1fIhGikFPnb7G5kr58OvYC3GN4io7MznnM0aAgadvJfc)

## Project

* Some sample ideas & recommendations for the project format [slides](project.pdf)
* More project ideas:
  * [Propaganda detection](https://propaganda.qcri.org/semeval2020-task11/)
  * [Machine translation](http://www.statmt.org/wmt19/translation-task.html)
  * [Hate speech detection](http://hatespeechdata.com/) - maybe for a new language
  * [Question answering](https://rajpurkar.github.io/SQuAD-explorer/)
  * [Morphology tasks](https://sigmorphon.github.io/sharedtasks/2020/) - inflection, grapheme-phoneme, unsupervised (choose max. one!)
  * [BioNLP tasks](https://2019.bionlp-ost.org/tasks) (choose just one!)
  * [Offensive language](https://sites.google.com/site/offensevalsharedtask/)
  * [Conversational AI challenge](http://convai.io/)
