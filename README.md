# search-img-tags

[![Build Status](https://travis-ci.com/arshadkazmi42/search-a-tags.svg?branch=master)](https://travis-ci.com/arshadkazmi42/search-a-tags)

Search image urls from &lt;img> tag from any HTML content

## Install

```
npm install search-img-tags
```

## Usage

```javascript
const SearchImgTags = require('search-img-tags');

const HTML = '<img src="https://github.com/arshadkazmi42"><a></a><b>Test</b><a href="https://google.com" />Click Here</a><p>This is a paragraph</p><a target="_" href="arshadkazmi42"><img src="test.png" /><img target="_" src="/images/1.png">';

const links = SearchImgTags(HTML);
console.log(links);
// [
//   'https://google.com',
//   'arshadkazmi42'
// ]
```

## Contributing

Interested in contributing to this project?
You can log any issues or suggestion related to this library [here](https://github.com/arshadkazmi42/search-img-tags/issues/new)

Read our contributing [guide](CONTRIBUTING.md) on getting started with contributing to the codebase

## Contributors

Thank you to all the contributors who have helped us in making this project better :raised_hands:

<a href="https://github.com/arshadkazmi42"><img src="https://github.com/arshadkazmi42.png" width="30" /></a>
