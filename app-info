Institutul Național de Gerontologie și Geriatrie „Ana Aslan” se străduiește să îmbunătățească starea de sănătate a bătrânilor, dar se confruntă cu un paradox: 
lipsa unei soluții digitale eficiente pentru programări. La momentul actual succesul efectuării unei programări se află sub steaua norocului.

Cum se întâmplă acum?
De luni până vineri, între orele 12 și 14, poți suna la una dintre cele trei linii deschise de către Institut. Dacă ești suficient de norocos încât să ți se 
răspundă, nu trebuie să te bucuri prea tare, întrucât afli repede că, exact ca în parabola kafkiană În fața legii”, ai întâlnit de abia primul „gardian”. 
Pentru a ajunge la următoarea poartă însă, cea decisivă, eforturile nu mai depind de tine. Dacă doamna către care vei fi redirecționat se află deja într-un apel,
vei fi încurajat să revii cu un telefon. Astfel, după mai multe procedee de încercare-eroare, vei putea obține o programare. Procesul poate dura oricât între 
câteva ore și câteva săptămâni. Consumă timp și provoacă frustrare.

Propunerea mea
Soluția mea este dată de o aplicație web de programări care va fi dezvoltată în cadrul acestui curs. 
Această aplicație va transforma procesul de programare într-o experiență transparentă și își propune să fie ușor de accesat și gestionat. Prin intermediul 
acestei platforme digitale, veți putea naviga cu ușurință între centrele noastre, verifica lesne capacitatea centrelor, listele de așteptare și solicitările 
zilnice. Veți avea controlul asupra programării dumneavoastră, putând accepta sau renunța la oferte spontane. Pentru administratorii noștri, va exista o 
interfață simplă și sigură, cu înregistrarea completă a activității.

Aplicația va avea următoarea structură:
FRONT-END

1. Pagină de prezentare: O pagină inițială care va oferi o prezentare a institutului și a serviciilor pe care le oferă.
2. Pagină de programări: Aici veți putea alege între cele două centre disponibile. Informațiile despre fiecare centru vor fi prezentate într-un mod clar și concis. 
Vom afișa capacitatea spitalului în funcție de gen, numărul persoanelor aflate pe lista de așteptare, precum și numărul de cereri făcute în ziua respectivă. 
De asemenea, veți putea observa tendința de a se face mai multe sau mai puține programări.
3. Proces de programare: Veți fi direcționat către o pagină de logare unde veți folosi CNP-ul ca parolă pentru a evita crearea de conturi duplicate. Aici veți 
putea furniza datele necesare pentru programare, cum ar fi numele, prenumele, sexul și datele de contact.
4. Pagină de gestionare a programării: Veți avea acces la o pagină personală unde veți putea vedea câte zile au mai rămas până la programare. Aveți posibilitatea 
să renunțați la o programare sau să acceptați o programare spontană în acest spațiu.
5. Pagină pentru administrator: O pagină dedicată administratorilor care le permite să vizualizeze programările curente și să șteargă o programare în anumite 
situații. Întreaga lor activitate va fi înregistrată într-un fișier de log separat pentru a asigura transparența și securitatea sistemului.


BACK-END (va respecta modelul Model-View-Controller)
1.Algoritm de prioritizare a programărilor: Vom dezvolta un algoritm care va determina prioritatea pacienților în funcție de ora la care au fost efectuate 
programările. În cazul în care o programare este anulată din motive obiective (cum ar fi uitarea, schimbarea deciziei sau decesul acestuia), algoritmul va 
ceda programarea respectivă următorului pacient fără a afecta programarea proprie a acestuia. Timpul de gândire al algoritmului va fi estimat la o zi.
2.Bază de date simplă: Vom crea o bază de date simplă cu două tabele distincte: PROGRAMĂRI și ADMINI

Tabela PROGRAMĂRI va conține următoarele informații: nume, prenume, telefon, adresă de e-mail, ora solicitării programării și data programării.
Tabela ADMINI va include următoarele informații: nume, prenume, telefon, adresă de e-mail și data începerii contractului. 
Această tabelă va fi accesibilă și gestionată exclusiv de către departamentul tehnic pentru a menține securitatea sistemului. 
Nu va fi furnizată o interfață grafică pentru această tabelă.
