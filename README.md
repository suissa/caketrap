# CakeTrap v 0.1
---
Caketrap is a simple HTML5 Ready Bootstrap for CakePHP Applications.

### Features
##### Front-end

1. HTML5 Boilerplate
2. RequireJS
3. Modernizr
4. Twitter Bootstrap

##### Back-end
1. CakePHP 2.0.x Security Authentication
2. Simple users register


## Quick start

- Create a table named `users` in your database with the following structure:


<pre>CREATE TABLE users (
id int(11) NOT NULL AUTO_INCREMENT,
username varchar(255) NOT NULL,
password varchar(255) NOT NULL,
name varchar(255) NOT NULL,
created datetime NOT NULL,
modified datetime NOT NULL,
PRIMARY KEY (id)
) ENGINE=InnoDB  DEFAULT CHARSET=latin1 AUTO_INCREMENT=5 ;
</pre>


- Open the file `app/Config/database.php` and change the database information



## Questions / Bugs

Have a question or found a bug? Please create an issue [here][] on GitHub!
[here]: https://github.com/hugodias/caketrap/issues
