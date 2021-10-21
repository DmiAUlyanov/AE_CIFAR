### Домашнее задание №3 (5+3 баллов). Срок выполнения: до 04.11.21.

- Реализовать автоэнкодер со сжатым внутренным состоянием (h=100):
    - Обучить на обучающей выборки Cifar10 (аномальный класс 'airplane')
    - Использовать полученные векторные представления для k-NN и LOF на тестовой выборке
        - Найти k дающий лучший average precision, построить precision-recall кривую
        - Найти лучший F1-score, построить confusion matrix для данного порога
        
- Реализовать sparse автоэнкодер с h=3*32*32
    - Обучить на обучающей выборки Cifar10 (аномальный класс 'airplane')
    - Использовать полученные векторные представления для k-NN и LOF на тестовой выборке
        - Найти k дающий лучший average precision, построить precision-recall кривую
        - Найти лучший F1-score, построить confusion matrix для данного порога

- Сравнить полученные результаты пунктов 1 и 2 с результатами домашних заданий 1 и 2

- (Дополнительно): Реализовать contractive автоэнкодера