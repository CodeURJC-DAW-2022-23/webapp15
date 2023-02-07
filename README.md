# webapp15

# Ayuntamiento URJC

## Team members

| Name | Mail | Github user|
|--------|--------|------------|
| Carlos García Pérez | c.garciape.2016@alumnos.urjc.es | Scabfull |
| Javier Cai Lin | j.cail.2016@alumnos.urjc.es | jcl4332 |
| Víctor López Rodríguez | v.lopezrodr@alumnos.urjc.es | Victorlopezro |
| Jesús Ortiz Lopo | j.ortizl.2019@alumnos.urjc.es | JesusOrtiz10 |
| Sergio Villagarcía Sánchez | s.villagarcia.2019@alumnos.urjc.es | Sergio-1502 | 

### Description

Ayuntamiento URJC is a page that provides info about URJC City. You can see the lastest news, activities and vote on everyday things like what is the best place to eat or the next band that should be on the next festival.

### Entities

* User: id(pk), email, password, address, rol
* Activities: id(pk), user id (fk), description, date
* Votes: id(pk), user id (fk), description, expire date
* News: id(pk), headline, description, date 

### User permissions

We distinguish between 3 types of user: non-registered users, registered users and administrators.

* Unregistered users: they will be able to see the news along with their descriptions but they will not have administrator permissions nor will they be able to access the votes or the activities
* Registered users: they will have the same things available as non-registered users, but they will be able to sign up for activities, participate in voting and modify their profile.
* Administrators: they will be able to add news, votes and activities, delete them and modify their characteristics (name, description, etc.).

### Images 

* Registered users will be able to set a profile image.
* When an administrator posts a piece of news, it must be accompanied by an image.

### Graphics

* Registered users will be able to see the results of the voting when they have finished

### Complementary technology

* Sending emails to users

### Algorithm or advanced query
