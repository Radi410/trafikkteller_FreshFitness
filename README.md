# trafikkteller_FreshFitness (ikke ferdigstilt)
Denne løsningen viser hvor mange medlemmer som er i senteret akkurat nå, og predikerer fremtidig trafikk basert på historiske mønstre fra forrige uke.

## Filstruktur
- `parser.py` - Parser inn-/utsjekk-data fra Exerp
- `calculator.py` - Beregner nåværende antall medlemmer
- `storage.py` - Lagrer data og genererer søylediagram
- `predictor.py` - Predikerer trafikk basert på forrige uke
- `index.html` - Frontend med sanntidsvisning
- `style.css` - Styling
- `dummy_data.json` - Testdata

## Installasjon
```bash
git clone https://github.com/[ditt-brukernavn]/trafikkteller_FreshFitness.git
cd trafikkteller_FreshFitness
python3 calculator.py
```

Åpne `index.html` i nettleser.

## Teknologi
Python | HTML | CSS | JavaScript
EOF

# Første commit
git add .
git commit -m "Initial commit: Prosjektstruktur for traffikteller"

# Koble til GitHub (erstatt med din repo-url)
git remote add origin https://github.com/radi410/trafikkteller_FreshFitness.git
git branch -M main
git push -u origin main
