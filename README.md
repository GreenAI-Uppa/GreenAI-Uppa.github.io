# Green AI UPPA website documentation


### Installation 

- install [ruby](https://jekyllrb.com/docs/installation/)

- install [Jekyll](https://jekyllrb.com/docs/step-by-step/01-setup/)
```
gem install jekyll bundler
```

- clone this repo
```
git clone https://github.com/GreenAI-Uppa/GreenAI-Uppa.github.io.git
```


- From the root directory, install the gems

```
bundle install 
```

### Running and modifying the site

- `bundle exec jekyll serve` to visit the website on your machine. It should be accessible at [http://127.0.0.1:4000/](http://127.0.0.1:4000/)

- See the [alembic template](https://alembic.darn.es/) if you wish to modify it.

Check `_config.yaml` to modify the News Feed and Quick Links sections.

Check the other `*.md` files for the rest.


- Once you pushed your modification, the [online website](https://greenai-uppa.github.io/) should be updated. No need to compile, there is an automatic github action for that.

### Modify the news feed
Open the `_config.yml` file, and then search for the news section. As you will see, the format is simple:
```
news:
   date: "description of your news"
```

### Modify the navigation bar
in `_config.yml`, got to the navigation part:

```
navigation_header:
- title: Home
  url: /
- title: Research
  url: /#our-research
...
```
As you can see, the title will be displayed on the web page, and the url correspond to the page
- `/` indicates the main page
- `/#our-research` indicates a subsection, and corresponds to a markdown title, in lower case, and with the spaces replaced by `-`

### add past seminar

modify the ./events.md
