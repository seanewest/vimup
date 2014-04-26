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
$ gem install ./vimup*.gem
```

Usage
-----------

#### Add a plugin
    vimup tpope/vim-rails

#### Remove a plugin
    vimup down vim-rails

#### List currently installed vim plugins
    vimup list

#### Install a user's vim configuration (experimental..)
    vimup user seanewest/vim_config
