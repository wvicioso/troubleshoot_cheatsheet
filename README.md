**reset local branch to mirror origin**

```git reset --hard origin/branch_name```

**remove untracked files**

```git add .```

```git reset --hard HEAD```

**compile assets**

```RAILS_ENV=production bundle exec rake assets:precompile```
