Полезный случай использования `aria-labelledby` — лейблы к [`<section>`](/html/section/). Благодаря лейблам пользователи скринридеров могут использовать целые секции как оглавление и быстро перемещаться между ними.

```html
<section aria-labelledby="heading">
  <h2 id="heading">Котики как вид</h2>
  <!-- Текст про котиков -->
</section>
```