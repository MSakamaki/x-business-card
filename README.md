# &lt;x-business-card&gt;

> A bare minimum custom element starter-kit using [VanillaJS](http://vanilla-js.com/).
>
> Like [Yeoman](http://yeoman.io/)? Use the [generator-element](https://www.npmjs.org/package/generator-element) instead.
>
> Looking for a working example? Check [hello-world-element](https://github.com/webcomponents/hello-world-element).

## Demo

[Check it live!](http://mitsuruog.github.io/x-business-card)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install x-business-card --save
```

Or [download as ZIP](https://github.com/mitsuruog/x-business-card/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/x-business-card/src/my-element.html">
    ```

3. Start using it!

    ```html
    <my-element></my-element>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`foo`         | *string*    | `bar`        | Lorem ipsum dolor.

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`unicorn()`   | None.        | Nothing.    | Magic stuff appears.

## Events

Event         | Description
---           | ---
`onsomething` | Triggers when something happens.

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/mitsuruog/x-business-card/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
