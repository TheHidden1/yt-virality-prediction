# Опис на проектот 📋
YouTube AI Virality Predictor е AI систем за предвидување на виралност што користи машинско учење за да анализира дали едно YouTube видео ќе стане вирално. Системот комбинира податоци од YouTube API со напредни алгоритми за да даде точни предвидувања со детални објаснувања.

# Клучни функционалности 🎯
* Автоматско собирање податоци од YouTube API

* 19 различни карактеристики за анализа на видеа

* Ансамбл машинско учење со Random Forest, Gradient Boosting и Logistic Regression

* Sentiment анализа на коментари користејќи VADER и TextBlob

* Интерактивни визуелизации со matplotlib и seaborn

* Model persistence за зачувување и вчитување на истрениран модел

* Confidence scoring за сигурност на предвидувањата

# Технички карактеристики 🛠️
## Архитектура
* Модуларна архитектура со одделни компоненти за секоја функционалност

* Ensemble learning со три ML алгоритми (Random Forest, Gradient Boosting, Logistic Regression)

* YouTube Data API v3 интеграција за real-time податоци

# Инсталација 📦
## Потребни библиотеки
```pip install google-api-python-client pandas numpy matplotlib seaborn
pip install scikit-learn textblob nltk transformers
python -m nltk.downloader vader_lexicon
```
## YouTube API Setup
1. Одете на Google Cloud Console

2. Создајте нов проект или изберете постоечки

3. Активирајте го YouTube Data API v3

4. Генерирајте API клуч
