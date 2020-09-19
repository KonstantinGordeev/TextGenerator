# TextGenerator
A model that generates text based on a given one.

Class LanguageModel включает методы fit(file) и generate(k, sid). fit(file) обучает модель на тексте из файла file, generate(k, sid) создает новый текст из k слов, начинающийся с sid % len(words) слова, встречающегося в тексте первый раз.
Во второй ячейке ipython notebook находится пример использования LanguageModel, генерирующий текст на основе text.txt, в котором находится статья о Machine Learning из англоязычной Википедии.
