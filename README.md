# Spring Boot oh-my-zsh plugin
oh-my-zsh Spring Boot plugin

## Spring Boot autocomplete plugin

- Adds autocomplete options for all spring boot commands.

## Installation

### Manual Install

     $ cd ~/.oh-my-zsh/plugins
     $ git clone git@github.com:linux-china/oh-my-zsh-spring-boot-plugin.git spring

Adjust your .zshrc file and add spring to plugins=(...)  

### [Zgen](https://github.com/tarjoilija/zgen)

Add `zgen load linux-china/oh-my-zsh-spring-boot-plugin` to your .zshrc file in the same function you're doing your other `zgen load` calls in.

### [Antigen](https://github.com/zsh-users/antigen)

Add `antigen bundle linux-china/oh-my-zsh-spring-boot-plugin` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start zsh. You can also add the plugin to your running zsh session with `antigen bundle linux-china/oh-my-zsh-spring-boot-plugin` for testing before adding it permanently to your `.zshrc`.

## Reference

* Spring Boot: http://projects.spring.io/spring-boot/
* Spring Boot CLI: http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#cli

Maintainer : linux_china ([@linux_china](https://twitter.com/linux_china))

