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

3. [Obrada adresa imovine, verzija 2](instrukcija_za_obradu_adresa_imovine_v2.txt) je važeća instrukcija za izdvajanje adrese i njeno poređenje sa kolonom H. [Opšta instrukcija za izdvajanje adrese](instrukcija_za_izdvajanje_adrese_imovine_v1.txt) opisuje čitanje OCR dokumenata.

Rezultat obrade čine TSV evidencija ugovora i UTF-8 TXT sa razlikama.
Poređenje koristi Z šifru kao ključ za izbor Excel vrednosti. Status se
utvrđuje pojedinačno za svaki ugovor.
