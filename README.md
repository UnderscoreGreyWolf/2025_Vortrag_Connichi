# Build me

## Build presentation (PDF)

```sh
npx @marp-team/marp-cli@latest  --theme ./style/dracula.css ./presentation.md -o presentation.pdf --pdf-notes --pdf-outline
```

## Build presentation (HTML)

```sh
npx @marp-team/marp-cli@latest  --theme ./style/dracula.css ./presentation.md -o presentation.html
```

## Build qrcodes

```sh
npx qrcode -o selfsuspend_safety.png "https://www.selfsuspend.com/safety"
```
