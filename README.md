# hse_iad4_2022
Здесь будут выкладываться материалы семинаров для ИАД4.

- Полезные ссылки
  - [Anaconda](https://www.anaconda.com/products/individual)
  - [Stackoverflow](https://stackoverflow.com)
  - Таблица с оценками

- Консультации
  - По Git и GitHub: [задание](https://github.com/V-Marco/hse_iad4_2022/blob/main/misc/git_cons.pdf), [видео](https://youtu.be/Cvd8tdK8CVo)
  - По matplotlib: [тетрадка](https://github.com/V-Marco/hse_iad4_2022/blob/main/misc/matplotlib_cons_2022.ipynb), [видео](https://youtu.be/BKWy5UiF3gM)

- Семинар 1: Немного про Jupyter notebook и numpy
  - [Кодспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_1/solved_sem01_numpy.ipynb)
  - [Видео](https://youtu.be/uUTb1PtWqSE)
  - [Хороший пост про np.random.seed()](https://stackoverflow.com/questions/21494489/what-does-numpy-random-seed0-do)
  - [Классный текст про генераторы случайных чисел](https://onlinelibrary.wiley.com/doi/pdf/10.1002/9783527683147.app1)
  - [Markdown Cheatsheet](https://www.markdownguide.org/basic-syntax#overview)

- Семинар 2: Pandas
  - [Кодспект – часть 1 (решали на семинаре)](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_2/solved_sem02_1_pandas.ipynb)
  - [Кодспект – часть 2 (для самост. изучения)](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_2/solved_sem02_2_pandas.ipynb)
  - [Видео](https://youtu.be/-ykdm7_vf8w)
  - [Разница между функциями `map`, `apply`, `applymap`](https://stackoverflow.com/questions/19798153/difference-between-map-applymap-and-apply-methods-in-pandas)
  - [Примеры индексации в Pandas](https://github.com/V-Marco/hse_iad5_2021/blob/main/misc/pandas_indexing_examples.ipynb)
  - [Здоровское пояснение про bitwise operators в Pandas](https://towardsdatascience.com/bitwise-operators-and-chaining-comparisons-in-pandas-d3a559487525)

- Семинар 3: sklearn и kNN **[UPDATE 9-го февраля: почему kNN хорошо сработал на цифрах]**
  - [Кодспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_3/solved_sem03_sklearn_knn.ipynb)
  - [Видео](https://youtu.be/6C4PBjQBtdc)

- Семинар 4: Визуализация данных
  - [Кодспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_4/solved_sem04_visualization.ipynb)
  - [Видео](https://youtu.be/sNPk7WTTxeo)
  - [Документация волшебных команд](https://ipython.org/ipython-doc/dev/interactive/magics.html)
  - [Бэкенды matplotlib](https://ipython.readthedocs.io/en/stable/interactive/plotting.html)
  - [Классная статья по разным видам корреляций](https://medium.com/@outside2SDs/an-overview-of-correlation-measures-between-categorical-and-continuous-variables-4c7f85610365)
  - Некоторые коэффициенты, отражающие ассоциацию между категориальными переменными:
    - Две категориальные ранговые переменные: [корреляция Спирмена (можно использовать и для непрерывных переменных)](https://en.wikipedia.org/wiki/Spearman%27s_rank_correlation_coefficient), [тау Кендалла](https://en.wikipedia.org/wiki/Kendall_rank_correlation_coefficient)
    - Две категориальные номинальные переменные: [коэффициент Крамера (V или Phi, одно и то же)](http://mlwiki.org/index.php/Cramer%27s_Coefficient), основанный на [хи-квадрат критерии согласия (раздел Testing for statistical independence, показывает независимость)](https://en.wikipedia.org/wiki/Pearson%27s_chi-squared_test)
    - Категориальная и непрерывная: [p-value в F-тесте на сравнение средних](http://mlwiki.org/index.php/One-Way_ANOVA_F-Test)

- Семинар 5: ООП
  - [Кодспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_5/solved_sem05_OOP.ipynb)
  - [Видео](https://youtu.be/Cx94tHmOuoA)
  - [Видео-2](https://youtu.be/phwL5Tb8NVs)
  - Про call-by-object в Python: [раз](https://stackoverflow.com/questions/8184244/i-thought-python-passed-everything-by-reference), [два](https://www.geeksforgeeks.org/is-python-call-by-reference-or-call-by-value/)
  - [Хорошая статья про декораторы](https://tproger.ru/translations/demystifying-decorators-in-python/)

- Семинар 6: Линейная регрессия
  - [Кодспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_6/solved_sem06_linreg.ipynb)
  - [Видео к кодспекту](https://youtu.be/bzHVfArfg-g)
  - [Конспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_6/lin_reg_notes.pdf)
  - [Видео к конспекту](https://youtu.be/ZtsDnF9LaH4)
  - [Функции потерь](https://heartbeat.fritz.ai/5-regression-loss-functions-all-machine-learners-should-know-4fb140e9d4b0)
  - [Мультиколлинеарность](https://stats.stackexchange.com/questions/361247/multicollinearity-and-predictive-performance)
  - [Минимизация MAE](https://stats.stackexchange.com/questions/355538/why-does-minimizing-the-mae-lead-to-forecasting-the-median-and-not-the-mean)

- Семинар 7: Градиентный спуск
  - [Кодспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_7/solved_sem07_grad.ipynb)
  - [Видео](https://youtu.be/LHSsOkuCoSE)
  - [О сходимости градиентного спуска на практике](https://datascience.stackexchange.com/questions/24534/does-gradient-descent-always-converge-to-an-optimum)

- Семинар 7.5: Консультация
  - [Кодспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_7_and_half/solved_sem07_5_cons.ipynb)
  - [Конспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_7_and_half/matr_diff_notes.pdf)
  - [Видео](https://youtu.be/iOyXdI7HEK8)

- Семинар 8: Линейная классификация
  - [Кодспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_8/solved_sem08_linclass.ipynb)
  - [Конспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_8/cl_metrics_notes.pdf)
  - [Видео](https://youtu.be/K5e0x_Df0PE)

- Семинар 9: Логистическая регрессия и SVM
  - [Кодспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_9/sem09_logit_svm.ipynb)
  - [Видео](https://youtu.be/NDe-m5aE8r0)

- Семинар 10: Обработка текстов
  - [Кодспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_10/solved_sem10_texts.ipynb)
  - [Видео](https://youtu.be/HKD-OS3yTmc)
  - [Примеры из Google-таблиц](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_10/examples.xlsx)
  - [Документация re](https://docs.python.org/3/library/re.html)

- Семинар 11: Многоклассовая классификация
  - [Кодспект](https://github.com/V-Marco/hse_iad4_2022/blob/main/seminar_11/solved_sem11_multiclass_calibration.ipynb)
  - [Видео]
  - [Хороший обзор проблемы калибровки](https://dyakonov.org/2020/03/27/проблема-калибровки-уверенности/)
