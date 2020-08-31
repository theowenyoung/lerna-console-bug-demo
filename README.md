# Lerna test

A `console.error('test')` bug with lerna

## How to reproduce

```bash
npm run build
```

You will only see:

```bash
test console.error start
test console.error end
```

expect:

```bash
test console.error start
test print error, but this will not be printed
test console.error end
```