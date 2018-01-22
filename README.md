## TO DO:
- social card
- README marketing
- footer

## Installing vendor

```bash
$ bower install
```

## Render CSS

```bash
$ sass _src/scss/styles.scss assets/css/styles.css
```

__For work in progress, use Sass pre-processor.__

```bash
$ sass --watch _src/scss/styles.scss:assets/css/styles.css
```

__Must write:__
- new css code below the import lines in the styles.scss file imperatively
- new variable code above the import lines in the styles.scss file imperatively

__When changed are final, put:__
- variable code into variables.scss
- css code into custom.scss
