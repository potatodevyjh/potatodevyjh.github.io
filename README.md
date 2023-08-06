# potatodevyjh.github.io


|사이트 빌드하고 로컬 서버에 적용|
|---|
> bundle exec jekyll serve

|사이트 접속|
|--|
> http://localhost:4000



## 구조
    ├── _data
    │   ├── locale.yml - 블로그 상단에 들어가는 내용
    │   ├── navigation.yml - 외국어 설정
    │   └── variables.yml -  yml 변수
    ├── _includes
    │   ├── analytics-providers
    │   ├── aside
    │   ├── comments-providers
    │   ├── markdown-enhancements
    │   ├── pageview-providers
    │   ├── scripts
    │   ├── sidebar
    │   ├── snippets
    │   ├── svg
    │   │   ├── icon
    │   │   │   ├── social
    │   │   │   │   ├── facebook.svg
    │   │   │   │   └── ...
    │   │   └── logo.svg
    │   └── ...
    ├── _layouts
    │   ├── 404.html
    │   ├── archive.html
    │   ├── article.html
    │   ├── base.html
    │   ├── home.html
    │   ├── none.html
    │   └── page.html
    ├── _sass
    ├── assets
    │   ├── css
    │   │   └── blog.scss
    │   └── images
    ├── tools
    ├── 404.html
    ├── Gemfile
    ├── _config.yml
    ├── about.md
    ├── archive.html
    ├── favicon.ico
    ├── gulpfile.js
    ├── index.html
    ├── jekyll-text-theme.gemspec
    └── package.json
