# Rofi Bookmarks

rofi frontend for [linkding bookmarking service](https://github.com/sissbruecker/linkding) using the [linkding cli](https://github.com/bachya/linkding-cli)

this was inspired by [a forked repo of mine on an awesome rofi frontend using buku](https://github.com/marcos-aparicio/rofi-buku). And all credit to [origin of the fork](https://github.com/carnager/buku_run)

As i want to start using a vps for everything, i adapted the previous code so that the frontend remains the same while doing the operations using linkding for the backend, this assumes that you have linkding-cli already setup


## Screenshots

![Screenshot2](images/screenshot2.png)

## Features
* Adding bookmarks with tags
* Editing URLs and tags inline
* Deleting bookmarks
* Open URLs

## Dependencies
* sed
* [rofi](https://github.com/DaveDavenport/rofi)
* bash
* jq
