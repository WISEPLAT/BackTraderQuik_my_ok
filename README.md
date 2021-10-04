# BackTraderQuik
Провайдер для автоторговли в BackTrader из Quik. Использует библиотеку [QuikPy](https://github.com/cia76/QuikPy).

### Для чего нужен
Чтобы торговые системы, написанные для BackTrader, можно было поставить на автоматическую торговлю в Quik.

### Установка провайдера
1. Скопируйте файлы проекта в папку с торговой системой BackTrader

### Начало работы
В папке DataExamples находится хорошо документированный код примеров по работе с биржевыми данными из Quik. С них лучше начать разбираться с библиотекой.

1. **Symbol.py** - Получение данных одного тикера по одному временнОму интервалу.
2. **Symbols.py** - Получение данных нескольких тикеров по одному временнОму интервалу. [Разбор кода >>>](https://finlab.vip/symbolspy/)
3. **Timeframes.py** - Получение данных одного тикера по разным временнЫм интервалам методом прямой загрузки.
4. **Resample.py** - Получение данных одного тикера по разным временным интервалом методом конвертации меньшего временнОго интевала в больший (Resample).
5. **Replay.py** - Точное тестирование большего временного интервала с использованием меньшего.
6. **Rollover.py** - Склейка фьючерсов

В папке BrokerExamples находится хорошо документированный код примеров по работе со счетами, заявками и позициями из Quik.

1. **LiveTradingEvents.py** - Перехват событий Quik
2. **LimitCancel.py** - Выставление и отмена заявок

### Авторство и право использования
Автор данной библиотеки Чечет Игорь Александрович. Библиотека написана в рамках проекта [Финансовая Лаборатория](https://finlab.vip/) и предоставляется бесплатно. При распространении ссылка на автора и проект обязательны.

### Что дальше
Исправление ошибок, доработка и развитие библиотеки осуществляется автором и сообществом проекта [Финансовая Лаборатория](https://finlab.vip/).