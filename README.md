# Yes-or-No
Если Затрудняетесь с выбором переходите по ссылке
https://github.com/dima41204120-commits/Yes-or-No
<!doctype html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Да или Нет</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <main class="app">
      <section id="question-screen" class="question-screen">
        <h1 class="title">Задай вопрос</h1>
        <p class="subtitle">Получи честный ответ: да или нет</p>
        <form id="question-form" class="question-form" novalidate>
          <input
            id="question-input"
            class="question-input"
            type="text"
            placeholder="Например: Получится ли сегодня?"
            autocomplete="off"
            maxlength="180"
          />
          <button id="ask-button" class="ask-button" type="submit">Задать</button>
        </form>
        <p id="error-text" class="error-text" aria-live="polite"></p>
      </section>

      <section id="result-screen" class="result-screen hidden" aria-live="polite">
        <button id="back-button" class="back-button" type="button">Назад</button>
        <img id="result-gif" class="result-gif" src="" alt="Ответ" />
        <h2 id="result-text" class="result-text"></h2>
        <button id="new-question-button" class="new-question-button" type="button">
          Задать новый вопрос
        </button>
      </section>
    </main>

    <script src="script.js"></script>
  </body>
</html>
