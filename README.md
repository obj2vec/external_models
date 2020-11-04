# external_models

В этом репозитории собираются представления, качество которых мы планируем оценивать на этапе I. и затем сравнивать с качеством своих представлений на этапе II.

Все представления содержательно делятся на два типа — у объекта одно представление(контекстно-независимые представления) и у объекта сколько угодно представлений, каждое из которых зависит и однозначно определяется по контексту(контекстно-зависимые представления)
 
Контекстно-независимые представления(функция от одного аргумента, объекта):
- Google word2vec
- Microsoft GLOVE
- EVE [http://mlg.ucd.ie/eve/]
- iPavlov
- fastText

Контекстно-зависимые(функция от двух аргументов, объекта и контекста):
- AdaGram [http://proceedings.mlr.press/v51/bartunov16.pdf]
- Elmo [https://github.com/ltgoslo/simple_elmo]
- Bert [http://files.deeppavlov.ai/deeppavlov_data/bert/rubert_cased_L-12_H-768_A-12_v1.tar.gz]

Часть представлений можно скачать с https://rusvectores.org/ru/models/

Также было бы очень здорово получить у Анны Потапенко тематические представления для Википедии
