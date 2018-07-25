


## Install Karma Plugins

`npm i -D karma-spec-reporter karma-notify-reporter`


### Altere o karma.conf.js


- Adicionando os plugins

```js
plugins: [
      require('karma-jasmine'),
      require('karma-chrome-launcher'),
      require('karma-jasmine-html-reporter'),
      require('karma-coverage-istanbul-reporter'),
      require('@angular-devkit/build-angular/plugins/karma'),
      require('karma-spec-reporter'),
      require('karma-notify-reporter')
    ]
```

- e configurando os reporters

```js
reporters: ['spec', 'notify', 'kjhtml'],
```

## Configurar task para execução de testes (Opcional)

## Configurar o launch para anexar debug ao ChromeHeadless

## Iniciar e aguard execução dos testes

## Lançar o `Karma Tests` para executar debug integrando VSCode e o ChromeHeadles que está executando os testes
