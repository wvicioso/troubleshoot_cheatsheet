**reset local branch to mirror origin**

```git reset --hard origin/branch_name```

**remove untracked files**

```git add .```

```git reset --hard HEAD```

**compile assets**

```RAILS_ENV=production bundle exec rake assets:precompile```

**run release version on device - React-Native IOS**

```react-native run-ios --configuration Release)```

**debugging command - React-Native Android**

```cd android/ && ./gradlew clean && cd .. && react-native run-android```

**install deprecated components**

```npm i react-native-deprecated-custom-components```

**npm and yarn parallels**

https://yarnpkg.com/lang/en/docs/migrating-from-npm/

**PG Bad connection troubleshoot for Rails**

```rm /usr/local/var/postgres/postmaster.pid && brew services restart postgresql```

****else nuke PG****

```gem uninstall pg```

```brew uninstall --force postgresql```

```brew install postgresql```

```gem install pg```

add pg with current version to gemfile. Delete Gem.lock

```bundle install```
