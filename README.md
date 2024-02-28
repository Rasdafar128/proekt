# Классификация рентгена лёгких с помощью Нейронных сетей
В распоряжении был датасет с изображениями рентгена грудной клетки, включая:
- изображения с COVID-19
- изображения с инфекциями, не связанными с COVID-19 (вирусная или бактериальная пневмония)
- изображения здоровой грудной клетки


Размер обучающей выборки (train) - 27 тысяч изображений, тестовой выборки (test) - 7 тысяч изображений.
Необходимо классифицировать картинки на 3 этих типа.
Код содержит предобработку картинок, написание функций обучения и валидации нейронной сети, а также сохранение результатов предсказаний в файл.

1) Постановка проблемы

Традиционная интерпретация рентгеновских снимков рентгенологами может быть субъективной и подверженной ошибкам, особенно в случаях, когда требуется высокая точность диагностики. Автоматизированные системы распознавания заболеваний на рентгеновских снимках с использованием нейронных сетей могут значительно улучшить этот процесс, повысив точность и эффективность диагностики.

2) Актуальность и значимость темы проекта

Актуальность:

Высокая частота использования рентгенографии в медицинской практике.
Необходимость в точной и своевременной диагностике заболеваний.
Потребность в автоматизированных системах для повышения эффективности и снижения субъективности интерпретации рентгеновских снимков.
Значимость:

Повышение точности диагностики заболеваний, что приводит к более эффективному лечению и улучшению результатов для пациентов.
Сокращение времени и усилий, необходимых для интерпретации рентгеновских снимков, что позволяет рентгенологам сосредоточиться на более сложных случаях.
Повышение доступности диагностических услуг в отдаленных районах, где может отсутствовать квалифицированный медицинский персонал.
Создание новых возможностей для исследований и разработки новых методов диагностики и лечения заболеваний.
3) Полезность и востребованность продукта

Полезность: Автоматизированная система распознавания заболеваний на рентгеновских снимках может повысить точность и эффективность диагностики, сократить время и усилия, необходимые для интерпретации снимков, и повысить доступность диагностических услуг.
Востребованность: Растущая потребность в точной и своевременной диагностике заболеваний, а также необходимость в автоматизированных системах для повышения эффективности и снижения субъективности интерпретации рентгеновских снимков создают высокий спрос на подобные продукты.
4) Анализ аналогичных технологических решений

Существуют различные аналогичные технологические решения, которые используют нейронные сети для распознавания заболеваний на рентгеновских снимках. К ним относятся:

Google AI Platform: Платформа машинного обучения, которая предоставляет инструменты и инфраструктуру для разработки и развертывания моделей нейронных сетей для медицинской диагностики.
IBM Watson Health: Набор облачных сервисов и приложений, которые используют искусственный интеллект для улучшения здравоохранения, включая решения для анализа медицинских изображений.
Arterys: Компания, которая предоставляет облачную платформу для анализа медицинских изображений, включая рентгеновские снимки, с использованием нейронных сетей.
Эти решения демонстрируют потенциал нейронных сетей для улучшения диагностики заболеваний на рентгеновских снимках. Однако, существует необходимость в дальнейших исследованиях и разработках для повышения точности и надежности этих систем, а также для обеспечения их интеграции в клиническую практику.
