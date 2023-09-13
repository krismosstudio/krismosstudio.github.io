### DOCS ###

### - комментарии jekyll
# - комментарии разработчика


source "https://rubygems.org"
### Hello! This is where you manage which Jekyll version is used to run.
### When you want to use a different version, change it below, save the
### file and run `bundle install`. Run Jekyll with `bundle exec`, like so:

###     bundle exec jekyll serve


# <--- @AreNotAvalible 2023-08-18 13:00
# > "GitHub Pages Docs / Настройка сайта с помощью Jekyll / Создание сайта с помощью Jekyll / пункт 9"
# > Добавьте "#" в начало строки, которая начинается с gem "jekyll", чтобы закомментировать эту строку.
# > 

### This will help ensure the proper Jekyll version is running.
### Happy Jekylling!
# gem "jekyll", "~> 4.3.2"

# "GitHub Pages Docs / Настройка сайта с помощью Jekyll / Создание сайта с помощью Jekyll / пункт 9" --->


### This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"


# <--- @AreNotAvalible 2023-08-18 13:00
# > "GitHub Pages Docs / Настройка сайта с помощью Jekyll / Создание сайта с помощью Jekyll / пункт 10"
# > Добавьте зависимость github-pages, изменив строку, начинающуюся с # gem "github-pages". Измените эту строку следующим образом:
# > gem "github-pages", "~> GITHUB-PAGES-VERSION", group: :jekyll_plugins
# > Замените GITHUB-PAGES-VERSION последней поддерживаемой версией зависимости github-pages. 
# > Эту версию можно найти здесь: https://pages.github.com/versions/
# > Правильная версия Jekyll будет установлена в качестве зависимости gem github-pages.
# >

### If you want to use GitHub Pages, remove the "gem "jekyll"" above and
### uncomment the line below. To upgrade, run `bundle update github-pages`.
### gem "github-pages", group: :jekyll_plugins
gem "github-pages", "~> 228", group: :jekyll_plugins

# "GitHub Pages Docs / Настройка сайта с помощью Jekyll / Создание сайта с помощью Jekyll / пункт 9" --->


### If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

### Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
### and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

### Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

### Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
### do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "webrick", "~> 1.8"
