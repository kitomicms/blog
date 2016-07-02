---
layout: post
title:  "Heroku command"
---

## Heroku Basics
- you have to commit everything before you push
- what you are pushing is not what you are "seeing"
- it is what you have commit

```
$heroku create
  - create a remote called heroku in git
  - create a repo/workplace for you to push
$heroku open
  - open in browser
```
- gemfile

```ruby
#gemfile
group :production do
    gem 'pg'
    gem 'rails_12factor'
end

group :development, :test do
  gem 'sqlite3'
end
```
