# Install & update

Clone this repo in *Packages/User/Snippets* on your [Sublime Text Data Directory](http://docs.sublimetext.info/en/latest/basic_concepts.html#the-data-directory)

## MacOSX:

Install:

```
$ git clone https://github.com/bertez/sublime-snippets ~/Library/Application Support/Sublime Text 3/Packages/User/Snippets
```

Update:

```
$ cd ~/Library/Application Support/Sublime Text 3/Packages/User/Snippets
$ git pull
```

## Linux (Ubuntu):

Install:

```
$ git clone https://github.com/bertez/sublime-snippets ~/.config/sublime-text-3/Packages/User/Snippets
```

Update

```
$ cd ~/.config/sublime-text-3/Packages/User/Snippets
$ git pull
```

## Windows 7 (PowerShell):

Install:

```
cd ~
git clone https://github.com/bertez/sublime-snippets "AppData\Roaming\Sublime Text 3\Packages\User\Snippets"
```

Update

```
cd ~"\AppData\Roaming\Sublime Text 3\Packages\User\Snippets"
git pull
```


# Snippets

## JavaScript

Command | Result
------- | ------
con + tab | `console.log($1)`
req + tab | `require([$1], function($2){$3})`
def + tab | `define([$1], function($2){$3})`
cc + tab | Block comment
aj + tab | jQuery ajax
