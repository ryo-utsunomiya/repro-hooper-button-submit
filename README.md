# repro-hooper-button-submit

When hooper is used inside the form, hooper-indicator unintentionally submits form.

```
  <form method="get" action="">
    <hooper>
      <slide>
        slide 1
      </slide>
      <slide>
        slide 2
      </slide>
      <pagination slot="hooper-addons" />
    </hooper>
  </form>
```

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
