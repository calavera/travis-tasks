tasks:   bundle exec sidekiq -c 25 -r ./lib/travis/tasks.rb -q campfire -q email -q flowdock -q github_commit_status -q github_status -q hipchat -q irc -q pusher -q webhook
archive: bundle exec sidekiq -c 4  -r ./lib/travis/tasks.rb -q archive
