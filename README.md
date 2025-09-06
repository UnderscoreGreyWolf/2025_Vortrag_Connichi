# Build me

## Build presentation (PDF)

```sh
npx @marp-team/marp-cli@latest  --theme ./style/dracula.css ./presentation.md -o presentation.pdf --allow-local-files --pdf-notes --pdf-outline
```

## Build presentation (HTML)

```sh
npx @marp-team/marp-cli@latest  --theme ./style/dracula.css ./presentation.md -o presentation.html --allow-local-files
```

## Build qrcodes

```sh
npx qrcode -o selfsuspend_safety.png "https://www.selfsuspend.com/safety"
```
