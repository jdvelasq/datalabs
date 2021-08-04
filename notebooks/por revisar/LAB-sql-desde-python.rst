LAB: SQL desde Python
=================================================
* *60 min*

En los ejemplos presentados debe modificar su nombre de usuario y password.

Para las actividades solicitadas a continuación, utilice la siguiente tabla:

.. code:: sql

   CREATE DATABASE SQLdb;
   USE SQLdb;

   CREATE TABLE persons (
       id INT,
       firstname VARCHAR(10),
       surname VARCHAR(10),
       birthday DATE,
       color VARCHAR(10),
       quantity INT
   );

   INSERT INTO persons VALUES
       (1,"Vivian","Hamilton","1971-07-08","green",1),
       (2,"Karen","Holcomb","1974-05-23","green",4),
       (3,"Cody","Garrett","1973-04-22","orange",1),
       (4,"Roth","Fry","1975-01-29","black",1),
       (5,"Zoe","Conway","1974-07-03","blue",2),
       (6,"Gretchen","Kinney","1974-10-18","viole",1),
       (7,"Driscoll","Klein","1970-10-05","blue",5),
       (8,"Karyn","Diaz","1969-02-24","red",1),
       (9,"Merritt","Guy","1974-10-17","indigo",4),
       (10,"Kylan","Sexton","1975-02-28","black",4),
       (11,"Jordan","Estes","1969-12-07","indigo",4),
       (12,"Hope","Coffey","1973-12-24","green",5),
       (13,"Vivian","Crane","1970-08-27","gray",5),
       (14,"Clio","Noel","1972-12-12","red",5),
       (15,"Hope","Silva","1970-07-01","blue",5),
       (16,"Ayanna","Jarvis","1974-02-11","orange",5),
       (17,"Chanda","Boyer","1973-04-01","green",4),
       (18,"Chadwick","Knight","1973-04-29","yellow",1);


Actividad 1
  Ejemplifique el uso de asignación, pandas y gráficos para el paquete
  `ipython-sql <https://github.com/catherinedevlin/ipython-sql>`__, de
  acuerdo con la descripción dada en el archivo README.rst del
  repositorio.

Actividad 2
  Adapte los ejemplos del blog https://towardsdatascience.com/sqlalchemy-python-tutorial-79a577141a91
  a la tabla presentada para esta actividad.
