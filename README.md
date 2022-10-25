# myFirstSqlDump
+----+---------------+-----------+----------+
| id | title         | genre     | duration |
+----+---------------+-----------+----------+
|  1 | Metropolis    | Sci-Fi    |      153 |
|  2 | Nosferatu     | Horror    |       94 |
|  3 | The kid       | Comedy    |       68 |
|  4 | The Gold Rush | Adventure |       95 |
+----+---------------+-----------+----------+
insert into movies2 (id, title,genre,duration)
    -> values (1, 'Metropolis', 'Sci-Fi',153 );
insert into movies2 (id,title,genre,duration)
    -> values (2,'Nosferatu','Horror',94);
insert into movies2 (id,title,genre,duration) 
    -> values (3,'The kid','Comedy',68);    
insert into movies2 (title,genre,duration) 
    -> values ('The Gold Rush','Adventure',95);
    
