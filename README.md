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
