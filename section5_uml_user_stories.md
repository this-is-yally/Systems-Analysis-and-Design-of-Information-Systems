# Розділ 5. UML-нотація для User Stories

## Діаграма Use Case (UML)

```mermaid
%%{init: { "theme": "base", "themeVariables": { "actorBorder": "#000000" }}}%%
usecaseDiagram
    actor Бібліотекар as Librarian
    actor Читач as Reader
    actor Гість as Guest

    Librarian --> (Додати/редагувати книгу)
    Librarian --> (Зареєструвати читача)
    Librarian --> (Оформити видачу)
    Librarian --> (Оформити повернення)
    Librarian --> (Переглянути прострочення)

    Reader --> (Пошук книги)
    Reader --> (Забронювати книгу)
    Reader --> (Переглянути історію позик)

    Guest --> (Пошук книги)
```

> **Примітка:** діаграма вище відображає основні ролі та їхню взаємодію з системою.
