Institutul Național de Gerontologie și Geriatrie „Ana Aslan” se străduiește să îmbunătățească starea de sănătate a bătrânilor, dar se confruntă cu un paradox: lipsa unei soluții digitale eficiente pentru programări. La momentul actual succesul efectuării unei programări se află sub steaua norocului.

Cum se întâmplă acum?
De luni până vineri, între orele 12 și 14, poți suna la una dintre cele trei linii deschise de către Institut. Dacă ești suficient de norocos încât să ți se răspundă, nu trebuie să te bucuri prea tare, întrucât afli repede că, exact ca în parabola kafkiană În fața legii”, ai întâlnit de abia primul „gardian”. Pentru a ajunge la următoarea poartă însă, cea decisivă, eforturile nu mai depind de tine. Dacă doamna către care vei fi redirecționat se află deja într-un apel, vei fi încurajat să revii cu un telefon. Astfel, după mai multe procedee de încercare-eroare, vei putea obține o programare. Procesul poate dura oricât între câteva ore și câteva săptămâni. Consumă timp și provoacă frustrare.

Propunerea mea
Soluția mea este dată de o aplicație web de programări care va fi dezvoltată în cadrul acestui curs. 
Această aplicație va transforma procesul de programare într-o experiență transparentă și își propune să fie ușor de accesat și gestionat. Prin intermediul acestei platforme digitale, veți putea naviga cu ușurință între centrele noastre, verifica lesne capacitatea centrelor, listele de așteptare și solicitările zilnice. Veți avea controlul asupra programării dumneavoastră, putând accepta sau renunța la oferte spontane. Pentru administratorii noștri, va exista o interfață simplă și sigură, cu înregistrarea completă a activității.

Aplicația (Ana Aslan, Institut, Gerontologie, Geriatrie, Programări, Consultații, Sănătate, Bătrâni, Servicii medicale, Platformă online) va avea următoarea structură:
FRONT-END
Pagină de prezentare: O pagină inițială care va oferi o prezentare a institutului și a serviciilor pe care le oferă.(cuvinte-cheie: Institut, Servicii, Prezentare, Informații, Echipă, Misiune, Viziune, Oferte, Pacienți)
Pagină de programări: Aici veți putea alege între cele două centre disponibile. Informațiile despre fiecare centru vor fi prezentate într-un mod clar și concis. Vom afișa capacitatea spitalului în funcție de gen, numărul persoanelor aflate pe lista de așteptare, precum și numărul de cereri făcute în ziua respectivă. De asemenea, veți putea observa tendința de a se face mai multe sau mai puține programări. (cuvinte-cheie: Programări, Centre, Capacitate, Lista de așteptare, Cereri, Programare online, Gen, Tendințe, Disponibilitate, Proces)
Proces de programare: Veți fi direcționat către o pagină de logare unde veți folosi CNP-ul ca parolă pentru a evita crearea de conturi duplicate. Aici veți putea furniza datele necesare pentru programare, cum ar fi numele, prenumele, sexul și datele de contact.(cuvinte-cheie: Logare, Autentificare, CNP, Date personale, Programare, Contact, Sex, Verificare, Securitate, Confirmare)
Pagină de gestionare a programării: Veți avea acces la o pagină personală unde veți putea vedea câte zile au mai rămas până la programare. Aveți posibilitatea să renunțați la o programare sau să acceptați o programare spontană în acest spațiu.(cuvinte-cheie: Gestionare programări, Acces personal, Renunțare, Confirmare, Zile rămase, Anulare, Programare spontană, Notificări, Administrare, Spațiu personal)
Pagină pentru administrator: O pagină dedicată administratorilor care le permite să vizualizeze programările curente și să șteargă o programare în anumite situații. Întreaga lor activitate va fi înregistrată într-un fișier de log separat pentru a asigura transparența și securitatea sistemului.(cuvinte-cheie: Administrare, Vizualizare, Programări curente, Ștergere, Activitate, Înregistrare, Transparență, Siguranță, Fișier de log, Securitate)


BACK-END (va respecta modelul Model-View-Controller)
Algoritm de prioritizare a programărilor: Vom dezvolta un algoritm care va determina prioritatea pacienților în funcție de ora la care au fost efectuate programările. În cazul în care o programare este anulată din motive obiective (cum ar fi uitarea, schimbarea deciziei sau decesul acestuia), algoritmul va ceda programarea respectivă următorului pacient fără a afecta programarea proprie a acestuia. Timpul de gândire al algoritmului va fi estimat la o zi.
Bază de date simplă: Vom crea o bază de date simplă cu două tabele distincte: PROGRAMĂRI și ADMINI

Tabela PROGRAMĂRI va conține următoarele informații: nume, prenume, telefon, adresă de e-mail, ora solicitării programării și data programării.
Tabela ADMINI va include următoarele informații: nume, prenume, telefon, adresă de e-mail și data începerii contractului. Această tabelă va fi accesibilă și gestionată exclusiv de către departamentul tehnic pentru a menține securitatea sistemului. Nu va fi furnizată o interfață grafică pentru această tabelă.


Site-uri de referință:

https://ana-aslan.ro/ 

Acest site de prezentare va servi ca punct de plecare pentru dezvoltarea aplicației mele. Aplicația propusă va completa și va extinde funcționalitatea acestui site.
Argumentele în favoarea site-ului de prezentare includ un design curat, clar, coerent și modern. De asemenea, este primul rezultat returnat de orice motor de căutare pe baza cuvintelor cheie „ana aslan programare”.
Cu toate acestea, există și argumente împotriva utilizării exclusiv a acestui site. Este important de remarcat că site-ul are un scop strict estetic și nu este conceput să ofere funcționalități specifice de programare. De asemenea, informația prezentată este uneori redundantă și dispersată în mod inutil pe mai multe pagini, în timp ce o abordare unitară ar fi mai eficientă pentru prezentarea datelor.

https://prod01.evexiaapp.ro/webapp/#/pacient 

Site-ul actual dedicat programărilor pentru consultația în ambulatoriu este neintuitiv și dificil de navigat, lipsind complet de design și de elementele necesare pentru a inspira încredere. Domeniul criptic al site-ului nu transmite încredere și poate genera îndoieli privind autenticitatea și validitatea informațiilor furnizate de către client.

https://www.medlife.ro/programare-online 

Pe partea pozitivă, designul este coerent și modul de navigare este intuitiv, facilitând accesul și utilizarea pentru utilizatori. De asemenea, informațiile solicitate se limitează la nume, date de contact și CNP, ceea ce nu încarcă deloc sistemul. Observ de asemenea faptul că și aici este solicitat CNP-ul, probabil pentru a valida identitatea pacientului și a oferi programării un caracter mai oficial și mai autentic. Pe baza CNP-ului eu vreau să fac validarea utilizatorului, pentru a feri Modelul de intrări dubioase/duplicat. Voi implementa și un algoritm de verificare a CNP-ului pentru a mă asigura că nu este doar o succesiune de cifre fără sens.
În schimb, există și aspecte negative. Utilizatorii pot alege data programării fără a avea opțiuni prestabilite de intervale de timp, ceea ce poate genera îndoieli cu privire la relevanța datei alese, având în vedere că aceasta poate fi considerată doar orientativă. De asemenea, comunicarea ulterioară se va realiza probabil exclusiv prin e-mail și/sau telefon, limitând confirmarea și gestionarea programărilor.

https://medicales.ro/programari/
Ca aspecte pozitive, simplitatea paginii este de apreciat, fără a fi încărcată cu informații inutile. Este o idee bună să se atenționeze clientul în cazul în care datele furnizate nu sunt completate corect înainte de a face requestul către server. De asemenea, notificarea că programarea poate fi anulată în orice moment este utilă. (voi prelua și eu aceste idei). Este de asemenea apreciat faptul că clinica se angajează să trimită un SMS în ziua programării; voi considera și eu implementarea unei notificări similare, dar prin e-mail.
În ceea ce privește aspectele negative, site-ul înregistrează prea puține date despre utilizator, ceea ce poate duce la poluarea sistemului cu prea multe requesturi, întrucât orice combinație de nume și telefon este considerată validă. De asemenea, ar fi util să fie adăugate niște informații despre statusul clinicii, pentru ca utilizatorul să poată evalua dacă clinica este solicitată în acel moment și să poată acționa în consecință.

