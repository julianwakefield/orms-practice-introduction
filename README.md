# Object-Relational Mapping Practice

Object-Relational Mapping in Ruby is the combination
of two technologies we've learned - object-orientation
and working with SQL databases. Either one alone is cool,
but potentially limiting - if we have a Ruby class alone,
we can have it do many different things, but it cannot
the persist data. With SQL, we can persist data but must
use SQL queries that can be difficult to write and work
with. By combining the two through an ORM, we can create
classes that contain SQL and can persist data. 

In this section are lessons on a particular concept within
Object-Relational Mapping, _Dynamic ORMs_. When it comes to
ORMs, the class structure is almost always the same - the
only real difference is the data we access from the database.
With a dynamic ORM, we create a generic class structure that
can be used with any SQL database to the information availalble
in a Ruby application. The dynamic ORM, in effect, becomes
the interface between the database and the rest of your 
application.

Ruby has several existing ORMs we can use, and we'll take a
closer look at one of them, Active Record, in this course.
Understanding how to build our own, however, will give us
a better understanding of how to use tools like Active 
Record.

