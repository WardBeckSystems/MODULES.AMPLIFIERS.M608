# M608 Audio Distribution Amplifier · Amplifiers

Ward-Beck Systems M608, 1975|8. Wiki page: [M608 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M608.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 88 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 18 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 12 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 200 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 9 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 13 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 57 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [19xx - M608 - DOC - US Sales Brochure pg 25.jpg](MANUALS/19xx%20-%20M608%20-%20DOC%20-%20US%20Sales%20Brochure%20pg%2025.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Dimensions** | 3.4 &quot; wide X 3.4&quot; high X 13.7&quot; deep (83 mm X 83 mm X 336 mm). |
| **Weight** | 6.5 pounds (3 kg) net. |

## Circuit description

From [1975 - M608 - Audio DA (2).pdf](MANUALS/1975%20-%20M608%20-%20Audio%20DA%20(2).pdf) pages 5-10 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

M6CB AUDIO DIS TR IBl!TINI AMPLlF'&quot;IER

,.~., _ ~ ~.;...::: ~:: t;;r:b...:T,;r, A&quot;' ~;::': e.-1 ~ &quot; ~::'_I'&gt; c ·,. &quot;,- ~::: i~ ~ ~: ~' I~:.&quot;&quot;, the 115V a c 60 Hz power line. The modular plug Tn unit i&quot; o e &quot; igned to bridge e e r-c ssa single audios ou r&lt;::e and provides 8 ind i v i dual l y 1so late d, trans former coupled, 600 ohm outputs.

Thea ud io input appears a t pins P 2-8 and P2~ 16 on the rear module connector. It i s connected tot h e primary o f T2 01, which iss trapped top resent ani n put impedance 01 30,000 ohms or great e r tot hes our c e. The Input Shield connects toP 2 _7. These c ond a r y o f T201 connects tot h e 8_1 16 amplifier card atp ins Ian d 2.

An overload protection circuit cons ls ting of R2, R3 and CRI through CR4 prevents excessive input levels o r voltage transients from pot e n tia l ly damaging thea mp l l fie r.

Thea u d i o &quot; i g n,, 1 is coupled through Cl to C4 to the pre-amp lif ier section, consisting of Ul and V2. R12 adjusts gain differences between VIand U2 optimiZing input longitudinal balance a t low frequencies. R9 provides longitudinal balance &quot; d just men t for high f r e q u e n c ie s.

The g&quot; in of the M608 is d e te....&quot; in ed by the setting of s e ns i t i v i t y control R201, which cont ro l&quot; the f.... d b &quot; ck around U2. The overall amp l i fie r g a ln i sad j u stable from +18 to -6 dB.

The pr e amplifier outputs ig n ali s coupled through C9 tot h e lower half oft h e output pewee amp l if i e r, comprisIng of U3, 01, 02, 03, Q4 and 05. The second o r upper half of the output power amp l l fle r consists o f V4, C6, 0 7, C8, 0 9 and Cl 0.

Thea c t i v e l y balanced e oe tc output appears lOt pins 18 &quot; n d 19 of the 8_116 amplifier card.

R23 and R41 &quot; d just the &quot;mpli/i er output o fh et volt &quot;ge s. 0 volts

+/-0.5 mV.

M6Ol! AUDIO OI S';';I Bu, ICN AM? L1F IE;;:

.~....;t • ••. ~....... r.~tl...~ I.;: •.~ &quot;.. I,;.&quot;,t a,;&gt;; ~ ~:0.&quot;.;1:i wi: 1&quot;,.. 8 -1 16 a mpl lfl.. r card is conn ec:led 10 Ine p r ima.. y 0 1 Ih e two ou tp u l t &quot;.nstorm era ssemb lies T20J and T 204.

Each.. ss~ l y consisls ot four sep.. rate trans forme.. s. Pro v i dins.. t o tai of 8 trar: s ' or:ne r CO&lt;.l;&gt;le &lt;j OUIP u IS, eaC;, camp l e l,, ' y l sol a l:!d trom e a c n c.n.....

The seeee e e.. y OUlpUI Sot T20J.nd T204...... conn.,;le d 10..es isto.. is ola ll o n n e l &quot;&quot;&lt;lt&quot;k s 00'l Ih e 8_ 118 p.. l n led c i &quot; cu it card assemblies. The resist i ve values a &quot; e such In.. 1 a 600 sour&lt;:e impedance Is pre~l.. d a leach of I he a OUlpul s. Four OUlpulS appear on r.. ar module cco oe c re rPI lind another four 01'1 Ine e e rmodu le CO&lt;'1ne&lt;:tor P2.

Tnr ee LEO Indl cli lor s are provided alt t-e front 01 the unit.

0 51 (yellow) mOl'lilors the +/ _ 32 volts supply vol la ge and serves e s a &quot;p ow er 0&lt;'1&quot; In di cal g.r.

DSJ (green) is known a s the &quot;Normal &quot; indicalOr. I I will Ill u min ate whenave r th.. nomin.1 program oulpu t level reaches ·e Vu under progr.m conclil ions.

Under s lead y _s tale lon a co nd ll lOtls OSJ will not Il lu mln ala unli l the OUlpu t re.ches a level o f 4 to 5 d B above...8 dBm.

053 Is ope... led b y one half of comparator UIOI via the coll.,;lor of 0 103. The Inputs oft he comp.ralor consists of a fi&quot;ed reference vol l age applied 10 pin 5 and.. de voltage derived fr'O'll tM. v _ged.. ud los lgn.. 1 via CRIM, CR105, Rl1 S, R 114 and C to 2, I• •ppl led top In 6.

052 f e-ed) Is a n &quot;Ov.....l_ d &quot; Indl c.. tor, which will op.... ate when Ihe. v..... ~ progr.m o u lp ul I&quot;&quot;al reaches..18 Vu.

Under steady -s l ale tone cond i llons 052 will not illuminate u nl ll Ihe

ou lpu t reaches.. level of &quot;22 10 &quot; 23 dBm.

**WA~ D -I!IECI&lt; BYII TEMB LTD,**

~&quot;6Je &quot;'UD 1C DISTR I&quot;uno&quot;l &quot;M P,--I F1 Ei'l

DS2 I,. dr l &quot;... b y Ih e &quot; e&lt;:on d half &quot;f c omp &quot;,.&quot;to&lt;&quot; UI OI. &quot;g&quot; in, • fixed ere e oc e &quot; Oil age i sap plied 10 pin 3, while pin 2 Is supplied w ll h ape aK-ce lec ted audios i g n a l &quot; oil age &lt;.le,.i &quot;ed fl&quot;'Olll CR102, e;::;'I::':&gt;,;; i i.i a no C; O;.

0 10 1 &quot;nd 0102 fo..m a p..eci s ion Cu....-enl source, '~ lng &quot; o ll &quot; g e di &quot; ide.. Rl07/Rl0e, Which in Iu,.n pro&quot; ldes Ihe Iwo compa,.alor- &quot;e ' e..en c e &quot;o l lag e s.

The U'lI·ee LED I...d;calor circuit,. a,.e packaged sepa..a lel)' on a p&quot;;n led c l rcu l ~ ca..d Iy pe 8_ 1 17.

1 15 &quot;olts, 60 Hz power i&quot; applied (0 Ihe unit &quot; Ia rear module conne&lt;:lor P I &quot; 1 p in&quot; 7 and 16. I I Is connected t o Ihe pc....e r Irans fonne.. T20 1 Ih l&quot;OUg h fu &quot;.. F 20 1.

Br idg&quot; re&lt;:l lfI.,r CRS....1(1'&gt; filler componenls RSS, R66 and C28 Ih rough C31 ulab li &quot;h nomin,,1 supply &quot;01Ill 9&quot;&quot; o f +1-32 and +1-18 &quot;o ilS as..equ;&quot;ed.

Tes l poin l TPI end Ju mp., r eonneclor J1 are p ro&quot; ide d 10 me asu.... the p o s i lJ &quot; e sup ply current during initial factory t esl. The d e curren I &quot; 1 Ih l &quot; poi n l Is &quot; om l na l l y 50 mAw i t h 115 volts ee In p u l &quot; n d u&quot; d e r quiescent condi lions.

**INSTALLATION**

MM8/ -M€ 08 A AU() IC D iST&quot; ~!!UTION AMPL IF !£P.

.~ 1.;, i&quot; s ~: &quot; '''-, I'o!;f: &lt;, ~'';;:I..,; S,,;.~&lt;!,,::; i.-,: ~: ~~ mounting f~ame, which maybe ins l&quot;,l led ina stan d&quot;' r d E IA 19 inch equip men t r &quot;'c k. The MF6 f~&quot;,me willa c co mmod a te&quot;, maximum o f 5 M60e series of amplifiers oran y comblnallon o f single or mulHp le width modules note xce &quot; ding Ie&quot;.. ing le width modules.

:f l ~,e mo &quot;&quot;H i n!.j ' n, meh a s 0 &quot;'''';&gt;rocu &quot; e o w il no UI &quot; e c&quot;,,, taci,,,,,. n...... must be inSl &lt;'ll led in thea p P rQ p r i ate module p osi lions. Each M60e type amplifier ~ e quires two lype MFR6 r e c e p t iel e s.

Note: Re&lt;:e ptacl&quot; PI, (w h ic h contains thea cline voltage input) i s r;:;v;;;: ted. This provides mec hnical polar iz a t ion oft h eco n n e cto r s ne&lt;:e ssary to prevent ina d v e r lent insertion of other comp&quot;,nion modules which do not operate from the &quot;'c line.

Where v ert lc &quot;, 1 ~ a c k space p e~mits &quot;,n d the ultimate In noise &quot;' nd cross talk performance Is desired, it Is ~ecommended lh&lt;'lt only modules of the s&quot;, met y pe be allocated toe &quot; chIn dlv ldu&quot;,1 mountl f&quot;lg frame. Alternative l y, i l Is possible to mix module.. o f different types bye xe rc is inge Xlr e me care to sep ar&quot;le cables carrying different levels and functions. Place all a cpo we red unltll to the r l g hl o f lh e frame, e s viewed from l h e front. rest au i s u l&quot; l l n g rubber sleeves Over &quot; II ec ect e eee terminal connections.

Fore x tern a l wiring conneC l lon sin cl u ding recommended shielding and grou&quot;d wiring le c h n lq u e s refer to Rear Conn~lor Layout d ~a wing B 606~04-00 1 &quot;nd System Wiring Schema l ic 6 60 8_ 0 2_ 003.

to ob t alf&quot;l OPll mum results, use insulated, shielded, twisted pairs for both If&quot;lp u t &quot; n d output wiring. Cables c p er&quot;,t ing with level differ e n c e sex cee ding 25 d B should b e laced separately and d ~e s se d apa ~t from each other. Keep power wiring away from low level clrcu l ls. Ground cables hie l d sat one e rrd only. Ground loops mUll l be avoided.

I t Is gene r &quot;,lly re&lt;:on-onended as good eng l n ee ~ l n g practice that a one rack unit space b e provided between full f~ames of distribution

amplifier s for optimum venli i&lt;'ltlon.

M60ll AuDIO OISTR I:! UTt ON Mi,PL IF 1£R

,J;;:iC ~. ': 'l' l v~ W&quot;G ?....;;; NU MS E'&quot;

F201 Fu •• 0.175.A S.8. Bu. s MOL 17!l/1000 R2'J I !='''IIt:''lli ome l ~ ~'(C t&quot;l'&quot;'Os: '!It ~1! S 10&quot;&quot;:::36;&gt;1&amp;;&gt;2 16Pl nCoro n ec.10I&quot; Amp her-.o l 2!&gt;-IS! -15 PJ 22 Pin Coronec.tOl&quot; Ed&quot;c;;);)7...022-501_102 TW' T,..n. fo.....el&quot; Hammond WBS 60-15 n 02 was 80-25

&quot;&quot;. WBS 70-9 was 70-9

C' Ca pa ~;tOl&quot; 22..uF /35 V TJ90 E 226M035AS

C' 4.7 p F Philips

3.9 pF 33 u F/l0 V K_, 222 2-638-09396

**TJ900 3J6 M01QAS**

C' 4.7 pF 2222-638 -094 78 C' 33 u F/I O V:::; s TJ9003J6MO lQAS coo 47pF P l&quot;lllip s 2222-638 _704 79 en 100 p F 2222-636 _7Ql 01 en e.a es 222 2-638-09826 C&lt;J 4.7pF 2222_638 -Q9478 WIS pF 222 2-636 _1015 9 m 47 p F 2222 -6 38-704 79 coo 15 u F/35 V K_, T390E I56 M035AS Cl7 22p F Philips 2222-638 -58 229 C&lt;8 0.0 22 uF esetce CQ92-MC_223M cre 33 u F/l0 V Kern.l TJ9003J6MOI OAS

l 00 p F Philips 2222-6 38_70 10 1

C2&lt; e.a es 2222-638 -09826

C22 4.7 pF 22 22_638_ 094 76 C2J 15 p F

222 2-638 -10159 cae &quot;I S,F 2222-6 38 _7068 9

cas uF / 35 V TJ 90E 156M035AS

&quot;'608 AUDIO D I Sr ~ l aUTl O,.........Pd F li.:t

O=:';':::l, PTI QN,.. ~ U ~....,:l T &quot;'u'&quot;'o;:;; C26 CllQlI.cit.... 22 pF Philips 22 22 -638-~8 2 29 C 27 0.022 uF ks e lc;o CQ!!2· MC-223M C: 8 470 uF ! 40V Philip,&quot; &quot;.!7ETG-lo7Q

C29 410 uF!40 V Ph ~F i P S 437e:r G410 C'&quot; 22 u F!2~ V 426e:TF22

CJ2 uF/ l0 V I(eme l TJ90 D336M010AS

**C,. &quot;' 00,F**

l OOpF Pn i tiplI 2222_638_70 101

CRS e.-ld g e Reetifle.

01 T.-lI.nll ill lo.- Natior&gt;lIl 2N3569

' Texas

**PN3S69**

Q' Texas TIP 29B Q' TlP30B

Q' 2N3569 Q' 2N40J7

**PN3569**

TlP29B Q&quot; Tl PJOB

R Re. l s~ 1/ 4W sS '&quot; Ph~F1 ps

**R'R' &quot;K**

T l&quot;'lmpo t 'OK P iner PT Ian 12.05) 20K

R&quot; Re.i. t.... 1/4W 51 &quot;K Philips

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

Not on Google Drive yet: `WBS - ART - M608 Distribution Amp - Inside(1).png`, `WBS-ART-M608-Distribution-Amp-Inside-1024x661.png`, `WBS-ART-M608-Distribution-Amp-Inside-150x150.jpg`, `WBS-ART-M608-Distribution-Amp-Inside-300x193.png`, `WBS-ART-M608-Distribution-Amp-Inside-624x403.png`, `WBS-ART-M608-Inside-1024x661.png`, `WBS-ART-M608-Inside-300x193.png`, `WBS-ART-M608-Inside-624x403.png`

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSXNqRVlXLS0wQnM/view?resourcekey=0-FccAB6V0aF8B8mow_i-MKg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSXNqRVlXLS0wQnM&resourcekey=0-FccAB6V0aF8B8mow_i-MKg" width="240" alt="1975 - M608 - 608-04-001 - AUDIO DISTRIBUTION AMPLIFIER.jpg"></a><br><sub>1975|8 · 608-04-001 - AUDIO DISTRIBUTION AMPLIFIER · <a href="MECHANICAL/1975%20-%20M608%20-%20608-04-001%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbUl6OTczS3prS3M/view?resourcekey=0-GbnRiroNOFJ4vYlnRjVHnA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbUl6OTczS3prS3M&resourcekey=0-GbnRiroNOFJ4vYlnRjVHnA" width="240" alt="1975 - M608 - 608-04-001 - CONNECT OUTPUT CAELE SHIELDS CHASSIS MODULE.jpg"></a><br><sub>1975|8 · 608-04-001 - CONNECT OUTPUT CAELE SHIELDS CHASSIS MODULE · <a href="MECHANICAL/1975%20-%20M608%20-%20608-04-001%20-%20CONNECT%20OUTPUT%20CAELE%20SHIELDS%20CHASSIS%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRWhxVFo0NVFST0E/view?resourcekey=0-BkXeYFpjIvVIHffbbRDqxg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRWhxVFo0NVFST0E&resourcekey=0-BkXeYFpjIvVIHffbbRDqxg" width="240" alt="1975 - M608 - 14-017-06-001 - ALL RESISTORS ARE.jpg"></a><br><sub>1975|8 · 14-017-06-001 - ALL RESISTORS ARE · <a href="SCHEMATICS/1975%20-%20M608%20-%2014-017-06-001%20-%20ALL%20RESISTORS%20ARE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM2FIcVEzZHJoQm8/view?resourcekey=0-ez2HPGca0zvMCPu4nylbQw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM2FIcVEzZHJoQm8&resourcekey=0-ez2HPGca0zvMCPu4nylbQw" width="240" alt="1975 - M608 - 14-017-06-001.jpg"></a><br><sub>1975|8 · 14-017-06-001 · <a href="SCHEMATICS/1975%20-%20M608%20-%2014-017-06-001%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQTktS3F1aXVJVTA/view?resourcekey=0-lhkEjsBcRdjxMMchV2hQYg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQTktS3F1aXVJVTA&resourcekey=0-lhkEjsBcRdjxMMchV2hQYg" width="240" alt="1975 - M608 - 608-01-001 - AUDIO DISTRIBUTION AMPLIFIER.jpg"></a><br><sub>1975|8 · 608-01-001 - AUDIO DISTRIBUTION AMPLIFIER · <a href="SCHEMATICS/1975%20-%20M608%20-%20608-01-001%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVkxiNU5vdWtXems/view?resourcekey=0-bX3P38ex4Jzwtlb34BuEdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVkxiNU5vdWtXems&resourcekey=0-bX3P38ex4Jzwtlb34BuEdQ" width="240" alt="1975 - M608 - 608-01-001 - BIE OUT.jpg"></a><br><sub>1975|8 · 608-01-001 - BIE OUT · <a href="SCHEMATICS/1975%20-%20M608%20-%20608-01-001%20-%20BIE%20OUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkZLTDNfRVJmcUU/view?resourcekey=0-lSxeNRS5AZUM_SlzVJQhTw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkZLTDNfRVJmcUU&resourcekey=0-lSxeNRS5AZUM_SlzVJQhTw" width="240" alt="1975 - M608 - 608-02-001 - ALL CAPACITCRSARE INAF UNLESS CTHERWSE SPECIFIED.jpg"></a><br><sub>1975|8 · 608-02-001 - ALL CAPACITCRSARE INAF UNLESS CTHERWSE SPECIFIED · <a href="SCHEMATICS/1975%20-%20M608%20-%20608-02-001%20-%20ALL%20CAPACITCRSARE%20INAF%20UNLESS%20CTHERWSE%20SPECIFIED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTGlwZ3N3ZF9JdGM/view?resourcekey=0-Y3NRlGkChLM_LxJ-HeUCTw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTGlwZ3N3ZF9JdGM&resourcekey=0-Y3NRlGkChLM_LxJ-HeUCTw" width="240" alt="1975 - M608 - 608-02-001 - OVLD NORM.jpg"></a><br><sub>1975|8 · 608-02-001 - OVLD NORM · <a href="SCHEMATICS/1975%20-%20M608%20-%20608-02-001%20-%20OVLD%20NORM%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS2hyMkl1am84QWM/view?resourcekey=0-_W5Kzpjy35AnaRs-gcvFCw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS2hyMkl1am84QWM&resourcekey=0-_W5Kzpjy35AnaRs-gcvFCw" width="240" alt="1975 - M608 - 608-02-003 - AUDIO DISTRIBUTION AMPLIFIER.jpg"></a><br><sub>1975|8 · 608-02-003 - AUDIO DISTRIBUTION AMPLIFIER · <a href="SCHEMATICS/1975%20-%20M608%20-%20608-02-003%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYW9rUlNqWHRmZ1U/view?resourcekey=0-f6euDU5SmJNyvf5kQL6OMA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYW9rUlNqWHRmZ1U&resourcekey=0-f6euDU5SmJNyvf5kQL6OMA" width="240" alt="1975 - M608 - 608-02-003 - STATION TECHNICAL GROUND INSULATED GROUND BAR.jpg"></a><br><sub>1975|8 · 608-02-003 - STATION TECHNICAL GROUND INSULATED GROUND BAR · <a href="SCHEMATICS/1975%20-%20M608%20-%20608-02-003%20-%20STATION%20TECHNICAL%20GROUND%20INSULATED%20GROUND%20BAR%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcm1Ra1NYWEtFejA/view?resourcekey=0-z_-ASZCK80-th-HC-dB5LA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcm1Ra1NYWEtFejA&resourcekey=0-z_-ASZCK80-th-HC-dB5LA" width="240" alt="1975 - M608 - 608-06-001 - AUDIO DISTRIBUTION AMPLIFIER COMPONENT LAYOUT.png"></a><br><sub>1975|8 · 608-06-001 - AUDIO DISTRIBUTION AMPLIFIER COMPONENT LAYOUT · <a href="SCHEMATICS/1975%20-%20M608%20-%20608-06-001%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeTNFRXRmMEV6UFk/view?resourcekey=0-2fq9IBNux4rYwlrey_GF9Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeTNFRXRmMEV6UFk&resourcekey=0-2fq9IBNux4rYwlrey_GF9Q" width="240" alt="1975 - M608 - 608-06-002 - AUDIO DISTRIBUTION AMPLIFIER.jpg"></a><br><sub>1975|8 · 608-06-002 - AUDIO DISTRIBUTION AMPLIFIER · <a href="SCHEMATICS/1975%20-%20M608%20-%20608-06-002%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOEdGSmpfWlRZZU0/view?resourcekey=0-kROQltRaRjwaMfyLv8nTpQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOEdGSmpfWlRZZU0&resourcekey=0-kROQltRaRjwaMfyLv8nTpQ" width="240" alt="1975 - M608 - 608-06-002.jpg"></a><br><sub>1975|8 · 608-06-002 · <a href="SCHEMATICS/1975%20-%20M608%20-%20608-06-002%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTWk4cW9DVG5Idnc/view?resourcekey=0-l2p3heIUsYkoKZkIHGAXvg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTWk4cW9DVG5Idnc&resourcekey=0-l2p3heIUsYkoKZkIHGAXvg" width="240" alt="1975 - M608 - 8-116-06-001 - COMPONENT SIDE OFF SET OFF SET.jpg"></a><br><sub>1975|8 · 8-116-06-001 - COMPONENT SIDE OFF SET OFF SET · <a href="SCHEMATICS/1975%20-%20M608%20-%208-116-06-001%20-%20COMPONENT%20SIDE%20OFF%20SET%20OFF%20SET%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM1BaQWJ0ZVFNbEU/view?resourcekey=0-UvIIP2nBwsH03IZkmIT7Vw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM1BaQWJ0ZVFNbEU&resourcekey=0-UvIIP2nBwsH03IZkmIT7Vw" width="240" alt="1975 - M608 - 8-116-06-001 - HEAT SINK FOR.jpg"></a><br><sub>1975|8 · 8-116-06-001 - HEAT SINK FOR · <a href="SCHEMATICS/1975%20-%20M608%20-%208-116-06-001%20-%20HEAT%20SINK%20FOR%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOXZRSnd4N1hSdEU/view?resourcekey=0-wCctXmMstcRvOfItEIIdPQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOXZRSnd4N1hSdEU&resourcekey=0-wCctXmMstcRvOfItEIIdPQ" width="240" alt="1975 - M608 - 8-117-06-001 - TRANSISTORS QII AND.jpg"></a><br><sub>1975|8 · 8-117-06-001 - TRANSISTORS QII AND · <a href="SCHEMATICS/1975%20-%20M608%20-%208-117-06-001%20-%20TRANSISTORS%20QII%20AND%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR3RjdmlBVE9VM28/view?resourcekey=0-ElKCpU6o1IXiTHZB4nsT_g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR3RjdmlBVE9VM28&resourcekey=0-ElKCpU6o1IXiTHZB4nsT_g" width="240" alt="1975 - M608 - 8-117-06-001.jpg"></a><br><sub>1975|8 · 8-117-06-001 · <a href="SCHEMATICS/1975%20-%20M608%20-%208-117-06-001%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1MvP47_z6MkFmlL-vwXA5tpTIwivzgO7r/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1MvP47_z6MkFmlL-vwXA5tpTIwivzgO7r" width="240" alt="19xx - M608 - DOC - 608-02-003 - TECHNICAL GROUND INSULATED GROUND BAR.png"></a><br><sub>19xx - M608 - DOC - 608-02-003 - TECHNICAL GROUND INSULATED GROUND BAR · <a href="SCHEMATICS/19xx%20-%20M608%20-%20DOC%20-%20608-02-003%20-%20TECHNICAL%20GROUND%20INSULATED%20GROUND%20BAR%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1980 - 608-02-003 - M608A AUDIO DISTRIBUTION AMPLIFIER SYSTEM WIRING SCHEMATIC - DRN P. MAHONEY - ENG MRW - ISS 1.png`, `19xx - 608-02-001 - AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC - DRN P. Mahoney.jpg`, `19xx - 608-02-002 - M608A AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC - DRN P. Mahoney - ENG MRW.png`, `19xx - 608-06-001 - M608A AUDIO DISTRIBUTION AMPLIFIER COMPONENT LAYOUT - DRN P. Mahoney - ENG MRW - ISS 2.png`, `19xx - 8-116-06-001.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `1980 - 608-04-001 - (cut off; connector wiring diagram, P1 P2, 'CT M608' note) - DRN D. Mahoney - ENG MRW - ISS 2.jpg`

## RTO-144 pinout

Read from 2 pinout pictures (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| P1-2 | OUTPUT 4 | out | OUTPUT 4 | high |
| P1-3 | OUTPUT 3 | out | OUTPUT 3 | high |
| P1-4 | OUTPUT 2 | out | OUTPUT 2 | high |
| P1-5 | OUTPUT 1 | out | OUTPUT 1 | high |
| P1-7 | 115 VAC | power |  | high |
| P1-10 | OUTPUT 4 | out | OUTPUT 4 | high |
| P1-11 | OUTPUT 3 | out | OUTPUT 3 | high |
| P1-12 | OUTPUT 2 | out | OUTPUT 2 | high |
| P1-13 | OUTPUT 1 | out | OUTPUT 1 | high |
| P1-15 | MODULE COMMON (OUTPUT SHIELDS) | ground |  | high |
| P1-16 | 115 VAC | power |  | high |
| P2-1 | MODULE COMMON | ground |  | high |
| P2-3 | OUTPUT 5 | out | OUTPUT 5 | high |
| P2-4 | OUTPUT 6 | out | OUTPUT 6 | high |
| P2-5 | OUTPUT 7 | out | OUTPUT 7 | high |
| P2-6 | OUTPUT 8 | out | OUTPUT 8 | high |
| P2-7 | INPUT SHIELD | shield | INPUT shield | high |
| P2-8 | INPUT | in | INPUT | high |
| P2-9 | CHASSIS | ground |  | high |
| P2-11 | OUTPUT 5 | out | OUTPUT 5 | high |
| P2-12 | OUTPUT 6 | out | OUTPUT 6 | high |
| P2-13 | OUTPUT 7 | out | OUTPUT 7 | high |
| P2-14 | OUTPUT 8 | out | OUTPUT 8 | high |
| P2-15 | CT (M608 ONLY) | other |  | high |
| P2-16 | INPUT | in | INPUT | high |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVGpJZ01yNkpYYmM/view?resourcekey=0-RJ7E0Z6mIHET55CCqMsoSg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVGpJZ01yNkpYYmM&resourcekey=0-RJ7E0Z6mIHET55CCqMsoSg" width="240" alt="1975 - M608 - Audio DA (2).pdf"></a><br><sub>1975|8 · Audio DA (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR3YxU3RWR1Z4elU/view?resourcekey=0-WP25eYN_C0cfVKaU4itWcA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR3YxU3RWR1Z4elU&resourcekey=0-WP25eYN_C0cfVKaU4itWcA" width="240" alt="1975 - M608 - Audio DA.pdf"></a><br><sub>1975|8 · Audio DA</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWUlXZm9MOE5JUTQ/view?resourcekey=0-T_ydbkQm_rWRGojj7Q7hqQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWUlXZm9MOE5JUTQ&resourcekey=0-T_ydbkQm_rWRGojj7Q7hqQ" width="240" alt="1975 - M608 - P001 - Title Page.jpg"></a><br><sub>1975|8 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbkZxRjFhS2swU0E/view?resourcekey=0-ioJZgjVuFp_TRJMHckjqqQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbkZxRjFhS2swU0E&resourcekey=0-ioJZgjVuFp_TRJMHckjqqQ" width="240" alt="1975 - M608 - P003 - 1-1.jpg"></a><br><sub>1975|8 · P003 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZnp4U1dmVHZyQjA/view?resourcekey=0-ReRBnVdAeiPjHpotLKSG6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZnp4U1dmVHZyQjA&resourcekey=0-ReRBnVdAeiPjHpotLKSG6w" width="240" alt="1975 - M608 - P004 - 1-2.jpg"></a><br><sub>1975|8 · P004 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWjUxR0FqdmlBTG8/view?resourcekey=0-q17q9AG1CJvn6aeVQwZ7hw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWjUxR0FqdmlBTG8&resourcekey=0-q17q9AG1CJvn6aeVQwZ7hw" width="240" alt="1975 - M608 - P005 - 2-1.jpg"></a><br><sub>1975|8 · P005 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcVhVTXFwSk1oQTQ/view?resourcekey=0-HKnCmvWrt8lw8ZZBlEXAVQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcVhVTXFwSk1oQTQ&resourcekey=0-HKnCmvWrt8lw8ZZBlEXAVQ" width="240" alt="1975 - M608 - P006 - 2-2.jpg"></a><br><sub>1975|8 · P006 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU2JmQ0ZLOVM4Tzg/view?resourcekey=0-39tOvCCkuhX-SlYSWh75aQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU2JmQ0ZLOVM4Tzg&resourcekey=0-39tOvCCkuhX-SlYSWh75aQ" width="240" alt="1975 - M608 - P007 - 2-3.jpg"></a><br><sub>1975|8 · P007 - 2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSTZCMmdUY2VKS2c/view?resourcekey=0-VaHt9jFY98ga_YEH202eQA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSTZCMmdUY2VKS2c&resourcekey=0-VaHt9jFY98ga_YEH202eQA" width="240" alt="1975 - M608 - P008 - 3-1.jpg"></a><br><sub>1975|8 · P008 - 3-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTzRmSzFEMkdEVTA/view?resourcekey=0-4V3lbJRNfbcLt_0EpvlQvA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTzRmSzFEMkdEVTA&resourcekey=0-4V3lbJRNfbcLt_0EpvlQvA" width="240" alt="1975 - M608 - P009 - 4-1.jpg"></a><br><sub>1975|8 · P009 - 4-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWTlYcWtwSHZJd0U/view?resourcekey=0-vDCQ6og_lFM4zUPK4b1XUA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWTlYcWtwSHZJd0U&resourcekey=0-vDCQ6og_lFM4zUPK4b1XUA" width="240" alt="1975 - M608 - P010 - 4-2.jpg"></a><br><sub>1975|8 · P010 - 4-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSW04SUlSMmNGY3c/view?resourcekey=0-eF28gNYgNCHx8lJ640PVDQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSW04SUlSMmNGY3c&resourcekey=0-eF28gNYgNCHx8lJ640PVDQ" width="240" alt="1975 - M608 - P011 - 4-3.jpg"></a><br><sub>1975|8 · P011 - 4-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1JnVFoxel92NHc/view?resourcekey=0-BJ_OevbvY4eKOi7u36TByw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1JnVFoxel92NHc&resourcekey=0-BJ_OevbvY4eKOi7u36TByw" width="240" alt="1975 - M608 - P012 - 4-4.jpg"></a><br><sub>1975|8 · P012 - 4-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVVAwakxMa0V2Slk/view?resourcekey=0-v-38J6FW6suAjxx_SFeGHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVVAwakxMa0V2Slk&resourcekey=0-v-38J6FW6suAjxx_SFeGHQ" width="240" alt="1975 - M608 - P013 - 4-5.jpg"></a><br><sub>1975|8 · P013 - 4-5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd1lOTVdiTEo4VG8/view?resourcekey=0-uTFT1-MKbcc0T2fFTN4tKA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd1lOTVdiTEo4VG8&resourcekey=0-uTFT1-MKbcc0T2fFTN4tKA" width="240" alt="1975 - M608 - WBS test procedures 0.jpeg"></a><br><sub>1975|8 · WBS test procedures 0</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM0l6ZEV5ZHV1ZFE/view?resourcekey=0-QoG1IrNxfwlb7TcsY0Zz1g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM0l6ZEV5ZHV1ZFE&resourcekey=0-QoG1IrNxfwlb7TcsY0Zz1g" width="240" alt="1975 - M608 - WBS test procedures 1.jpeg"></a><br><sub>1975|8 · WBS test procedures 1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd2gyS25aRkJoR0E/view?resourcekey=0-EOKfzIUPaCkW8d-JklfI7g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd2gyS25aRkJoR0E&resourcekey=0-EOKfzIUPaCkW8d-JklfI7g" width="240" alt="1975 - M608 - WBS test procedures 2.jpeg"></a><br><sub>1975|8 · WBS test procedures 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd0tvdldnZ2p3WHc/view?resourcekey=0-1EFGZlUzlPrDzgjZRYH6Cw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd0tvdldnZ2p3WHc&resourcekey=0-1EFGZlUzlPrDzgjZRYH6Cw" width="240" alt="1975 - M608 - WBS test procedures 3.jpeg"></a><br><sub>1975|8 · WBS test procedures 3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSjBlTkFZSzgyYVU/view?resourcekey=0-MuEaZeNs6fShOTtjIbBZ2w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSjBlTkFZSzgyYVU&resourcekey=0-MuEaZeNs6fShOTtjIbBZ2w" width="240" alt="1975 - M608 - WBS test procedures 4.jpeg"></a><br><sub>1975|8 · WBS test procedures 4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaGhJSjVQN0RZUXM/view?resourcekey=0-r3b1v_uS_aXxkjKxsBEm0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaGhJSjVQN0RZUXM&resourcekey=0-r3b1v_uS_aXxkjKxsBEm0Q" width="240" alt="1980 - M608 - P002.jpg"></a><br><sub>1980|13 · P002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTi1QQlhyRGw2XzA/view?resourcekey=0-urNxOrgjwQFRDjpVU-OGPg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTi1QQlhyRGw2XzA&resourcekey=0-urNxOrgjwQFRDjpVU-OGPg" width="240" alt="19xx - M608 - AD - WBSPS - AD - for the engineer who has everything.jpg"></a><br><sub>19xx - M608 - AD - WBSPS - AD - for the engineer who has everything</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVGxmcHp4ejNOTnM/view?resourcekey=0-iiyRPxnyvNdSioFxJYuEig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVGxmcHp4ejNOTnM&resourcekey=0-iiyRPxnyvNdSioFxJYuEig" width="240" alt="19xx - M608 - DOC - US Sales Brochure pg 11.jpg"></a><br><sub>19xx - M608 - DOC - US Sales Brochure pg 11</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZVBTVUFla1BxbU0/view?resourcekey=0-r84YCex-61AGkExJUxIQ6Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZVBTVUFla1BxbU0&resourcekey=0-r84YCex-61AGkExJUxIQ6Q" width="240" alt="19xx - M608 - DOC - US Sales Brochure pg 25.jpg"></a><br><sub>19xx - M608 - DOC - US Sales Brochure pg 25</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1Ph4bH2EJh1R7BDyQtuy94lE0pm1IO7Ie/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1Ph4bH2EJh1R7BDyQtuy94lE0pm1IO7Ie" width="240" alt="19xx - M608 - DOC - WBSps.ca - 20210317 11X 17 Scans.png"></a><br><sub>19xx - M608 - DOC - WBSps.ca - 20210317 11X 17 Scans</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [19xx - M608 - DOC - WBSPS - AD - for the engineer who has everything](https://drive.google.com/file/d/0B0yR0b5T78SKbGlUcFh6b0hqcVE/view?resourcekey=0-ciA_tsM-sD9I8DGfjlKSwA)

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1975 - M608 - 608-01-001 - AUDIO DISTRIBUTION AMPLIFIER.kicad_sch](KICAD/1975%20-%20M608%20-%20608-01-001%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER.kicad_sch)
- [1975 - M608 - 608-01-001 - BIE OUT.kicad_sch](KICAD/1975%20-%20M608%20-%20608-01-001%20-%20BIE%20OUT.kicad_sch)
- [1975 - M608 - 608-02-001 - ALL CAPACITCRSARE INAF UNLESS CTHERWSE SPECIFIED.kicad_sch](KICAD/1975%20-%20M608%20-%20608-02-001%20-%20ALL%20CAPACITCRSARE%20INAF%20UNLESS%20CTHERWSE%20SPECIFIED.kicad_sch)
- [1975 - M608 - 608-02-001 - OVLD NORM.kicad_sch](KICAD/1975%20-%20M608%20-%20608-02-001%20-%20OVLD%20NORM.kicad_sch)
- [1975 - M608 - 608-02-003 - AUDIO DISTRIBUTION AMPLIFIER.kicad_sch](KICAD/1975%20-%20M608%20-%20608-02-003%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER.kicad_sch)
- [1975 - M608 - 608-02-003 - STATION TECHNICAL GROUND INSULATED GROUND BAR.kicad_sch](KICAD/1975%20-%20M608%20-%20608-02-003%20-%20STATION%20TECHNICAL%20GROUND%20INSULATED%20GROUND%20BAR.kicad_sch)
- [1975 - M608 - Audio DA p19.kicad_sch](KICAD/1975%20-%20M608%20-%20Audio%20DA%20p19.kicad_sch)
- [1980 - 608-02-003 - M608A AUDIO DISTRIBUTION AMPLIFIER SYSTEM WIRING SCHEMATIC - DRN P. MAHONEY - ENG MRW - ISS 1.kicad_sch](KICAD/1980%20-%20608-02-003%20-%20M608A%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20SYSTEM%20WIRING%20SCHEMATIC%20-%20DRN%20P.%20MAHONEY%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [19xx - 608-02-001 - AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC - DRN P. Mahoney.kicad_sch](KICAD/19xx%20-%20608-02-001%20-%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20P.%20Mahoney.kicad_sch)
- [19xx - 608-02-002 - M608A AUDIO DISTRIBUTION AMPLIFIER SCHEMATIC - DRN P. Mahoney - ENG MRW.kicad_sch](KICAD/19xx%20-%20608-02-002%20-%20M608A%20AUDIO%20DISTRIBUTION%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20P.%20Mahoney%20-%20ENG%20MRW.kicad_sch)
- [19xx - M608 - DOC - 608-02-003 - TECHNICAL GROUND INSULATED GROUND BAR.kicad_sch](KICAD/19xx%20-%20M608%20-%20DOC%20-%20608-02-003%20-%20TECHNICAL%20GROUND%20INSULATED%20GROUND%20BAR.kicad_sch)
- [M608.kicad_sym](KICAD/M608.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
