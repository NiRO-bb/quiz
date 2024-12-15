# quiz
"Сервис для создания викторины"
Проект представляет из себя REST-сервис для создания викторины и ее проведения.
Список запросов:
1. Получить список всех сохраненных вопросов - GET http://localhost:8080/projects/api/quizzes
2. Получить вопрос по id - GET http://localhost:8080/projects/api/quizzes/{id вопроса}
3. Дать ответ на вопрос - POST http://localhost:8080/projects/api/quizzes/{id вопроса}/solve?answer={ваш ответ}
4. Добавить новый вопрос - POST http://localhost:8080/projects/api/quizzes
   
Выполнено в качестве лабораторной работы по дисциплине "Архитектура информационных систем". 
