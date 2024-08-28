## GETTING STARTED WITH RUBY

# Building from Scratch

`rails new <pname>`

`rails routes`

`rails g model comment body:text`

`rails g migration add_article_id_to_comment article_id:integer`

`rails g controller comments`

`rails console`

`Article.first` or `Article.create(title:"hi",content:"bye")`

`rails s`


# Simplify using scafold 

`rails new scaffold_blog`

`rails g scaffold article title: string content:text`

`rails db:migrate`

# Hotwire

approach to build modern web applications without js but sending html instead of json hence fast load pages. more productive development, speed responsiveness


