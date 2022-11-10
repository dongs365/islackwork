# I Slack Works

[visit site](http://islack.work)

From [iloveworks](https://github.com/sorcererxw/iloveworks)
## Usage

### Url Params

name  |values
------|--------------------
lang  |`zh-hant`, `zh-hans`, `en`
slogan|Any text you want to show, [Reference](http://islack.work/settings/slogan). In addition, you can use <code>&#124;&#124;</code> as paragraph break.  
theme |`light`, `dark`, `white`, `black`, `chrome-dark`


#### Env
1. node v9.0
npm install -g n

## develop

### Run on local
1. fork and clone this repository
2. `npm install`
3. `npm run build`
4. `npm run start`

### Deploy on your github pages

1. fork and clone this repository
2. `npm install`
3. change the `CNAME`(/public/CNAME) file to your domain
4. change the `homepage` config in `package.json` to your github homepage (example.github.io)
5. `npm run deploy`
