# Count app with p5.js and Python

## TODO

- Qiitaの記事のリンクを貼る。


## What is this?

- This app is a proof of concept that you can use python function from p5.js program via flask and ajax.

- [minimal branch](https://github.com/KazukiOhta/advent20201221/tree/minimal) is minimal code. You can run the app locally.

- [main branch](https://github.com/KazukiOhta/advent20201221/tree/main) is full code. I deployed the app on heroku using this branch.

- Please take a look at [this article (Japanese)]() for the details.

## How can I see the app?

- You can see the app on [heroku](https://aqueous-refuge-85467.herokuapp.com/).



## How to run?

### Requirements

```
python3 (eg. python3.9.1)
flask   (eg. flask1.1.1)
```

### Installation

```shell
$ git clone git@github.com:KazukiOhta/advent20201221.git
$ pip3 install flask
```

### Running the app

```shell
$ cd advent20201221
$ python3 app.py
```

open http://0.0.0.0:8080/ to see your app on a browser.

![demo.gif](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/145009/f87b64ff-7553-13e5-2ffd-770381a35867.gif)
