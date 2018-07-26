
# eyeson Ruby Quickstart Tutorial

A short and simple video conferencing application using eyeson API services.

The application requires a single method call to start a video meeting and
creates random users that can join the room. The software uses [sinatra] and
[heroku] to host a single website as landing page.

## Setup

Get your own eyeson API key at [accounts.eyeson.team/projects]. Create a new
project at heroku and set the `EYESON_API_KEY` as config variable in the heroku
project settings. Download the repository, push the files to trigger the heroku
build and deploy pipeline. Afterwards visit your application at
`https://<heroku-project-name>.herokuapp.com/`.

```sh
$ git clone https://github.com/eyeson-team/ruby-quickstart.git eyeson-ruby-quickstart
$ cd eyeson-ruby-quickstart
$ heroku git:remote -a <heroku-project-name>
$ git push heroku master
```

[accounts.eyeson.team/projects]: https://accounts.eyeson.team/projects "eyeson API projects"
[sinatra]: http://sinatrarb.com/ "Sinatra, ruby web application framework"
[heroku]: https://www.heroku.com/ "Heroku, platform as a service (PaaS)"
