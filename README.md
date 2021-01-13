# Introduction Active Admin - Ruby on Rails

* ruby -v: 2.7.1
* rails -v 6.0.3.2
* activeadmin -v 2.9.0
[Active Admin]: https://activeadmin.info/0-installation. 

### Application: 
_Control States to Cities, being able to comment on actions._

### Validation:
* _rails g model State uf name_
* _rails g active_admin:resource State_
* States contains uf and name
----
* _rails g model City state:references name_
* _rails g active_admin:resource City_
* Cities contains state_id, name
