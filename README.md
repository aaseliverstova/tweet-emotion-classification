# tweet-emotion-classification
Проект по многоклассовой классификации эмоций в текстах твитов с использованием различных методов машинного обучения.
## Данные
Набор данных содержит 40,000 твитов с 13 различными эмоциональными метками:
- anger, boredom, empty, enthusiasm, fun, happiness, hate, love, neutral, relief, sadness, surprise, worry

## Методы предобработки текста
1. С учетом регистра
2. Нижний регистр
3. Без стоп-слов
4. Специфичные слова для классов
5. Уникальные слова

## Модели машинного обучения
- Random Forest
- Logistic Regression
- SVM (LinearSVC)
- Naive Bayes (MultinomialNB)

## Результаты
Лучшие результаты показала Logistic Regression с предобработкой "Нижний регистр":
- Accuracy: 0.3449
- F1-score: 0.3183

## Установка и запуск

```bash
# Клонирование репозитория
git clone https://github.com/aaseliverstova/tweet-emotion-classification.git

# Переход в папку проекта
cd tweet-emotion-classification

# Запуск ноутбука
jupyter notebook notebooks/tweet-emotion-classification.ipynb
