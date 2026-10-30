# ARST - Collegamento Ferroviario Alghero Centro – Alghero Aeroporto, con impianto di produzione di idrogeno

## Planimetria delle emergenze

Planimetria interattiva delle aree di cantiere, dei varchi di accesso e della viabilità esistente utilizzata anche dai mezzi di cantiere.

| Contenuto | File |
|---|---|
| Planimetria interattiva (aprire il sito del repository) | [index.html](index.html) |
| Planimetria per Google Maps / Google Earth | [Planimetria_emergenze.kml](Planimetria_emergenze.kml) |
| Solo varchi per Google Maps | [Varchi_cantiere.kml](Varchi_cantiere.kml) |
| Cartelli A3 di tutti i varchi (un PDF, una pagina per varco) | [cartelli/Cartelli_varchi_A3.pdf](cartelli/Cartelli_varchi_A3.pdf) |
| Cartelli A3 singoli | cartella [cartelli](cartelli) |
| Dati GeoJSON (EPSG:32632 e WGS 84) | cartella [dati](dati) |
| Stato dei varchi (in esercizio / dismesso) | [stati_varchi.json](stati_varchi.json) |

### Tipi di varco

- **Cerchio rosso**: varco di cantiere
- **Rombo blu**: varco in condivisione con ANAS (V5, V6)
- **Quadrato verde**: ingresso campo base (V12)
- **Grigio**: varco dismesso

### Raggiungere un varco con il navigatore

- Dalla planimetria interattiva: aprire il varco (menu a tendina, tabella o mappa) e premere **Naviga fino al varco**.
- Dal cartello: inquadrare il QR code.
- Su Google My Maps (<https://www.google.com/mymaps>): *Crea una nuova mappa* → *Importa* → caricare `Planimetria_emergenze.kml`. La mappa si apre poi dall'app Google Maps (*Salvati* → *Mappe*) e ogni varco ha il pulsante *Indicazioni*.

### Stato dei varchi

Tutti possono consultare la planimetria. Lo stato *in esercizio / dismesso* può essere cambiato solo dal gestore (il proprietario del repository):

1. Creare un token su GitHub: *Settings* → *Developer settings* → *Personal access tokens* → *Fine-grained tokens* → *Generate new token*; *Repository access*: solo questo repository; *Permissions* → *Contents*: **Read and write**.
2. Nella planimetria premere **Accesso gestore** e incollare il token (resta salvato solo nel proprio browser).
3. Aprire un varco e scegliere lo stato: la modifica viene salvata nel repository ed è subito visibile a tutti.

GitHub accetta la modifica solo da chi ha permesso di scrittura sul repository: gli altri utenti vedono lo stato ma non possono cambiarlo.

Il file KML e i cartelli riportano lo stato al momento della generazione; la planimetria interattiva mostra sempre lo stato aggiornato.

---
Sistema di riferimento: EPSG:32632 (WGS 84 / UTM 32N). Strade e cartografia di base: © OpenStreetMap contributors (ODbL).
