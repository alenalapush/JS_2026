# Условие: стрелочная функция вместо Function Expression

Замените код Function Expression стрелочной функцией:

```js
function ask(question, yes, no) {
  if (confirm(question)) yes();
  else no();
}

ask(
  'Вы согласны?',
  function () {
    alert('Вы согласились.');
  },
  function () {
    alert('Вы отменили выполнение.');
  }
);
```

## Ожидаемое поведение

- Пользователь нажал «Ок» → «Вы согласились.»
- Пользователь нажал «Отмена» → «Вы отменили выполнение.»
