# Vim-RNB, a Vim colorscheme template

## What is this thing?

RNB is a template designed to help vimmers create their own colorschemes without much effort.

In reality, Vim colorschemes are not that hard to write but there are several benefits to using a template such as RNB:

* you can define/modify variables once instead of messing around with potentially botched substitutions,
* you can distribute a lean colorscheme, free from unnecessary logic,
* you can distribute the source alongside the colorscheme, making it easy for your users to experiment and adapt *your* colorscheme to *their* needs,
* you can focus on the design of your colorscheme rather than its implementation,
* you can start working on new colorscheme ideas very easily.

## What do I need to use it?

[ERB](https://ruby-doc.org/stdlib-2.6.3/libdoc/erb/rdoc/index.html), the templating engine used here, is part of Ruby's standard library so you will need [Ruby](https://www.ruby-lang.org/) to generate your colorscheme. Neither ERB nor Ruby knowledge is required, though.

## How do I use it?

The process is divided in five steps:

1. rename `colors/rnb.erb` to `colors/name_of_your_colorscheme.erb`,
2. start by editing your colorscheme's information,
3. define your colors,
4. define your highlight groups and links,
5. and generate your colorscheme (refer [how to generate](https://github.com/romainl/vim-rnb/blob/009cedd755ae1eeabe8842a320035f73459d39dd/colors/rnb.erb#L242)).

Steps 2 to 5 are thoroughly described in the [colorscheme template](https://github.com/romainl/vim-rnb/blob/master/colors/rnb.erb) itself in an effort to make it portable: if you ever decide to distribute your colorscheme you can simply package the template with it.

## Necessary Tool:

you need to have ruby installed before get started: 
- apt (Debian or Ubuntu): `sudo apt install ruby`  
- pacman (Arch Linux): `sudo pacman -S ruby`
- Homebrew (macOS): `brew install ruby`
- FreeBSD: `pkg install ruby`

## Built with RNB

The following colorschemes are known to be built with RNB:

* [Apprentice](https://github.com/romainl/Apprentice)
* [Dark Frost](https://github.com/Softmotions/vim-dark-frost-theme)
* [Dichromatic](https://github.com/romainl/vim-dichromatic)
* [Bruin](https://git.sr.ht/~romainl/vim-bruin)
* [Sweet16](https://github.com/romainl/vim-sweet16)
* [Paper](https://github.com/swalladge/paper.vim)
* [Journeyman](https://github.com/markeganfuller/vim-journeyman)
* [Warlock](https://github.com/hardselius/warlock)
* [Cyberpunk-Neon](https://github.com/Roboron3042/Cyberpunk-Neon)
* [Tutfish](https://github.com/benwr/tuftish)
* [Nisha](https://github.com/heraldofsolace/nisha-vim)
* [Photon](https://github.com/axvr/photon.vim)
* [vim-J](https://github.com/arthurealike/vim-J)
* [crystalcove](https://github.com/jayhowie/crystal-cove)
* [antarctic](https://github.com/swalladge/antarctic-vim)
* (your colorscheme here, send us a PR!)

## TODO

* `README.md` template


[//]: # ( Vim: set spell spelllang=en: )
