# Lotterie Keramiek Website

Een mooie, responsive one-page website voor Lotterie Keramiek.

## Folder Structuur

```
LotterieKeramiek/
├── index.html              # De hoofdwebsite
├── hero-desktop/           # Desktop hero afbeelding
│   └── heroDesktop.jpg     # Plaats hier je desktop sfeerfoto
├── hero-mobile/            # Mobiele hero afbeelding
│   └── heroPhone.jpg       # Plaats hier je mobiele sfeerfoto
├── stappen/                # Proces/stappenplan foto's
│   ├── stap1.jpg           # Stap 1: Voorbereiding
│   ├── stap2.jpg           # Stap 2: Vormgeving
│   ├── stap3.jpg           # Stap 3: Droging
│   └── stap4.jpg           # Stap 4: Glazuren & Bakken
├── collectie/              # Galerij / collectie foto's
│   ├── foto1.jpg
│   ├── foto2.jpg
│   ├── foto3.jpg
│   └── foto4.jpg
└── README.md               # Deze file
```

## Hoe voeg je foto's toe?

### 1. Desktop Hero Foto
Plaats een foto in `hero-desktop/` met de naam **exact**: `heroDesktop.jpg`

### 2. Mobiele Hero Foto
Plaats een foto in `hero-mobile/` met de naam **exact**: `heroPhone.jpg`

### 3. Stappen Proces Foto's
Plaats de 4 proces foto's in de `stappen/` folder met exacte namen:
- `stap1.jpg` - Voorbereiding
- `stap2.jpg` - Vormgeving
- `stap3.jpg` - Droging
- `stap4.jpg` - Glazuren & Bakken

### 4. Collectie Foto's
Plaats alle collectie foto's in de `collectie/` folder met deze namen:
- `foto1.jpg`
- `foto2.jpg`
- `foto3.jpg`
- `foto4.jpg`
- Enzovoort...

Om meer foto's toe te voegen:

1. **Plaats je foto** in de `collectie/` folder (bijv. `foto5.jpg`)
2. **Voeg een nieuw gallery item toe** in `index.html` onder de "Onze Collectie" sectie:

```html
<div class="gallery-item">
    <img src="collectie/foto5.jpg" alt="Collectie item 5">
    <div class="gallery-caption">
        <h3>Titel van het werk</h3>
        <p>Korte beschrijving</p>
    </div>
</div>
```

3. **Sla het bestand op** en refresh de website - je nieuwe foto verschijnt automatisch!

## Contactgegevens aanpassen

Zoek in `index.html` naar de "Contact" sectie en pas aan:
- Email adres (regel met `mailto:`)
- Telefoonnummer (regel met `tel:`)
- Instagram handle
- Adresgegevens

## Website bekijken

Open `index.html` in je browser, of gebruik een lokale server:

```bash
# Als je Python hebt:
python -m http.server 8000

# Ga dan naar http://localhost:8000
```

## Features

- **Responsive**: Werkt perfect op PC, tablet en mobiel
- **Eén pagina**: Alle informatie op één overzichtelijke pagina
- **Snel ladend**: Geen zware frameworks, puur HTML/CSS/JS
- **Makkelijk uitbreidbaar**: Voeg onbeperkt foto's toe aan de collectie
- **Twee verschillende designs**: Desktop en mobiel hebben elk hun eigen unieke look
- **Proces sectie**: Toont het stappenplan van het keramiek maken
