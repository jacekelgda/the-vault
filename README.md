## ![](https://raw.githubusercontent.com/snipe/awesome-emoji/master/mario/Coin-Pip.gif) ![](https://raw.githubusercontent.com/snipe/awesome-emoji/master/mario/Coin-Pip.gif) ![](https://raw.githubusercontent.com/snipe/awesome-emoji/master/mario/Coin-Pip.gif) the-vault ![](https://raw.githubusercontent.com/snipe/awesome-emoji/master/mario/Coin-Pip.gif) ![](https://raw.githubusercontent.com/snipe/awesome-emoji/master/mario/Coin-Pip.gif) ![](https://raw.githubusercontent.com/snipe/awesome-emoji/master/mario/Coin-Pip.gif)

![](https://user-images.githubusercontent.com/1003372/31174665-a82f1678-a90c-11e7-9cd2-0d29d727857e.gif)

### Heroes! :bow: :muscle: :star:

This is the time where you can show your true commitment and unleash your passion for open source.

Let's have a look at the original message about ***The Vault***:

>We are finally providing you a path to access the ever-exclusive X-Team collectibles vault. You'll now be able to snag the latest, most exclusive X-Team collectibles by first earning gold coins ![](https://raw.githubusercontent.com/snipe/awesome-emoji/master/mario/Coin-Pip.gif) ![](https://raw.githubusercontent.com/snipe/awesome-emoji/master/mario/Coin-Pip.gif) ![](https://raw.githubusercontent.com/snipe/awesome-emoji/master/mario/Coin-Pip.gif) through participating and unleashing in community initiatives, and then cashing them in for the collectible of your choice. There are only 3 collectibles at a time and they will come and go after each Town Hall. Start unleashing today so that you can unlock The Vault.

### We need your help! :fire_engine: :scream: :zap:

In order to bring this to the whole different level ![](https://github.com/snipe/awesome-emoji/blob/master/mario/toad.gif?raw=true) we need to have proper technical support. We would like to create slack app which will help out with all things related to gold coins ![](https://raw.githubusercontent.com/snipe/awesome-emoji/master/mario/Coin-Pip.gif) management.

### Specs! :pencil: :green_book: :card_index:

Check out [issues](https://github.com/jacekelgda/the-vault/issues) section to pick up, propose and comment issues for this project. We would like to keep this as much community effort as possible, that means ***YOUR IDEAS MATTER!***

This project will be in focus for some time now and we would like to just go crazy with all different kinds of functionality. We already have some ideas but that doesn't mean we figured out 100% of it.


### Setup

The-Vault bot is based on [Serverless Slack App](https://github.com/johnagan/serverless-slack-app). Head there to get Slack Setup instructions.

To fill out secrets, run `cp serverless.env.yml.example serverless.env.yml` and edit `serverless.env.yml` file.

### Deployment

```bash
npm run deploy
```

To quicky see code changes on AWS Lambda environment (deploying only the code)
```bash
npm run codedeploy
```
