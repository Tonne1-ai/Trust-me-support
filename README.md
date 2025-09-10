# Trust Me - Support & Developer Site

Dette er support-nettsiden og utviklernettstedet for Trust Me spillet. Nettstedet fungerer både som support for brukere og som utviklernettsted for AdMob-integrasjon.

## Funksjonalitet

### Support
- Spillregler og instruksjoner
- Vanlige spørsmål (FAQ)
- Kontaktinformasjon

### Utviklernettsted
- AdMob Publisher ID: `pub-3194286622206833`
- `app-ads.txt` fil på rotnivå for AdMob-godkjenning
- Teknisk informasjon om appen

## Hvordan deploye til GitHub Pages

1. Gå til repository settings
2. Scroll ned til "Pages" seksjonen
3. Under "Source", velg "Deploy from a branch"
4. Velg "main" branch og "/ (root)" folder
5. Klikk "Save"

## Filstruktur

- `index.html` - Hovedside (support + utviklerinfo)
- `styles.css` - Styling
- `privacy.html` - Personvernerklæring
- `app-ads.txt` - AdMob publisher verifisering
- `robots.txt` - SEO og crawler instruksjoner
- `README.md` - Denne filen

## AdMob-integrasjon

For at AdMob skal fungere optimalt, må `app-ads.txt` filen være tilgjengelig på rotnivå av domenet. Filen inneholder:

```
google.com, pub-3194286622206833, DIRECT, f08c47fec0942fa0
```

## Oppdateringer

For å oppdatere siden, bare push endringer til main branch. GitHub Pages vil automatisk redeploye.

## SEO og Meta Tags

Nettstedet inkluderer:
- Meta beskrivelser og nøkkelord
- Open Graph tags for sosiale medier
- Robots.txt for søkemotoroptimalisering
- Strukturert innhold for bedre indeksering