# Install & update

Clone this repo in *Packages/User/Snippets* in your [Sublime Text Data Directory](http://docs.sublimetext.info/en/latest/basic_concepts.html#the-data-directory)

For example in MacOSX:

`$ git clone https://github.com/bertez/sublime-snippets ~/Library/Application Support/Sublime Text 3/Packages/User/Snippets`

In windows 7 (PowerShell):
```
cd ~
git clone https://github.com/bertez/sublime-snippets "AppData\Roaming\Sublime Text 3\Packages\User\Snippets"
```

To update, simply execute a `git pull` command in the folder:

For example in MacOSX:

```
$ cd ~/Library/Application Support/Sublime Text 3/Packages/User/Snippets
$ git pull
```

In windows 7 (PowerShell):
```
cd ~"\AppData\Roaming\Sublime Text 3\Packages\User\Snippets"
git pull
```


# Snippets

## JavaScript

Command | Result
------- | ------
con + tab | `js console.log($1)`
req + tab | `require([$1], function($2){$3})`
def + tab | `define([$1], function($2){$3})`
