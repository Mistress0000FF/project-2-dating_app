# project-2-dating_app
Проект №2 выполнен на основе данных крупного приложения для знакомств.
Помимо базовых функций, в приложении также имеется премиум-подписка, которая дает доступ к ряду важных дополнительных возможностей. Был проведен A/B тест, в рамках которого для новых пользователей из нескольких стран была изменена стоимость премиум-подписки* при покупке через две новые платежные системы. При этом стоимость пробного периода оставалась прежней.
Проверим:
1. Был ли эксперимент успешен в целом.
2. Проанализируем, имеет ли нововведение смысл среди каких-либо конкретных групп пользователей.

В рамках проекта использовала библиотеки pandas, numpy, matplotlib.pyplot, plotly.express, seaborn, scipy, tqdm, pingouin.
Был проведен EDA, А1/А2 между двумя контрольными группами тест, а так же А1/Б и А2/Б тесты на метриках (ARPU, ARPPU) с помощью статистических тестов Левена, Шапиро-Уилка, а также с помощью метода Anova.
