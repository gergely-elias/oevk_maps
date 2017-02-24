<h3>Orszaggyulesi egyeni valasztokeruletek (OEVK) terkepei</h3>
Ebben a repository-ban egyetlen GeoJSON formatumu file-ba gyujtve talalhato meg az osszes OEVK teruletet leiro adat.  
A forrasadat a Nemzeti Valasztasi Iroda (NVI) honlapjan szabadon elerheto, de nem szabvanyos strukturaja miatt a tovabbi felhasznalashoz feldolgozast igenyel. A felhasznalast az sem konnyiti meg, hogy minden OEVK-hoz tartozo adat kulon file-ban talalhato (pl. a Budapesti 1-es OEVK-e a http://www.valasztas.hu/dyn/pv14/map/oevk/M01/01/oevk.js allomanyban).  
Az `oevk.geo.json` allomany szokozokkel es sortoresekkel emberi szem szamara attekinthetobb, az `oevk.min.geo.json` ezzel szemben nem tartalmaz ilyen karaktereket. A ket file kozott egyeb elteres nincsen.  

Ismereteim szerint az NVI honlapjan szereplo adatokat szerzoi jog nem vedi.  
Mivel azonban onnan szarmazik a forrasadat, illendo ennek megemlitese ezen repository-beli file-ok felhasznalasa eseten.

<hr>
<h3>Maps of the Hungarian constituencies</h3>
This repository contains the areas in a single file of standard GeoJSON format.  
The data was collected from the website of the National Election Office, where it is publicly available, but spread across many files, and it is in a format which needs some preprocessing before it can be put to actual use. You can find an actual example at http://www.valasztas.hu/dyn/pv14/map/oevk/M01/01/oevk.js.  
`oevk.geo.json` is a human readable version, while `oevk.min.geo.json` does not contain any whitespace characters. Otherwise the files are identical.  

As far as I know, the raw data on the website of the National Election Office is not copyrighted.  
Still I think they deserve credits, and I recommend mentioning them as source if you are using the files of this repository.
