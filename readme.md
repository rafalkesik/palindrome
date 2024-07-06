<h1>Phrase object (with palindrome detector)</h1>

This is a sample NPM module created in Learn Enough JavaScript to Be Dangerous by Michael Hartl.

The module can be used as follows:


    $ npm install --global mhartl-palindrome
    $ vim test.js
    let Phrase = require("mhartl-palindrome");
    let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
    console.log(napoleonsLament.palindrome());
    $ node test.js
    true
