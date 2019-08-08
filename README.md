# WordHunter

## WordHunter is now live on https://wordhunter.niweera.gq

> WordHunter lets you to find the words for the letters you have when you are playing Scrabble.

The following is the basic architecture of the WordHunter application. (The web application will use the WordHunter-api to get the results according to the letters that the user has given.)




![](https://raw.githubusercontent.com/Niweera/wordhunter-api/master/w.png)

### Example use case

User wants to find words which can be created from `a, o, n, t`

The WordHunter service will provide the following results.
1. nato - North Atlantic Treaty Organization.

(The initial version would only give the words which contains all the letters. Later versions would provide all the letter combinations.)

![](wh.gif)

## Meta

Nipuna Weerasekara – [@Niweera](https://twitter.com/Niweera) – w.nipuna@gmail.com

Distributed under the MIT license. See ``LICENSE`` for more information.

[https://github.com/Niweera/wordhunter](https://github.com/Niweera/wordhunter)

The back-end for this application is in [wordhunter-api](https://github.com/Niweera/wordhunter-api) repo.

This repo is a part of `WordHunter` project.

`WordHunter` uses [GoogleDict](https://dict.niweera.gq) Dictionary API service. Find its repo [here](https://github.com/Niweera/googledict).

## Contributing

1. Fork it (<https://github.com/Niweera/wordhunter/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki

## Acknowledgement

Without the gigantic help from this guy [koolify](https://github.com/koolify), the development of WordHunter would be impossible...

