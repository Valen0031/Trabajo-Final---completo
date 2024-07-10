# Trabajo-Final
Diccionario de datos

Base de datos: Latinobarómetro 2023

Unidad de análisis: Peruanos encuestados

numentre: Número de entrevista 

**Variables independientes**

satis_dem = Satisfacción de los peruanos con la democracia en el 2023

-	Unidad de análisis: peruanos encuestados sobre la satisfacción de la democracia

1.	Not at all satisfied
2.	Not very satisfied 
3.	Quite satisfied 
4.	Very satisfied 

creencias = ¿Qué frase refleja las creencias de los peruanos en el 2023 con respecto a la gobernabilidad?
-	Unidad de análisis: peruanos encuestados sobre las creencias sobre la gobernabilidad
1.	Democracy is preferable to any other kind of government
2.	Under some circumstances, an authoritarian government can be preferable to a democratic one
3.	For people like me, it doesn’t matter whether we have a democratic or non-democratic regime



**Variables de control**

etnia = ¿Con qué raza o etnicidad se identifica mejor?
-	Unidad de análisis: peruanos encuestados sobre la raza o etnia con la cual se identifican
2.	White
3.	Mestizo
4.	Indigenous 
6.	Black


estrato = ¿A qué clase social considera que pertenece?

-	Unidad de análisis: peruanos encuestados sobre su clase social
1.	Lower Class
2.	Lower- Middle class 
3.	Middle class 
4.	Upper-Middle class
5.	Upper class 


partido_pol = Familia Partido Político
-	Unidad de análisis: peruanos encuestados sobre su pertenencia a un partido político
0.	(Vote null / white, Do not vote / none)
20.	Social Democratic Parties
30.	Christian Democrat Parties
40.	Liberal Parties
50. Christian Democrat Parties 
60. Conservative Parties 
70. Nationalist Parties 
80. Agrarian Parties 
98. Electoral alliances (diverse origins) 
Se hizo una dicotomización donde
0: No se identifica con ningún partido  partido_pol1
1: Se identifican con un partido 

**Variable dependiente**

Para la variable dependiente se ha creado el siguiente índice:
Confianza en las instituciones = ¿Qué tanto confías en las instituciones públicas (Congreso, Gobierno, Presidente, Partidos políticos)?

-	Unidad de análisis: peruanos encuestados sobre la confianza que tienen en las instituciones públicas

1. No trust 
2. Little 
3. Some 
4. A lot 

Este índice está compuesto por las siguientes 4 variables:

Congreso: Confianza de los peruanos en el Congreso de la República en el 2023
1.	No trust 
2.	Little 
3.	Some 
4.	A lot 

Partidos _Políticos: Confianza de los peruanos/as en los partidos políticos en el 2023 
1.	No trust 
2.	Little 
3.	Some 
4.	A lot 

Presidente: Confianza de los peruanos en el Presidente de la República en el 2023
1.	No trust
2.	Little 
3.	Some 
4.	A lot

Gobierno: Confianza de los peruanos en el Gobierno en el 2023
1.	No trust 
2.	Little 
3.	Some 
4.	A lot

