# twitter-analyzer

Сентимент-анализ постов в Twitter об организации

## Фонд “Подари жизнь” - один из самых известных благотворительных фондов в России. 

Чтобы узнать, какой имидж у фонда в соцсетях, можно собрать все упоминания фонда в Twitter, проанализировать тональность высказываний и создать тематическую кластеризацию.

- **Data mining:** используем [tweepy](https://docs.tweepy.org/en/stable/)  
- **Sentiment-анализ:** выявляем эмоционально-окрашенную лексику в высказываниях о фонде  
- **Частотный анализ:** какие слова или понятия чаще всего упоминаются, когда люди пишут о фонде?  
- **Тематическая кластеризация:** о чем вообще пишут люди, говоря о фонде?  
- **Анализ реакций пользователей:** какие твиты о фонде собрали больше всего реакций (like/retweet)?  


В задаче можно использовать другие организации, например, из списка Forbes или из американского топа благотворительных организаций.


В зависимости от языка твитов могут использоваться разные библиотеки или ранее обученные модели.

Дополнительные ссылки:  
- Набор [Russian Language Toxic Comments Dataset](https://www.kaggle.com/blackmoon/russian-language-toxic-comments) представляет собой коллекцию аннотированных комментариев с сайтов Двач и Пикабу. Он опубликован на Kaggle в 2019-м и содержит 14 412 комментариев, из которых 4 826 помечены как токсичные, а 9 586 — как нетоксичные.  
- Другие [ссылки о токсичных комментариях](https://habr.com/ru/company/vk/blog/526268/) — Хабр  
- [Getting Started with Sentiment Analysis using Python](https://huggingface.co/blog/sentiment-analysis-python)  
- [Общедоступный тональный словарь PolSentiLex](http://www.linis-crowd.org/)  
- [Collect Data from Twitter: A Step-by-Step Implementation Using Tweepy](https://towardsdatascience.com/collect-data-from-twitter-a-step-by-step-implementation-using-tweepy-7526fff2cb31)  
