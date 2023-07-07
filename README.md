# Тестове завдання на позицію QA manual engineer 

Завдання бажано писати в Google docs / spreadsheet. Переконайтеся що документ має доступ за посиланням (налаштування 

## Завдання
**1.** Треба протестувати наступну вимогу: сайт не має бути доступним в США та Канаді. Як ви це будете робити?

**2.** Є лендінг який продає послуги страхування і лід-форма на ньому. Розпишіть яким має бути юзер флоу (наприклад яка має бути поведінка форми і на що ви би звернули увагу під час тестування)

**3.** У користувача 5 спроб увійти на сайт (однакові комбінації логіна та пароля), з них 4 невдалі і тільки одна вдала. Логов сервера немає. Як би ви розслідували цей баг і на що б звернули увагу?

**4.** Протестуйте форму реєстрації (напишіть тест кейси або чеклист) - https://mir-s3-cdn-cf.behance.net/project_modules/max_3840/9bc6cc174021499.649aa3db858f3.jpg

## Як відправити нам результат роботи

Використовуючи інструмент такий як Postman або інші - відправити POST запит на наступний ендпоінт

```plaintext
https://api.byteplex.info/api/test/contact/
```

Приклад JSON формату який необхідно відправити

```plaintext
{
    "name": "",
    "email": "",
    "message": ""
}
```

Відправте ваші імʼя, імейл і в полі message посилання на результат вашого тестового завадання з коментарями
