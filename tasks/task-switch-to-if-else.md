# Условие: если..иначе вместо switch

Напишите `if..else`, соответствующий следующему `switch`:

```js
switch (browser) {
  case 'Edge':
    alert("You've got the Edge!");
    break;

  case 'Chrome':
  case 'Firefox':
  case 'Safari':
  case 'Opera':
    alert('Okay we support these browsers too');
    break;

  default:
    alert('We hope that this page looks ok!');
}
```

## Ожидаемое поведение

| Значение `browser`                             | Результат                            |
| ---------------------------------------------- | ------------------------------------ |
| `'Edge'`                                       | «You've got the Edge!»               |
| `'Chrome'`, `'Firefox'`, `'Safari'`, `'Opera'` | «Okay we support these browsers too» |
| любое другое значение                          | «We hope that this page looks ok!»   |
