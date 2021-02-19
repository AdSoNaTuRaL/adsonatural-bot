<div align="center">
   <h4>A Twitter bot that retweets each tweet given a search keyword/ hashtag </h4>
</div>

<div align="center">
  <sub>Follow me on
    <a href="https://twitter.com/adsonatural">
      Twitter
    </a>
  </sub>
</div>

<br />

<p align="center">Before running this application, you need to create a developer Twitter account; create an application and generate your credentials (keys and tokens)</p>

<br />

# :construction_worker: How to run
```bash
# Clone Repository
$ git clone https://github.com/AdSoNaTuRaL/adsonatural-bot.git
```
```bash
# Go to source folder
$ cd adsonatural-bot/src

# Rename config.example.js to config.js
$ mv config.example.js config.js

#  Open the config.js and fill it in with your credentials and save
```
```js
// Before running this project, put the word you want to search for
setInterval(function () {
  retweet('#PutYourKeywordHere OR #PutYourAnotherKeywordHere');
}, 60000)
```

```bash
# Return a folder
$ cd ..

# Install Dependencies
$ yarn

# Run Aplication
$ node src/bot.js
```

# :bug: Issues

Feel free to **file a new issue** with a respective title and description on the [adsonatural-bot](https://github.com/AdSoNaTuRaL/adsonatural-bot/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**!
