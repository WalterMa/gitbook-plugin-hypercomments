# HyperComments2 widget for GitBook

Forked from [akulov/gitbook-plugin-hypercomments](https://github.com/akulov/gitbook-plugin-hypercomments).Seems original author is no longer maintained since 2016.

This is a plugin for GitBook since version 2.3.0.

It integrates a [HyperComments](https://www.hypercomments.com/) widget into you book.

![Image](https://raw.githubusercontent.com/WalterMa/gitbook-plugin-hypercomments2/master/preview.png)

## Usage

Add the plugin to your book's configuration `book.json` and set `wid` required option.

`wid` - HyperComments widget ID (you create a `wid` for HyperComments by adding a new website on the [HyperComments](https://www.hypercomments.com/) website)

```js
{
    "plugins": [
        "hypercomments2"
    ],
    "pluginsConfig": {
        "hypercomments2": {
            "wid": XXXXX
        }
    }
}
```

`lang` - set widget language for all books languages. Additional option. By defaults - current book language.

Аfter configuring `book.json`, run `gitbook install` to install all added plugins.

## Links

This plugin on [github.com](https://github.com/WalterMa/gitbook-plugin-hypercomments2), [plugins.gitbook.com](https://plugins.gitbook.com/plugin/hypercomments2), [npmjs.com](https://www.npmjs.com/package/gitbook-plugin-hypercomments2)