# Twitter Calcio Wiki — Backup & Archivio

Questo repository contiene i backup periodici completi di **Twitter Calcio Wiki**, l'enciclopedia collaborativa dedicata alla cultura, ai protagonisti e agli eventi del Twitter/X calcistico italiano.

🔗 **Wiki online:** https://twittercalcio.miraheze.org

## Contenuto del repository
* `*.xml` — Dump completo di tutte le voci, i template, le categorie e la cronologia delle revisioni (formato MediaWiki).
* `*.json` — Configurazione completa della wiki (estensioni attive, namespace e permessi utenti).

## Come ripristinare la wiki in caso di emergenza
1. Creare una nuova istanza MediaWiki (su Miraheze o su un server proprio).
2. Importare il file `.xml` tramite la pagina `Speciale:Importa` (`Special:Import`).
3. Applicare le estensioni e i permessi elencati nel file `.json` tramite `ManageWiki`.
