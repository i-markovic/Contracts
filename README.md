# Contracts

Contracts dokumentuje postupak za utvrđivanje zakupodavaca iz OCR prepisa
ugovora o zakupu i podzakupu poslovnih prostora, kao i za proveru tih nalaza
prema Excel evidenciji.

Za svaki zaseban ugovor nastaje jedan zapis. Aneksi se vezuju za konkretan
ugovor prema broju ili datumu u tekstu i predmetu zakupa. U zapisu se navodi
merodavni zakupodavac prema poslednjem povezanom aneksu, uz prenos prethodnog
potvrđenog stanja kada aneks ne menja zakupodavca.

## Instrukcije

1. [Identifikacija zakupodavca, verzija 4](instrukcija_za_identifikaciju_zakupodavca_v4.txt) određuje vrstu dokumenta, vezu aneksa sa ugovorom i način zapisivanja imena.
2. [Poređenje zakupodavaca sa Excelom i izlaz](instrukcija_za_poredjenje_sa_excelom.txt) određuje redosled provere, pravilo podskupa i format izveštaja.

3. [Obrada adresa imovine](instrukcija_za_obradu_adresa_imovine.txt) opisuje izdvajanje adrese iz OCR dokumenata i poređenje sa kolonom H u Excelu.

Rezultat obrade čine TSV evidencija ugovora i UTF-8 TXT sa razlikama.
Poređenje koristi Z šifru kao ključ za izbor Excel vrednosti. Status se
utvrđuje pojedinačno za svaki ugovor.
