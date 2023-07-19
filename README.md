# RecSys
Построение рекомендательной системы для фильмов на основе данных про фильмы и отзывы с оценками на эти фильмы.
Что выполнено:
- Сетевой анализ. Визуализация не показало четко оформленных сообществ и логичных связей между ними, поэтому не результаты данного анализа не использовались далее для построения content-based рекомендательной системы.
- Текстовый анализ. Выявилось, что подсчет частотности слов как в названиях фильмов, так и в их описаниях, не позволяет уточнить рекомендации т.к. это не позволяет определить, о чем именно фильм, и какие у него особенности.
- Collaborative filtering рекомендация. Наилучшая модель получилась при применении метода SVD, однако затруднительная интерпретация данного метода с текущем уровнем знаний и необходимость проведения операций над матрицами для получения необходимых рекомендаций вынудили нашу команду остановиться на более простом методе - UBCF.
- Content-based рекомендация. Было 4 разных моделей, из которых выбрали самый лучший. На основе множества рассмотренных примеров можно сказать, что система получилась качественной, так как она выдает фильмы похожих жанров, а также, зачастую, из одной вселенной, например, Гарри Поттера или Марвел, что определенно свидетельствует об эффективности рекомендательной системы.
