### Parametry Rest
Parametry Rest (oznaczone przez `...argumentName` dla ostatniego argumentu) pozwalają szybko zaakceptować wiele argumentów w funkcji i uzyskać je jako tablicę. Pokazano to w poniższym przykładzie.

```ts
function iTakeItAll(first, second, ...allOthers) {
    console.log(allOthers);
}
iTakeItAll('foo', 'bar'); // []
iTakeItAll('foo', 'bar', 'bas', 'qux'); // ['bas','qux']
```

Parametry rest mogą być używane w dowolnej funkcji `function`/`()=>`/`class member`.
