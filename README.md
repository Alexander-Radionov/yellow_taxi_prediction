# yellow_taxi_prediction
Проект в рамках завершающего курса специализации ["Машинное обучение и анализ данных"](https://www.coursera.org/specializations/machine-learning-data-analysis).
На github собраны только файлы, необходимые для получения конечного результата. Промежуточные решения отсутствуют.
## Назначение
Репозиторий создан в демонстрационных целях: демонстрации применённых решений, стиля написания кода и прочего.

## Важно: об исходных данных
Поскольку файлы с необходимыми исходными данными весят почти 7 гб, их не будет непосредственно в проекте. Эти файлы всегда можно найти по [ссылке](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml).

Скачивание:
Внизу страницы жёлтая таблица под именем Trip Sheet Data (CSV Format). Выбрать **2016** год, затем из столбца **Yellow** выбрать месяцы:
* March
* April
* May
* June
Для запуска кода файлы необходимо положить в **папку Data**

## Библиотеки
Для выполнения кода (кроме демо) понадобится установка следующих библиотек:
* [pandas](https://pandas.pydata.org/) (version 0.20.3)
* [numpy](http://www.numpy.org/) (version 1.13.1)
* [sklearn](http://scikit-learn.org/stable/) (version 0.19.0)

Дополнительно для выполнения демо:
* [xarray](http://xarray.pydata.org/en/stable/) (version 0.10.0)
* [ipywidgets](https://ipywidgets.readthedocs.io/en/stable/)
* [holoviews](http://holoviews.org/) (version 1.9.2-x-g94abb1bdb)
* [geoviews](http://geo.holoviews.org/) (version 1.4.2)
* [geopandas](http://geopandas.org/) (version 0.3.0)

Консольные команды для установки можно получить на anaconda.org. Проще всего - при помощи поискового запроса "conda libName", где libName - имя библиотеки.

## Платформа
Весь проект создавался на Windows 7 через Anaconda. Для работы демо необходимо, чтобы Jupyter Notebook был 5.0+ версии (возможно, его придётся обновить отдельно).
