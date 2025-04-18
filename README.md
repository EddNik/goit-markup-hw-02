# 📍 Модуль 1: Основи HTML

## goit-hw-02

## 🔹 1. (hierarchical structure) або деревоподібна структура (tree structure)

- ✅ Дочірні – безпосередньо вкладені.
- ✅ Нащадки – всі вкладені (не тільки дочірні).
- ✅ Сестринські – мають спільного батька.
- ✅ Батьківські – безпосередній контейнер.
- ✅ Предки – всі батьківські елементи вгору по дереву.

### HTML-розмітка макета сторінки домашнього завдання #1, без CSS

- 🇫
  [Figma model](<https://www.figma.com/design/wuEpGhwCepGCOUw7mZFRac/Web-Studio-(Version-5.0)?node-id=0-1&p=f&t=dqyl1qIESvdDCWUJ-0>)

  ## 🔹 2. Структура HTML

  ### 📌 Основні елементи:

- **Структура документа**
- **Теги та атрибути:**

  - Типи тегів: текстові, посилання, списки, таблиці, блоки
  - Семантичні теги та доступність: `<header>`, `<main>`, `<footer>`, `<nav>`, `<aside>`
  - Парні та одинокі теги
  - DOM: батьківські, дочірні, нащадки, предки, сестринські елементи
  - Атрибути тегів

  ## 🔹 3. Графіка

- **Растрова та векторна графіка**

---

## 🔹 4. Структурні теги

| Тег      | Опис                    |
| -------- | ----------------------- |
| `<html>` | Кореневий тег документа |
| `<head>` | Метаінформація сторінки |
| `<body>` | Вміст сторінки          |

---

## 🔹 5. Заголовки та текст

| Тег             | Опис                    |
| --------------- | ----------------------- |
| `<h1>` – `<h6>` | Заголовки різних рівнів |
| `<p>`           | Абзац тексту            |
| `<span>`        | Рядковий контейнер      |
| `<div>`         | Блочний контейнер       |
| `<strong>`      | Жирний текст            |
| `<em>`          | Курсивний текст         |
| `<br>`          | Перенесення рядка       |
| `<hr>`          | Горизонтальна лінія     |

---

## 🔹 6. Списки

| Тег    | Опис                 |
| ------ | -------------------- |
| `<ul>` | Ненумерований список |
| `<ol>` | Нумерований список   |
| `<li>` | Пункт списку         |

---

## 🔹 7. Таблиці

| Тег       | Опис              |
| --------- | ----------------- |
| `<table>` | Таблиця           |
| `<tr>`    | Рядок таблиці     |
| `<td>`    | Комірка таблиці   |
| `<th>`    | Заголовок комірки |

---

## 🔹 8. Форми

| Тег          | Опис               |
| ------------ | ------------------ |
| `<form>`     | Форма введення     |
| `<input>`    | Поле введення      |
| `<textarea>` | Багаторядкове поле |
| `<button>`   | Кнопка             |
| `<label>`    | Мітка для введення |
| `<select>`   | Випадаючий список  |
| `<option>`   | Варіант у списку   |

---

## 🔹 9. Посилання та зображення

| Тег     | Опис           |
| ------- | -------------- |
| `<a>`   | Гіперпосилання |
| `<img>` | Зображення     |

---

## 🔹 10. Семантичні теги

| Тег         | Опис                     |
| ----------- | ------------------------ |
| `<header>`  | Заголовок секції         |
| `<nav>`     | Навігаційне меню         |
| `<section>` | Розділ сторінки          |
| `<article>` | Незалежний блок контенту |
| `<aside>`   | Додаткова інформація     |
| `<footer>`  | Нижній колонтитул        |

---

## 🔹 11. Скрипти та стилі

| Тег        | Опис               |
| ---------- | ------------------ |
| `<script>` | JavaScript-код     |
| `<link>`   | Підключення стилів |
| `<style>`  | CSS-стилі          |

---

## 🔹 12. Підключення стилів

- Вбудований (inline styles)
- Внутрішній (internal styles)
- Зовнішній (external styles)

## 🔹 13. Селектори CSS

| Селектор       | Приклад                                 | Опис                                                    |
| -------------- | --------------------------------------- | ------------------------------------------------------- |
| Тега           | `p {}`                                  | Застосовує стилі до всіх `<p>`                          |
| Тега           | `h1 { color: blue; }`                   | Застосовує стилі до всіх `<h1>`                         |
| Класу          | `.title {}`                             | Застосовує стилі до елементів з `class="title"`         |
| Класу          | `.red-text { color: red; }`             | Застосовує стилі до всіх елементів з `class="red-text"` |
| Ідентифікатора | `#main {}`                              | Застосовує стилі до елемента з `id="main"`              |
| Ідентифікатора | `#header { color: green; }`             | Застосовує стилі до елемента з `id="header"`            |
| Атрибута       | `[type="text"] {}`                      | Стилізує всі `<input type="text">`                      |
| Атрибута       | `a[target="_blank"] { color: purple; }` | Стилізує всі посилання, що відкриваються в новому вікні |
| Нащадка        | `div p {}`                              | Стилізує `<p>`, які знаходяться в `<div>`               |
| Дитини         | `div > p {}`                            | Стилізує `<p>`, які є тільки першими дітьми `<div>`     |

## 🔹 14. Псевдокласи стану

| Псевдоклас               | Опис                                                         |
| ------------------------ | ------------------------------------------------------------ |
| `:hover`                 | Застосовується при наведенні миші                            |
| `:focus`                 | Коли елемент у фокусі (наприклад, у полі вводу)              |
| `:first-child`           | Перший дочірній елемент                                      |
| `:last-child`            | Останній дочірній елемент                                    |
| `:nth-child(odd/even/n)` | Вибирає елементи за номером (парні, непарні або за індексом) |

## 🔹 15. Колір тексту

| Назва кольору          | Формат      | Значення                       |
| ---------------------- | ----------- | ------------------------------ |
| 🔹 Червоний            | CSS `color` | `color: red;`                  |
| 🎨 HEX-код             | HEX         | `color: #ff0000;`              |
| 🎭 RGB                 | RGB         | `color: rgb(255, 0, 0);`       |
| 🌈 RGBA (з прозорістю) | RGBA        | `color: rgba(255, 0, 0, 0.5);` |
| 🔥 HSL                 | HSL         | `color: hsl(0, 100%, 50%);`    |

## 🔹 16. Каскад, пріоритетність, спадкування

### Каскад

| Опис                              | CSS правила                                                           |
| --------------------------------- | --------------------------------------------------------------------- |
| Правила для кольору тексту        | `p { color: red; }`                                                   |
| Перезапис правил, останнє спрацює | `p { color: blue; }` /_ Спрацює останнє правило → текст буде синім _/ |

### Пріоритетність

| Порядок застосування   | Тип селектора           | Опис                                                  |
| ---------------------- | ----------------------- | ----------------------------------------------------- |
| 1. Найвищий пріоритет  | Inline-стилі (style="") | Стилі, задані безпосередньо в HTML-елементі           |
| 2. Вищий пріоритет     | ID-селектор (#id)       | Стилі, задані за допомогою унікальних ідентифікаторів |
| 3. Середній пріоритет  | Клас (.class)           | Стилі, задані через класи елементів                   |
| 4. Найнижчий пріоритет | Тег (h1, p, div тощо)   | Стилі, задані через HTML теги                         |

## 🔹 17. Спадкування

- Деякі властивості (наприклад, color, font-family) успадковуються від батьківських елементів, інші
  (border, margin, padding) — ні.

## 🔹 18. CSS змінні

| Опис                          | CSS код                                                        |
| ----------------------------- | -------------------------------------------------------------- |
| Оголошення змінних у `:root`  | `:root { --main-color: blue; --font-size: 16px; }`             |
| Використання змінних у стилях | `p { color: var(--main-color); font-size: var(--font-size); }` |

---

## 🧷 Додаткові ресурси 📚

- 🖼 [Remove.bg](https://www.remove.bg/) – сервіс для видалення фону із зображень
- 🛠 [iLoveIMG](https://www.iloveimg.com/) – інструменти для обробки зображень
- ✅ [W3C Validator](https://validator.w3.org/) – перевірка HTML-коду на помилки
- 📖 [MDN HTML Docs](https://developer.mozilla.org/en-US/docs/Web/HTML) – офіційна документація HTML

- 🖼 [toptal.com](https://www.toptal.com/designers/htmlarrows/symbols/) – спеціальні символи
- 🛠 [Caninclude](https://caninclude.glitch.me/) – чи можу вкласти тег в інший тег
- 📖 [Emmet commands](https://docs.emmet.io/cheat-sheet/) – швидкі команди emmet
- 📖 [MDN HTML Docs](https://developer.mozilla.org/en-US/docs/Web/HTML) – офіційна документація

- 🛠 [Squoosh](https://squoosh.app/) – Оптимізація картинок (jpeg)
- 🛠 [Tiny PNG](https://tinypng.com/) – Оптимізація картинок (png)

- 📖
  [Figma Template](https://www.figma.com/design/LWMTodUscRGMcbTpxE3kgI/Simply-Chocolate?node-id=1-5060&t=FZ9D8VYSe7z6EkSG-0)
  – Figma
