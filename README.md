# Hello CircleCI

This project was created to evaluate if I can/want to use CircleCI for building GTK based apps on macOS.

TL;DR: No, CircleCI does not qualify.

## the good

- easy to set up with GitHub
- UI/UX is great
- in less than 5 minutes you'll have your first pipeline running

## the bad

While they're patting themselves on the back for what they claim to be industry-leading generosity towards open source projects...

> How much do 80,000 build minutes on CircleCI cost? Nothing. No other platform supports CI/CD for the open source community more than CircleCI. _([source](https://circleci.com/open-source/))_

...you better read the fine print. You get [30.000 credtis for macOS](https://support.circleci.com/hc/en-us/articles/360049928971-Are-free-credits-available-for-macOS-open-source-projects) and my initial testing with this repository ([circleci-project-setup](https://github.com/dehesselle/hellocircleci/tree/circleci-project-setup) branch) here consumed 2,107 credits in 20 minutes. My estimate is I'll have about 4.7 hours of macOS CI per month. Given what I've seen so far, that's enough for one complete build of Inkscape and it's dependencies, but not suitable for my development purposes. I run dozens of full rebuilds each month. So I'm stopping the evaluation right here.

