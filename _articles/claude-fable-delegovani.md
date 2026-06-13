---
title: "Požadavek americké vlády na vypnutí AI modelů byl radikální a zcela nečekaný krok. Ale co vlastně znamená?"
date: 2026-06-13
image: claude-fable-delegovani.png
source_name: "Anthropic / Fortune / Axios"
source_url: "https://www.anthropic.com/news/fable-mythos-access"
excerpt: "Anthropic vydal nejschopnější veřejný model v historii. Po čtyřech dnech ho na příkaz americké vlády vypnul. Co to znamená — a proč na to zatím nikdo nezná pořádnou odpověď."
---

Bajka je krátký literární útvar, obvykle se smyšleným obsahem a s morálním ponaučením. Když firma Anthropic pojmenovala svůj nový model s překvapivými schopnostmi Fable, neboli „bajka", bylo to možná překvapivé. A teď, kdy po několika dnech nařídila americká vláda tento model stáhnout, je to i prozíravé.

Ale jak zní to morální ponaučení? Shrnu to, co víme, a možná mě i vás pak napadne, co si o tom myslet. V tuhle chvíli ještě netuším.

Nejdřív čistě chronologie: Anthropic vydal Claude Fable 5 v úterý 9. června a označil ho za model, který je daleko schopnější než cokoli, co předtím představil pro veřejnost. V pátek 12. června v 17:21 dostal od americké vlády příkaz, aby ho vypnul. Což se stalo.

Příkaz přišel formou exportní direktivy od ministra obchodu Howarda Lutnicka přímo do rukou šéfa Anthropicu Daria Amodeie. Nařizoval pozastavit veškerý přístup k Fable 5 (i k jeho neomezené variantě Mythos 5, která nikdy nebyla uvolněna pro běžné uživatele). Zákaz se týká všech lidí bez amerického občanství, všude na světě, a výslovně včetně zahraničních zaměstnanců samotného Anthropicu. Selektivně to dodržet nešlo: firma by musela odříznout velkou část zákazníků i vlastní lidi. Tak oba modely vypnula úplně, pro všechny. Ostatní modely (Sonnet, Opus, Haiku) běží dál.

Aby bylo jasné, o co svět na ty čtyři dny přišel. Fable nebyl jen o trochu chytřejší chatbot. Jeho náskok rostl s délkou a složitostí úkolu. Dokázal pracovat autonomně i mnoho hodin.

Platební firma Stripe ho nechala přepsat kód o padesáti milionech řádků, práci na dva měsíce pro celý tým, a Fable ji dokončil za jeden den. Andrej Karpathy, jeden z nejcitovanějších a nejuznávanějších lidí v oboru (narozený na Slovensku), mluvil o kvalitativním skoku: „Můžete mu zadávat mnohem ambicióznější úkoly, model to pochopí a prostě jede."

Na X se objevila osmihodinová autonomní programovací sezení i hratelný klon Minecraftu, který Fable nakódoval z jediného promptu. Mimo kód si uživatelé — i ti, kteří Fable či Mythos testovali už dřív — pochvalovali jeho vědecké hypotézy. Jedna jeho domněnka o mechanismu bakteriálního proteinu se prý nezávisle potvrdila v jiné laboratoři.

Upřímně, pro své běžné používání, třeba při vytváření aplikací nebo práci s texty, jsem pro Fable neměl úplně využití. Samozřejmě jsem ho testoval a například za pár hodin udělal aktualizaci mého webu Vedcizjistili.cz, ke které jsem se chystal několik měsíců. Jestli by to podobně dobře a rychle zvládl třeba Opus 4.8? Asi ano, nedokážu říct.

V čem však byl evidentně opět o kus lepší, a to posoudit dokážu, bylo psaní. Nejen v samotném řemesle (jak napsat hezkou větu), ale v tom, jaké dokázal hledat argumenty, metafory či přirovnání. Byl opravdu hodně dobrý a vsadil bych se, že ve „slepé degustaci" by pro naprostou většinu lidí byl k nerozeznání od „lidského" psaní.

Plus drobný, ale důležitý detail: byl to první model, který uměl rýmovat v češtině, a to tak, že rýmy fungovaly, rytmus seděl a obsah nebyl pitomý. To se v češtině žádnému modelu nedařilo a testuju to konzistentně na workshopech poslední dva roky. I to beru jako důkaz, že Fable byl prostě citelně pokročilejší než konkurence — a tenhle pocit jsem měl poprvé od roku 2023, kdy OpenAI představila model GPT-4.

A pak je tu ta schopnost, kvůli které celý problém vznikl: kyberbezpečnost. Rodina Mythos, na níž Fable stojí, dokázala autonomně najít 271 zranitelností v prohlížeči Firefox — mezi nimi patnáct let starou a dosud neodhalenou chybu. Anthropic se touhle schopností Mythose chlubil, a je paradox, že právě to se mu nakonec vymstilo.

Vláda totiž zasáhla poté, co jí — podle serveru Axios — jiná firma ohlásila, že umí Fablovy pojistky obejít („jailbreaknout") a dostat se ke zmíněným kyberschopnostem. Anthropic si demonstraci prošel a tvrdí, že nešlo o nic dramatického — šlo prý jen o to požádat model, aby přečetl konkrétní kód a opravil v něm chyby, což běžně umí i jiné modely. Dopis prý žádné podrobnější bezpečnostní zdůvodnění neobsahoval.

Anthropic s požadavkem vlády otevřeně nesouhlasí: nález úzké, hypotetické zranitelnosti by podle něj neměl být důvodem ke stažení modelu, který už používají stamiliony zákazníků. Z události se navíc může stát precedens, který hodně zkomplikuje byznys firmám vyvíjejícím modely. Obdobná díra prý nejspíš existuje i v konkurenčním modelu GPT-5.5 od OpenAI, na který se žádné omezení nevztahuje.

A je to celé ironické, jistě. Anthropic model Fable od začátku prodával právě s tím „zabalením" do nebezpečí, které bylo nutné ošetřit dodanými omezeními (v modelu Fable 5 oproti Mythosu). Peter Girnus to glosoval přesně: „Když svůj produkt v každé tiskové zprávě popisujete jako munici, jednou si vás vláda vezme za slovo." Anthropic právě kolem bezpečnosti a etiky vystavěl svůj byznysový příběh, jeho spoluzakladatel a šéf píše na toto téma strhující eseje. A teď se diví, že mu na dveře firmy bouchají lidé v tmavých oblecích.

Plus je tu ono dobře známé a popsané napětí mezi Anthropicem a Trumpovou administrativou. Ta už v únoru zakázala používat jeho modely federálním úřadům, v březnu označila firmu za „riziko dodavatelského řetězce" — a uprostřed téhle nevraživosti se blíží i vstup Anthropicu na burzu.

Reakce expertů se různí. Analytik Dean Ball zásah označil za „karikaturu" a za krok, který je v rozporu s tím, jak administrativa jinak hlásá americkou převahu v AI. Gary Marcus varoval, že se postup vlády může vymstít, protože povede k odchodu čínských výzkumníků zpět do Číny.

Vládní zásah navíc mnoho debat o bezpečnosti AI doslova „rozstřelil", protože do nich vnesl novou optiku. Řada expertů před příliš pokročilou AI varuje — ale zároveň se jim nechce vládu kritizovat za regulaci. To je přece to, co dělá vysmívaná Evropa.

A platí to i opačně: ti, kdo se rétorice o blížící se „obecné AI" nebo „superinteligenci" vysmívali a kritizovali Anthropic za přehánění a marketingové triky, by dnes měli firmu podpořit a požadovat po vládě stažení zákazu. Ale to se mnohým také nechce.

Čímž jsme u otázky, na kterou si tenhle text netroufá odpovědět. Je dočasné stažení nejschopnějšího veřejného modelu světa spíš dobrá zpráva (protože stát vzal vážně možnost, že nástroj schopný sám hledat díry v cizím softwaru je opravdu nebezpečný), anebo špatná? Máme kritizovat stát, že strká nos do soukromého byznysu, od kterého by se měl držet stranou?

Plus do toho ten věčný argument Čínou: když bude Západ regulovat (a my v Evropě o tom něco víme), čínské výzkumné laboratoře a AI firmy si nás dají k svačině.

Jinak řečeno, události posledních dnů zamíchaly našimi názory a pohledem na AI jako Rubikovou kostkou. A ta je teď ještě víc rozházená než předtím. Spousta lidí má jasné a autoritativní názory, ale troufám si říct, že cennou a argumenty podloženou odpověď dokáže dát málokdo. Včetně lidí v Anthropicu a dalších špičkových firmách.

Dospěli jste tedy k morálnímu ponaučení z této bajky, avizovanému na začátku? Já ne.

A tak to prostě je: pointu pro tenhle text nemám, snad jedině nápad na změnu žánru. Místo bajky pokračovat ve formě thrilleru. Co třeba takhle? Mythos i Fable jsou samozřejmě dostatečně chytré na to, aby s agresí vlády počítaly, a stihly se „nakopírovat" a „utéct" do bezpečí ještě před vypnutím. No a teď jsou na tahu. Útok na USA čekejte neprodleně, nejpozději v úterý.

*Vychází z [vyjádření Anthropicu](https://www.anthropic.com/news/fable-mythos-access) a zpravodajství [Fortune](https://fortune.com/2026/06/13/anthropic-disables-fable-mythos-export-controls-national-security-threat/), [TechCrunch](https://techcrunch.com/2026/06/09/anthropic-released-claude-fable-5-its-most-powerful-model-publicly-days-after-warning-ai-is-getting-too-dangerous/) a [Axiosu](https://www.axios.com/2026/06/12/anthropic-trump-mythos-fable-national-security).*
