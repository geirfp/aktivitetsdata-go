# Vocabulary
This vocabulary - based on the the [ADL Vocabulary](http://xapi.vocab.pub/datasets/adl/) - is being developed by Standards Norway Committee for Learning Technology ([SN/K 186](http://www.standard.no/fagomrader/ikt/laringsteknologi/)).

* [Verbs](#verbs)
* [Activity Types](#activityTypes)

<a name="verbs"></a>
## Verbs
Label|Description|ID (IRI)|Vocabulary|
-----|-----------|--------|----------|
abandoned|Indicates the activity provider has determined that the session was abnormally terminated either by an actor or due to a system failure.|https://w3id.org/xapi/adl/verbs/abandoned|https://w3id.org/xapi/adl
stoppet (evt: forlot, forkastet)|Angir at leverandøren av aktiviteten har fastslått at sesjonen stanset på unormal måte, enten av en aktør eller på grunn av systemsvikt.
answered|Indicates the actor replied to a question, where the object is generally an activity representing the question. The text of the answer will often be included in the response inside result.|http://adlnet.gov/expapi/verbs/answered|https://w3id.org/xapi/adl
besvarte|Angir at aktøren svarte på et spørsmål der objektet (som verbet gjelder) som regel er en aktivitet som representerer spørsmålet. Teksten i svaret blir ofte tatt inn i responsen i resultatet.
asked|Indicates an inquiry by an actor with the expectation of a response or answer to a question.|http://adlnet.gov/expapi/verbs/asked|https://w3id.org/xapi/adl
spurte|Angir at en aktør har gjort en forespørsel med forventning om å få et svar.
attempted|Indicates the actor made an effort to access the object. An attempt statement without additional activities could be considered incomplete in some cases.|http://adlnet.gov/expapi/verbs/attempted|https://w3id.org/xapi/adl 
forsøkte|Angir at aktøren gjorde et forsøk på å få tilgang til objektet. Et forsøk uten ytterligere aktiviteter kan i enkelte tilfeller anses som ufullstendig.
attended|Indicates the actor was present at a virtual or physical event or activity.|http://adlnet.gov/expapi/verbs/attended|https://w3id.org/xapi/adl 
deltok|Angir at aktøren var til stede ved en virtuell eller fysisk hendelse eller aktivitet.
commented|Indicates the actor provided digital or written annotations on or about an object.|http://adlnet.gov/expapi/verbs/commented|https://w3id.org/xapi/adl 
kommenterte|Angir at aktøren leverte digitale eller skrevne anførsler på eller om et objekt.
completed|Indicates the actor finished or concluded the activity normally.|http://adlnet.gov/expapi/verbs/completed|https://w3id.org/xapi/adl 
fullførte|Angir at aktøren fullførte eller avsluttet aktiviteten normalt.
exited|Indicates the actor intentionally departed from the activity or object.|http://adlnet.gov/expapi/verbs/exited|https://w3id.org/xapi/adl 
forlot (evt: gikk ut av)|Angir at aktøren med vilje forlot en aktivitet eller et objekt.
experienced|Indicates the actor only encountered the object, and is applicable in situations where a specific achievement or completion is not required.|http://adlnet.gov/expapi/verbs/experienced|https://w3id.org/xapi/adl 
erfarte (evt: opplevde)|Angir at aktøren kun påtraff objektet; kan anvendes i situasjoner der det ikke kreves spesielle resultater eller fullføring.
failed|Indicates the actor did not successfully pass an activity to a level of predetermined satisfaction.|http://adlnet.gov/expapi/verbs/failed|https://w3id.org/xapi/adl 
strøk (evt: feilet, mislyktes)|Angir at aktøren ikke fullførte en aktivitet på et forutbestemt prestasjonsnivå.
imported|Indicates the actor introduced an object into a physical or virtual location.|http://adlnet.gov/expapi/verbs/imported|https://w3id.org/xapi/adl
innførte (evt: importerte)|Angir at aktøren førte et objekt inn på et fysisk eller virtuelt sted.
initialized|Indicates the activity provider has determined that the actor successfully started an activity.|http://adlnet.gov/expapi/verbs/initialized|https://w3id.org/xapi/adl 
oppstartet (evt: startet, klargjorde, initialiserte)|Angir at leverandøren av aktiviteten har fastslått at aktøren har startet en aktivitet tilfredsstillende.
interacted|Indicates the actor engaged with a physical or virtual object.|http://adlnet.gov/expapi/verbs/interacted|https://w3id.org/xapi/adl
samhandlet (evt: benyttet, interagerte)|Angir at aktøren benyttet et fysisk eller virtuelt objekt.
launched|Indicates the actor attempted to start an activity.|http://adlnet.gov/expapi/verbs/launched|https://w3id.org/xapi/adl 
begynte (evt: påbegynte, åpnet)|Angir at aktøren forsøkte å starte en aktivitet.
logged-in|Indicates the actor gained access to a system or service by identifying and authenticating with the credentials provided by the actor.|https://w3id.org/xapi/adl/verbs/logged-in|https://w3id.org/xapi/adl 
logget inn|Angir at aktøren fikk tilgang til et system eller en tjeneste gjennom identifisering og autentisering med identifikator lagt fram av aktøren.
logged-out|Indicates the actor either lost or discontinued access to a system or service.|https://w3id.org/xapi/adl/verbs/logged-out|https://w3id.org/xapi/adl
logget ut|Angir at aktøren enten mistet eller avsluttet tilgang til et system eller en tjeneste.
mastered|Indicates the highest level of comprehension or competence the actor performed in an activity.|http://adlnet.gov/expapi/verbs/mastered|https://w3id.org/xapi/adl 
mestret|Angir høyeste nivå av forståelse eller kompetanse for aktørens prestasjon i en aktivitet.
passed|Indicates the actor successfully passed an activity to a level of predetermined satisfaction.|http://adlnet.gov/expapi/verbs/passed|https://w3id.org/xapi/adl 
besto|Angir at aktøren har lykkes i å gjennomføre en aktivitet på et forutbestemt nivå av tilfredsstillelse.
preferred|Indicates the selected choices, favored options or settings of an actor in relation to an object or activity.|http://adlnet.gov/expapi/verbs/preferred|https://w3id.org/xapi/adl 
foretrakk|Angir valgte eller foretrukne muligheter eller innstillinger for en aktør i forhold til et objekt eller en aktivitet.
progressed|Indicates a value of how much of an actor has advanced or moved through an activity.|http://adlnet.gov/expapi/verbs/progressed|https://w3id.org/xapi/adl 
nådde|Angir en verdi for hvor mye en aktør har gått fram eller endret seg gjennom en aktivitet.
registered|Indicates the actor is officially enrolled or inducted in an activity.|http://adlnet.gov/expapi/verbs/registered|https://w3id.org/xapi/adl 
registrerte|Angir at aktøren er offisielt innskrevet eller innført i en aktivitet.
responded|Indicates an actor reacted or replied to an object.|http://adlnet.gov/expapi/verbs/responded|https://w3id.org/xapi/adl 
besvarte (evt: responderte)|Angir at en aktør reagerte eller svarte på et objekt.
resumed|Indicates the application has determined that the actor continued or reopened a suspended attempt on an activity.|http://adlnet.gov/expapi/verbs/resumed|https://w3id.org/xapi/adl 
gjenopptok|Angir at applikasjonen har fastslått at aktøren fortsatte eller gjenåpnet et utsatt forsøk på en aktivitet.
satisfied|Indicates that the authority or activity provider determined the actor has fulfilled the criteria of the object or activity.|https://w3id.org/xapi/adl/verbs/satisfied|https://w3id.org/xapi/adl 
tilfredsstilte|Angir at leverandøren av (eller myndigheten for) aktiviteten har besluttet at aktøren har oppfylt kriteriene for objektet eller aktiviteten.
scored|Indicates a numerical value related to an actor's performance on an activity.|http://adlnet.gov/expapi/verbs/scored|https://w3id.org/xapi/adl
skåret|Angi en numerisk verdi knyttet til en aktørs prestasjon i en aktivitet.
shared|Indicates the actor's intent to openly provide access to an object of common interest to other actors or groups.|http://adlnet.gov/expapi/verbs/shared|https://w3id.org/xapi/adl 
delte|Angir aktørens hensikt om å gi åpen tilgang til et objekt av felles interesse for andre aktører eller grupper.
suspended|Indicates the status of a temporarily halted activity when an actor's intent is returning to the or object activity at a later time.|http://adlnet.gov/expapi/verbs/suspended|https://w3id.org/xapi/adl 
utsatte (evt: satte på vent)|Angir status for en aktivitet som er midlertidig stanset, når aktøren har til hensikt å komme tilbake til objektet eller aktiviteten på et senere tidspunkt.
terminated|Indicates that the actor successfully ended an activity.|http://adlnet.gov/expapi/verbs/terminated|https://w3id.org/xapi/adl 
avsluttet|Angir at aktøren har fullført en aktivitet tilfredsstillende.
voided|A special reserved verb used by a LRS or application to mark a statement as invalid. See the xAPI specification for details on Voided statements.|http://adlnet.gov/expapi/verbs/voided|https://w3id.org/xapi/adl 
ugyldiggjorde|Et spesielt reservert verb brukt av en LRS eller applikasjon for å merke at et utsagn ikke gjelder. Se xAPI-spesifikasjonen for detaljer om Ugyldige utsagn.
waived|Indicates that the learning activity requirements were met by means other than completing the activity. A waived statement is used to indicate that the activity may be skipped by the actor.|https://w3id.org/xapi/adl/verbs/waived|https://w3id.org/xapi/adl
avsto|Angir at kravene for læringsaktiviteten ble tilfredsstilt på annen måte enn ved å fullføre aktiviteten. Avstått blir brukt for å angi at aktøren kan hoppe over aktiviteten.

<a name="activityTypes"></a>
## Activity Types
Activity Type|Description|ID (IRI)|Vocabulary|
-------------|-----------|--------|----------|
assessment|An assessment is an activity type that determines a learner’s mastery of a particular subject area. An assessment typically has one or more questions.|http://adlnet.gov/expapi/activities/assessment|https://w3id.org/xapi/adl 
vurdering (evt: kartlegging)|En vurdering er en aktivitetstype som fastsetter en elevs mestring av et visst fagområde. En vurdering inneholder typisk ett eller flere spørsmål.
attempt|An attempt is a discrete set of learner experiences in an activity. This activity gives systems the ability to uniquely identify experiences when they may have happened in different interactions with the same activity.|http://adlnet.gov/expapi/activities/attempt|https://w3id.org/xapi/adl 
forsøk|Et forsøk er et særskilt sett av læringserfaringer i en aktivitet. Denne aktiviteten gir systemene mulighet til å identifisere erfaringer unikt når de kan ha oppstått i ulike interaksjoner med samme aktivitet.
course|A course represents an entire “content package” worth of material. The largest level of granularity. Unless flat, a course consists of multiple modules.|http://adlnet.gov/expapi/activities/course|https://w3id.org/xapi/adl 
kurs|Et kurs representerer en hel «innholdspakke» av materiale. Det er groveste nivå av granularitet. Med mindre det er flatt, består et kurs av flere moduler.
file|A file is similar to a link, only the resource is more likely to be used at a) a different time, b) can be used offline, and/or c) could be used with a different system. Only the expectation changes. Files are not considered learning content or SCOs. If a file is intended for this purpose, it should be re-categorized.|http://adlnet.gov/expapi/activities/file|https://w3id.org/xapi/adl
fil|En fil ligner på en lenke, kun at ressursen sannsynligvis a) brukes på et annet tidspunkt, b) kan brukes frakoplet, og/eller c) kan brukes i et annet system. Kun forventningen endrer seg. Filer blir ikke ansett å være læringsinnhold eller SCOer. Dersom en fil er tiltenkt et slikt formål, bør den kategoriseres annerledes.
interaction|An interaction is typically a part of a larger activity (such as an assessment, game, or simulation) and refers to a control to which a learner provides input. An interaction can be either an asset or function independently.|http://adlnet.gov/expapi/activities/interaction|https://w3id.org/xapi/adl 
interaksjon|En interaksjon er typisk en del av en større aktivitet (for eksempel en vurdering, et spill eller en simulering) og viser til styring som eleven gir innspill til. En interaksjon kan uavhengig enten være et aktivum eller en funksjon.
lesson|A lesson is learning content that may or may not take on the form of a SCO (formal, tracked learning). A lesson may stand-alone or may be part of a larger course.|http://adlnet.gov/expapi/activities/lesson|https://w3id.org/xapi/adl 
leksjon|En leksjon er læringsinnhold som eventuelt kan anta form av en SCO (formell, sporet læring). En leksjon kan være frittstående eller være del av et større kurs.
link|A link is simply a means of expressing a link to another resource within, or external to, an activity. A link is not synonymous with launching another resource and should be considered external to the current resource. Links are not learning content, nor SCOs. If a link is intended for this purpose, it should be re-categorized.|http://adlnet.gov/expapi/activities/link|https://w3id.org/xapi/adl
lenke|En lenke er helt enkelt en måte å uttrykke kopling til en annen ressurs i eller utenfor en aktivitet. En lenke forutsetter ikke at en annen ressurs åpnes og bør anses som ekstern i forhold til den aktuelle ressursen (aktiviteten). Lenker er ikke læringsinnhold eller SCOer. Dersom en lenke er tiltenkt et slikt formål, bør den kategoriseres annerledes.
media|Media refers to text, audio, or video used to convey information. Media can be consumed (tracked: completed), but doesn’t have an interactive component that may result in a score, success, or failure.|http://adlnet.gov/expapi/activities/media|https://w3id.org/xapi/adl
medium|Medium viser til tekst, lyd eller video som benyttes til å formidle informasjon. Et medium kan forbrukes (sporing: fullført, som i result.complete), men har ikke en interaktiv komponent som kan resultere i skåre (angitt i result.response.score), vellykket (angitt via result.success = true) eller stryk (angitt via result.success = false).
meeting|A meeting is a gathering of multiple people for a common cause or interest.|http://adlnet.gov/expapi/activities/meeting|https://w3id.org/xapi/adl
møte|Et møte er en samling av flere mennesker for felles formål eller interesse.
module|A module represents any “content aggregation” at least one level below the course level. Modules of modules can exist for layering purposes. Modules are not content. Modules are one level up from all content.|http://adlnet.gov/expapi/activities/module|https://w3id.org/xapi/adl
modul|En modul representerer en «innholdssamling» på minst ett nivå lavere enn kursnivå. Moduler av moduler kan finnes for å oppnå lagdeling. Moduler er ikke innhold. Moduler er ett nivå opp fra alt innhold.
objective|An objective determines whether competency has been achieved in a desired area. Objectives typically are associated with questions and assessments. Objectives are not learning content and cannot be SCOs.|http://adlnet.gov/expapi/activities/objective|https://w3id.org/xapi/adl
mål|Et mål fastslår om det er oppnådd kompetanse på et visst område. Mål blir typisk knyttet til spørsmål og vurderinger. Mål er ikke læringsinnhold og kan ikke være SCOer.
performance|A performance is an attempted task or series of tasks within a particular context. Tasks would likely take on the form of interactions, or the performance could be self-contained content. It emphasizes students or learners being able to do, or perform, specific skills as a result of the instruction.|http://adlnet.gov/expapi/activities/performance|https://w3id.org/xapi/adl
prestasjon|En prestasjon er et forsøk på en oppgave eller en serie oppgaver i en viss sammenheng. Oppgaver har sannsynligvis form av interaksjoner, eller prestasjonen kan være innhold i seg selv. Det legges vekt på at studenter eller elever evner å utføre visse ferdigheter som resultat av instruksjonen.
profile|A profile is an activity that defines a set of rules and recommendations for generating xAPI statements for a particular domain. The inclusion of a profile activity in a statement identifies that statement as following the rules outlined in the profile.|http://adlnet.gov/expapi/activities/profile|https://w3id.org/xapi/adl 
profil|En profil er en aktivitet som definerer et sett regler og anbefalinger for å generere xAPI-utsagn for et visst fagområde. Ved å inkludere en profilaktivitet i et utsagn vises at utsagnet følger reglene i profilen.
question|A question is typically part of an assessment and requires a response from the learner, a response that is then evaluated for correctness.|http://adlnet.gov/expapi/activities/question|https://w3id.org/xapi/adl
spørsmål|Et spørsmål er som regel del av en vurdering/kartlegging og krever et svar fra eleven; det blir så vurdert om svaret er korrekt.
simulation|A simulation is an attempted task or series of tasks in an artificial context that mimics reality. Tasks would likely take on the form of interactions, or the simulation could be self-contained content.|http://adlnet.gov/expapi/activities/simulation|https://w3id.org/xapi/adl
simulering|En simulering er et forsøk på en oppgave eller serie oppgaver i en kunstig sammenheng som etterligner virkeligheten. Oppgaver har sannsynligvis form av interaksjoner, eller simuleringen kan være innhold i seg selv. 
