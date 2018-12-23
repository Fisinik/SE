# HelpDesk

- [Hyrje](#Hyrje)
  - [Qëllimi i dokumentit](#Qëllimi%20i%20dokumentit)
  - [Vlefshmëria e dokumentit](#Vlefshmëria%20e%20dokumentit)
  - [Definimi i termeve dhe shkurtesave](#Definimi%20i%20termeve%20dhe%20shkurtesave)
  - [Relacionet me dokumentet tjera](#Relacionet%20me%20dokumentet%20tjera)
  - [Pasqyra e dokumentitt](#Pasqyra%20e%20dokumentit)
  
- [Përshkrimi i përgjithshëm i produktit](#Përshkrimi%20i%20përgjithshëm%20i%20produktit)
  - [Qëllimi i produktit](#Qëllimi%20i%20produktit)
  - [Përmbledhje e funksionalitetit të kërkuar](#Përmbledhje%20e%20funksionalitetit%20të%20kërkuar)
  - [Kufizimet e përgjithshme](#Kufizimet%20e%20përgjithshme)
  - [Specifikimet harduerike dhe softuerike](#Specifikimet%20harduerike%20dhe%20softuerike)
  - [Shfrytëzuesit e sistemit](#Shfrytëzuesit%20e%20sistemit)
    - [Guest User](#Guest%20User)
    - [Registered User](#Registered%20User)
    - [Ofruesi i shërbimit RTC](#Ofruesi%20i%20shërbimit%20RTC)
    - [Admininistratori](#Admininistratori)
  
- [Përshkrimi i detajuar i sistemit](#Përshkrimi%20i%20detajuar%20i%20sistemit)
  - [Fusha e dorëzimit](#Fusha%20e%20dorëzimit)
  - [Pritjet e përdoruesit](#Pritjet%20e%20përdoruesit)
  - [Skenaret e interaksioneve me rrethinën](#Skenaret%20e%20interaksioneve%20me%20rrethinën)
    - [Shfrytëzuesi shikon dashboard](#Shfrytëzuesi%20shikon%20dashboard)
    - [Shfrytëzuesi bën kërkim (search)](#Shfrytëzuesi%20bën%20kërkim%20(search))
    - [Shfrytëzuesi komunikon me AI Chat Bot](#Shfrytëzuesi%20komunikon%20me%20AI%20Chat%20Bot)
    - [Sub](#sub)
    - [Sub](#sub)
    - [Sub](#sub)
    - [Sub](#sub)
    - [Sub](#sub)
    - [Sub](#sub)
    - [Sub](#sub)
    - [Sub](#sub)
  - [Funksionet e kërkuara nga sistemi](#Funksionet%20e%20kërkuara%20nga%20sistemi)
    - [Kërkesat funksionale](#Kërkesat%20funksionale)
    - [Kërkesat jofunksionale](#Kërkesat%20jofunksionale)
  - [Funksionet tjera të kërkuara nga produkti](#Funksionet%20tjera%20të%20kërkuara%20nga%20produkti)
    - [Siguria](#Siguria)
    - [Besueshmëria](#Besueshmëria)
    - [Mbështetja](#Mbështetja)
    - [Dokumentimi dhe trajnimi](#Dokumentimi%20dhe%20trajnimi)
    - [Përdorueshmëria](#Përdorueshmëria)
    - [Performanca](#Performanca)
    - [Mirëmbajtja](#Mirëmbajtja)
  
- [Specifikimet për menaxhimin e projektit](#Specifikimet%20për%20menaxhimin%20e%20projektit)
  - [Komponentet e gatshme dhe të investuara](#Komponentet%20e%20gatshme%20dhe%20të%20investuara)
  - [Kushtet e pranimit](#Kushtet%20e%20pranimit)
  - [Kushtet e dorëzimit](#Kushtet%20e%20dorëzimit)
  - [Garancioni](#Garancioni)

## Hyrje

### Qëllimi i dokumentit

Qëllimi i dokumentit për sistemin online HelpDesk kërkon që të arrijë definimin profesional rreth realizimit të projektit softwerik duke përfshirë këtu edhe paisjet hardwerike. Me rastin e përfundimit të projektit duhet që platforma të jetë funksionale dhe e gatshme për shfrytezuesit e kësaj platforme. Ky dokument është ndërtuar për mbështetje të klientëve  të kompanisë teknologjike “Xiaomi” në rajonet shqip-folëse.

### Vlefshmëria e dokumentit

Ky dokumentim është i vlefshëm  gjatë fazës së definimit të kërkesave të sistemit, zhvillimit të sistemit dhe implementimit të sistemit  deri në funksionalitet të plotë.
Në rast të ndonjë përmirsimi eventual për dokumentin, përgjegjës do jetë ekipi punues në dokumentimin e krijuar.

### Definimi i termeve dhe shkurtesave

- RTC – Real Time Chat
- AI – Artificial Intelligence
- PU – Central Processing Unit
- GB – Gigabytes
- GHz – Gigahertz
- RAM – Random Access Memory
- OS – Operating System
- HTTPS – Hyper Text Transfer Protocol Secure
- SSD – Solid State Drive
- SQL – Structured Query Language
- IIS – Internet Information Services
- OWASP—Open Web Application Server Project
- XSS – Cross-Site Scripting
- TB – Terabytes
- SCSI - Small Computer System Interface

### Relacionet me dokumentet tjera

Ky dokument lidhet me:

- Dokumentin e studimit të fizibilitetit në lidhje me sistemin online HelpDesk të kompanisë “Xiaomi”.
- Vendimin e kompanisë  dhe kushtet në lidhje me zhvillimin e sistemit.

### Pasqyra e dokumentit

Seksioni i dytë përfshin përshkrim të përgjithshëm të produktit, i cili jep një pamje të sistemit të tërë për shitjen e biletave online. Përfshin qëllimin e produktit, përshkrimin e funksionalitetit dhe të kufizimeve të sistemit. Këtu hyjnë gjithashtu specifikimet hardverike dhe softuerike si dhe përshkrim për shfrytëzuesit e sistemit.
Seksioni i tretë përfshin përshkrim të detajuar të sistemit, fushën e dorëzimit, kërkesat funksionale dhe jofunksionale, interaksionin e përdoruesit me sistemin dhe pritjet e përdoruesit. Gjithashtu përfshin edhe veti te sistemit siç janë: portabiliteti, siguria, performanca, mirëmbajtja dhe ripërdorimi. Ky seksion është i bërë enkas për zhvilluesit e sistemit, me detajet e funksionalitetit të produktit të shkruar me terma teknik.
Seksioni i katërt përshkruan specifikimet për menaxhimin e projektit, ku përfshihen komponentet e gatshme dhe të investuara, kushtet e dorëzimit, kushtet e pranimit dhe në fund garancioni

## Përshkrimi i përgjithshëm i produktit

Ky sistem ka për qëllim automatizimin e procesit të shtruarjes së pyetjeve të konsumatorëve dhe përgjigjes së tyre brenda një kohe sa më të shkurtër përmes aplikacionit softuerik. Implementimi i një sistemi të tillë do të lehtësonte dukshëm eksperiencën e përdoruesve gjatë kërkimit të zgjidhjeve për produktet e XIAOMI  duke ofruar një web aplikacion të përshtatshëm dhe lehtë të përdorshëm. <br/> Softueri duhet të ofrojë një ndërfaqe interaktive të përdoruesit së bashku me një bazë të të dhënave për ruajtjen e shënimeve. Përdoruesit duhet të kenë qasje të ndryshme në sistem duke u bazuar në privilegjet që posedojnë ashtu që të plotësohen nevojat si nga ana adminstrative ashtu edhe nga ana e shfrytëzuesve

### Qëllimi i produktit

Qëllimi i kësaj platforme HelpDesk është të ofrojë shërbim kualitativ, të sigurtë, dhe të sofistikuarë për paisjet e kompanisë “Xiaomi”. Duke marrë në konsideratë që numri i konsumatorëve të kompanisë  është gjithnjë në rritje, është ndjerë nevoja për një sistem elektronik i cili mund të plotsojë kërkesat e konsumatorëve. Kërkesat e konsumatorëve mund të jenë nga aspekti hardwerik dhe softwerik prandaj sistemi HelpDesk duhet t’i përkrah të dy llojet e kërkesave qofshin ato hardwerike apo softwerike në lidhje me paisjet e kompanisë “Xiaomi”. Kjo mbështetje për këto produkte të kompanisë është marrë si iniciative nga drejtuesit e kompanisë pas kërkesave dhe interesimit për mbështetje nga konsumatorët e kompanisë dhe komunitetit shqip-folës që kanë interes në produktet “Xiaomi”.
Një pjesë e vetive më kryesore të këtij projekti do të jenë:

- Mundësia e mbështetjes teknike së çdo produkti të kësaj kompanie.
- Mundësia e qasjes në shërbimet  HelpDesk edhe nga konsumatorët Guest (me disa funksione të limituara).
- Qasja e plotë në platformë nga ana e konsumatorëve të regjistruar (registered mode).
- Search Engine për mundësi më të lehtë të gjetjes së problemeve.
- AI Chat Bot për parashtrimin e pyetjeve në mënyrë interaktive.
- Mbështetje pa pagesë për klientët që përmbajnë garancion dhe pagesë të arsyeshme për klientët të cilët nuk kanë garancion në produktet e tyre për shërbimin RTC

### Përmbledhje e funksionalitetit të kërkuar

Ky produkt i cili pritet që të krijohet ka për qëllim të i’u mundsojë konsumatorëve të kësaj kompanie që të kenë mbështetje të paisjeve të tyre për problemet me paisjet të cilat mund të rregullohen edhe nga vetë klienti. Klienti mund të gjejë zgjidhje të problemit duke kërkuar në platformën online HelpDesk për problemin e caktuar. Udhëzimet mbi problemet e caktuara do paraqiten përmes përshkrimeve, fotove, dhe në raste të caktuara edhe përmes videos. Pra kjo platformë synon që do ti përmbushë të gjitha kërkesat rreth problemeve për produktet e “Xiaomi”. <br/>
Sistemi online HelpDesk siguron mbeshtetje online për 24 orë në ditë, stafë të kualifikuar ekskluzivisht nga “Xiaomi” i cili është i gatshëm t’ju ndihmojë drejtë gjetjes së një zgjidhje sa më të shpejtë dhe efektive. Stafi do të jetë i gatshëm që t’ju ndihmojë përmes chat dhe përmes telefonatës (call). Sistemi do të përmbaj po ashtu edhe AI Chat Bot i cili do jetë i gatshëm për ndëgjimin e klientëve dhe gjetjes së zgjidhjes sa më efikase dhe adekuate. Në këtë platformë do të jenë po ashtu edhe pyetjet më të shpeshta në të cilat klienti mund të gjejë zgjidhje më të shpejtë. Nëse problemi të cilin e kërkonë klienti nuk gjindet në pyetjet e shpeshta atëherë mund që të kërkojë në platformë përmes Search Engine ose chat bot. <br> 
Duke pasur parasysh që koha është e njëjtë në të gjitha vendet ku pritet që të shfrytëzohet kjo platformë  online, stafi nuk ka nevojë të jetë 24 orë aktivë, kështu që gjatë ditës mund të shfrytëzohet chat live me stafin e caktuar,  kurse gjatë natës mund të shfrytëzohet Chat Bot ose Search Engine. <br>
Për të pasur qasje në chat live klient duhet të jetë i regjistruar si përdorues dhe të shfrytëzoj benifite më të mëdha, gjithmonë duke i siguruar klientit se të dhënat e tij do jenë të siguruara nga  kompania.Sistemi do jetë në gjuhën shqipe pasi do të krijohet pikërisht për rajonin shqip-folës. Dizajni i kësaj platforme do të bëhet duke u bazuar në site-in global të “Xiaomi”.

### Kufizimet e përgjithshme

Sistemi pa marrë parasysh përshtatjen me shumicën e popullsisë në të cilën do të zhvillohet do të jetë  I kufizuar për përdorimin e pakicave të cilat ndodhen në vend, për ata që kanë probleme me gjuhën në të cilën është krijuar sistemi.Edhe pse shumica e browserve japin mundsinë e përkthimit në cilendo gjuhë prape do të jete problem mënyra e përkthimit dhe përdorimi I opsioneve si chat bot dhe telefonatës . Sistemi do të jetë I kufizuar edhe në ofrimin e shërbimeve ndihmëse për shkak të llojllojshmerisë së problemeve që mund të kenë paisjet, duke marrë parasysh kualifikimin e stafit do të mundohemi që ta minimizojmë pamundsimin e ofrimit të sherbimeve.

### Specifikimet harduerike dhe softuerike

Implementimi:
Zyrat qendrore preferohet të kenë dy Web Serverë me këto specifika harduerike:
Specifikiat harduekrike të Web Serverëve:

- Sistemi qendror duhet të ketë më së paku 2 web servere.
- Njeri prej tyre aktiv me performanca të preferueshme si : Intel(R) Xeon(R) CPU E5-2630 v3, 32-Core Server Processor.
- 128GB DDR4 RAM.
- 7.2TB (4 RAID 1 arrays - cdo array te kete hapsire disku prej 1.8TB).
- Back-up web-serveri i dytë përdoret në rast komplikimeve në serverin e pare.

Specifikat softuerike te Web Serverëve:

- Te operojnë në ndonjë nga Sistetem operative të Microsoft Windows.
- Te perdorin IIS ose Apache.

Specifikat harduerike të Database serverit:

- 4 x 4 CPU at 2.0 GHz.
- 16 GB RAM.
- Ruajtje të mjaftueshme me shpejtsi të larte dhe alokim rezervë.
- SCSI RAID Disk Array me hapsire të lirë minimale prej 100 GB.

Specifikat softuerike të Database Serverit:

- Të ketë të instaluar Microsoft ose Oracle SQL server.
- Të ketë një sistem operativ (preferohet CentOS).

### Shfrytëzuesit e sistemit

#### Guest User

Shrytëzuesit janë përfituesit më të mëdhenjë të këtij sistemi edhe një nga arsyet e fillimit të ketij projekti.Shfrytëezuesit mund të shohin pyetjet dhe përgjigjet e bëra nga përdoruesit e tjerë mund të informohen rreth produkteve të ‘XIAOMI’, gjithashtu mund te informohen edhe për pikat e shitjes në lokacionet e afërta

#### Registered User

Shfrytëzuesit të cilët janë të regjistruar po ashtu si shfrytëzuesit normal janë përfitues të këtij sistemi ata përveç se mund të shohin pyetjet dhe pergjigjet e bëra nga përdoruesit e tjerë ata edhe mund të bejnë pytje për të cilat janë të interesuar, shfrytëzuesit e regjistruar të cilët janë të abonuar edhe për RTC mund të kontaktojnë në kohë reale edhe me stafin te cilët mund ti ndihmojnë në zgjidhjen e problemit. Përdoruesit mund të bejnë paraqitjen e problemeve me tekst,foto,viedo dhe të marrin pergjigje në të njetjtat menyra ose nëse nuk rezultojnë në ndihmesë në zgjidhjen e problemit mund të komunikojnë me Chat Bot-in e sistemit ose edhe më ndonjë nga stafi.

#### Ofruesi i shërbimit RTC

Puntorët të cilët do të merren me komunikimin direkt me shfrytezuesin dhe jepjen informacioneve direkt tek shfrytëzuesi. Do të merren gjithashtu edhe me krijimin e videove ndihmuese për problemet të cilat jane më të shpeshta. Raportimin e çdo rregullimi dhe ndihmese ndaj ndonjë konsumatori

#### Administratori

Administratori ka akses në të gjitha pjesët e sistemit, në regjistrimin dhe fshierjen e përdoruesëve dhe ndryshimin e të dhënave në databaze ose sistem. Merret me mirëmbajtjen e sistemit dhe merr pergjegjsi per cdo parregullsi në sistem. Monitoron raportet adminstrative dhe financiare.

## Përshkrimi i detajuar i sistemit

Me këtë softuer shfrytëzuesi do të gjej zgjidhje për problemet me pajisjet që ofrohen nga kompania “XIAOMI”.
Shfrytëzuesit duhet të kenë:

- Qasje në internet
- Llogari në faqen për shfrytëzimin e të gjitha funksioneve të sistemit
- Të shtoj të dhënat bankare për përdorimin e shërbimit RTC

### Fusha e dorëzimit

Produkti përfundimtar i punës në projekt duhet të jetë një web aplikacion. Si rezultat i projektit duhet të përfshihet edhe raporti i strategjisë, raporti i shërbimit dhe raporti i progresit. Sistemi duhet të ofroj edhe informimin e shfrytëzuesit përmes email-it për çdo gjë të re në sistem

### Pritjet e përdoruesit

Përdoruesit do t’i ofrohet një web aplikacion i cili do ti mundësoj përdorim sa më të lehtë të produkteve të XIAOMI-it, duke gjetur mbështetje dhe zgjidhje për problemet që mund të kenë gjatë përdorimit të tyre. Ky web aplikacion iu ofron shfrytëzuesve çasje të sigurtë, pëmbajtje të navigueshme dhe të lehtë për tu gjetur

### Skenarët e interaksioneve me rrethinën

#### Shfrytëzuesi shikon dashboard

Shfrytëzuesi në momentin e çasjes në web aplikacion do i shfaqet një panel kontrollues (dashboard). Privilegji i shfrytëzuesit për të përdorur këtë funksion nuk ekziston andaj çdo shfrytëzues mund ti çaset panelit (guest user privilege). Paneli përmban informacione të përgjithshme mbi produktet si dhe pjesën e pyetjeve më të shpeshta dhe më të fundit të parashtruara më parë. Funksioni i tillë mundëson interaksionin “One-Click” për të thjeshtësuar dhe përmirsuar mënyrën e çasjes.

#### Shfrytëzuesi bën kërkim (search)

Çdo shfrytëzues mund të përdor kërkimin në databazën e sistemit. Kështu arrihet gjetja e problemeve të parashtruara më përpara dhe të dhënat që i shfaqen shfrytëzuesit në këtë rast janë të sortuara varësisht se a kanë gjetur zgjidhje apo jo në forum.

#### Shfrytëzuesi komunikon me AI Chat Bot

Shfrytëzuesi ka mundësinë të komunikoj me AI Chat bot-in. Përdorimi i këtij funksioni të sistemit nuk kërkon privilegje shtesë, prandaj edhe një shfrytëzues (guest user) mund ta përdor. Në mënyrë interaktive Chat Bot-i parashtron pyetjet shfrytëzuesit me ç’rast mledhë një sasi të madhe të informacionit mbi problemin në fjalë. Këto të dhëna shfrytëzohen për të shikuar se a ka zgjidhje për problemin në fjalë në databazën e sistemit. Në rastin kur nuk ka zgjidhje për këtë problem, Chat Bot i ofron mundësinë shfrytëzuesit për ta postuar pyetjen në forum bazuar në të dhënat që veq ja ka japur Chat Bot-it ose krijimit të një lidhje me shërbimin RTC.

#### Shfrytëzuesi regjistrohet

Një përdorues i ri mund të regjistrohet në sistemin HelpDesk. Shfrytëzuesi dëshiron të regjistrohet dhe të krijojë llogarinë me lehtësi dhe brenda një kohe të shkurtër. Kompania dëshiron të kënaq interesat e përdoruesit dhe të validoj të dhënat e përdoruesit.

- Përdoruesi i ri klikon tek "krijoni llogari të re".
- Përdoruesit ju shfaqet ekrani për informacionet e llogarisë.
- Përdoruesi jep të dhënat personale në ekranin për informacionet e llogarisë.
  - Emri (obligative)
  - Mbiemri (obligative)
  - Emailin (obligative)
  - Adresa e rrugës (e preferueshme)
  - Qyteti (e preferueshme)
  - Shteti (e preferueshme)
  - Kodi Postar (obligative)
  - Numri i telefonit (obligative)
  - Kredia Bankare (e preferueshme)
  - Security Number (e preferueshme)
- Përdoruesi klikon mbi butonin i cili validon të dhënat dhe pastaj shfaqet faqja për krijimin e llogarisë
- Përdoruesi jep emrin dhe fjalëkalimin për krijim të llogarisë.
- Sistemi vërteton se a ekziston ky përdorues me këtë username. Nëse jo, sistemi shfaqë faqen për konfirmimin e llogarisë së re.
- Sistemi i dërgon përdoruesit një njoftin në email që llogaria e tij është krijuar me sukses

#### Shfrytëzuesi kyçet

Përdoruesit fitojnë qasje në sistemin HelpDesk nëpërmjet procesit
të regjistrimit (krijimit të llogarisë).

1. Përdoruesi hap faqen për tu authentikuar.
2. Përdoruesi fut emrin e përdoruesit dhe fjalëkalimin e tij.
3. Sistemi validon emrin e përdoruesit dhe fjalëkalimin (me sukses) dhe tregon faqen e informacionit mbi llogarinë e përdoruesit.

#### Shfrytëzuesi (registered mode) përdor shërbimin RTC

Shërbimi RTC (Real Time Chat) i ofron shfrytëzuesit mundësinë e bisedimit me një ofrues të shërbimit për support. Çasja e tillë ndaj problemit është më efikase dhe përderisa shfrytëzon resurse njerëzore është shërbim me pagesë. Përjashtim bëjnë shfrytëzuesit të cilët kanë garancion paraprak për paisjen për të cilën kërkohet asistencë. Kërkohet nga shfrytëzuesi të jetë i kyçur me llogarinë e tij dhe t'i ketë paraprakisht të dhënat e sakta bankare në llogarinë e tij në sistem.

#### Shfrytëzuesi (registered mode) parashtron problemin në forum

@ NOT DONE

#### Ofruesi i shërbimit RTC/registered user i përgjigjet një pyetje në forum

@ NOT DONE

#### Shfrytëzuesi (registered/guest mode) përdor shërbimin pikat e shitjes

Shfrytëzuesi qoftë ai i regjistruar apo jo, në të dy privilegjet ka në dispozicion të përdor shërbimin pikat e shitjes. Ky shërbim i ofron klientit të gjejë lokacionin më të afërt i cili ofron produktet e kompanisë. Nëse klienti përdorë këtë shërbim atëherë do paraqitet një hartë me lokacionin e preferuar i cili është më i afërti me klientin.

#### Administratori regjistron/fshin ofruesin e shërbimit RTC

Administratori duhet të ketë qasje më të privilegjuar në sistem. Administratori mund të regjistrojë ose të fshij punëtorë. Ai do ketë qasje tek disa meny të cilat nuk kanë qasje punëtorët si: raporti mbi punëtorët, administrimi i punëtorëve, caktimi i detyrave. Administruesi mund të kontrollojë edhe menynë e ankesave për punëtorët e tij. Në menynë ankesat, klientet mund të japin ndonjë ankesë për punëtorët e këtij sektori.

#### Administratori nxjerr raporte administrative dhe financiare

NOT DONE

### Funksionet e kërkuara nga sistemi

#### Kërkesat funksionale

- Sistemi duhet të mundësoj qasjen në katër nivele: nga shfrytëzuesi, shfrytëzues i regjistruar, ofruesit e shërbimeve dhe stafi administrativ.
- Sistemi duhet të ofroj mundësinë e regjistrimit të shfrytëzuesit.
- Sistemi duhet të njoftoj shfrytëzuesin nëpermjet email për regjistrimin.
- Sistemi duhet të mundësoj authentikimin e përdoruesit.
- Shfrytëzuesit i ofrohet mundësia për të zgjedhur mënyrën e parashtrimit të problemit.
- Ofrohet mundësia e përdorimit të panelit kontrollues nga shfrytëzuesi.
- Sistemi ofron mundësinë e komunikimit në kohë reale RTC (me pagesë).
- Mundësia e ofruar për shfrytëzuesin për të komunikuar me AI Chat Bot.
- Sistemi duhet të ofroj shikimin e pikave të shitjes.
- Përdorimin e search engine nga shfrytëzuesi.
- Ofrimi i përgjigjes për një problem në forum nga shfrytëzuesi i regjistruar ose ofruesi i shërbimeve RTC.
- Sistemi të mundësoj regjistrimin/fshirjen e ofruesit të shërbimeve RTC
- Mundësia e pagesës online me PayPal, Mastercard dhe Visa.
- Rimbursim në rast të mos zgjidhjes së problemit nga komunikimi në kohë reale (RTC).

#### Kërkesat jofunksionale

- Sistemi duhet të ofroj siguri gjat futjes së të dhënave bankare
- Back-up serveri të shërbej si rekuperim të dhënash në rast të humbjes së dhënave te serverit kryesor.
- Sistemi duhet të ofroj shërbimet në gjuhen shqipe.
- Sistemi duhet të jetë i kuptueshëm për përdorim me interaksione user-friendly.
- Shfrytëzuesi duhet të jetë në gjendje që me numër minimal të dhënash të regjistrohet dhe të kyçet.
- Shfrytëzuesit nuk duhet t’i lejohet të përdor shërbimin RTC nëse nuk është i regjistruar.
- Shfrytëzuesit nuk duhet t’i lejohet të parashtroj pyetje ose të përgjigjet në forum nëse nuk është i regjistruar.
- Sistemi duhet të përkrahë browserët si: Chrome, Firefox, Edge, Safari, Opera, Explorer dhe mini browserët.
- Shfrytëzuesit t’i ndalohet mundësia e shfrytëzimit së dy ose më shumë shërbimeve RTC në të njejtën kohë.
- Shfrytëzuesit t’i ndalohet përdorimi i shërbimit RTC për një interval 5 minutësh pas thirrjes së parë e cila njofton shfrytëzuesin se të gjitha linjat janë të nxëna.
- Serveri back-up duhet të shërbej si server primar në rast dështimi të serverit të deritanishëm primar.
- Sistemi duhet të jetë responsiv edhe për paisje mobile, tabletë.
- Sistemi duhet të jetë online gjatë tërë kohës për shfrytëzuesit, me përjashtim të shërbimit RTC i cili është aktiv 8 orë.
- Të ketë bandwidth me së paku 20GB paketë të rrjetit.

### Funksionet tjera të kërkuara nga produkti

#### Siguria

- Sistemi ofron enkriptimin e kredencialeve.
- Përdorimi i HTTPS.
- Validimi i fjalëkalimit, fjalëkalimi duhet të ketë shkronja, numra, së paku një shkronjë të madhe si dhe karaktere speciale.
- Mbrojtja nga SQL Injections duke përdorur query parametrik.
- Mbrojtja nga XSS sulmet.
- Sistemi përkrahë standartet e sigurisë nga OWASP (Open Web Application Security Project).

#### Besueshmëria

- Sistemi duhet të jetë aktiv gjatë gjithë kohës (minimumi 68 - 70% të kohës).
- Nëse ndodhë dështimi i sistemit, kohëzgjatja minimale të mos jetë më e madhe se 2 orë.

#### Mbështetja

- Sistemi duhet të përkrahë browserët si: Chrome, Firefox, Edge, Safari, Opera, Explorer dhe mini browserët.
- Sistemi duhet të jetë responsiv edhe për paisje mobile, tabletë.
- Sistemi duhet të jetë online gjatë tërë kohës për shfrytëzuesit, me përjashtim të shërbimit RTC i cili është aktiv 8 orë.

#### Dokumentimi dhe trajnimi

- Sistemi ofron udhëzues për përdorim, sistemin ndihmës (help system).
- Trajnimi duhet të përfshijë shembuj të përdorimit të sistemit, siq janë webinar-et online WebEx, GoToMeeting etj.

#### Përdorueshmëria

- Shfrytëzuesit duhet të jenë në gjendje të përdorin softuerin pas një kohe mjaft të shkurtë të marrjes së instruksioneve për përdorim.
- Shfytëzuesi që dëshiron të kërkojë informacione për produktin duhet të jetë në gjendje të marrë përgjigjje brenda disa sekondave.
- Faqja duhet të jetë e thjeshtë për përdorim.  
- Sistemi duhet të ofroj shërbimet në gjuhen shqipe.

#### Performanca

- Sistemi është i gatshëm të iu ofroj shumë shfrytëzuesve që në të njëjtën kohë të kenë mundësi të qasen të gjithë.
- Sistemi përdor një back-up server i cili ruan funksionalitetin e sistemit gjersa serveri kryesor është jashtë funksionimit.
- Limiti kohorë për shkarkimin e një manuali/dokumenti në sistem të jetë 5 minuta për arsyjen e mos ngarkimit të serverit të sistemit

#### Mirëmbajtja

- Përditësimi i vazhdueshëm i sistemit
- Sistemi duhet të mirëmbahet vazhdimisht nga kompania në mënyrë që gabimet eventuale të bëra në sistem të evitohen.
- Përmirësimi i njësive të sistemit, zhvillimi i funksioneve të reja në sistem.

## Specifikimet për menaxhimin e projektit

### Komponentet e gatshme dhe të investuara

Komponentet e gatshme të cilat mund të perdoren për funksionimin të sistemit janë:

- Kompjuteret personal shtepiakë.
- Laptopët personal.
- Telefonet mobil.
- SQL Serveri (Microsoft ose Oracle).
  
Komponentet që preferohet të blihen për të arritur funksionimin e sistemit janë:

- Web Serverët. (2)
- Database Serveri. (1)
- Kompjuterë shtesë.
- Kamera per regjistrimin e videove.
- Paisjet kryesore për zyra.

### Kushtet e pranimit

Për pranimin e këtij projekti duhet bërë testime nga antarë të kompanisë XIAOMI dhe ekspertëve të kësaj fushe. Rezultatet e këtyre testimeve do të paraqiten para ekipës kontrolluese të caktuar nga  kompania në fjalë. Një ditë para realizimit final të projektit testitmet preliminare do të paraqiten para bordit të kompanisë në fjalë edhe do shqyrtohet miratimi i këtij projekti. Produkti duhet të jetë në përputhje me të gjitha kërkesat dhe standardet e kompanisë ‘XIAOMI’ dhe të gjitha pikat e këtij sistemi të jenë funksionale.

### Kushtet e dorëzimit

Sistemi online HelpDesk pritet që të jetë i gatshëm për jo më shumë se  6 muaj prej ditës së nënshkrimit të kontrates me të cilën hynë në fuqi ky projekt. Sistemi  duhet të testohet para lansimit dhe duhet të jetë i qëndrueshëm, stabil ndaj kërkesave të klientëve. Paisjet të cilat mundësojnë funksionalitetin e kësaj platforme online duhet të jenë të reja  dhe me garancion nga prodhuesit përkatës.
Dokumentimi i cili duhet të dorëzohet me rastin e finalizimit të projektit janë:

- Dokumenti që përfshin çdo paisje të blerë.
- Manuali për përdorimin e sistemit.
- Manuali për secilën paisje hardwerike.

### Garancioni

Sistemi online në momentin e dorëzimit duhet të jetë në funksionalitet 100% dhe i çasshëm nga përdoruesit e kësaj platforme. Sistemi duhet të jetë në gjendje të punojë 24/7 dhe për kohë të pacaktuar deri në marrjen e ndonjë vendimi për mos funksionim nga ana e kompanisë. Për çdo dëmtim eventual hardwerik përgjegjës është kompania “Xiaomi”. Për mos funksionalitet të plotë të softwerit atëherë përgjegjësia bie mbi punëtorët e  kompanisë. Mirëmbajtja bëhet nga punëtorët e kompanisë “Xiaomi” të cilët janë në kontratë të pacaktuar nga kompania. Për çdo ndryshim eventual rreth sistemit, vendim merr bordi përgjegjës i kompanisë.
