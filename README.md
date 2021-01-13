# Introduction Active Admin - Ruby on Rails

* ruby -v: 2.7.1
* rails -v 6.0.3.2
* activeadmin -v 2.9.0
[Active Admin]: https://activeadmin.info/0-installation. 

### Application: 
_Control States to Cities, being able to comment on actions._

### Validation(Order):
* rails g model State uf name
* rails g active_admin:resource State
* rails db:migrate
* rails g model City state:references name
* rails db:migrate
* rails g active_admin:resource City
* rails s
----
obs: enable in states.rb | cities.rb  `permit_params`
...
