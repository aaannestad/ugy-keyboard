# ugy-keyboard

This is a custom ergonomic keyboard layout for English that I developed in 2014, and currently use as my daily driver on all of my non-phone computers. The keyboard is meant to be optimised for speed and ease of typing, with the following goals:

- keep the most common letters in the most easily accessible locations (e.g. vowels on the row your fingers rest on)
- minimise the need to use the same finger to type two successive letters
- after the above, minimise the need to use the same hand to type two successive letters
- have easy access to a very wide variety of accented or otherwise altered Roman letters

I evaluated various layout choices through patorjk.com/keyboard-layout-analyzer/, using the text of my undergrad thesis (which I was writing at the time) as my primary test text. The end result is the layout you see below:

![A display of base the Úgy ergonomic layout. The rows are as follows, from top to bottom: 'ugyfcdhp?/ oaei.lrtns- ;qjkxbmwvz](/layout.png "The base Úgy layout")

The name Úgy has the same rationale as 'QWERTY'; typing the first four keys on the top row outputs \úgy (where <'> is a dead key.).

The layout gives access to a wide variety of non-base Latin letters by means of the alt key and/or dead keys:

* alt: uc?/ oa.rs- ;vz > µ©¿× œæ.®ß¥ ¶vȝ
* alt+shift: C+ OA,TS :Z > ¢÷ ŒÆ,Þ§ °Ȝ

(note that alt+t _should_ produce lower-case Þ; this is a known bug)

The dead keys are:

* ` > àèìòùẁ
* ~ > ãẽĩñõũṽ
* ^ > âĉêĝĥîĵôŝûŵŷẑ
* | > āđēḡħīōŧūȳ
* ' > áćéíḱĺḿńóṕŕśúẃýź
* " > äëḧïöüẅẍÿ
* / > ðłø
* µ (alt+u) > ăĕğĭŏŭ
* œ (alt+o) > åḃċḋḟġḣıŀṁṅṗṙṡṫůẇẏż
* alt+. > ḁḅḍgḥḳḷṃṇṛṣṭṿẉẓ
* alt+, > ḁçęģįķļņŗşţų
* alt+v > ǎčěȟǐňǒřšǔ

All of the above should work with capital versions as well.

Note that one downside of this dead key setup is the need to type a space whenever you type the English possesive clitic _='s_, as just typing <'s> directly outputs <ś>; the use of </> as a dead key also makes some coding more difficult. In a future revision I may move </> and some <'> dead keys to alt+/ and alt+', respectively.
