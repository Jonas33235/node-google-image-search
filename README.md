[![build status](https://secure.travis-ci.org/Filirom1/node-google-image-search.png)](http://travis-ci.org/Filirom1/node-google-image-search)
Node Google Image Search
========================

Get images from Google Image as simply as a CLI :

    $ google-image-search logo google > google.jpg


Or programmatically in nodeJs:

    var giSearch = require('google-image-search');
    giSearch('logo google').pipe(fs.createWriteStream('google.jpg'));


LICENSE
-------

MIT
