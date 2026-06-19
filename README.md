# uscio.exe - The Wrongverse Game

Un gioco horror 2D platform basato sulla storia originale di un giovane chiamato Michael che viene risucchiato nel **Wrongverse**, un universo alternativo e distorto dove tutto è sbagliato.

## Trama

Michael scarica un gioco misterioso chiamato **uscio.exe**. Quando lo apre, la schermata iniziale gli chiede di "Inserire anima". Il gioco lo risucchia nel **Wrongverse**, una versione horror del suo quartiere di Uscio (nelle alture di Recco, Liguria).

In questo universo distorto:
- Il cielo è coperto di nuvole pesanti
- Il sole è di un colore viola malato
- I mostri glitchati lo inseguono
- Esiste un suo doppio malvagio: **Wrong Michael**
- Deve raccogliere le lettere del suo nome (**M-I-C-H-A-E-L**) per scappare

## Gameplay

### Controlli
- **A / Freccia Sinistra**: Muoviti a sinistra
- **D / Freccia Destra**: Muoviti a destra
- **Spazio / W / Freccia Su**: Salta
- **X**: Inizia il gioco

### Meccaniche
- **Raccolta Lettere**: Raccogli tutte le 6 lettere per vincere
- **Nemici**: Evita o affronta i mostri glitchati che fanno danno
- **Sistema di Salute**: Inizi con 5 HP, ogni attacco toglie 0.5 HP
- **Finale**: Quando raccogli tutte le lettere, il portale si apre

## Nemici

1. **L'Ombra con gli Artigli**: Un mostro alto e scuro con occhi e denti luminosi bianchissimi
2. **Il Pastore con i Caproni Neri**: Un pastore misterioso con caproni aggressivi

## Installazione Locale

```bash
# Clonare il repository
git clone <repository-url>
cd uscio-exe-game

# Installare le dipendenze
npm install

# Avviare il server di sviluppo
npm run dev

# Compilare per la produzione
npm run build
```

## Deploy

Il gioco è costruito con Vite e React. Puoi deployarlo su qualsiasi piattaforma che supporta applicazioni Node.js o file statici HTML/CSS/JS.

### Con Docker
```bash
docker build -t uscio-exe-game .
docker run -p 3000:3000 uscio-exe-game
```

## Crediti

- **Gioco**: Sviluppato con React e Vite
- **Asset**: Generati con AI
- **Trama Originale**: Ispirata da una storia creativa

## Licenza

Tutti i diritti riservati.
