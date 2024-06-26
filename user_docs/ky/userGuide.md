# NVDA NVDA_VERSION программасынын колдонмо башкаруусу

[TOC]

<!-- KC:title: NVDA NVDA_VERSION командаларынын кыскача маалымдамасы -->



## Киришүү {#toc2}

NVDAга Кош келдиңиз!

NonVisual Desktop Access (NVDA)- Microsoft Windows үчүн акысыз иштеп жаткан системасы , ачык булак, экран окугуч программасы болуп саналат.
синтезделген  сөз жана Брайль шрифти аркылуу байланышты камсыз кылуу, көзү начар көргөн адамдарга NVDA программасы аркылуу Windows операциондук системасын колдонууга толук мүмкүнчүлүк берет.
NVDA программасы [NV Access](https://www.nvaccess.org/), коммерциялык эмес уюм тарабынан  иштелип чыккан, коомчулук  аркылуу таратылууда.

### Негизги өзгөчөлүктөрү {#toc3}

NVDA көрбөгөн адамдарга жана начар көргөн адамдарга Windows операциондук системада жана көптөгөн программаларда иштөөгө мүмкүндүк берет 

Программанын кийинки эң маанилүү мүмкүнчүлүктөрү:

* Популярдуу тиркемелерди колдоо, мисалы web-браузерлер,почта кардарлары, интернет мессенджерлерди жана офис файлдарын
* 80 тилди колдогон сүйлөө- синтезатору+
Жеткиликтүү болгон жерде текстти форматтоонун маалымдамасы, мисалы тексттин стили, өлчөмү, форматтоо стили жана орфографиялык каталар.
Чычкандын алдындагы текстти автоматтык түрдө жарыялоо жана чычкандын турган жеринде атайын үн индикациясы.
Көп сандагы  Брайльдык дисплейди колдоо, анын ичинде Брайльдык тергичи бар  дисплей кирүүсү бар.
NVDAны USB-флеш-картадан же орнотууну талап кылбаган  башка эс тутум түзмөктөн орнотуу мүмкүнчүлүгү
Сүйлөө орнотуусунун оңой колдонулушу
51 тилге которулган 
Акыркы моделдеги 32 жана 64 бит Windows операциалык системаларын колдойт
Windows экранына кирүүдө жана башка коргонгон экрандарда NVDAны орнотуу мүмкунчүлүгү
Башкаруу элементтерин жана текстти колдонуудагы кыймылдарын жарыялоо
Жалпы колдонулуучу интерфейстерди колдоо мүмкүнчүлүгү мисалы Microsoft Active Accessibility, Java Access Bridge, IAccessible2 и UI Automation (UI Automation бир гана windows 7 жана андан кийинки версияларды колдойт)
Windows Command Prompt жана консульдук колдонмону колдоо

++ Интернационалданышы ++[Интернационалданышы ]
Дүйнө жүзүндөгү элдер, кайсы тилде суйлөсө да, технологияга тең мүмкүнчүлүгү болгон маанилүү.
Англис тилинен тышкары NVDA программасы 51 тилге которулган: африкалык, немис, амхар, араб, арагон, португал (Бразилия), болгар, бирман, каталанс, колумбия испан, хорват, чех, дат, голландиялык, персид, фин, француз, галисий, грузин, алман, грек, иврит, хинди, венгер, ислан, ирлан, италья, япон, каннада, корей,кыргыз, литва, македон, непал, норвег, польша, португал, панджаб, румын, орус, серб, словак, словен, испан, швед, тамильдик, тай, кытай, түрк, украин жана вьетнам тилдерине которулган.

++ Сүйлөө синтезаторун колдоо ++[Сүйлөө синтезаторун колдоо]
Өзүнүн каттарынан жана программанын интерфейсинен тышкары NVDA, колдонуучуларга ичиндеги маалыматтарды ар түрдүү тилдерде окуй алат,эң башкычы синтезатор колдосо эле.

 NVDA комплектте  көп тилдүү синтезатору камтыйт[eSpeak NG](https://github.com/espeak-ng/espeak-ng).

 NVDA колдогон башка синтезаторлор тууралуу кийинки бөлүмдөн тапса болот[Колдогон сүйлөө синтезатору](#SupportedSpeechSynths) 

++ Брайль дисплейин колдоо ++[Брайль дисплейин колдоо]
Брайль дисплейинин ээлери өзүлөрүнүн тузмөгүнөн  Брайльдык чыгуу NVDA аркылуу маалыматты ала алышат.
Брайль тергичи аркылуу ошондой эле толук камдуу жана кыскартылган Брайль кирүүсү колдоодо.
Толук маалыматты алуу үчүн, сураныч кийинки бөлүмгө өтүңүз [Supported Braille Displays](#SupportedBrailleDisplays)

NVDA көп тилдер үчүн Брайль кодировкасын колдойт, алардын ичинде кыскартылган, толук жана компьютердик көлөмдүү Брайль кодировкалары бар.

### Лицензия жана автордук укук {#toc4}

(C) NVDA_COPYRIGHT_YEARS автордук укуктары NVDA коомунун катышуучуларына тийиштүү.

 NVDA программасы GNU General Public License лицензиясы аркылуу таратылат(Версия 2). 
 NVDA нылицензиянын коштоосунда бул программаны тарата аласыз.
Бул оригинал жана модифицацияланган көчүрмөлөргө тийиштүү
Толук маалымат алуу үчүн [бул лицензиянын толук версиясын көрүү үчүн](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).

## Системалык талаптар {#toc5}

-Баардык операциондук системада колдойт: 32 жана 64 биттик Windows 7, Windows 8, Windows 8.1, Windows 10, ошондой эле Windows Server 2008 R2 дон баштап Windows тун баардык  версиялары.

* Windows 7де иштөөсү үчүн, NVDA Service Pack 1 же андан жогорку орнотууну талап кылат.
* Windows Server 2008 R2 де иштөө үчүн, NVDA Service Pack 1 же андан жогорку орнотууну талап кылат.
* Оперативдик эс тутум: 256 mb жана андан жогору
-Процессордун жыштыгы: 1.0 ГГц жана андан жогору
* 90 MB жакын диск мейкиндиги бар болушу зарыл.

## NVDAны алуу жана орнотуу {#toc6}

Эгерде сизде NVDA көчүрмөсү жок болсо, анда аны [www.nvaccess.org](NVDA_URL) сайтынан жүктөп алсаңыз болот.

“ Көчүрүү” бөлүмүндө NVDAнын акыркы версиясын көчүрүүгө шилтеме ала аласыз.

Жаңы эле көчүрүлгөн файлды орнотууда NVDAнын убактылуу көчүрмөсү иштей баштайт.
Андан соң сизге көчүрмө же жөн гана NVDA менен убактылуу колдонууну улантууга сунушталат.

Эгерде сиз NVDA менен дайыма ушул компьютерде колдоно турган болсоңуз, анда сизге NVDAны орнотууну тандашыңыз керек болот.

Орнотулган  NVDAдан каалаган убакытта портативдүү көчүрмөсүн жазаса болот.

NVDA программасын сиз жаныңызга USB-карта аркылуу алып жүрүү үчүн, портативдүү көчүрмөсүн түзүшүңүз керек болот.
Портативдүү көчүрмөнү ошондой эле каалаган компьютерге орноштурса болот.
Андыктан, эгер NVDAны окууга гана багытталган тузмөккө көчүрүүнү кааласаңыз, мисалы, компакт - диск көчүрмөсү катары, анда сиз орноштуруу үчүн гана керек болгон пакетти көчүрүп алсаңыз болот.
 Азыркы учурда портативдүү нускасын окууга гана мүмкүн болгон учурда орнотуусу жеткиликтүү эмес.

NVDAнын убактылуу көчүрмөсүн колдонсо болот. ( Мисалы демонстрация максат үчүн), бирок NVDAны мындай учурда орнотуу бир аз ыңгайсыз болушу мүмкүн.

### Портативдүү жана убактылуу көчүрүү үчүн чектөөлөр {#toc7}

Системага кирүү учурунда, автоматтык түрдө жүргүзүүнүн мүмкүнсүздүгүнөн тышкары портативдүү жана убактылуу NVDA кийинки чектөөлөргө ээ:

* Башка орнотмолор менен бирге иштөөнүн мүмкүнсүздүгү, администратордун укугу менен иштейт, эгерде NVDA өзүнүн укугу менен орнотулбаса (сунуш талбайт)
* (UAC) Каттоо эсебинин орнотмолорун администратордун укугу менен орнотууну аракет кылуу экранды окуу мүмкүнсүздүгү.
* Windows 8 жана андан жогоркуларда: сенсордук экрандын колдоосунун мүмкүнсүздүгү.
* Windows 8 жана андан жогоркуларда: Microsoft Store катары орнотмолор дүконүндөгү символдордун окулушу жана карап чыгуу режими сыяктуу функцияларга жеткиликсиздиги.
* Windows 8 жана андан жогоркуларда: Башка үндөрдүн үнүн азайтуу функциясынын колдоосунун мүмкүн эмес болгондугу.

### NVDA Орнотуу {#toc8}

NVDAны орнотуу үчүн, орнотуу пакетинен, “ NVDAны бул компьютерге орнотуу” баскычын басыңыз.
Эгерде сиз диалог терезесин жапкан болсоңуз же NVDAны портативдүү көчүрмөдөн орнотууну кааласаңыз, анда сураныч, "NVDA менюсу > Сервис > NVDAны орнотуу..." баскычтарын басыңыз.

Пайда болгон диалог терезеси ырастоону сунуштайт, NVDAны бул компьютерге орнотууну жандырырышыңар керекбы, жана бул орнотуу мурунку орнотуунун оордуна болот деп билдирет.
“Улантуу” баскычын басаарыңыз менен, орнотуу процесси башталат.
Ошондой эле бул диалог терезесинде бир нече варианттар бар, алар тууралуу төмөнкүдө жазылган.
Орнотууда аяктоодон кийин, орнотуу ийгиликтүү аяктады деген терезечеде билдируү чыгат.
"Макул" баскычын басканда, жаңы эле орнотулган NVDA кайрадан жүргүзүлөт.

#### NVDAны Windows экранына киргенде колдонуу {#toc9}

 Бул вариант Windows экранына киргенде, парольду тергенге чейин ,NVDAны автоматтык түрдө жүргүзүлүшүн тандоого мүмкүнчүлүк берет.
 Бул ошондой эле (UAC) эсептик жазуусунун жана башка корголгон иш тактасына тийиштүү

#### Иш тактасында белги жаратуу жана тез баскычтарды орнотуу (ctrl+alt+n) {#toc10}

Бул бөлүм кийинкини тандоого мүмкүнчүлук берет: NVDA кийинки программанын орнотулушу үчүн   иш столунунда тез чакырым жаратуу
Эгерде тез чакырым(Ярлык) түзүлсө,жана ошондой эле тез баскычтар каралса control+alt+n, алар аркылуу NVDAны каалаган убакытта ачса болот.

#### Учурдагы колдонуучунун тескөөлөр папкасына портативдүү версиясын көчүрүү {#toc11}

Бул бөлүм аркылуу, NVDAны учурдагы иштеп жаткан портативдүү көчүрмөдөн колдонуучу тескөөлөрүунө көчүрүлүшү же көчүрүлбөшү керек экенин тандоо мүмкүн.
Бул учурда бул системанын  башка колдонуучуллардын тескөөлөрү көчүрүлбөйт, ошондой эле башка системдик тескөөлөр, мисалы Windows экранына кирүү жана башка корголгон иш такта терезелери.
Бул бөлүм орнотуу пакети эмес, портативдүү көчүрмөдөн гана орнотуулгандан жеткиликтүү.

### Портативдик көчүрмөнү түзүү {#toc12}

NVDA орнотуу пакетинен портативдик көчүрмөнү түзүү үчүн, жөн гана “Портативдик көчүрмөнү түзүү” баскычын басып коюңуз.
Эгерде сиз диалог терезени жапкан болсоңуз дже сизде NVDAнын орнотулган көчүрмөсү киргизилген болсо, анда сураныч, "NVDA менюсу > Сервис > Портативдик көчүрмөнү түзүү..."  бөлүмүн тандаңыз.

Пайда болгон диалог терезечеси NVDAнын портативдик көчурмөсүн түзүү үчүн папканын тандоосун  сунуштайт.
Бул аппараттык камсыздоо диск түзмөгүндөгү же  каалаган USB-картадагы папка болушу мүмкүн.
Бул жерде ошондой эле, NVDAнын  өзүнүн тескөөлөрү үчүн учурдагы колдонуучунун портативдик көчүрмө түзүлүшүнүн тандоого мүмкүн берет
Бул бөлүм орнотуу пакети эмес, NVDAнын портативдүү көчүрмөсүнүн орнотуулушунан гана жеткиликтүү.
“ Улантуу” баскычын басаарыңыз менен, дароо портативдик көчүрмөнүн түзүлүш процесси башталат.
Портативдик көчүрмөнү түзүүнү аяктаганда, ийгиликтүү аякталды деген диалог терезече чыгат.
Диалог терезечении жабуу үчүн "Макул"баскычын басып коюңуз.

## NVDA менен иштөөнүн башталышы {#toc13}
### NVDAны орнотуу {#toc14}

Эгерде NVDAны орнотуу пакети аркылуу орнотсоңуз, анда NVDAны орнотуу абдан жөнөкөй, ал үчүн"control+alt+n",  тез баскычтары аркылуу орнотсо болот, же башкы Windows менюдан   NVDA меню баскычын басуу менен.
Жана ошондой  эле бул программаны орнотуу үчун  Диалог терезечеде “NVDA” деп жазып, диалог терезеде жана Enter баскычын басуу керек.
Сиз ошондой эле кээбир  [буйрук тизме ачкычтарын](#CommandLineOptions), алар NVDA (-r) өчүрүп кайра жандыруу, (-q) аяктоо, (--disable-addons) кошумчаларды өчүрүү ж.б берсеңиз болот.

NVDAнын демейки боюнча орнотулган көчүрмөсү өзүнүн тескөөлөрүн кийинки каталогдо: AppData\Roaming учурдагы колдонуучунун (мисалы "C:\Users\<пользователь>\AppData\Roaming").
Муну NVDA учурдагы колдонуучунун AppData\Local  каталогу аркылуу өзүнүн тескөөлөрүн жүктөөсү аркылуу өзгөртсө болот.
Толук маалымат алуу үчүн [Коомдук тескөөлөр](#SystemWideParameters) деген бөлүмгө өтүңүз.

NVDAнын портативдик көчүрмө версиясын орнотуу үчүн, программанын ачкан папкасын өтүп, "Enter" баскычын басып, же эки чычкан менен "nvda.exe" файлына басуу жетиштүү.

NVDA орнотулганда, сиз алгач тондордун чыгышын уга аласыз, алар NVDA жүктөлүүдө дегенди маалымадайт
Компьютерге карай, эгерде NVDAны бир аз жай иштеген USBден орнотуп аткан болсөңуз, программа үчүн кичине убакыт талап кылынат.
Эгерде орнотуу убактысы бира көбүрөөк убакытты алса, анда NVDA “ Сураныч, күтө туруңуз, NVDA жүктөлүүдө” деген маалымдоо айтат.

Эгерде сиз жогоруда айтылгандардын бирин да укпасаңыз,  же Windows катасы тууралуу уксаңыз,  демек программада ката бар, жана сиз бул каталар жөнүндө программаны иштеп чыгуучуларга мааламдашыңыз керек болот.Муну аткарыш үчүн, сураныч, NVDAнын веб  баракчасына өтүңүз.

#### Кош келдиңиз диалогу {#toc15}

 NVDA биринчи жолу орнотулуп жатканда, сизди диалог терезече кабыл алат, анда кээ бир баскыч-модификатор жөнүндө баштапкы маалымат билдирилет.
 ( Сураныч, бул темага багытталган кийинки бөлумдөрдү караңыз)
 Диалог терезече ошондой эле комбинацияланган тизмек жана үч желекти камтыйт.
 Комбинацияланган тизмек сизге тергичтин сиз каалаган түрдө орноштурууга мумкүнчүлүк берет.
 Биринчи желек "Capslock" баскычын NVDAнын модификатору катары  колдонула тургандыгын тандоого коет.
 Экинчиси , Windowsго киргенде, NVDAнын  автоматтык түрдө    жүктөлүүсү керекпи же жокпу деп аныктайт. Бул параметр NVDAнын орнотулган көчүрмөлөрүнө гана жеткиликтүү.
 Үчүнчүсү, NVDA орнотулганда, “Кош келдиңи” деген диалог терезечесин пайда болугун башкарат.

### NVDAнын тергич буйруктары жөнүндө {#toc16}
#### NVDA модификатор-баскычтары {#toc17}

 NVDA үчүн кобүнчө баскыч буйруктары атайын баскычтардын комбинациясынан турат ( бул модификатор- баскычтар деп аталат) бир же эки басыкчтардын кошулуусу.
 Бул эрежеден тышкары болуп, текстти  көрүү баскычы жана стол баскычы саналат, аларда баскычтардын өзү гана колдонулат, бирок башка да эрежеден тышкаркы баскычтар да бар

"Insert" баскычы да NVDAнын модификатор-баскычы катары тууралап койсок болот, жөнөкөй эле "Insert" же "Capslock" баскычын атасак болот.
 Модификатор баскычы катары жөнөкөй "Insert" баскычы колдонулат, ошондой эле "Insert” цифралык тергичте да колдонулат.

 Эгерде сиз NVDAнын баскычтар менен байланышкан кандайдыр бир иш аткаруусу үчүн модификатор баскычын колдонууну кааласаңыз, мисалы Модификатор баскыч катары эгерде сизде "Capslock" баскычы болсо, анда аны жандыруу үчүн, ал баскычты экм жолу басышыңыз керек болот.

#### Баскычтоптун жайылмасы {#toc18}

 NVDA Азыркы учурда эки нускадагы баскычтардын буйруктары менен чыгып жатат ( баскычтоп катары белгилүү) : жеке компьютер үчүн жана ноутбук үчүн жайылма баскычтоп.
 Өзү коюлган боюнча NVDA жеке комьютер үчүн жайылма баскычтопту колдонот, бирок сиз ноутбука ыңгайлуу болгонуна алмаштырсаңыз болот, ал үчүн "NVDA меню > Тескөөлөр > баскычтопту тандаңыз

 Жеке компьютер үчүн жайылма  баскычтопто цифралык баскычтоп активдүү колдонулат.  ("Numlock" режимин ажыратканда).
 Көбүнчө ноутбуктардын цифралык баскычтоптору бар болсо деле, кээбир ноутбуктар "FN" баскычын басуу менен жана оң тараптагы (7 8 9 u i o j k l и ж. б.) баскытарды басуу менен бул буйрукту аткарса болот.
 Эгерде сиздин ноутбугуңузда мындай мүмкүнчүлүк каралган эмес болсо, же "Numlock" буйругун өчүрүү мүмкүн болбосо, анда сиз ноутбук үчүн жайылма баскычтопту жандырууну жандырырышыңар керек.

#### NVDAнын кыймылдары {#toc19}

 Эгер сизде сенсордук экрандуу түзмөк бар болсо,жана анда Windows 8 жана жогорку нускасы орнотулган болсо, анда сиз NVDA программасын сенсордук түзмөк аркылуу да башкарсаңыз болот.
 NVDA иштеп жатканда, бардык сенсордук киргизүү программасына өткөрүлүп берилет.
 Ошентип, NVDAсыз кадимки ыкма менен аткарылган иш-аракеттер, иштебейт.

 +++ +++ Экранды изилдөө
 Сиз кыла ала турагандын эң жөнөкөйү,бул башкаруунун  элементи тууралуу маалыматты же текстти экрандн каалаган сенсордук чекитинде уга аласыз.
 Бул кыймылды аткаруу үчүн бир бармак менен сенсордук экрандын каалаган аймагына тийсеңиз болот.
 Ошондой эле сиз бармакты албай туруп жана аны үстүнөн тийүү менен бармак алдындагы башкаруунун элементи жана текстти окуй аласыз.

#### Кыймылдар {#toc20}

 Сенсордук экран аркылуу бул буйруктарды активация кылуу үчүн кыймыл аракеттер NVDAнын буйруктарын мүнөздөмөсүндө бар.
 Төмөндө бир ишаратты аткаруу үчүн айрым сунуштар бар. 

##### тийүү {#toc21}

  Экранга бир же бир нече жолу тез арада тийүү
  Манжа менен бир жолу тийүү бул жөн гана тийүү

  Ошол эле бир учурда, эки манжа менен тийүү бул эки манжалуу тийүү ж.б

  Эгерде бир эле тийүү тез учурда бир же бирнече жолу болсо, NVDA бул иш аракетти составдык бөлүгү катары карайт.
  Эки жолку тийүү кош басууга алып келет.
  Үч жолку – үчтүк ж.б
  Мында иш аракеттерде, составдык бөлүк катары канча манжа колдонулуп жаткандыгы же башкача айтканда эки манжа менен үч жолку тийүү, же бир манжа менен төрт жолку тийүүгө ж.б каралган.

##### Барактоо {#toc22}

  Манжа менен экрандан өтүңүз

  Тараптарга байланыштуу 4 кыймылдуу  барактоо мүмкүн: солго барактоо, оңго барактоо, өйдө жана ылдый барактоо.

  Ошондой эле тийүү же кыймылдарды түзүүдө бир же бирнече манжалар катышса болот.
  Ошондуктан, мындай эки манжа аркылуу өйдөгө барактоорлор, төрт манжа аркылуу солго барактоолордун аткарылышы толук мүмкүн.

#### Сенсордук режимди киргизүү {#toc23}

 NVDAнын буйруктары кыймылдарынан да кыйла көп болгондуктан, NVDAда сенсордук киргизүү үчүн бирнече режимдер бар. Көпчүлүк буйруктарды жеткиликтүү кылуу менен,режимдер ортосунда которулса болот.
 Эки режим бар: тексттик режим жана обьекттерди кароо режими.
 NVDAнын бул колдонуудагы айтылган кээбир буйруктары, кыймылдан соң кашанын ичинде сенсордук режимди көрсөтүү менен кошо каралган.
 Мисалы, “Өйдө барактоо ( тексттик режим)”кыймылы, “Өйдө барактоо” буйругу аркылуу аткарылат бирок тексттик режимде гана.
 Буйрук менен режим көргөзүлбөсө, анда бул кыймыл сенсордук кирүүдөгү баардык режимдерде иштейт.

 <!-- KC:beginInclude -->
 Сенсордук кирүүдө режимдер арасы которулуу үчүн үч манжа менен тийиңиз.
 <!-- KC:endInclude -->

 +++ Сенсордук топбаскыч +++[Сенсордук топбаскыч]
 Сенсордук колбаскыч сенсордук текстти жана буйруктарды кирүү үчүн колдонулат.
 Тууралоо талаасында болгондо, сенсордук топбаскычты ачсаңыз болот, ал үчүн ылдый жактагымсенсордук топтун белгисин эки жолу басуу керек.
 Microsoft Surface Pro планшеттери үчүн, сенсордук топбаскыч дайыма жеткиликтүү.
 Сенсордук топбаскычтан баш тартуу үчүн, снесордук баскыч белгисин эки жолу басыңызже  тууралоо талаасын ачыңыз.

 Сенсордук топбаскыч активдүү болуп турганда, андагы баскычтарды табуу үчүн, сенсордук баскыч турган жерге манжаңызды коюңуз ( көбүнчө экрандын ылдый жагында), андан соң клавиатура аркылуу бир манжа менен жылыңыз.
 Басайын деген ачкычты тапканда, манжаны көтөрүп же баскычты эки жолу басыңыз , диалог терезечеде тандалган тескөөлөргө караганда  «Диалог терезечеси «Байланышуу тескөөлөрү»#TouchInteraction].

### Маалым кат режими {#toc24}

 NVDAнын көбүнчө буйруктары жөнүндө  калган бул колдонмо китепчеде айтылат,  бирок бул программанын ар түдрүү буйруктары жөнүндө билүү үчүн оңой жол бар, ал үчүн маалым кат режимин жандыруу жеткиликтүү.

 Маалым кат режимин жандыруу үчүн "NVDA+1" буйругун басыңыз.
 Бул режимден чыгуу үчүн, кайрадан NVDA+1" баскычын басыңыз.
 Кирүү боюнча, кандайдыр бир иш-аракеттерди аткарууда маалымкат режиминде ( баскычты басуу же кыймылды аткаруу) бул кыймыл жана ал жөнүндө( эгерде ал жөнүндө бар болсо) маалымдалат.

 Ошол эле учурда маалымкат режиминде бул буйруктар чынында аткарылбайт.

### NVDA Менюсу {#toc25}

 NVDA Менюсу программаны тескөөлөгөнгө, керектүү маалыматты алууга, сактоого/тескөөлөрдү калыбына калтирүүгө, сүйлөө сөздүктөрүн өзгөртүүгө, кошумча аспаптар менен колдонууга жана маалыматты жүктөөгө мүмкүн берет.

 NVDA менюсун активдештирүү үчүн Windowsтун каалаган жеринен жана NVDAнын иштеп жаткан программасында, "NVDA+n" же сенсордук экранда эки манжа аркылуу басуу менен кош кыймылды аткарыңыз.
 NVDAны сиз ошондой эле Windows системдик трей аркылуу активдештирсеңиз болот.
 Ал үчүн системдик трейде жайгашкан NVDAнын белгисинде чычкандын оң баскычы аркылуу басыңыз  же болбосо, "Windows+b", баскычын басуу менен системдик трейди активдештируү менен, NVDAнын вертикалдык белисин табыңыз жана аны "Applications (контексттик меню)" баскычы менен активдештириңиз, ал болсо "Control" баскычынын оң жагында жайгашкан.
Меню ачылганда, анда жылуу үчүн, жебеси бар баскычты колдонсоңуз болот жана тандалган менюну активация кылуу үчүн "Enter" баскычын басыңыз.

### NVDAнын негизги буйруктары {#toc26}

 <!-- KC:beginInclude -->

| Аталышы |Столдук жайылма |ноутбук үчүн жайылма |Кыймыл| Мүнөздөмө|
|---|---|---|---|

 |Сүйлөөнү токтотуу | көзөмөл | көзөмөл | эки манжа менен тийүү| Тез арада сүйлөөнү токтотуу |

|Сүйлөөнү токтотуу| shift |shift |жок| Тез арада сүйлөөнү токтотот |Эки жолу басууда, сүйлөөнү токтогон жеринен кайра жандырат ( эгерде бул функцияны учурдагы синтезатор колдосо)|
|Меню NVDA |NVDA+n |NVDA+n |Манжа менен эки жолу басууда| NVDA менюсун активдештирет|
|Сүйлөө режимин которуу |NVDA+s |NVDA+s |жок |"Сүйлөө", "Сигнал" жана "Өчүрүлгөн" режимдер арасы которот.|
|Маалымкат баскыч режимин жандыруу |NVDA+1 |NVDA+1 |жок |Бул режимдеги каалаган баскычты басканда баскычты оку жана анын мүнөздөмөсун окуйт||
|NVDAдан чыгуу |NVDA+q |NVDA+q |жок |NVDA ишин аяктоодо|
|Кийнки баскычтардын басуусун өткөрүү |NVDA+f2 |NVDA+f2 |жок| NVDA баскычтоп буйрутмасы катары иштелсе да, NVDA кийинки басууну активдүү колдонмого багыттайт|
|Уктоо режимин жандыруу/ өчүрүү |NVDA+shift+s |NVDA+shift+z |жок |Уйку режимин жандырганда,учурдагы колдонмого  NVDAнын буйруктары, Брайльга чыгуу/сүйлөөсү иштебейт.Бул экранды окууга мүмунчүлүгү бар болгон колдонмолорго абдан керектүү. Эки жолу басууда уктоо режими өчүрүлөт.||

 <!-- KC:endInclude -->

### Системдик маалыматты окуу {#toc27}

 <!-- KC:beginInclude -->

| Аты |ачкыч |Мүнөздөмөсү|
|---|---|---|
|Убакытты/датаны окуу |NVDA+f12 |бир жолу басууда убакытты айтат, тез эки жолуу басууда датаны айтат|

 |Түзмөктүн кубаттуулугун окуу| NVDA+shift+b | Түзмөктүн кубаттуулугун окуйт м.а пайыз өлчомүндө канча кубаттуулук калганын же кубатуулук алынып жатабы|

|Алмашуу буферинде текстти окуу |NVDA+c |Алмашуу буферинде текстти окуйт, эгерде ал кандайдыр бир текстти камтыса||

 <!-- KC:endInclude -->

## NVDAда навигациясы {#toc28}

 NVDA системада жүрүүнүн түрдүү ыкмаларын тааныгууга мүмкүн берет, алардын ичинде жөнөкөй навигация режими жана кароо режими бар.

### Объекттер {#Objects}

 Ар бир колдонмо жана операциондук системанын өзү  көп объектилерден турат.
 Обьект өз алдынча бирдиктүү элемент катары белгилүү. Мисалы тексттин фрагменти, баскыч,желекче,тизме же  оңдоо талаасы.

### Системдик фокус аркылуу фокус {#SystemFocus}

 Системдик фокус же мындайча айтканда, фокус бул – обьект,мисалы баскычтарды басууда топбаскычка  кеткен сигнал.
 Мисалы, тууралоо талаасында текстти терип жатсаңыз, фокус ошол талаада болот.

 Windowsту NVDAны навигациялоонун бирдиктүү жолу бул жөн гана системдик фокусту Windowsтун стандарттык клавиатурасы менен жылдыруу, мисалы "tab" жана "shift+tab". Алар элементти башкарууда алдыга жана артка жылууга жардам берет. Ошондой эле "alt" баскычы болсо меню тилкесин жандантууга, андан кийин"alt+tab"  баскычтары болсо иштеп жаткан колдонмолор арасында которууга колдонулат.
 Бул кыймылдарды аткарууда NVDA обьекттин фокусу тууралуу маалымат айтып турат, мисалы обьекттин аталышы, түрү,  мааниси, сүрөттөлүшү,тез баскычтары жана объектинин жайгашуусун.

 Системдик фокус аркылуу навигацияга колдонулган кээбир баскычтар төмөнкүлөр:
 <!-- KC:beginInclude -->

| Аталышы |Үстөлдүк жайылуу |Ноутбук үчүн жайылуу |Сүрөттөлүшү|
|---|---|---|---|
|Учурдагы фокусту окуу |NVDA+tab |NVDA+tab |Учурдагы обьектти же башкаруу элементин окуйт. Тез жана эки жолуу басууда бул маалыматты символдоп окуйт||
|Атылышын окуу |NVDA+t |NVDA+t |Активдуү терезеченин аталышын окуйт. эки жолуу басууда бул маалыматты символдоп окуйт. Үч жолу басууда бул маалыматты алмашуу буферине көчүрөт||
|Активдүү терезчени окуу| NVDA+b |NVDA+b |Актидүү терезечедеги башкаруу элементтердин баардыгын окуйт. (диалог терезечелер үчүн пайдалуу)|
|Тилкенин абалын окуйт |NVDA +end |NVDA+shift+end |Белгиленген тилкенин абалын окуйт. Ошондой эле бул жерге навигаторду  жылдырат. Сиз тез жана эки жолу басканда, маалыматты символдоп боюнча окуп берилет. Үч жолу басканда ,алмашуу буферине  маалыматтарды көчүрүп берет|

 <!-- KC:endInclude -->
 ++ Багыттоо системасы навигациялоо ++ [SystemCaret]
 ++ Багыттоо системасы навигациялоо ++ [SystemCaret]
 Навигация же текстти оңдоо обектиси [объект](#Objects), [фокус](#SystemFocus) камтыса, андасиз тексттен системдик багыттоону колдонуп жылсаңыз болот ошондой эле ал тексттик курсор катары да белгилүү.

 Обьект фокуста турган болсо жана ал багыттоо системасына ээ болсо, тексттен жылуу үчүн "page up", "page down", "home", "end", жана башка баскычтарды колдонсоңуз болот.
 Сиз ошондой эле тестти өзгөртсөңүз болот, эгерде башкаруу элементи тууралоону колдосо.
 NVDA сиздин жылганыңызды символдоп, сөз менен тилкелер боюнча айтып турат, ошондой эле текстти белгилөөдө жана андан чыгарууну да айтып турат.

 Системдик багыттоо менен иштөө үчүн NVDAнын   кийинки баскычтары колдонулат:
 <!-- KC:beginInclude -->

| Аталышы| Үстөлдүк жайылуу |Ноутбук үчүн жайылуу| Сүрөттөө||
|---|---|
|Баардыгын окуу |NVDA+жебе_төмөн |NVDA+a |Учурдагы курсор кызматынан окуп баштайт, аны жылып окуп жатканда|
|Учурдагы сапты окуйт| NVDA+жебе_өйдө| NVDA+l |Системдик багыттоо турган сапты окуйт. Эки жолу басканда сиволдоп окуйт.Үч жолу басканда ар бир сиволго фонетикалык түшүндүрмө берет.|
|Белгиленген текстти окуйт |NVDA+Shift+жебе_өйдө |NVDA+shift+s |Белгиленген текстти окуйт|
|Кийинки сүйлөм| alt+жебе_төмөн| alt+жебе_төмөн| Багыттону кийинки сүйлөмгө гана жылдырат жана аны жарыялайт (Бир гана Microsoft Word жана OutloМакул- колдоого алынган)|
|Мурунку сүйлөм| alt+жебе_өйдө| alt+жебе_өйдө| Багыттону мурунку сүйлөмгө  жылдырат жана аны жарыялайт (Бир гана Microsoft Word жана Outlook- колдоого алынган)|

 Таблицанын ичинде ошондо эле кийнки топбаскычтын буйруктары жеткиликтүү:

| Аталышы |Клавиша |Сүрөттөлүшү||
|---|---|
|мурунку мамычага өтүү| control+alt+жебе_солго |Жылдырат багыттоону  мурунку мамычага (бул тилкедеги)|
|кийнки мамычага өтүү |control+alt+жебе_оңго |Жылдырат багыттоону  кийнки мамычага (бул тилкедеги)|
|мурунку тизмеге өтүү |control+alt+жебе_өйдө| Жылдырат багыттоону мурунку тизмеге (бул тизмдеги)|
|кийинки тизмеге Өтүү |control+alt+жебе_төмөн| Жылдырат багыттоону кийинки тизмеге (бул тизмедеги)|

 <!-- KC:endInclude -->

### Обьекттик навигация {#ObjectNavigation}

 Убакыттын көбүнчөсүн колдонмолордун буйруктарына колдоносуз[системдик фокустун](#SystemFocus) жана [каретка](#SystemCaret).
 Андыктан  сиз учурдагы колдонмону фокусту же каретканы жылдырбай туруа үйрөнүүнү каалайт болушуңуз керек.
 Сиз балким [объекттер](#Objects) менен иштөөнү каалайт болушуңуз керек,  алар жөнөкөй топбаскыч менен жеткиликтүү болбошу мүмкүн.
 Мындай учурларда сиз обьекттик навигацияны колдонсоңуз болот.

Обьекттик навигация  өзүнчө [объекттер](#Objects) арасында жылууга жана алар жөнүндө маалымат алууга мумкүнчүлүк берет.
 Кайсыл бир обьектке өтүп жатканда, NVDA аны системдик фокус катары эле окуйт.
 Баардык документ экранда кандай көрүнүп жаткандыгын көрүү үчүн, сиз обьекттин навигациянын ордуна колдонсоңуз болот. [экранды көрүү](#ScreenReview).

 Системада алдыга же артка жылуу дайыма эле жеткиликтүү эмес, себеби обьеттер иерархиялык түзүлүштө.
 Мунун мааниси бул кээбир обьекттер өзүнө башка обекттерди камтыйт жана  алар сизге жеткиликтүү болуу үчүн обьект камтыган обьектердин  ичине кириш керек болот.
  Мисалы,тизме элементтин тилкелеринен турат жана аларга өтүш үчүн  ошол үчүн тилкеге өтүш керек болот.
  Тизмедеги кайсылбир элементке келсеңиз, анда алдыга же артка жылуу же учурдагы обьектке келсеңиз, башка тизмедеги обьектке кирүүгө мүмкүн болот.
  Тизмедеги элементтерди камтыган обьектке жылууда сиз кайрадан тизмеге келесиз.
  Башка объекттерден уруксат алуу керек болсо, Сиз тизменин жанынан гана өтсөңүз болот.
  Ошо сыяктуу эле, панелинин башкаруу каражаттары бар, ошондуктан панелдин ичине өтүп башкаруу элементтерине мүмкүнчүлүк алсаңыз болот.

 Учурда каралып жаткан обьект навигатор обьектиси деп аталат.
 Обьектке өтөрүңуз менен, аны көрө аласыз [текстти көрүу буйруктары аркылуу#ReviewingText], [объекти көрүү режиминде](#ObjectReview) болуу менен.
 Демейки. Систеидик фокустун артынан навигатор ээрчип жылат, бирок мындай аракеттерди өчүрүп же жандырса болот.

Көңүл буруңуз,демейки боюнча,Брайль [системдик фокустун](#SystemFocus) жана [каретанын#SystemCaret] артынан ээрчийт,бирок навигатордун обьектисин эмес жана көрүү курсорун эмес.
 Эгерде навигатордуе артынан ээрчүнү кааласаңыз, каралвп жаткан куросор менен сизге [Брайльга байлампта болууну тескөөлөшүңүз керек болот#BrailleTether] Көңүл буруңуз,демейки боюнча,Брайльь [системдик фокустун](#SystemFocus) жана [каретанын#SystemCaret] артынан ээрчийт,бирок навигатордун обьектисин эмес жана көрүү курсорун эмес.

 Кийинки топбаскыч буйруктары обьекттик навигация аркылуу жеткиликтүү:

 <!-- KC:beginInclude -->

| Аталышы |Үстөлдүк жайылма| Ноутбук үчүн жайылма| Кыймыл|Сүрөттөлүшү||
|---|---|
|Учурдагы обьектти окуу| NVDA+numpad5 |NVDA+shift+o |жок |Навигатордун учурдагы обьектисин окуйт. Эки жолу басуу бул маалыматты символдоп окуйт, ал эми үч жолу басуу аталышын жана обьекттин маанисин алмашуу буферине көчүрөт.|
|Өтүү на баштапкы объект |NVDA+numpad8 |NVDA+shift+жебе_өйдө| Өйдө  барактоо(обьектти көрүү) |Учурдагыны камтыган обьектке навигаторду орнотот||
|Өтүү объектке мурунку |NVDA+numpad4 |NVDA+shift+жебе_солго |Барактоо солго (обьектти көрүү)|

 |Ошол эле логикалык денгээлдин мурунку обьектисине навигаторду орнотот |

|Өтүү кийнки объектке |NVDA+numpad6 |NVDA+shift+жебе_оңго |Барактоо оңго (обьектти көрүү) |Ошол эле логикалык денгээлдин мурунку обьектисине навигаторду орнотот|
|Өтүү биринчи  туунду объектке |NVDA+numpad2 |NVDA+shift+жебе_төмөн |Барактоо төмөн (обьектти көрүү) |Навигаторду орнотот  биринчи объектке||
|Өтүү фокустагы обьектке| NVDA+numpadMinus |NVDA+backspace |жок |системдик  фокустагы обьектке навигаторду орнотот  жана бул обьекттин системдик кареткасынын көрүү куросруна  эгер бул мүмүн болсо.|
|Учурдагы навигатордун обьектисин активдешитирүү| NVDA+numpadEnter |NVDA+enter |Эки жолу басуу| Учурдагы навигатордун обьектисин активдешитирет (Чычкан менен баскандай же  "Боштук" ту басуудай ,системдик фокуста турган кезде)|
|Курсордун учурдагы позициясына келтирүү же системдик фокусту жылдыруу |NVDA+shift+numpadMinus |NVDA+shift+backspace |жок |Бир гана жолу басуу Жылдырат системдик фокусту навигатордун учурдагы обьектисине, Эки жолу басуу Жылдырат системдик багыттоону көрүү куросорунун позициясына|| Көрүлүп жаткан курсордун жайгашуусун окуу| NVDA+numpadDelete |NVDA+delete |жок |Тесттин абалы тууралуу маалыматты жана каралып жаткан курсорду  окуйт . Мисалы, бул жака курсордун абалы жөнүндө маалымат кирет, барактын четине, же экрандагы курсордун ээлеген алыстыгы.Эки жолу басуу дагы да толугураак маалыматты айтат.|

  <!-- KC:endInclude -->

  Эскертүү: Сиз туура иштөөсү үчүн "numlock" режимин өчүрүшүңүз керек.

### Текстти көрүү {#ReviewingText}

  NVDA мазмунун окуп берет [экрандын](#ScreenReview), учурдагы [документ](#DocumentReview) же учурдагы [объектти](#ObjectReview) символдоп, сөз менен жана сап менен
   Бул көбүнчө  (Windowsтун консулун кошо эсептегенде), [системдик каретка](#SystemCaret)жок жерде жеткиликтүү.
    Мисалы, Чоң маалыматтык катты диалог терезечеде окууга,  көбүнчө бул колду колдонушуңуз мүмкүн.

 Көрүү курсорун жылдырганда системдик карта оордунда калат, ошондуктан сиз тексттин тууралоосун жоготпостон аны көрө аласыз.
 Системдик каретканы демейки түрдө жылдырганла көруү курсору да аны ээрчийт.
 Бул кыймылдарды өчүрүп же жандырса болот.

 Көңүл буруңуз, демейки боюнча  [системдик фокусту#SystemFocus] жана  за [каретканы](#SystemCaret) ээрчийт  , бирок обьекттин артынан эмес жана и көрүү курсорунан эмес.
 Брайль навигатордун артынан жана көрүү курорунун ээрчишини кааласаңыз, сизге [брайлды #BrailleTether ге байлашыңыз керек болот]

 Кийинки топбаскыч буйруктары текстти көрүүгө жеткиликтүү:
 <!-- KC:beginInclude -->

|текстти көрүү режиминде биринчи катарга Өтүү |shift+numpad7 |NVDA+control+home |жок |көрүү курсорун  тексттин биринчи сабына жылдырат жана аны окуйт||
|текстти көрүү режиминде мурунку сапка өтүү |numpad7 |NVDA+жебе_өйдө| Өйдө  барактоо(текстти көрүү) |тексттин  мурунку сабын көрүү курсоруна  жылдырат  жана аны окуйт||
|текстти көрүү режиминде учурдагы сапты окуу |numpad8 |NVDA+shift+. |жок |көрүү курсорунун алдында тексттин сабын окуйт. Эки жолу басууда, аны символдоп айтат. Үч жолу басканда символдордун фонетикалык түзүлүшүн окуйт|
|текстти көрүү режиминде кийинки сапка өтүү |numpad9 |NVDA+жебе_төмөн |Барактоо төмөн (текстти көрүү) |кийинки сапты тексттин  көрүү курсоруна жылдырат жана аны окуйт||
|көрүү режиминде акыркы сапка өтүү |shift+numpad9 |NVDA+control+end |жок |тексттин акыркы сапты көрүү курсоруна жылдырат жана аны окуйт||
|көрүү режиминде тексттин мурунку сөзүнө өтүү |numpad4 |NVDA+control+жебе_солго |эки манжа менен солго барактоо (текстти көрүү) |тексттеги мурунку сөзгө жылдырат жана аны окуйт||
|көрүү режиминде учурдагы тексттеги сөздү окуу |numpad5 |NVDA+control+. |жок |тексттеги кароо курсору алдындагы сөздү окуйт.. Эки жолу басууда аны символдоп окуйт. Үч жолу басууда символдордун фонетикалык түзүлүшүн окуйт||
|текстти көрүү режиминде кийинки сөзгө өтүү |numpad6 |NVDA+control+жебе_оңго |эки манжа менен оңго барактоо (текстти көрүү) |тексттеги кийинки сөздү жылдырат жана аны окуйт||
|тексттин  катардын башына көрүү режиминде өтүү |shift+numpad1 |NVDA+home |жок |Жылдырат көрүү курсоруна учурдагы тексттеги   тизмени  жана курсор алдындагы символду окуйт||
|текстти көрүү режиминде мурунку символго өтүү |numpad1 |NVDA+жебе_солго |Барактоо солго (текстти көрүү) |Жылдырат көрүү курсоруна мурунку символ учурдагы  тексттин тизмесин жана аны окуйт||
|текстти көрүү режиминде учурдагы символду окуу |numpad2 |NVDA+. |жок |Көрүү курсору алдында символду окуйт учурдагы тексттин тизмесинде . Эки жолу басуу символдун фонетикалык түзүлүшүн окуйт.Үч жолу басууда фонетикалык маанисин окуйт||
|текстти көрүү режиминде кийинки символго өтүү |numpad3 |NVDA+жебе_оңго |Барактоо оңго (текстти көрүү) |Жылдырат көрүү курсоруна кийнки символду тексттин учурдагы тизмегин жана аны окуйт||
|текстти көрүү режиминде сызыктын аягына өтүү |shift+numpad3 |NVDA+end |жок |курсор алдында символду окуйт||
|текстти көрүү режиминде баардыгын окуу| numpadPlus |NVDA+shift|

  Белгилөө, көрүү курсорнунун позициясынан көчүрүү | NVDA+f9 | NVDA+f9 | жок | Учурдагы көрүү курсорунун позициясын тексттин көчүрүү фрагменти жана белгилөөнүн башталышы катары белгилейт.|

|Белгилөө, анан көрүү курсорунун  позициясына чейин көчүрүү |NVDA+f10 |NVDA+f10 |жок |Бир жолу басылган болсо, фрагменттин башталышынан, учурдагы позицияга чейин текстти белилейт . Эки жолу басылган болсо, алмашуу буферине көчүрөт||
|тексттин форматтоосун окуу |NVDA+f |NVDA+f |жок |учурдагы позицидагы тексттин  Форматтоосун окуйт . Эки жолу басууда бул маалыматты кароо режиминде тартуулайт.|

  <!-- KC:endInclude -->

 Эскертүү: Туура иштөөсү үчүн "numlock"режимин өчүрүү керек.

 Топбаскычтык буйруктарын жакшы эстеп калуу үчүн,кийинки эстөө керек: үчөө үч тармак боюнча, сызык-жогрудан ылдый,сөз  жана символ, солдон оңго мурунку, учурдагы жана  кийнки элемент.
 Таблица кийинкидей таанылат:

|Мурунку сап| Учурдагы сап| Киийнки сап|
|Мурунку сөз |учурдагы сөз |кийинки сөз|
|мурунку символ |Учурдагы символ |кийнки символ|

### Көрүү режими {#ReviewModes}

 [NVDAнын тектти көрүү буйруктары менен](#ReviewingText) кайсыл режим тандалганына карабастан учурдагы обьекттин мазмунун көрүүгө мүмкүн
 Көрүү режими- NVDAнын мурунку нускаларынын эски көрүү концепциясын жаңыртуусу.

 Кийинки буйруктар менен көрүү режимдер арасы которулса болот.
 <!-- KC:beginInclude -->

| Аталышы |Үстөлдүк жайылма| Ноутбук үчүн жайылма| Кыймыл|Сүрөттөлүшү||
|---|---|
|кийнки көрүү режимине которулуу |NVDA+numpad7 |NVDA+pageUp |эки манжа менен өйдө барактоо |Которулат кийнки жеткиликтүү көрүү режимине||
|мурунку көрүү режимине  которулуу |NVDA+numpad1 |NVDA+pageDown |эки манжа менен төмөндү көздөй барактоо |мурунку жеткиликтүү көрүү режимине которулат|

 <!-- KC:endInclude -->

#### Обьектти көрүү {#toc34}

 "Обьектти көрүү" режиминде сизге көрүүгө учурдагы  гана [навигатор обьектиси#ObjectNavigation] жеткиликтүү.
 Обьекттер үчүн,  тексттик тууралоо талаасы сыяктуу же башка тексттик башкаруу элементтери, бул көбүнчө  тексттик талааны камтыйт.
 Башка обьекттер үчүн бул аталыш же маани болушу мүмкүн.

#### Документти көрүү {#DocumentReview}

 [навигатор обьектиси#ObjectNavigation] көрүү режиминде турса документ (Мисалы, web-баракча) же башка документте  (Мисалы, Lotus Symphony программасынын документи), "Документти көрүү"  режимине которулуу мумкүнчүлүгү бар.
 "Документти көрүү" Режиминде сиз бардык документтин тексттин көрө аласыз.

 "Обьектти көрүү" режиминен которулууда "Документти көрүү" режиминде көрүү курсору учурдагы документтеги обьекттин навигатору ордунда жайгашкан.
 Документти навигациялоо учурунда көрүү буйруктары менен навигатор обьектиси автоматтык түрдө жаңыланат,  учурдагы обьект үчүн көрүү курсорунун позициясы тууралуу маалыматты алат.

 Көңүл буруңуз,  NVDA "Обьектти көрүү" дөн көрүү режими менен документти навигациялоодо автоматтык түрдө "Документти көрүү" гө которулат.   

#### Экранды көрүү {#ScreenReview}

 "Экранды көрүү" режиминде сиз экран аркылуу текстти учурдагы колдонмодон тышкары визуалдык түрдө кандай көрүнөт экенин көрө аласыз.
 Бул чычкандын функционалына окшоштурулат жана көбүнчө программаларда жжеткиликтүү.

 "Экранды көрүү" режимине Которулууда көрүү курсору [обьекттин навигатору#ObjectNavigation]  учурдагы экран позициясында жайгашат.
 Навигация учурунда экранда  көрүү буйруктары менен навигатор обьектиси автоматтык түрдө жаңыланат, маалыматты алып көрүү курсорунун позициясы тууралуу.

 Кээбир жаңы колдонмолордо NVDA,экранда чыгып жаткан баардык тексттин бөлүктөрүн көрбөйт экенине көңүл буруңуз.

### чычкандын жардамы менен навигация {#toc37}

 сиз чычканды жылдырганда , NVDA демейки боюнча чычкандын алдында жайгашкан  текстти окуйт.
  Бул колдогон жерде,  башкаруу элементи болсо да,NVDA жакын жайгашкан абзацты окуйт.

 [объекта](#Objects)түрүн айтып туруу үчүн NVDA тескөөлөнсө болот,бул чычкандын көрсөтүүсү аркылуу (Мисалы тизме, баскыч ж.б)
 Бул толук көрүүсү чектелген адамдарга пайдалуу болушу мүмкүн,  толук маалымат алуу үчүн текст жеткиликтүү болбой жатканда.  

