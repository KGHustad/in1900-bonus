Dette repoet inneholder materialet fra bonusforelesningen i IN1900 19. desember 2017. Screencast finnes [her](https://screencast.uninett.no/relay/ansatt/krihusuio.no/2017/19.12/2338798/IN1900_2017-12-19_Bonusforelesning_-_20171219_132900_39.html), og lysarkene ligger [her](http://folk.uio.no/krihus/in1900/h17/bonus.pdf).

Du kan laste ned hele dette repoet med følgende kommando (logg inn med vanlig UiO-brukernavn og -passord)
``` sh
git clone https://github.com/KGHustad/in1900-bonus.git
```

Du kan også kjøre eksemplene på [UiOs JupyterHub](https://jupyterhub.uio.no). Opprett en ny terminal, og kjør
``` sh
git clone https://github.com/KGHustad/in1900-bonus.git ~/work/in1900-bonus
```
da blir filene herfra lastet en mappe på øverste nivå i JupyterHub.

## Kompatibilitet
Det meste bør fungere fint hvis man allerede har Anaconda installert. For å kunne laste ned notebooks som PDF, må man i tillegg ha LaTeX installert.

* Jupyter
  * __Linux__: `sudo -H pip install jupyter`
  * __Mac__: Følger med Anaconda
  * __Windows__: Følger med Anaconda
* LaTeX
  * __Linux:__ Dette er trivielt å installere om det ikke allerede er installert.
    * __Ubuntu__ `sudo apt-get install texlive-full` (Dette inneholder alle LaTeX-pakker, og kan ta litt tid å laste ned og installere)
    * __Fedora__ `sudo dnf install texlive-scheme-full` (bytt ut `dnf` med `yum` på eldre versjoner av Fedora)
  * __Mac__: Se instruksjoner på http://tug.org/mactex/
  * __Windows__: Installér fra https://miktex.org/ (For å kunne kjøre LaTeX fra kommandolinjen og for at Jupyter skal finne programmet, kan det hende at `C:\\Program Files\MikTeX\bin` (eller noe tilsvarende) må legges inn i miljøvariablen `PATH`.)
