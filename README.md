# nlp-hse-autumn2018
Практический курс в рамках программы "Text Mining" специализации "Современный анализ данных, глубокое обучение и приложения". Читается в Высшей Школе Экономики, https://cs.hse.ru/dpo/datapp#pagetop

Емельянов Антон

email: login-const@mail.ru

telegram: @king_menin

|                       | Лекции                                                                                                                                           | Практика                                                    | Домашнее  задание                                                   |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|---------------------------------------------------------------------|
| занятие 1 (21 января)  | Введение: задачи автоматической обработки текстов и основные подходы к их решению. Токенизация, морфологический анализ. Sequence labeling  | Регулярные выражения, лемматизация, POS-тэггинг, морфологический анализ. | Генерация текста по шаблону. Извлечение телефонных номеров из текста.   
| занятие 2 (26 января)  | Вектора слов. Дистрибутивная семантика  | Вектора слов. Близость документов. | Диалог с поэтом   
| занятие 3 (29 января)  | Тематическое моделирование  | Применение тематического моделирования и визуализация коллекций. Классификация, fasttext.| Тематический анализ коллекции
| занятие 4 (2 февраля)  | Нейронные сети. | Классификация текстов с помощью нейронных сетей. | Извлечение именованных сущностей.
| занятие 5 (5 февраля)  | Языковые модели. | Языковые модели для классификации и генерации | Применение Elmo на imdb
| занятие 6 (9 февраля)  | Seq2Seq and attention. | Attention на tensorflow для NMT  | coming soon


## 27 октября

Данные к занятию лежат в папке: [git:lecture 1. intro to nlp](https://github.com/king-menin/nlp-hse-autumn2018/tree/master/lecture%201.%20intro%20to%20nlp)

[Лекция 1. Часть 1. Введение](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%201.%20intro%20to%20nlp/lecture%201.%20part%201.%20intro.pdf), [Лекция 1. Часть 2. Морфологический анализ](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%201.%20intro%20to%20nlp/lecture%201.%20part%202.%20morphology.pdf), [ноутбук с семинара](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%201.%20intro%20to%20nlp/sem1.ipynb), [домашнее задание](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/hw1.ipynb).

Необходимые библиотеки Python описаны в начале [ноутбука с семинара](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%201.%20intro%20to%20nlp/sem1.ipynb).


## 1 ноября

Данные к занятию: инструкции в [ноутбуке](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%202.%20word%20vectors/ds.ipynb)

[Лекция 2. Вектора слов](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%202.%20word%20vectors/word%20vectors.pdf), [ноутбук с семинара](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%202.%20word%20vectors/ds.ipynb), [домашнее задание](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/hw2.ipynb).


## 8 ноября

Данные к занятию в [папке](https://github.com/king-menin/nlp-hse-autumn2018/tree/master/lecture%203.%20topic%20modeling%20and%20classification) и на [google диске](https://drive.google.com/file/d/19e2fOFpykP4iWCCCxzlJraAilvnVb1m9/view)

[Лекция 3. Тематическое моделирование](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%203.%20topic%20modeling%20and%20classification/topic%20modeling.pdf), ноутбуки семинара - тематическое моделирование: [git](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%203.%20topic%20modeling%20and%20classification/topic_modeling.ipynb); [colab](https://colab.research.google.com/drive/18QKAqSRyHxueej6XBSNLcEgY9Fr7_kAO), fasttext классификация [git](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%203.%20topic%20modeling%20and%20classification/classification.ipynb); [colab](https://colab.research.google.com/drive/1I9qBSkgILoLl0fLtm7Mqrl6L3xBv3IOr) [домашнее задание](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/hw3.ipynb).

Необходимые библиотеки Python:
* nltk; после установки nltk необходимо из командной строки Python3 вызвать команды
```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```
* pymorphy2
* matplotlib
* pandas
* sklearn
* pymystem3
* python-rake
* wordcloud
* gensim
* pyLDAvis
* fasttext (не путайте с fastText)


## 10 ноября

Данные к занятию лежат в папке: [ru.vec](https://www.dropbox.com/s/0x7oxso6x93efzj/ru.tar.gz), [articles_lemmatized_noSW.csv](https://www.dropbox.com/sh/513tgmhz2ollna5/AAB6W-J3zwKDxKHSUnhjaYINa?dl=0&preview=articles_lemmatized_noSW.csv)

[Лекция 4. Нейронные сети в анализе текстов.](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%204.%20neural%20networks%20in%20nlp/neural%20networks%20in%20nlp.pdf),  практика [git](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%204.%20neural%20networks%20in%20nlp/RU_FNN_CNN_and_RNN.ipynb); [colab](https://colab.research.google.com/drive/1_CiD5xTMSxXSLdxD3b89pl1jmysc0pet), [домашнее задание](https://github.com/king-menin/nlp-course/blob/master/hw4.ipynb)

## 15 ноября

Данные к занятию лежат в папке: [git](https://github.com/king-menin/nlp-hse-autumn2018/tree/master/lecture%205.%20language%20models)

[Лекция 5. Языковые модели.](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%205.%20language%20models/language%20models.pdf),  практика в папке с лекцией [git](https://github.com/king-menin/nlp-hse-autumn2018/tree/master/lecture%205.%20language%20models); [colab, lm](https://colab.research.google.com/drive/12Px51s4HRa75F59SHe7Degh52_YQN9JT); [colab, elmo](https://drive.google.com/file/d/1Z1rUSpV7xSHGksZNyijjIwl1nCI-pxUN/view?usp=sharing), [домашнее задание](https://github.com/king-menin/nlp-course/blob/master/hw5.ipynb)

Ссылки на реализации языковых моделей/примеры использования:
* ELMO: tf - [ru](http://docs.deeppavlov.ai/en/master/apiref/models/embedders.html#deeppavlov.models.embedders.elmo_embedder.ELMoEmbedder), [en](https://tfhub.dev/google/elmo/2); pytorch - [for many languages](https://github.com/HIT-SCIR/ELMoForManyLangs/)
* ULMFit: pytorch - [en](https://github.com/fastai/fastai/blob/master/courses/dl2/imdb.ipynb)
* Flair: pytorch - [en chars](https://github.com/zalandoresearch/flair)
* BERT: tf - [multilingual](https://github.com/google-research/bert), pytorch - [multilingual](https://github.com/huggingface/pytorch-pretrained-BERT)

## 22 ноября

[Лекция 6. Seq2Seq and Attention.](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%206.%20seq2seq%20and%20attention/seq2seq%20and%20attention.pdf),  практика [git](https://github.com/king-menin/nlp-hse-autumn2018/blob/master/lecture%206.%20seq2seq%20and%20attention/tf_attention.ipynb); [colab](https://colab.research.google.com/drive/1yTyBdBOho3f29Hbm2FCW3Yj0WzR_caTd), [домашнее задание](https://github.com/king-menin/nlp-course/blob/master/hw6.ipynb)



## Рекомендуемые ресурсы
### На английском

* [Jurafsky & Martin](https://web.stanford.edu/~jurafsky/slp3/)
* [Курс Лауры Каллмайер по МО для NLP](https://user.phil.hhu.de/~kallmeyer/MachineLearning/index.html)
* [Курс Нильса Раймерса по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Оксфорде по DL для NLP](https://github.com/UKPLab/deeplearning4nlp-tutorial)
* [Курс в Стенфорде по DL для NLP](http://cs224d.stanford.edu)
* [Reinforcment Learning for NLP](https://github.com/jiyfeng/rl4nlp)


### На русском (и про русский, в основном)

* [Курс nlp в яндексе](https://github.com/yandexdataschool/nlp_course)
* [НКРЯ](http://ruscorpora.ru)
* [Открытый корпус](http://opencorpora.org)
* [Дистрибутивные семантические модели для русского языка](http://rusvectores.org/ru/)
* [Морфология](https://tech.yandex.ru/mystem/)
* [Синтаксис](https://habrahabr.ru/post/317564/)
* [Томита-парсер](https://tech.yandex.ru/tomita/)
* [mathlingvo](http://mathlingvo.ru)
* [nlpub](https://nlpub.ru)
* [Text Visualisation browser](http://textvis.lnu.se)



## Литература

* Manning, Christopher D., and Hinrich Schütze. Foundations of statistical natural language processing. Vol. 999. Cambridge: MIT press, 1999.
* Martin, James H., and Daniel Jurafsky. "Speech and language processing." International Edition 710 (2000): 25.
* Cohen, Shay. "Bayesian analysis in natural language processing." Synthesis Lectures on Human Language Technologies 9, no. 2 (2016): 1-274.
* Goldberg, Yoav. "Neural Network Methods for Natural Language Processing." Synthesis Lectures on Human Language Technologies 10, no. 1 (2017): 1-309.