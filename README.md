# Paljassaare radari töö juhend

Antud README fail on juhend kaldaradari andmete lugemiseks, analüüsiks ja 
statistilise masinõppe läbiviimiseks. 

Tegemist on osa AI ja suurandmed (NSO8025 - Taltech) ainest.

Autor: Sander Rikka, sander.rikka@taltech.ee 

### Python environment
- Projekti kaustas on requirements.txt file, mis defineerib vajalikud python paketid antud töö tegemiseks.
- Spyder kasutab conda
  - Kellel on ka Anaconda prompt, saab selle konsooliga environmente luua ja pakette installida
- Võib kasutada ka virtual environments: https://docs.python.org/3/library/venv.html
  - Vajab CMD programmi kasutamist või mõnda muud terminali 
  - Oluline on CMD või Anaconda prompt'iga liikuda sinna kausta, kus antud projekti failid on alla laetud.

>**using pip** (if environment is already created and activated)
> 
>pip install -r requirements.txt
>
>**using Conda**
> 
>conda create --name <env_name> --file requirements.txt
> 

# Nädal 1
1. Eesmärk radari andmed sisse lugeda, neid joonisele panna ja neid paremini tundma õppida 
> notebook/radar_explore.ipynb
2. Eesmärk radari andmetest välja lugeda mõõtmisandmete kohal olevad väärtused
   3. Milline strateegia? 
      4. Mingi mõõtmist ümbritseva ala statistilised näitajad?
      5. Valitud ala piksli väärtused (vektorina, 2D)?
      6. Midagi muud - paku tunnis.
> notebook/radardata_extract.ipynb
3. Eesmärk mõõtmisandmed sisse lugeda, neid graafikutel joonistada ja analüüsida 
> notebook/measurements_explore.ipynb

| Buoy station     | Paljassaare | Vahemadal | Hülkari |
|------------------|-------------|-----------|---------|
| Longitude &deg;E | 24.7033     | 24.6662   | 24.6116 |
| Latitude &deg;N  | 59.4982     | 59.5102   | 59.5394 |
| Distance (km)    | 1.42        | 3.60      | 8.07    | 

# Nädal 2
1. Töö _feature'itega_, nende graafikutel kujutamine, filtreerimine, analüüs/kirjeldamine.
2. Esimesed treeningud.


# Nädal 3
1. Mudelite treenimine. _Feature importance_. 
2. Tulemuste kirjeldamine ja raporti tegemine. 