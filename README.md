# OAuth 2.0 - Chamada HTTP

> Dados para utilizar na autenticação do OAuth 2.0 para as APIS do Google

Esse projeto é destinado a todos as pessoas que já visitaram [meu vídeo no Youtube](https://youtu.be/Cwwd9iiMeQo) sobre como realizar chamada para recuperar "Access Token".

![](miniatura-video.png)

## Configuração

### Documentação da API Oauth 2.0:

https://developers.google.com/identity/protocols/oauth2/web-server

### Console Google para criar as credenciais: 

```sh
Lembre de selecionar o projeto correto
```

https://console.cloud.google.com/apis/credentials

### Playground OAuth 2.0 - Google: 

```sh
Esse link também será utilizado para utilizar como URI de redirecionamento na tela de consentimento
```

https://developers.google.com/oauthplayground

## Dados para a chamada HTTP

Para recuperar o "Access Token" gerado através de uma chamda HTTP para o serviço OAuth 2.0 da Google você precisa seguir esse passo-a-passo.

Lembre-se de sempre realizar a requisição com o método _POST_

```sh
POST https://accounts.google.com/o/oauth2/token
```

Alguns exemplos interessantes e úteis sobre como seu projeto pode ser utilizado. Adicione blocos de códigos e, se necessário, screenshots.

_Para mais exemplos, consulte a [Wiki][wiki]._ 

## Configuração para Desenvolvimento

Descreva como instalar todas as dependências para desenvolvimento e como rodar um test-suite automatizado de algum tipo. Se necessário, faça isso para múltiplas plataformas.

```sh
make install
npm test
```

## Histórico de lançamentos

* 0.2.1
    * MUDANÇA: Atualização de docs (código do módulo permanece inalterado)
* 0.2.0
    * MUDANÇA: Remove `setDefaultXYZ()`
    * ADD: Adiciona `init()`
* 0.1.1
    * CONSERTADO: Crash quando chama `baz()` (Obrigado @NomeDoContribuidorGeneroso!)
* 0.1.0
    * O primeiro lançamento adequado
    * MUDANÇA: Renomeia `foo()` para `bar()`
* 0.0.1
    * Trabalho em andamento

## Meta

Seu Nome – [@SeuNome](https://twitter.com/...) – SeuEmail@exemplo.com

Distribuído sob a licença XYZ. Veja `LICENSE` para mais informações.

[https://github.com/yourname/github-link](https://github.com/othonalberto/)

## Contributing

1. Faça o _fork_ do projeto (<https://github.com/yourname/yourproject/fork>)
2. Crie uma _branch_ para sua modificação (`git checkout -b feature/fooBar`)
3. Faça o _commit_ (`git commit -am 'Add some fooBar'`)
4. _Push_ (`git push origin feature/fooBar`)
5. Crie um novo _Pull Request_

[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/seunome/seuprojeto/wiki
