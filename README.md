# alphabet-game
Alphabet game


# Enviroment tested
- Raspberry Pi (with Raspbian)
- Mac OS X High Sierra 10.13.6

# Setup

## Mac
Execute following command:
```sh
$ brew install espeak
```

## Raspberry Pi (with Raspbian)
Execute following command for setting analog audio:
```sh
$ amixer cset numid=3 1
```

Check audio
```sh
$ aplay /usr/share/sounds/alsa/*
```

You can hear "Front Center”,”Front Left”, “Front Right” and so on, your sound is working!

Execute following command for setup:
```sh
$ sudo apt-get install -y espeak
```

Check espeak
```sh
$ espeak "Hello World" 2>/dev/null
```

# Usage
Clone this repository
```sh
$ git clone https://github.com/karaage0703/alphabet-game
$ cd alphabet-game
$ python alphabet_game.py
```

# Licence
This software is released under the MIT License, see LICENSE.

# Authors
karaage0703

# References
- https://www.dexterindustries.com/howto/make-your-raspberry-pi-speak/
- http://yoshi-python.blogspot.com/2009/10/blog-post_6551.html
