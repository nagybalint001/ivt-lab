# Test tervek

* fireTorpedo SINGLE módban hívása egyszer. Az első tár nem üres, csak az elsődleges tár fire metódusa hívódik meg, végül sikeres lesz a tüzelés.
* fireTorpedo SINGLE módban hívása egyszer. Az első tár üres, a második nem. Az első tár nem tüzel, csak a második egyszer. Sikeres lesz a tüzelés.
* fireTorpedo SINGLE módban hívása egyszer. Mindkét tár üres, egyik tár fire metódusa sem hívódik meg. A tüzelés nem lesz sikeres.
* fireTorpedo ALL módban hívása egyszer. Mindkét tár nem üres, mindkét tár tüzel, sikeres lesz a tüzelés.
* fireTorpedo ALL módban hívása egyszer. Az első tár üres, a második nem. Csak a második tár tüzel. Sikeres a tüzelés.
* fireTorpedo ALL módban hívása egyszer. A második tár üres, az első nem. Csak az első tár tüzel. Sikeres a tüzelés.
* fireTorpedo ALL módban hívása egyszer. Mindkét tár üres. Egyik fire metódusa sem hívódik meg. Sikertelen a tüzelés.


