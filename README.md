# Audio-Streaming-Dienstes
## Das End-Ziel besteht daran,  ein Systems zur Verwaltung eines Audio-Streaming-Dienstes zu implementieren.

### Das Projkt besteht aus insgesamt 4 Schritten.
#### 1- ER-Modellierung der Datenbank.
#### 2- Überführung der ER-Modellierung in das relationale Modell.
#### 3- Implementierung der Datenbank in SQLite.
#### 4- Umsetzung des dazugehörigen RESTful Web Services.

## In dieser Repo werde ich  den ersten Schritt und den zweiten zusammen machen . 
#### So ich werde das ER-Model mit Hilfe yEd Fraph Editor erstellen.

## was ich in diesem Schritt gmecht habe ist folgendes ..

man kann sich in das System mit name, machname ..usw anmelden, und die normale Dienst nutzen, oder man meldet sich dann mit der Premium-Veriante, und so hat man dann ein paar Vorteile mehr wie zb. ,dass man ein Playlist mit bieliebigen titels erstellt. 

Es gibt auch Kuenstler, die Titels erstellen, und sich zu einem Band-Mitglied machen.

Albums können von einem Kuenstler oder von einem Band erstellt werden, und ein Album besteht aus mindestens ein Titel.

Titels haben Speicherorte, und können zu einem Genre gehören.

Nutzer können Titles kommentieren, und Playlist bewerten ,..


## Hier könnte man sich das Graph des System anschauen.

https://github.com/JosephAlzieb/Audio-Streaming-Dienstes-1-and-2/blob/master/er_Joseph_Alzieb.pdf

## der Zweite Schritt bestehr daran, das ER-model in erin Relation-model zu überführen. 
##### in diesem Schritt habe ich ein paar Sachen korrigiert, und zwar ich habe "Email" statt "Nutzername" bei "Nutzer" als primary-key gesetzt.

## Hier könnte man sich die Überführung in die Relation-model anschauen.

https://github.com/JosephAlzieb/Audio-Streaming-Dienstes-1-and-2/blob/master/Phase2/relation-model.pdf
