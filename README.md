# zsh_completions_mongodb

ZSH completion files for [MongoDB Server](https://docs.mongodb.com/manual/), [Database Tools](https://docs.mongodb.com/database-tools/), and [MongoDB Shell](https://docs.mongodb.com/mongodb-shell/):
 * `bsondump`
 * `mongo`
 * `mongod`
 * `mongodump`
 * `mongoexport`
 * `mongofiles`
 * `mongoimport`
 * `mongorestore`
 * `mongos`
 * `mongosh`
 * `mongostat`
 * `mongotop`

### Install for [oh-my-zsh](http://github.com/robbyrussell/oh-my-zsh)

* Clone `zsh_completions_mongodb` inside your `oh-my-zsh` custom plugins directory:

        git clone https://github.com/JamesKovacs/zsh_completions_mongodb.git ~/.oh-my-zsh/custom/plugins/mongodb

* Enable the `mongodb` plugin in your `~/.zshrc`:

        plugins=(… mongodb)

* Start a new `zsh` session or reload completions:

        autoload -U compinit && compinit

### Install for [oh-my-zsh](http://github.com/robbyrussell/oh-my-zsh) with [Antigen](https://github.com/zsh-users/antigen)

* Installation with antigen

        antigen bundle JamesKovacs/zsh_completions_mongodb

### Manual installation

* Clone the repository:

        git clone https://github.com/JamesKovacs/zsh_completions_mongodb.git

* Include the directory in your `$fpath`, for example by adding in `~/.zshrc`:

        fpath=(path/to/zsh_completions_mongodb $fpath)

* You may have to force rebuild `zcompdump`:

        rm -f ~/.zcompdump; compinit
