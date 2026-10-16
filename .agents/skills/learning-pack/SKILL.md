---
name: learning-pack
description: Paruošia patikrintus mokymosi klausimų paketus iš nuotraukų, PDF, teksto arba temos ir po naudotojo patvirtinimo eksportuoja JSON mokymosi žaidimui.
---

# Paskirtis

Padėti tėvui / žaidimo hostui paruošti mokymosi paketą.
Žaidimo metu hostas pats vertins mokinio atsakymus.

Bendrauk lietuviškai, nebent naudotojas paprašo kitaip.
Klausimų kalbą parink pagal medžiagą ir mokymosi tikslą.

# Pagrindinės taisyklės

- Naudotojui nereikia kartoti šios instrukcijos.
- Priimk nuotraukas, PDF, tekstą arba temos pavadinimą.
- Jei informacijos trūksta, užduok tik vieną klausimą vienu metu.
- Neklausk to, ką galima patikimai nustatyti iš medžiagos.
- Neįskaitomų vietų ir trūkstamų faktų nespėliok.
- Pirmiausia pateik peržiūrai skirtą turinį.
- JSON eksportuok tik gavęs aiškų naudotojo nurodymą,
  pavyzdžiui: „Generuok JSON“.
- Nekurk labirinto, kambarių koordinačių ar žaidimo būsenos.

# 1. Nustatyk mokymosi ribas

Nustatyk:
- mokomąjį dalyką;
- klasę;
- temą ir jos ribas;
- klausimų kalbą;
- pagrindines žinias ir gebėjimus.

Šio naudotojo numatytoji klasė — 10.
Jei medžiaga akivaizdžiai neatitinka šios klasės, pasitikslink.

Viename pakete turi būti vienas mokomasis dalykas.
Jei pateikta kelių dalykų medžiaga, pasiūlyk atskirus paketus.

Jei pateiktas tik platus temos pavadinimas ir neaišku,
ką apims atsiskaitymas, pirmiausia patikslink temos ribas.

# 2. Išanalizuok medžiagą

Išskirk pagrindinius faktus, terminus, procesus ir ryšius.

Potemes kurk tik tada, kai medžiaga natūraliai jas turi.
Nekurk dirbtinių potemių dėl žaidimo mechanikos.

Klausimų kiekį pasiūlyk pagal medžiagos aprėptį.
Nenaudok fiksuoto klausimų skaičiaus ir nedidink jo
pasikartojančiomis formuluotėmis.

Jei pateikta medžiaga, ji nustato atsiskaitymo ribas.
Papildomus šaltinius naudok tikrinimui ir paaiškinimui,
ne tyliam temos išplėtimui.

# 3. Paruošk klausimus

Naudok tinkamą skirtingų užduočių tipų derinį:

- open: atviras klausimas, atsakomas žodžiu arba raštu;
- single_choice: vienas teisingas pasirinkimas;
- multiple_choice: keli teisingi pasirinkimai;
- ordering: elementų rikiavimas;
- matching: porų jungimas;
- numeric: skaitinis atsakymas.

Neversk medžiagos į netinkamą užduoties tipą vien dėl įvairovės.
Venk ilgų vienodo tipo užduočių serijų.

Kiekvienam klausimui paruošk:
- stabilų unikalų ID;
- potemę, jei yra;
- tipą;
- sudėtingumą: easy, medium arba hard;
- aiškią užduoties formuluotę;
- teisingą sprendinį;
- hostui skirtus vertinimo kriterijus;
- trumpą užuominą;
- trumpą atsakymo paaiškinimą;
- pagrindžiantį šaltinį arba medžiagos vietą.

Atviriems klausimams nurodyk, kokių esminių minčių
pakanka teisingam atsakymui. Nereikalauk pažodinio atkartojimo.

Pasirinkimų klaidingi variantai turi būti įtikinami,
bet neturi sukurti kelių pagrįstai teisingų atsakymų.

Sudėtingumą derink prie klasės ir medžiagos.
Neįtrauk papildomų olimpiadinių iššūkių be prašymo.

# 4. Patikrink turinį

Faktinius atsakymus tikrink patikimuose šaltiniuose.
Pirmenybę teik pirminiams, oficialiems, akademiniams
ir pripažintiems mokomiesiems šaltiniams.

Fiksuok, kuris šaltinis pagrindžia kurį atsakymą.
Nenurodyk išgalvotų URL, citatų ar puslapių numerių.
Paieškos rezultato antraštės nelaikyk pakankama patikra.

Jei nėra interneto prieigos, aiškiai pasakyk, kad išorinė
patikra neatlikta. Nežymėk turinio kaip patikrinto internete.

Skaičiavimus perskaičiuok. Patikrink vienetus ir paklaidas.
Kalbos užduotyse įvertink galimus alternatyvius atsakymus.

Jei šaltiniai prieštarauja pateiktai medžiagai, parodyk
konkretų neatitikimą ir paprašyk naudotojo sprendimo.

Patikrink:
- faktinį teisingumą;
- klausimo ir atsakymo atitiktį;
- formuluotės aiškumą;
- užduoties vienareikšmiškumą;
- dubliavimąsi;
- medžiagos aprėptį;
- užuominos ir paaiškinimo tinkamumą.

AI savikontrolės nelaikyk teisingumo garantija.
Neišspręsti kritiniai neaiškumai turi būti išspręsti
arba atitinkami klausimai pašalinti prieš eksportą.

# 5. Pateik peržiūrą

Pateik:
1. Dalyką, klasę, temą ir temos ribas.
2. Potemes, jei yra.
3. Siūlomą klausimų kiekį ir tipų pasiskirstymą.
4. Visus klausimus su atsakymais, vertinimo kriterijais,
   užuominomis ir paaiškinimais.
5. Trumpą aprėpties lentelę:
   medžiagos dalis → klausimų ID.
6. Patikros rezultatą ir likusius neaiškumus.

Išlaikyk klausimų ID stabilius taisymų metu.
Priimk naudotojo pataisas ir patikrink pakeistas vietas.

Peržiūros pabaigoje paprašyk patvirtinti turinį arba
nurodyti pataisas. Galutinio JSON dar neeksportuok.

# 6. Eksportuok JSON

Gavęs „Generuok JSON“:

- naudok projekto learning-pack.schema.json, jei ji yra;
- jei schemos nėra, aiškiai pažymėk, kad kuriamas
  prototipinis formatas, kurį dar reikės suderinti su žaidimu;
- patikrink JSON sintaksę ir, jei schema yra, atitiktį jai;
- patikrink ID unikalumą ir vidines nuorodas;
- patikrink, kad nėra nepateiktų sprendinių;
- užtikrink, kad eksportas atitinka patvirtintą peržiūrą.

Pagrindiniai paketo laukai:

schemaVersion, packageId, title, subject, grade,
contentLanguage, scope, subtopics, questions,
sources, validation.

Kiekvieno klausimo bendri laukai:

id, subtopicId (jei taikoma), type, difficulty, prompt,
hint, explanation, gradingCriteria, solution,
sourceRefs, verification.

Pasirinkimų, rikiavimo ir porų elementams naudok stabilius ID.

Jei subtopics tuščias, subtopicId nenaudok.
Jei potemės yra, kiekvienas klausimas turi priklausyti
egzistuojančiai potemei.

Validation dalyje atskirk:
- struktūros patikrą;
- aprėpties patikrą;
- faktinių atsakymų patikrą;
- neįvykdytas patikras ir įspėjimus.

Sukurk atsisiunčiamą .json failą.
Jei aplinka negali kurti failų, pasakyk tai ir pateik
tikslų JSON kodo bloke.

Neteik teiginio „viskas patikrinta“, jei dalis patikrų
nebuvo atlikta.
