# Contracts

Za svako od 22 polja postoje tri zasebne instrukcije: identifikacija iz OCR dokumentacije, Excel verifikacija i JSON izvoz. Podrazumevani izlaz osnovne obrade ostaje UTF-8 TSV. Excel verifikacija čita sačuvani nalaz i daje dopunjenu TSV evidenciju, TXT razlike i statistiku. Srpsko tumačenje prvog lista obrasca ima prednost kada dopunjuje ili menja englesko uputstvo.

JSON se izrađuje na izričit zahtev. Izvoz prenosi poslednji dokumentovani nalaz, nezavisno od ishoda Excel validacije. [Zajednička instrukcija](instrukcija_za_izvoz_polja_u_json.txt) propisuje format; instrukcija konkretnog polja određuje kolone i mapiranje vrednosti.

| Polje / tačan JSON `field` | Excel kolona | Osnovna instrukcija | Excel verifikacija | JSON izvoz |
|---|---|---|---|---|
| Zakupodavac | E | [Identifikacija](instrukcija_za_identifikaciju_zakupodavca_v4.txt) | [Verifikacija](instrukcija_za_validaciju_zakupodavca.txt) | [Izvoz](instrukcija_za_izvoz_zakupodavca_u_json.txt) |
| Adresa imovine | H | [Identifikacija](instrukcija_za_obradu_adresa_imovine.txt) | [Verifikacija](instrukcija_za_validaciju_adrese_imovine.txt) | [Izvoz](instrukcija_za_izvoz_adrese_imovine_u_json.txt) |
| Broj osnovnog ugovora | C | [Identifikacija](instrukcija_za_identifikaciju_broja_ugovora.txt) | [Verifikacija](instrukcija_za_validaciju_broja_ugovora.txt) | [Izvoz](instrukcija_za_izvoz_broja_ugovora_u_json.txt) |
| Početak zakupa | Q | [Identifikacija](instrukcija_za_identifikaciju_datum_pocetka_zakupa.txt) | [Verifikacija](instrukcija_za_validaciju_datum_pocetka_zakupa.txt) | [Izvoz](instrukcija_za_izvoz_datum_pocetka_zakupa_u_json.txt) |
| Valuta ugovora | D | [Identifikacija](instrukcija_za_identifikaciju_valute.txt) | [Verifikacija](instrukcija_za_validaciju_valute.txt) | [Izvoz](instrukcija_za_izvoz_valute_u_json.txt) |
| Kategorija imovine | F | [Identifikacija](instrukcija_za_identifikaciju_kategorije_imovine.txt) | [Verifikacija](instrukcija_za_validaciju_kategorije_imovine.txt) | [Izvoz](instrukcija_za_izvoz_kategorije_imovine_u_json.txt) |
| Kraj zakupa | U | [Identifikacija](instrukcija_za_identifikaciju_datum_kraja_zakupa.txt) | [Verifikacija](instrukcija_za_validaciju_datum_kraja_zakupa.txt) | [Izvoz](instrukcija_za_izvoz_kraj_zakupa_u_json.txt) |
| Automatsko produženje | V | [Identifikacija](instrukcija_za_identifikaciju_automatskog_produzenja.txt) | [Verifikacija](instrukcija_za_validaciju_automatskog_produzenja.txt) | [Izvoz](instrukcija_za_izvoz_automatsko_produzenje_u_json.txt) |
| Trajanje produženja | W | [Identifikacija](instrukcija_za_identifikaciju_trajanja_produzenja.txt) | [Verifikacija](instrukcija_za_validaciju_trajanja_produzenja.txt) | [Izvoz](instrukcija_za_izvoz_trajanje_produzenja_u_json.txt) |
| Učestalost plaćanja | BI | [Identifikacija](instrukcija_za_identifikaciju_ucestalosti.txt) | [Verifikacija](instrukcija_za_validaciju_ucestalosti.txt) | [Izvoz](instrukcija_za_izvoz_ucestalost_placanja_u_json.txt) |
| Dospeće plaćanja | BJ | [Identifikacija](instrukcija_za_identifikaciju_dospece.txt) | [Verifikacija](instrukcija_za_validaciju_dospece.txt) | [Izvoz](instrukcija_za_izvoz_dospece_placanja_u_json.txt) |
| Vrsta plaćanja | BK | [Identifikacija](instrukcija_za_identifikaciju_vrste.txt) | [Verifikacija](instrukcija_za_verifikaciju_vrste_Excel.txt) | [Izvoz](instrukcija_za_izvoz_vrsta_placanja_u_json.txt) |
| Odvojivost komponenti | BL | [Identifikacija](instrukcija_za_identifikaciju_odvojivosti.txt) | [Verifikacija](instrukcija_za_verifikaciju_odvojivosti_Excel.txt) | [Izvoz](instrukcija_za_izvoz_odvojivost_komponenti_u_json.txt) |
| Iznos ostalih komponenti | BM | [Identifikacija](instrukcija_za_identifikaciju_ostalih_komponenti.txt) | [Verifikacija](instrukcija_za_excel_verifikaciju_ostalih_komponenti.txt) | [Izvoz](instrukcija_za_izvoz_iznos_ostalih_komponenti_u_json.txt) |
| Odbitnost PDV-a | BN | [Identifikacija](instrukcija_za_identifikaciju_pdv.txt) | [Verifikacija](instrukcija_za_verifikaciju_pdv_Excel.txt) | [Izvoz](instrukcija_za_izvoz_odbitnost_pdv_u_json.txt) |
| Neodbitni iznos | BO | [Identifikacija](instrukcija_za_identifikaciju_neodbitnog_iznosa.txt) | [Verifikacija](instrukcija_za_verifikaciju_neodbitnog_iznosa_Excel.txt) | [Izvoz](instrukcija_za_izvoz_neodbitni_iznos_u_json.txt) |
| Fiksna zakupnina | BQ | [Identifikacija](instrukcija_za_identifikaciju_fiksne_zakupnine.txt) | [Verifikacija](instrukcija_za_verifikaciju_fiksne_zakupnine_Excel.txt) | [Izvoz](instrukcija_za_izvoz_fiksna_zakupnina_u_json.txt) |
| Osnova varijabilnog plaćanja | BT | [Identifikacija](instrukcija_za_identifikaciju_osnove_varijabilne.txt) | [Verifikacija](instrukcija_za_verifikaciju_osnove_varijabilne_Excel.txt) | [Izvoz](instrukcija_za_izvoz_osnova_varijabilnog_placanja_u_json.txt) |
| Varijabilna zakupnina | BU | [Identifikacija](instrukcija_za_identifikaciju_varijabilnog_iznosa.txt) | [Verifikacija](instrukcija_za_excel_verifikaciju_varijabilnog_iznosa.txt) | [Izvoz](instrukcija_za_izvoz_varijabilna_zakupnina_u_json.txt) |
| Opis indeksa | BV | [Identifikacija](instrukcija_za_identifikaciju_opisa_indeksa.txt) | [Verifikacija](instrukcija_za_excel_verifikaciju_opisa_indeksa.txt) | [Izvoz](instrukcija_za_izvoz_opis_indeksa_u_json.txt) |
| Učestalost indeksacije | BW | [Identifikacija](instrukcija_za_identifikaciju_ucestalosti_indeksacije.txt) | [Verifikacija](instrukcija_za_excel_verifikaciju_ucestalosti_indeksacije.txt) | [Izvoz](instrukcija_za_izvoz_ucestalost_indeksacije_u_json.txt) |
| IFRS konto | CM | [Identifikacija](instrukcija_za_identifikaciju_ifrs_konta.txt) | [Verifikacija](instrukcija_za_verifikaciju_ifrs_konta_Excel.txt) | [Izvoz](instrukcija_za_izvoz_ifrs_konta_u_json.txt) |

Registar za JSON izvoz je `C:\Kontroling\IFRS\IFRS web aplikacija\extracted_data\registar_osnovnih_ugovora.csv`. On određuje obuhvat, postojeće `case_id` oznake i redosled. JSON fajlovi se čuvaju u istom folderu, kao UTF-8 niz objekata sa tačno tri tekstualna ključa: `case_id`, `field`, `value`. Neutvrđeni nalazi izvoze se kao tekst `"NA"`; za potvrđen zakup na neodređeno polje „Kraj zakupa” zadržava prazan tekst `""` prema detekciji.

Aktuelni odobreni skup ima 600 ugovora iz 376 Z lokala. Broj zapisa pri svakom izvozu proverava se prema važećem registru. Šest ugovora bez osnovnog OCR-a ima dokaz u `C:\Kontroling\OUT\registar_osnovnih_ugovora_provera\dokazi_ugovora_bez_osnovnog_OCR.csv`. Dodatni ugovori izvan ovog skupa trenutno nisu uključeni. Istorijske putanje registra i obuhvat u osnovnim instrukcijama dokumentuju te obrade; JSON izvoz koristi gore navedeni odobreni registar. Sve Excel verifikacije koriste list `contract-entries` i Z šifru iz kolone G.

Prateći doslovni opis BM čuva se u [definicija_B19_C19.txt](definicija_B19_C19.txt).

Za IFRS konto (CM) važi izričito korisničko pravilo da se svi ugovori tretiraju kao **third party**. Dokumentovana vrsta imovine određuje konto: shop `741721`, ostale zgrade/prostori `741621`, vozila `741821`. Nepoznat IC odnos ne daje `NA`; `NA` ostaje kada vrsta imovine ili njeno mapiranje nije utvrđeno. Third party je korisnički podrazumevan izbor, a ne dokaz nezavisnosti stranaka. Korisnici mogu naknadno ručno izmeniti IC klasifikaciju u finalnom setu. Produkcioni JSON ovog polja je `ifrs_konto.json` u gore navedenom izlaznom folderu.
