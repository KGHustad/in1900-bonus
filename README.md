Dette repoet inneholder materialet fra bonusforelesningen i IN1900 19. desember 2017. Screencast finnes [her](FIXME).

Du kan laste ned hele dette repoet med følgende kommando (logg inn med vanlig UiO-brukernavn og -passord)
``` sh
git clone https://github.com/KGHustad/in1900-bonus.git
```


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
