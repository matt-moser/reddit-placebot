# Reddit Place Bot

Follow discussion on [/r/iastate](https://www.reddit.com/r/iastate/comments/62xpsa/everyone_go_to_rplace_and_support_isu/)

Here's the current logo we're working towards:
![less aggressive logo](https://raw.githubusercontent.com/matt-moser/placebot-isu-target/master/reference.jpg)


## Installation

You need to have [NodeJS installed](https://nodejs.org)

```
git clone https://github.com/matt-moser/reddit-place-bot
cd reddit-place-bot
npm install
```

## Configuration

Change `users.example.json` to `users.json` and add your username and password
of your account and all your throwaways.


## Usage

```
  npm run start
```

It'll keep keep drawing forever and if it can't draw anymore it's gonna
wait until something breaks and fix it.

## Similar Projects

Thanks to [Zequez](https://github.com/Zequez/reddit-placebot) for the original code I forked.

Thanks to [trosh/rplace](https://github.com/trosh/rplace) to figure out how to actually read the bitmap from the server. I just ported that to Node.

## License

MIT
