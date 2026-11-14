# Tuttocrea — piano di validazione

Data: 14 novembre 2026 (Europe/Rome). Prezzi competitor verificati su pagine ufficiali o fonti che le citano, novembre 2026.

## Nome

**Tuttocrea**. Nome coniato (tutto + crea). Non risulta un marchio software o un prodotto IA già noto con questo nome. Evitati nomi già occupati nello stesso campo: Lumora, Reeluno, Narrivo, Velora, Publora, ProntoPack, Creatio, Creao, Creato, Unibot. Prima di un marchio o di un dominio a pagamento, Marian dovrebbe controllare tuttocrea.com / .ai e un’eventuale ricerca anteriore all’UIBM/EUIPO.

## Posizionamento (onesto)

L’utente scrive solo un argomento. Un unico bot produce in un flusso il pacchetto: nicchia/idea, script, titolo e tag SEO, thumbnail, voce IA, video, sottotitoli, calendario di pubblicazione. Il vantaggio rispetto a Canva, Jasper, Copy.ai, InVideo ed ElevenLabs non è «essere meglio su ogni pezzo», ma fare tutto insieme, a un prezzo unico, senza incollare cinque abbonamenti. Limiti da dire sempre: al lancio il video è un montaggio slideshow o testo-video breve, non un film generativo da studio; il calendario è un piano, non la pubblicazione automatica sui social; l’utente rivede e pubblica lui.

## Prezzi competitor (novembre 2026)

- **Canva Pro** (canva.com/pricing, pagina US): 144 USD/anno a persona; in Germania/area euro fonti che hanno letto la pagina riportano 12 €/mese oppure 110 €/anno. Business: 250 USD/anno a persona (17 €/mese o 170 €/anno in Germania). È un editor di design, non uno script-to-publish completo.
- **Jasper Pro** (jasper.ai/pricing): 69 USD/mese a posto, o 59 USD/mese se annuale. Prova 7 giorni. È scrittura e marketing, non voce/video completi.
- **Copy.ai Chat** (copy.ai/prices, ottobre–novembre 2026): 29 USD/mese, o 24 USD/mese se annuale (288 USD/anno), 5 posti. I piani workflow partono da 1.000 USD/mese. È chat/copy, non produzione video.
- **InVideo** (invideo.io/pricing): Starter 20 USD/mese oppure 10 USD/mese se annuale (400 crediti/posto); Plus 60 USD oppure 30 USD annuale (2.000 crediti). Forte sul video, non sul pacchetto intero da un solo bot.
- **ElevenLabs** (elevenlabs.io/pricing): Starter 6 USD/mese (5 USD annuale); Creator 22 USD/mese (18,33 USD annuale, 121k crediti). È il riferimento sulla voce, non su script, SEO e video insieme.

Uno stack tipico Canva Pro + InVideo Plus + ElevenLabs Creator + Copy.ai Chat arriva, a pagamento mensile, intorno a 87–114 €, e i pezzi restano da unire a mano.

## Prezzi Tuttocrea (EUR, IVA esclusa in attesa dei dati di fatturazione)

- **Prova 14 giorni**: 3 pacchetti completi, nessuna carta, poi si ferma. Serve a tenere bassi i costi API.
- **Avvio**: 19 €/mese — 12 pacchetti completi (circa 3 a settimana).
- **Creatore** (consigliato): 39 €/mese — 40 pacchetti, più varianti di thumbnail, voce fino a circa 2 minuti, video HD.
- **Studio**: 79 €/mese — 100 pacchetti, 2 utenti, voce fino a circa 3 minuti, priorità sulla coda.

I pagamenti non sono live: il sito raccoglie solo richieste di prova o accesso anticipato.

## Costo stimato per pacchetto (API, ordine di grandezza)

Un pacchetto = idea + script + SEO + 1 thumbnail + 5–8 immagini per lo slideshow + voce + montaggio + sottotitoli + calendario.

- Testo (modello economico tipo GPT-4o-mini / Haiku): circa 0,01–0,06 USD.
- Immagini (modello economico, 6–9 pezzi): circa 0,20–0,40 USD.
- Voce: OpenAI TTS circa 0,02 USD per 90 secondi; ElevenLabs circa 0,08–0,15 USD. Budget 0,05–0,15 USD.
- Montaggio slideshow (ffmpeg, storage): pochi centesimi.
- **Totale base: circa 0,40–0,70 USD (0,35–0,65 €)** a pacchetto. Un percorso voce/immagini più cari: 0,80–1,20 USD.

Non includere al lancio clip generative tipo Seedance: costano facilmente 0,50–2+ USD l’una e bruciano il margine.

Costo prova (3 pacchetti): circa 1–2 €. Se l’utente usa tutto il piano: Avvio ~6 € di API su 19 €; Creatore ~20 € su 39 €; Studio ~50 € su 79 €. Tenere i tetti rigidi. Se i costi reali superano queste stime, si riducono i pacchetti prima di alzare il prezzo.

## Cosa serve da Marian per andare live

1. **Stripe** (o equivalente UE) intestato a lui, con partita IVA: il sito oggi non prende carte e non deve prenderle finché Stripe non è collegato.
2. **Dati partita IVA** (ragione sociale, numero, sede) per fatture, footer e termini. Ha già detto di averla: servono i dettagli prima del primo pagamento, non per questa validazione.
3. **Conferma dell’email FormSubmit** se arriva una mail di attivazione su balint.marian2607@gmail.com: l’indirizzo era già attivato per hostbot su raw.githack.com, ma un URL nuovo può richiedere una nuova conferma.
4. **Chiavi API** (testo, immagini, voce) a suo nome, con tetto di spesa mensile, quando si passa dalla demo simulata al prodotto vero.
5. **Dominio** (se vuole tuttocrea.com / .ai) e in seguito un hosting vero; raw.githack va bene per validare.
6. **Testi legali** minimi (privacy, termini, recesso 14 giorni per i consumatori UE) prima di accettare abbonamenti a pagamento.

## Come arrivare alle prime iscrizioni (organico, niente spam a freddo)

1. Pubblicare landing + demo e chiedere la prova solo a chi visita il sito o chiede informazioni.
2. Marian può mostrare la demo sul suo Instagram, TikTok o YouTube, con un link in bio, senza promesse di guadagno.
3. Rispondere, senza sollecitare a freddo, a chi già chiede in commenti «che tool usi?» o cerca un flusso unico.
4. Un post onesto su Reddit/Facebook di creator (dove è permesso l’auto-promozione) che spiega il limite del video al lancio e la prova a 3 pacchetti.
5. Quando arrivano le prime mail: attivare la prova a mano, chiedere un feedback, e solo dopo collegare Stripe. Niente newsletter comprate, niente scraping di indirizzi, niente cold email.

## Prossimi passi prodotto (dopo le prime richieste)

1. Costruire il flusso reale con tetti credito identici a quelli dichiarati.
2. Esportare file (script, WAV/MP3, MP4 slideshow, SRT, PNG thumbnail, calendario in testo).
3. Solo più avanti, e solo con consenso e API ufficiali, valutare la pubblicazione assistita. Non è nel lancio.
