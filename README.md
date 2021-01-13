# Introduction Active Admin - Ruby on Rails

* ruby -v: 2.7.1
* rails -v 6.0.3.2
* activeadmin -v 2.9.0

### Application: 
_Control States to Cities, being able to comment on actions._

### Validation:
* _rails g model State uf name_
** States contains uf and name
* _rails g model City state:references name_
** Cities contains state_id, name
