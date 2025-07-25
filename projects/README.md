1. Калибровка модели Хестона 

    Статья: https://arxiv.org/abs/1511.08718

    Предполагаемый результат: 
    * Расчёт цен в модели Хестона.
    * Расчёт производных по параметрам в модели Хестона.
    * Реализация алгоритма Левенберга — Марквардта.
    * Применение к реальным данным. 

2. Вычисление несобственных интегралов от быстроосцилирующих функций

    [Оригинальная статья](https://www.sciencedirect.com/science/article/pii/S0377042713003385)

    [Применение к модели Хестона](https://hpcquantlib.wordpress.com/2020/05/17/optimized-heston-model-integration-exponentially-fitted-gauss-laguerre-quadrature-rule/)

    Предполагаемый результат:

    * Реализация кода для расчёта параметров квадратуры
    * Расчёт цен опционов в модели Хестона
    * Анализ сходимости. Сравнение с классическими методами (метод COS)

3. Прайсинг европейских/американских опционов в модели Хестона с помощью численных методов для УРЧП
    Статьи: 
    * [Европейские опционы](https://www.math.ualberta.ca/ijnam/Volume-7-2010/No-2-10/2010-02-06.pdf)
    * [Американские опционы](https://arxiv.org/pdf/1309.0110)

    Ожидаемый результат:
    * Реализовать код для численного решения двумерного УРЧП для европейских или американских опционов.
    * Исследовать области устойчивости и сходимости.
    * Исследовать разные способы задания неравномерных сеток
    * Сравнить с полуаналитической формулой.

4. Сравнение разных подходов к калибровке моделей стохастической-локальной волатильности.

    Статьи: ссылка на книгу Бергоми. Ссылки на статьи.

    Ожидаемый результат:
    * Реализация разных методов: УРЧП для плотности, метод частиц, regression-based Monte-Carlo. 
    * Сравнение качества калибровки разных методов на ванильных опционов
    * Сравнение цен экзотических опционов: американских, азиатских, forward-start options, барьерных.

5. Методы снижения дисперсии для AMC
    Статьи: 
    * [Variance Reduction](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4221136)
    * [Robust Regression MC](https://kups.ub.uni-koeln.de/4442/1/Diss_Jonen.pdf)

    Ожидаемый результат:
    * Реализация Control Variate для прайсинга американского опциона.
    * Реализация Importance sampling для прайсинга американского опциона, исследование оптимального дрифта.
    * Исследование эффекта снижения дисперсии.

6. Deep-hedging

    Статья:
    Ожидаемый результат:

7.  Прайсинг азиатских опционов: обзор разных методов. 

    Статьи:
    * [PDE methods overview](https://personal.ntu.edu.sg/nprivault/MA5182/asian-options.pdf)

    Ожидаемый результат:
    * Реализация методов на основе Monte-carlo и снижения дисперсии: MC, Moment Matching, Control Variate, Quasi MC.
    * Реализация методов на основе УРЧП через сведение к одномерному уравнению.
    * Сравнение разных способов. 


8. xVA. Differentiable machine learning

    Статьи: 
    * [LSM Reloaded - Differentiate xVA on your iPad Mini](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2966155)
    * [Differential Machine Learning](https://arxiv.org/abs/2005.02347)

    Ожидаемый результат:
    ...

9. American options, upper bounds
    Статьи: 
    * [Robust Regression MC](https://kups.ub.uni-koeln.de/4442/1/Diss_Jonen.pdf)

10. Прайсинг американского опциона через уравнение на границу экспирации.
    Статьи:
    * [Early exercise premium representation](https://engineering.nyu.edu/sites/default/files/2019-03/alternative-characterizations-of-american-put-options.pdf)
    * [Volterra equation for expiration boundary](https://arxiv.org/pdf/2502.00740)
    * https://hpcquantlib.wordpress.com/2022/10/09/high-performance-american-option-pricing/
    * https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2547027
