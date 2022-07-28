# JS Game Development Guide for Losha


Some [getting started resources](https://phaser.io/tutorials/getting-started-phaser3)
*^ I think this can be skipped ^*

## Run this program

1. Install nodejs from here [download node](https://nodejs.org/en/download/)

2. cd into this repo's directory and run the following commands
    ```
    npm install --global yarn
    yarn init phaserExample --yes
    yarn add http-server
    yarn run http-server site
    ```
3. Open the url that's printed to the console (for me it was `http://127.0.0.1:8080`)


## Development

I took the code from stage of [this guide](https://phaser.io/tutorials/making-your-first-phaser-3-game/part1) and put it in the [site/index.html](site/index.html) file. So you can skip the section that prompts you to download a zip file.


You can modify the [site/index.html](site/index.html) to make changes. I recommend setting it to the initial state of the guide and working through it from there.

You can find more resources about `phaser` [here](
https://phaser.io/learn)

## Phaser Docs

I've put the phaser docs in this repo for convenience. After you've run the `yarn run http-server site` command you can find the docs at `http://127.0.0.1:8080/docs/index.html` (replace the value `8080` with the port number you received when you ran the `run http-server site` command)