# Haskell for Project Euler

## Templated from Baltimore Black Techies
[![Join the slack channel](https://img.shields.io/badge/slack-Baltimore%20Black%20Techies-purple.svg?logo=slack)](http://bit.ly/3r4lPQm)
[![Join the slack channel](https://img.shields.io/badge/github-BBT-blue.svg?logo=github)](https://github.com/baltimoreblacktechies/haskell-template)
[![bazel-test](https://github.com/baltimoreblacktechies/haskell-template/actions/workflows/bazel.yml/badge.svg)](https://github.com/baltimoreblacktechies/haskell-template/actions/workflows/bazel.yml)

<p align="center"><img width="250" alt="Haskell template banner" src="https://raw.githubusercontent.com/baltimoreblacktechies/haskell-template/master/banner.png"><br>get your lambda calculus on</p>

## What is this?

Installing, setting-up, configuring and playing with Haskell can initially be a pain. This template uses [rules_haskell](https://github.com/tweag/rules_haskell), and defines a Visual Studio development environment for [Github Codespaces](https://github.com/features/codespaces/signup), so that you can start programming ASAP. This repository is targeted at teaching [our community](https://www.meetup.com/Baltimore-Black-Techies-Meetup) to learn functional programming during one of our [regular events](https://www.meetup.com/Baltimore-Black-Techies-Meetup/events/277186235/). [Join us](http://bit.ly/3r4lPQm)! 

### How to use

Click `template` in the upper right of the page, and rename it to the project you want. Once you've created your project, click `Code`, then `Open with Codespaces`. Wait for the project to finish provisioning.

Awesome! Are you booted? Press `ctrl`-`alt`-`space` to bring up Visual Studio Tasks. The currently configured tasks are as follows:

 - **all**: This will run all your problems.
 - **edit**: This will create a file in order for you to start solving a given problem.
 - **examine**: This will print out the problem statement for a given problem.
 - **repl**: This will start a Haskell repl for debugging a given problem.
 - **single**: This will run a test for a single problem (whatever problem number is open).

Run `all` to make sure everything is working.

### How to customize

This template is derived from [Dylan's Project Euler](https://github.com/dmadisetti/painfulHaskell). Pushes to this project automatically generates a tracking image, e.g. [progress.svg](https://github.com/dmadisetti/painfulHaskell/blob/gh-pages/progress.svg).  You'll also probably want to change this README to reflect your journey :)

### How to go beyond Project Euler

This project uses [rules_haskell](https://github.com/tweag/rules_haskell) and [bazel](https://bazel.build/). However typical usage of Haskell development either uses [Cabal](https://www.haskell.org/cabal/) or [Stack](https://docs.haskellstack.org/en/stable/README/). `rules_haskell` is well engineered and documented. As such, for a quick project, it's recommended to remove the project euler specific information, and modify this project to fit your needs. For more involved projects, it's suggested to do the research all the options
