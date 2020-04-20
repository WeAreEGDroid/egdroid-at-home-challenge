# EGDroid at-home challenge
A collection of somewhat tricky Android challenges, intended to collectively learn and get the most out of Android development.

If you’d like your solution to be included in this repository, please [join our slack community](https://bit.ly/2PhQ4VI) and follow the updates on `#egdroid-at-home-challenge` channel. All submissions will be credited.

## How it works
1. We post a challenge
2. Users submit their solutions.
3. Other users vote on submissions
4. By the deadline of the challenge, the submission with the highest vote count will make it to this repository.


## Challenges
1. [Custom animation](https://github.com/eg-droid/animation-challenge)

## Installation
### Cloning this repository
This repository contains [submodules](https://github.com/blog/2104-working-with-submodules).

Git expects us to explicitly ask it to download the submodule's content. You can use `git submodule update --init --recursive` here as well, but if you're cloning this repository for the first time, you can use a modified clone command to ensure you download everything, including any submodules:

```
git clone --recursive git@github.com:eg-droid/egdroid-at-home-challenge.git
```

###  Updating latest changes from submodules
In order to updated the repository submodules content, you can execute the following command regularly:

```
git submodule update --remote --recursive
```

##  Contribution
For suggestions, please feel free to [open an issue](../../issues/new).

##  License
Copyright (c) 2020 EGDroid

Licensed under the [MIT License](LICENSE.md)