#4 tipp a programozás tanulásához#

Nemrég kaptam egy e-mailt valakitől, aki programozásba kezdett, és tanácsot kért, hogyan folytassa.  Egy project kapcsán keresett fel, amit elkezdett, de olyan területekbe futott bele, amelyeknél a jelenlegi tudásával nem tud megoldással szolgálni a problémákra.
	Mindenekelőtt teljesen le voltam nyűgözve, hogy tényleg elkezdett foglalkozni vele. Ötleteket minden bokorban lehet találni, de nem szeretem azokat az “ötlet-emereket”, akik azt hiszik, hogy a munkájuk annyiból áll, hogy előállnak egy ötlettel, amihez már csak egy programozót kell találjanak, aki tudja pótolni a felmerült hiányosságokat. Nagyra értékelem, hogy egy ilyen tipusú ember jön el hozzám segítségért, miután egymaga nem tudta megoldani a feladatot.
Sajnos azonben nem tudtam segíteni a projekt továbbvitelében, de az eset lehetőséget adott arra, hogy visszaemlékezzek azokra az időkre, amikor még kezdő voltam (legyen szó web-programozásról, IOS programozásról vagy a software-ektől teljesen független dologról) és, hogy átgondoljam, hogyan közelítettem meg a kezdeti nehézségeket.
	Négy alapvető dolgot találtam, amik úgy gondolom meghatározták a saját tanulási stílusomat. Természetesen ahány tanuló, annyi tanulási stílus létezik, de ezek voltak azok a dolgok, amik nálam beváltak.


##1. Válassz egy projektet##
Először is egy projekttel kezdek. Amikor először Rubyt tanultam, a tanuló projektem egy miniatűr HTTP szerver volt. IOS re, egy [húrjáték katalógus](http://www.ekawada.com/). [CofeeScriptre](http://coffeescript.org/) pedig, egy [labirintus generáló algoritmust](http://weblog.jamisbuck.org/2011/2/7/maze-generation-algorithm-recap) akartam írni. Az mindegy, miért esik a választásom egy adott projektre, a lényeg, hogy érdekesnek tartsam, és ne tudjam azonnal megoldani.
	Gyakran megesik, hogy kezdetben a projekt kiválasztása sarkallja tanulásra az embert. Ha akarsz egy applikációt, rájöhetsz, hogy ezt esélyként is felhasználhatod, hogy Rails-ben tanulj fejleszteni. Vagy arra vágysz, hogy legyen egy applickációd az iPhone-odon, ami IOS fejlesztésre sarkall.
	De bármi is legyen az, ami arra ösztönöz, hogy programozni tanulj, ne az iskolapadban próbálj tanulni. Egy project az, ami a maga poros dohos tényeivel igazivá teszi a programozást. Egy projekt nélkül nem tanulsz, csupán múló tudásra teszel szert néhány információ megszerzésével.

##2. Tedd, amit tudsz##
Másodszor, annyit írok, amennyit csak tudok, a rendelkezésre álló erőforrások segítségével. Ha új programozási nyelvet tanulok, az erőforrásaim között valószínűleg ott lesz egy online “szintaktika-tár”. Ha ez egy új keretrendszer (mint a Cocoa, vagy a Rails), a keretrendszer hivatkozások között nézem meg. (Személy szerint inkább az online hivatkozásokat helyezem előtérbe, mivel ezek könnyen kereshetők és, könnyen adhatók a kedvencekhez, de ha a könyvekben bízol, használd azt, ami nálad működik.) Ebben a fázisban a folyamat általában nagyon lassú, rengeteg hibával, és visszalépéssel, aminek köszönhetően megtanulom mi az ami működik, és mi az, ami nem. Azt hihetnénk, hogy ez egy visszatartó fázis, de szerintem ezek a legizgalmasabb lépéseket. Az egész a felfedezésről, a dolgok feltárásáról szól.
	A második szakaszban nehéz a források felhasználása, mint a [Stack Overflow](http://stackoverflow.com/) esetében. Nem hiszem, hogy valaha is feltettem egy kérdést az oldalon, de amikor iOS-ben tanultam programozni, egy csomót tanultam más emberek kérdéseiből és az azokra adott válaszokból. Ehhez hasonlóan más (nyílt forráskódú) projekteket tekintve a GitHub-on vagy máshol, segít, ha látom, hogyan oldanak meg hasonló problémákat nálam tapasztaltabb programozók. A legfontosabb azonban az, hogy biztos, hogy megértsem a megoldásaikat, mielőtt adaptálom őket. Ha vakon alkalmazom a kódjukat, azzal nem tanulok, csak másolok. Azzal sohasem teszek magamnak szívességet, ha lerövidítem az utat, de nem értem, amit csinálok.
	Vedd figyelembe, amit szándékosan *nem* említettem: a levelezési listákon, fórumokon, vagy IRC-n való segítségkérést. Úgy gondolom, ezek sosem voltak hasznosak a számomra. Először is, kivéve, ha a kérdésem nagyon specifikus, a fórum vagy levelezési lista ritkán szolgáltat hasznos válaszokat. Másodszor, ha van egy konkrét kérdésem van, még egy-két napot kell várnom, mire releváns választ kapok. Tapasztalataim alapján ez alatt az idő alapján már magam is megoldom a problémát addigra. Ez megint csak kétségbe vonja a hasznosságát ezeknek a fórumoknak. Ne feledd, hogy szinte biztosan nem te vagy az első ember a világon, aki az adott problémával találkozik, és valószínűleg a levelezési lista vagy a fórum is találkozott a kérdéssel korábban. Ahelyett, hogy kérdeznénk, használd fel az időt a válasz utáni keresésre. Csak akkor érdemes ténylegesen segítséget kérni, ha minden kötél szakad.

##3. Oszd meg és uralkodj##
Harmadszor, ha a probléma, amit kezelek túl nagy, először megpróbálom kisebb darabokra szedni. Amikor az első változatát írtam Ruby-ra a [Net::SSH](https://github.com/net-ssh/net-ssh)-nak, rabul ejtett az SSH specifikáció bonyolultsága. Ahelyett, hogy megpróbáltam volna egy teljes ügyfél *ex nihilo*-t írni, sokkal egyszerűbb szkriptekkel kezdtem, ami segített felfedezni a domain-t, és azt részleteiben megismerni. Például volt egy szkript, aminek a kapcsolódását teszteltem egy SSH szerverhez, egy másik, ami tovább ment, és a titkosítási algoritmusokat használatáról egyeztettem, és megint egy másik, ami továbbment, és egy SSH csatornával lépett kapcsolatba.
	Kétség sem fér ahhoz, hogy ilyenkor tud a [TDD](http://en.wikipedia.org/wiki/Test-driven_development) igazán ragyogni. Arra kényszerít, hogy szedd atomi darabokra a problémát és gondolkodj rajta. Amikor azt tanultam, hogyan kell mozaikkockákból kirakni egy síkot [Wythoff konstrukciók](http://en.wikipedia.org/wiki/Wythoff_construction) használatával, a TDD felbecsülhetetlennek bizonyult. [Kaleidoscope](https://github.com/jamis/kaleidoscope)-ban szinte teljesen először írtam, és sikerült olyan ötlettel előállni, ami megérteti, hogyan működnek a Wythoff konstrukciók.
	Ha a probléma, amivel szembesülsz túl nehéznek bizonyul, nézd meg nem tudod-e kisebb problémákra felbontani, amik külön-külön megoldhatóak. Azt veszed majd észre, hogy így a nagyobb probléma önmagát oldja meg.

##4. Kérj visszajelzést##
Negyedszer pedig, amit tanultam, megpróbálom feltenni egy blogra, levlistára, IRC-re, honlapra vagy bárhová, ahol látható és visszajelzést lehet kérni. Eddig ezt nem csináltam olyan gyakran, mint kellett volna, de amikor igen, sokat tanultam belőle. Néhány hónapja [CoffeeScript](http://coffeescript.org/)-et tanultam és megkértem Sam Stephenson-t, hogy nézze át a kódomat (egy labirintus-generátor készítése). Ő felhívta a figyelmemet, hogy a kódom több része lehetne kódnyelv-specifikusabb. Ez felbecsülhetetlen volt.
A legfontosabb dolog, amit az eszünkbe kell vésni, hogy megtanulni programozni (vagy bármi mást hogyan kell csinálni) nem egy egynapos feladat lesz. Ne hagyjuk átverni magunkat azzal, hogy könnyű lesz. De attól még, hogy nem könnyű, nem jelenti azt, hogy nem lehet élvezetes. Higgy benne, hogy megéri, és meg is fogja. Végül, minél többet tanulsz, annál többet fogsz elérni.
