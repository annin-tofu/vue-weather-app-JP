# vue-weather

## to start up the app

yarn serve (like yarn start in React Apps)

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Lints and fixes files

```
yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

# Vuejs setup

## To install Vuejs

\$ npm -g i @vue/cli

## To create an vue app

\$ vue create vue-weather

Then the prompt asks you few questions 1.
“? Your connection to the default yarn registry seems to be slow.
Use https://registry.npm.taobao.org for faster installation? “

> > > Answer “Yes”

2.
“? Please pick a preset”:

> > > Pick “Default (Vue 2) ([Vue 2] babel, eslint)”

3
“? Pick the package manager to use when installing dependencies”:

> > > Pick “Yarn”

References:
https://youtu.be/JLc-hWsPTUY

https://a-jaco.hatenablog.com/entry/2018/05/26/003356

https://johobase.com/vue-js-cli-create-project/

Then
\$ cd vue-weather

then
$ code . (to start VSCode)
then 
$ yarn serve (to start up app on the server)

or
\$ code . && yarn serve

## ADD EXTENTIONS https://code.visualstudio.com/docs/nodejs/vuejs-tutorial

Q. Why? VSCode is freaking out? (Though the code is working)
A. “Now expand the src folder and select the App.vue file. You'll notice that VS Code doesn't show any syntax highlighting and it treats the file as Plain Text”
https://code.visualstudio.com/docs/nodejs/vuejs-tutorial

> > > Install an Extension “Vetur”. And JSCno longer freaks out

###### auto close tag doesn't work in vue file

vue のテンプレートを書いていると、閉じタグが補完されなくて面倒です。
（<p まで書いて>を入力すると<p></P>になるやつです）
ただの html や Angular のテンプレートではできていたのですが
何がこれをやってくれていたのでしょうか。

それは VSCode のビルトイン機能で、settings の html.autoClosingTags に対応していますが、Vetur にはないようです。
https://teratail.com/questions/173501

https://github.com/microsoft/vscode/issues/94614

A. Installed an Extension “Auto Close Tag”. And it should work right off the bat without tweaking any settings.

## vue-weather app setup

We need to pull API from weather database @openweather.org

1. Make an account in openweather.org
   https://openweathermap.org/

2. Create key with VueApp as API key name
   ￼
# vue2-weather-app
