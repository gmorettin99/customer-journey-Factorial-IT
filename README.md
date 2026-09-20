# Factorial IT — Mappa ecosistema

Mappa animata interattiva. Un clic sull'omino al centro rivela un blocco alla volta;
un clic sulla card **Inventario** apre il video demo.

## Contenuto della cartella

| File | Cosa |
|---|---|
| `index.html` | la mappa |
| `inventario-one.mp4` | video demo (H.264) |
| `inventario-one.webm` | stesso video, formato di riserva |
| `.nojekyll` | dice a GitHub di servire i file così come sono |

I quattro file vanno caricati insieme, nella stessa cartella.

## Pubblicare su GitHub Pages

Tutto dal browser, senza riga di comando.

1. Su **github.com** → **New repository**. Nome: `factorial-it-map`. Crea.
2. Nel repository vuoto → **uploading an existing file**. Trascina i quattro file. **Commit changes**.
3. **Settings** → **Pages** → Source: *Deploy from a branch* → Branch: `main`, cartella `/ (root)` → **Save**.
4. Dopo circa un minuto la mappa è online su:
   `https://<tuo-utente>.github.io/factorial-it-map/`

Se il file `.nojekyll` non compare quando trascini (alcuni sistemi nascondono i file
che iniziano con un punto), non è un problema: qui non serve davvero, ma se vuoi
aggiungerlo usa **Add file → Create new file** e chiamalo `.nojekyll`, lasciandolo vuoto.

## Lingue

La pillola in basso a destra cambia lingua a ogni clic, oppure tasto **L**.
Per aprire direttamente in una lingua, aggiungi il parametro all'indirizzo:

```
.../factorial-it-map/?lang=en     it · en · es · de · pt · fr
```

## Comandi

| Azione | Come |
|---|---|
| Avanzare di un blocco | clic sull'omino, o **barra spaziatrice** |
| Completare subito il blocco in corso | clic di nuovo mentre scrive |
| Ricominciare da capo | tasto **R** |
| Modalità automatica (senza clic) | tasto **A** |
| Velocità | frecce **←** / **→** |
| Nascondere i comandi | tasto **H** |
| Chiudere il video | **Esc**, la **X**, o clic fuori dal riquadro |
| Pausa del video | **barra spaziatrice** mentre il video è aperto |

## Video ospitato altrove

Se preferisci tenere il video su un altro server, punta la mappa lì senza
modificare il file:

```
.../index.html?video=https://esempio.com/inventario-one.mp4
```

## Nota

Un repository su GitHub Pages con piano gratuito è **pubblico**: chiunque abbia
l'indirizzo può vedere la mappa e il video, che contiene dati di inventario di
esempio. Verifica internamente prima di pubblicare.
