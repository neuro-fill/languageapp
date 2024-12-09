# Language Learning Voice Assistant
Чат-бот для тренировки иностранного языка

### Задача:
Облегчить изучение иностранных языков, предоставляя пользователям возможность тренироваться в произношении и общении с помощью голосового помощника.

### Что сделано:
* Интеграция модели распознавания речи OpenAI Whisper для точного анализа речи.
* Разработка алгоритма оценки произношения на основе ключевых слов и ошибок в речи.
* Веб-интерфейс с Flask, где пользователь может общаться с ботом, а также получать текстовые и голосовые рекомендации.
* Генерация обратной связи с помощью gTTS (Google Text-to-Speech).
  
### Использованные технологии:
* OpenAI Whisper для точного распознавания речи.
* Flask для создания лёгкого и доступного веб-приложения.
* gTTS для генерации голосовых ответов, чтобы пользователь мог получать рекомендации не только текстом, но и звуком.
 Выбор технологий обусловлен необходимостью высокоточной обработки речи и возможностью быстрого прототипирования.

### Результат:
Рабочий прототип, который позволяет пользователю тренировать произношение, отвечать на вопросы и получать рекомендации. Тестирование показало, что бот помогает улучшить понимание языка и корректировать ошибки.

### Команды:
* Установка зависимостей: pip install -r requirements.txt
* Запуск сервера: flask run
* Распознавание речи из аудиофайла: python recognize.py input_audio.wav
