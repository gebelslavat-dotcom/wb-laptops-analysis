# Competitive Analysis: Laptop Market on Wildberries 2026 - Wildberries Ноутбуки: анализ рынка и конкуренции 

## 📌 О проекте
Анализ конкурентной среды в категории "Ноутбуки" на маркетплейсе Wildberries.
Данные собраны через WB API — июнь 2026, 1 400 товаров.

## 🎯 Цель
Понять структуру рынка ноутбуков на WB — для нового поставщика,
который хочет выйти на площадку и оценить конкуренцию.

## 🔍 Исследовательские вопросы
- Q1: What is the price distribution? — Как распределены цены?
- Q2: Which brands dominate? — Какие бренды доминируют?
- Q3: Which brands offer the biggest discounts? — Кто даёт самые большие скидки?
- Q4: Does discount correlate with feedbacks? — Скидка связана с отзывами?
- Q5: Which price segments are most competitive? — Какой сегмент самый конкурентный?
- Q6: Do higher-rated products cost more? — Дорогие товары имеют рейтинг выше?
- Q7: What % of products have no reviews? — Сколько товаров без отзывов?
- Q8: Which suppliers have the most listings? — Какие поставщики лидируют?

## 🔑 Ключевые выводы
- Asus доминирует с 18.6% — в 2.2x больше Apple на втором месте
- Самый конкурентный сегмент — 30-60к (31.2% всех товаров)
- Скидки и рейтинги слабо связаны с ценой — покупатели выбирают по другим критериям
- 37% товаров без отзывов — рынок активно пополняется новыми позициями
- Рынок поставщиков фрагментированный — лидер WB занимает только 6.6%

## 🛠️ Технологии
| Инструмент | Применение |
|------------|-----------|
| Python | Сбор и анализ данных |
| requests | Работа с WB API |
| pandas | Обработка данных |
| matplotlib | Визуализация |
| Jupyter Notebook | Среда разработки |

## 📁 Структура репозитория
| Файл | Описание |
|------|---------|
| `wb-laptops-analysis.ipynb` | Основной ноутбук с анализом |
| `wb_notebooks_v2.csv` | Датасет (1 400 товаров) |
| `price_distribution.png` | Распределение цен |
| `brand_dominance.png` | Доминирование брендов |
| `brand_discounts.png` | Скидки по брендам |
| `discount_from_feedbacks.png` | Скидка vs Отзывы |
| `price_sale_from_review_rating.png` | Цена vs Рейтинг |
| `top_segment.png` | Конкурентность сегментов |
| `supplier_dominance.png` | Топ поставщиков |

## 🔗 Источник данных
Wildberries Internal API — категория "Ноутбуки" (subjectId=2290)

## 👤 Автор
Вячеслав Тихомиров (Гебель) — BI / Data Analyst
📧 gebel@internet.ru | Telegram: @gebel_slava
🔗 [GitHub портфолио](https://github.com/gebelslavat-dotcom)
