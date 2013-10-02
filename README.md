INF100 høsten 2013
==============

## HUSK: Forelesningen utgår torsdag 3. oktober. Øvingene går som normalt.

I dette arkivet finner du alt materiale til INF100 ved UMB høsten 2013.

For mer informasjon om arkivet og hvordan du kan bruke det, se [oversiktssiden for INF100](http://heplesser.github.io/UMB_INF100_H13/).

#### 2013-10-02
- **Forelsningen utgår torsdag 2. oktober.**
- Obligatorisk innleveringsoppgave 3 med frist 18. oktober er tilgjengelig i mappen [Obliger](https://github.com/heplesser/UMB_INF100_H13/tree/master/Obliger) og på [NBViewer](http://nbviewer.ipython.org/urls/raw.github.com/heplesser/UMB_INF100_H13/master/Obliger/INF100_H13_Oblig3.ipynb).

#### 2013-09-26
- Notebooken til forelesningen 26.09. er lagt ut, se mappen [Forelesninger](https://github.com/heplesser/UMB_INF100_H13/tree/master/Forelesninger).
- Notebooken er også tilgjengelig [via NBViewer](http://nbviewer.ipython.org/urls/raw.github.com/heplesser/UMB_INF100_H13/master/Forelesninger/INF100_H13_F04.ipynb)

#### 2013-09-19
- **Viktig:** De første versjonen av forelesningsplansjene inneholdt `snowflake()`-funksjoner som mikset bruk av `padde` og `sam`. Dette var feil! I den nyeste versjonen (lagt ut 19.09. kl 22.25) er dette rettet: inne i `snowflake()` funksjonen skal det bare stå `padde`.
- IPython Notebook for forelesningen 19.09. er lagt ut, se mappen [Forelesninger](https://github.com/heplesser/UMB_INF100_H13/tree/master/Forelesninger). Det er også tilgjengelige på [NBViewer](http://nbviewer.ipython.org/urls/raw.github.com/heplesser/UMB_INF100_H13/master/Forelesninger/INF100_H13_F03.ipynb).
- Obligatorisk innleveringsoppgave 2 med frist 4. oktober er tilgjengelig i mappen [Obliger](https://github.com/heplesser/UMB_INF100_H13/tree/master/Obliger) og på [NBViewer](http://nbviewer.ipython.org/urls/raw.github.com/heplesser/UMB_INF100_H13/master/Obliger/INF100_H13_Oblig2.ipynb).
- Se tipset under for råd til nedlasting.

#### 2013-09-17
- **Løsning for nedlastingsproblemer**: Jeg beklager at dette kommer sent, men løsningen på nedlastingsproblemene var "hidden in plain sight", som det heter på engelsk. Hvis du har problemer med å laste ned IPython Notebooks fra siden her, kan du laste ned hele arkivet som en Zip-fil ved å klikke på "Download ZIP" knappen ved siden (eller du kan [klikke på denne lenken](https://github.com/heplesser/UMB_INF100_H13/archive/master.zip)). Lagre filen, åpne den ved å dobbelklikke og den pakkes ut som `UMB_INF100_H13-master`. I den mappen finner du alle `.ipynb` filene (i undermappende `Forelesninger` og `Obliger`) og du kan flytte de til din `Python` mappe på vanlig måte for ditt operativsystem.
- **Utsatt innleveringsfrist**: Fristen for innleveringen av den første obligatoriske oppgaven utsettes med en uke til **fredag 27.09. kl 12.00** pga de tekniske problemene mange av dere har opplevd. NB: fristen for den andre obligatoriske innleveringen vil fortsatt være fredag 04.10.!

#### 2013-09-14
- Forlesningsplansjene er nå oppdatert iht materiale gjennomgått i forelesningen. De er også tilgjengelige via Fronter (under *Info*), i tilfelle du har problemer med nedlasting fra GitHub
- Anaconda installasjonen på datasalene er oppdatert til bl a IPython 1.0.0. Det bør gi bedre stabilitet, samt at tabellene vises nå korrekt i Notebooks.
- Hvis du har Internet Explorer som din standard nettleser på datasalene, kan du starte IPython med

        i:\anaconda\scripts\ipython notebook --pylab=inline --no-browser

  IPython vil da ikke åpne noen nettleservindu, men vise en nettadresse, vanligvis `http://127.0.0.1:8888`. Åpne Firefox og gå til den adressen for å åpne IPython Dashbord.

#### 2013-09-11
- [Forelesningsplansjene for torsdag, 12. september](https://github.com/heplesser/UMB_INF100_H13/tree/master/Forelesninger) er lagt ut. Du kan også se de på og laste de ned fra [nbviewer](http://nbviewer.ipython.org/urls/raw.github.com/heplesser/UMB_INF100_H13/master/Forelesninger/INF100_H13_F02.ipynb)
- Jeg har lagt inn informasjon vedrørende en del problemer på [Issues listen](https://github.com/heplesser/UMB_INF100_H13/issues)
- Mac OSX: Noen får `Permission denied` feilmeldinger når de prøver å utfør "Et ekstra skritt på Mac" i installasjonsveiledningen. [Her finner du en løsning.](https://github.com/heplesser/UMB_INF100_H13/issues/2)
- Øvingsgruppe 6, onsdager 10-12, utgår pga manglende etterspørsel

#### 2013-09-09
- Installasjonsveiledning for programvare oppdatert: "Et ekstra skritt på Mac" oppdatert
- Turtle vinduet kan virke død, men er det (oftest) ikke. Skilpadden vil bevege seg når den får et kommando.
- Hvis du får en voldsom feilmelding ved oppstart av Python på Mac som ender med noe som `ValueError: unknown locale: UTF-8`, se avsnittet "Et ekstra skritt på Mac" i den oppdaterte installasjonsveiledningen.

Mvh
Hans E Plesser
