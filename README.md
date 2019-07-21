Instagram Challenge
===================
## How tos:

Download or clone.

`> bundle install`  
`> bin/rails db:create`  
`> bin/rails db:migrate`  
`> bin/rails server` - starts the server. Open `http://localhost:3000/photo/index` in your browser to view.

To run tests:  
`> bundle exec rspec`  
`> bundle exec rubocop`  


## User stories

- [ ] As a user, so that I can share my pictures, I would like to be able to sign up and post pictures
- [ ] As a user, so that I can become an influencer, I would like to see my username next to my posts
- [ ] As an influencer, so that I can get sweet sponsorship deals, I would like my posts to be liked and show the # of likes

**nice to have**

- [ ] As an influencer, so that I can generate zeitgeist, I would like to have a comment section on all my posts
- [ ] As a user, to save my time and sanity, I want to be able to filter posts to see only those relevant to my interests

## Development todo: 

- [x] Produce some stories, break them down into tasks, and estimate
- [x] Fork this repo, clone, etc
- [x] Initialize a new rails project
- [x] Add rubocop
- [x] add instructions to README
- [ ] first feature test

## Credits:

In this challenge I used the following resources:

- [this tutorial](https://pusher.com/tutorials/photo-sharing-ruby-rails)
- [this Eliot Sykes repo](https://gist.github.com/eliotsykes/6fc16f428d4e6bb9b32d)
- [previous week's Makers challenge repo](https://github.com/bengscott2/acebook-livewire)
- [this tutorial for switching from sqlite to a PG db](https://www.daveferrara1.com/ruby-in-rails-switch-from-sqlite3-to-postgres/)
