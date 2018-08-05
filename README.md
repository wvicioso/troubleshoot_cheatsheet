## Here are links, commands, and other trouble shooting methods I have found myself looking up more than once

### MISC

**bash cheat sheet https://ss64.com/bash/syntax-prompt.html**

**bash style**

```PS1='\e[31;1m\e[31m\w\e[0m $ '```

### Ruby on Rails

**Install Rails Walkthrough**

http://railsapps.github.io/xcode-command-line-tools.html

**compile assets**

```RAILS_ENV=production bundle exec rake assets:precompile```

**PG Bad connection**

```rm /usr/local/var/postgres/postmaster.pid && brew services restart postgresql```

**else nuke PG**

```gem uninstall pg```

```brew uninstall --force postgresql```

```brew install postgresql```

```gem install pg```

*add pg with current version to gemfile. Delete Gem.lock*

```bundle install```

### GIT

**reset local branch to mirror origin**

```git reset --hard origin/branch_name```

**remove untracked files**

```git add .```

```git reset --hard HEAD```

**force push**

```git push origin <branchName> -f```

**WARNING:(Destructive) -rollback to a previous commit**

 ```git checkout master```

```git reset --hard <commit>```

```git push origin master```

### React-Native

**run release version on device - React-Native IOS**

```react-native run-ios --configuration Release```

**debugging command - React-Native Android**

```cd android/ && ./gradlew clean && cd .. && react-native run-android```

**install deprecated components**

```npm i react-native-deprecated-custom-components```

**npm and yarn parallels**

https://yarnpkg.com/lang/en/docs/migrating-from-npm/


### Code-Push

**check active downloads**

```code-push deployment ls <appName>```

**deploy to production**

```code-push release-react <appName> ios -d Production```
