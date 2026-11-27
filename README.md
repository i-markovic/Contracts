# Contracts

Za svaki entitet primeni instrukciju za identifikaciju na OCR ugovorima i povezanim dokumentima. Podrazumevani izlaz identifikacije je UTF-8 TSV. Excel verifikacija čita taj TSV i daje dopunjenu TSV evidenciju, TXT razlike i statistiku. Sve verifikacije koriste list `contract-entries` i Z šifru iz kolone G.

JSON je zaseban izvoz iz TSV-a na zahtev.

| Entitet | Identifikacija | Excel verifikacija | Excel kolona | Opcioni JSON izvoz |
|---|---|---|---|---|
| Zakupodavac | [TSV](instrukcija_za_identifikaciju_zakupodavca_v4.txt) | [Verifikacija](instrukcija_za_validaciju_zakupodavca.txt) | E | [Izvoz](instrukcija_za_izvoz_zakupodavca_u_json.txt) |
| Adresa imovine | [TSV](instrukcija_za_obradu_adresa_imovine.txt) | [Verifikacija](instrukcija_za_validaciju_adrese_imovine.txt) | H | [Izvoz](instrukcija_za_izvoz_adrese_imovine_u_json.txt) |
| Broj osnovnog ugovora | [TSV](instrukcija_za_identifikaciju_broja_ugovora.txt) | [Verifikacija](instrukcija_za_validaciju_broja_ugovora.txt) | C | [Izvoz](instrukcija_za_izvoz_broja_ugovora_u_json.txt) |
| Početak zakupa | [TSV](instrukcija_za_identifikaciju_datum_pocetka_zakupa.txt) | [Verifikacija](instrukcija_za_validaciju_datum_pocetka_zakupa.txt) | Q | [Izvoz](instrukcija_za_izvoz_datum_pocetka_zakupa_u_json.txt) |
| Valuta ugovora | [TSV](instrukcija_za_identifikaciju_valute.txt) | [Verifikacija](instrukcija_za_validaciju_valute.txt) | D | [Izvoz](instrukcija_za_izvoz_valute_u_json.txt) |
| Kategorija imovine | [TSV](instrukcija_za_identifikaciju_kategorije_imovine.txt) | [Verifikacija](instrukcija_za_validaciju_kategorije_imovine.txt) | F | [Izvoz](instrukcija_za_izvoz_kategorije_imovine_u_json.txt) |
| Kraj zakupa | [TSV](instrukcija_za_identifikaciju_datum_kraja_zakupa.txt) | [Verifikacija](instrukcija_za_validaciju_datum_kraja_zakupa.txt) | U | — |
| Automatsko produženje | [TSV](instrukcija_za_identifikaciju_automatskog_produzenja.txt) | [Verifikacija](instrukcija_za_validaciju_automatskog_produzenja.txt) | V | — |
| Trajanje produženja | [TSV](instrukcija_za_identifikaciju_trajanja_produzenja.txt) | [Verifikacija](instrukcija_za_validaciju_trajanja_produzenja.txt) | W | — |
| Dospeće plaćanja | [TSV](instrukcija_za_identifikaciju_dospece.txt) | [Verifikacija](instrukcija_za_validaciju_dospece.txt) | BJ | — |
| Odvojivost komponenti | [TSV](instrukcija_za_identifikaciju_odvojivosti.txt) | [Verifikacija](instrukcija_za_verifikaciju_odvojivosti_Excel.txt) | BL | — |
| Učestalost plaćanja | [TSV](instrukcija_za_identifikaciju_ucestalosti.txt) | [Verifikacija](instrukcija_za_validaciju_ucestalosti.txt) | BI | — |
| Neodbitni iznos | [TSV](instrukcija_za_identifikaciju_neodbitnog_iznosa.txt) | [Verifikacija](instrukcija_za_verifikaciju_neodbitnog_iznosa_Excel.txt) | BO | — |
| Fiksna zakupnina | [TSV](instrukcija_za_identifikaciju_fiksne_zakupnine.txt) | [Verifikacija](instrukcija_za_verifikaciju_fiksne_zakupnine_Excel.txt) | BQ | — |
| Osnova varijabilne zakupnine | [TSV](instrukcija_za_identifikaciju_osnove_varijabilne.txt) | [Verifikacija](instrukcija_za_verifikaciju_osnove_varijabilne_Excel.txt) | BT | — |
| Varijabilna zakupnina | [TSV](instrukcija_za_identifikaciju_varijabilnog_iznosa.txt) | [Verifikacija](instrukcija_za_excel_verifikaciju_varijabilnog_iznosa.txt) | BU | — |
| Opis indeksa | [TSV](instrukcija_za_identifikaciju_opisa_indeksa.txt) | [Verifikacija](instrukcija_za_excel_verifikaciju_opisa_indeksa.txt) | BV | — |
| Učestalost indeksacije | [TSV](instrukcija_za_identifikaciju_ucestalosti_indeksacije.txt) | [Verifikacija](instrukcija_za_excel_verifikaciju_ucestalosti_indeksacije.txt) | BW | — |
