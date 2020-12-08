# Whitelabel - React Native

Estrutura para desenvolvimento de aplicatios whitelabel, utilizando o framework React Native.

### Estrutura

Dillinger uses a number of open source projects to work properly:

```
├── build                   # Aplicativos gerados
├── docs                    # Documentation files (alternatively `doc`)
├── profiles                # Informações sobre os apps
├── wl-app                  # Projeto padrão para o desenvolvimento
├── wl-engine               # Reponsável por gerar e preparar os apps
└── README.md
```

### Gerando um novo app

Necessário ter instalado o [Node.js](https://nodejs.org/) .

Obs: É necessário que os icones e as informações básicas do app, estejam na pasta com o nome do app a ser gerado, dentro de profiles

```sh
$ node ./index.js build -c ../profiles/lugano/config.json -s ../wl-app -d ../build/visit-lugano
```

## License

MIT

**Bora dale!**
