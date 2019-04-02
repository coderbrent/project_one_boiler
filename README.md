# Project One Awesome Boilerplate 🍛

Before getting started, as a general rule of thumb, you should be running the commands you see within the project directory. If you experience errors, your first check should be to run `pwd` and ensure the folder name you see returned is the one you should be in.

## Install Yarn

If you have not already installed yarn, do so now.

* Windows Users: Install Yarn [here](https://yarnpkg.com/latest.msi).
* Mac Users: Using Homebrew Install Yarn like this: `brew install yarn`

## Using The Dev Environment

The first time you use this, run `yarn` in the project directory.

Now and every other time, just run `yarn start-dev`.

Visit `localhost:3000` in your chrome browser and you will see the `index.html`

With the server running you can restart it at any time by typing `rs` into the window and hitting enter.

Your files go in the following folders:

```
...
public
 --html <- html files get generated here
 --css <- put your css here
 --javascript <- put your javascript files here
 --images <- put your images here
...
```

## Screen Generator

To generate a new screen for example an "about" page, you can run `yarn generate-screen -- about` in a new terminal tab and then reload the server in the previous tab with `rs` like stated above.

The result of these commands will give you an autogenerated html file in your `public/html` folder and call it `about.html`.

After a successful restart of the server you can visit your newly generated screen at `localhost:3000/about`. EZ PZ.

Obviously when you do this yourself, change the `about` to whatever you want to name your new screen.
