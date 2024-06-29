# Website

This repo contains the code for my [portfolio](https://aatmanvaidya.github.io/). 
<br>
<br>
The portfolio is powered by [Jekyll](https://jekyllrb.com/) with [al-folio](https://github.com/alshedivat/al-folio) theme.

## Setting up this Website Locally (Ubuntu)

Make sure you have you have [Ruby](https://www.ruby-lang.org/en/downloads/) and [Bundler](https://bundler.io/) installed on your system. for ease of managing ruby gems, consider using [rbenv](https://github.com/rbenv/rbenv). 

Given that run the below command in the folder of the code:

```bash
$ bundle install
$ bundle exec jekyll serve
```

I just have setup a docker conainer, so the site can be brought up in one command
```bash
docker-compose up
```
This will host the site at `localhost:8080`

## License

The theme is available as open source under the terms of the [MIT License](https://github.com/alshedivat/al-folio/blob/master/LICENSE).

Originally, **al-folio** was based on the [\*folio theme](https://github.com/bogoli/-folio) (published by [Lia Bogoev](https://liabogoev.com) and under the MIT license). Since then, it got a full re-write of the styles and many additional cool features.

