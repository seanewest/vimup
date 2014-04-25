Vimup
=============

A proof-of-concept vim plugin manager based on pathogen.

Install
-----------
First make sure that you have [vim-pathogen](https://github.com/tpope/vim-pathogen) installed.

Then from the command line:
```
$ git clone https://github.com/seanewest/vimup
$ cd vimup
$ gem build vimup.gemspec
$ gem install ./vimup-0.0.1.gem
```

Usage
-----------

#### Add a plugin
    vimup tpope/vim-rails

#### Remove a plugin
    vimup down vim-rails

#### Install a user's vim configuration (experimental..)
    vimup user seanewest/vim_config

#### List currently installed vim plugins
    vimup list

