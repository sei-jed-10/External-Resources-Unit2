# External-Resources
Hey, guys! Here's a list of useful tips and resources for unit 2

**[Rico's cheatsheets](https://devhints.io/)** //Mohammed Almahdawi Shared this
 
## Ruby Steps:
1. **Create Ruby file:** in the terminal write $touch filename.rb
2. **Add youe code:** Add a your code inside filename.rb
3. **Run Ruby:** Run the file using ruby in the terminal $ruby filename.rb

---

## Ruby:
1. **[Ruby Beginner Cheatsheet](https://www.pragtob.info/rails-beginner-cheatsheet/#ruby-concepts)**
2. **[Ruby API Document](https://ruby-doc.org/core-2.6.5/)**
3. **[Complete Guide to the Ruby Programming World](https://rubygarage.org/blog/cool-stuff-in-ruby-language)**
4. **[Ruby Document](https://devdocs.io/ruby/)**
5. **[Ruby for Beginners](http://ruby-for-beginners.rubymonstas.org/index.html)**

---

## Ruby vs Ruby on Rails:
**[Ruby vs Ruby On Rails](https://www.educba.com/ruby-vs-ruby-on-rails/)**

---
 
## Rails Steps:
1. **Create Rails project:** in the terminal write $`rails new project_name -d mysql`
2. **Start rails project:**  in the terminal write $`rails s`

---

## Rail:
1. **[What is Ruby on Rails?](https://www.rubyguides.com/2018/10/what-is-ruby-on-rails/)**
2. **[Understanding the basics of Ruby on Rails](https://www.freecodecamp.org/news/understanding-the-basics-of-ruby-on-rails-http-mvc-and-routes-359b8d809c7a/)**
3. **[Rails Beginner Cheatsheet](https://www.pragtob.info/rails-beginner-cheatsheet/)**
4. **[Rails Document](https://devdocs.io/rails~5.0/)**
5. **[Rails API Document](https://api.rubyonrails.org/)**
6. **[Rails cheatsheets](https://devhints.io/rails)** //Mohammed Almahdawi Shared this

---

## Active Record:
1. **[Active Record Basics](https://guides.rubyonrails.org/active_record_basics.html)**
2. **[Active Record Cheat Sheet](https://gist.github.com/jessieay/3131622)**
3. **[Active Record querying](https://guides.rubyonrails.org/active_record_querying.html)**
---

## Asset Pipeline:
**[Ruby on Rails Guides: Asset Pipeline](https://guides.rubyonrails.org/asset_pipeline.html)**

---

## Rails Commands:
#### Create App
**Create Rails project:** in the terminal write 
```bash 
rails new movie_app -d mysql
```

### Model Related Commands
**Create Database within your Rails app:**  in the terminal write 
```bash
rails db:create
```
**Create a Movie model with fields:** 
```bash
rails g model Movie director:string
```
(your model name should be <ins>single/capital</ins> if table name has 2 words TableName)

**Add a name column to the Movie model:** 
```bash
rails g migration AddNameToMovies name:string
```
**Remove column from table:** 
```bash
rails g migration RemoveNameFromUsers
```
**Enter the database console and use SQL commands:** 
```bash
rails db
```
**To start migrations:** 
```bash
rails db:migrate
```
**To get a list of your migrations:** 
```bash
rails db:migrate:status
``` 
**To seed your database:** 
```bash
rails db:seed
```
**To rollback/undo a migration:** 
```bash
rails db:rollback
```
**To rollback/undo multiple migrations:** 
```bash
rails db:rollback STEP=2
``` 
(2 is an example number of migrations to roll back)

**To destroy the whole databse:** 
```bash
rails db:drop
```

### Controller Related Commands
**To create a new controller with index, new, show, and edit methods:** 
```bash
rails g controller ControllerName index new show edit
``` 
(your controller should be <ins> plural and capital</ins>)

**To destroy a controller:** 
```bash
rails destroy controller ControllerName
```

### Improtant Rails Commands
**Show all the possible Rails commands:** 
```bash
rails
```
**Show all available routes:** 
```bash
rails routes
```
**Enter the console:**
```bash
rails c
```
**Start the server:** 
```bash
rails s
```
**Start a server on a specific port:** 
```bash
rails s -p 3003
```
(3003 is an example)








