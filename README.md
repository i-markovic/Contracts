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
