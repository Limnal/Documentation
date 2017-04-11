This is not the official Lietal, but a transitional version of language combininig some established ideas from Traumae with published details of Lietal. Hopefully, some ideas from this document would be useful in Lietal development.

# Phonology and transliteration
(provisional)
```
p   /p/    t   /t/    k /c ~ k/
f   /f/    s   /s/    x /ʃ ~ x/
v   /ʋ/    l /ɹ ~ l/  y   /j/
           n   /n/

o   /o/    a   /a/     i  /i/
```
For now, lexical stress is always on the first syllable in a word. The nature of accent (dynamic, pitch, quantitative, and/or qualitative) is not decided yet.

# Morphophonology and basic vocabulary
The basic semantic unit of the language is called aeth and consist of two components, key and vector. The basic phonetic realization of aeth is syllable, with key realized as onset and vector, as nucleus; however for phonoaesthetic reasons consecutive aeths sharing key or vector can merge, and key may be realized as coda instead of onset. The basic realization is called “childspeak” and variations, “adultspeak”.
The whole product of key × vector combination is called Aebeth.
Aeth keys have very broad, abstract semantic fields, orthogonal to one another. 
Vectors are, on other hand, simple three-valued modificators, having values of zero and positive and negative units; with basic phonetic realizations of /a/, /i/ and /o/.
```
    Traverse        State           Nature
ki  Milieu      xi  Psyche      yi  Emergent
ka  Instance    xa  Form        ya  Person
ko  Attribute   xo  Matter      yo  Minimal

    Direction       Relation        Counter        Structural
ti  Outward     si  With        li  Continuity  ni Keep
ta  Stable      sa  ...         la  Unit        na
to  Inward      so  Without     lo  Void        no Apply

    Modality        Alignment       Interaction    Structural-2
pi  Certain     fi  Agreement   vi  to Act      mi
pa  Possible    fa  Doubt       va  to Exist    ma Switch
po  Impossible  fo  Conflict    vo  Communicate mo
```
Depending on the key,  aebeth is subdivided into  content and structure aeth. Structural aeths is a smaller part; they are only means for controlling syntactical flow, and as devoid of other meaning as possible. Content aeth cover all other meaning , both lexical and grammatical.

*TODO:  detailed explanation of each aeth; example of key+vector combination; examples of childpeak and adultspeak*

# Grammar
## Morphology
Aeths form words, divided in writing by space. Word consist of zero or more content aeth, forming stem, and (optional, if stem is not empty) structural aeth. Structural aeth (or its absence) determine part of speech of the word, it syntactical behaviour and the interpretation of content part – some structural aeth use the latter just as a key. 
Each aeth in a word, except for the first, acts as a modifier to the whole word before it to the left. 

## Stem
Often, the stem can be divided into two groups of aeth, first expressing lexical meaning, and second, grammatical one.
Limnal do not have familiar parts of speech (nouns, verbs etc); that being said, stems are often have nominal or verbal meaning. __Interaction__ key tend to produce verbal, and __State__ key tends to produce nominal. However, this primary meaning can then be reinterpeted either nominally or verbally:
```
\ Reinterpretation     Nominal            Verbal
Primary meaning
Noun                   Object             ⎫ To be...,
                                          ⎬ to make/be made (into) ... (by Agent),
Adjective              State of...        ⎭ to be considered ... (by Experiencer)
Verb                   Event of...        Action
```
__*Examples:*__
`ya`, interpreted nominally, means “a person”, but interpreted verbally, means “to be person/to personify”. `vo` means “to communicate” verbally, but interpreted nominally, means “(event of) communication”.
Note that this means that, if we interpret ya verbally and then nominally back, it will also mean “an event of being  person”, or “personhood”. This is normal; more precise meaning is achieved by inflection. In particular, `yax(a)` __*Person.Form*__ means  “a person as an entity”, and `yav(a)` __*Person.Exist*__ “(a state or a process of) being a person”.
Word consisting of two content aeth is called diveth and is a basic dictonary unit.

Some common grammatic and derivative suffixes:
```
-li    Continuity     Explicit plural, mass
-xa    Form           Nominal suffix. Other aeth of key Shape also
                      produce noun-like meaning. Implicitly non-singular.
-la    Unit           Explicit singular.
-yi    Emergent       Higher-order entity.

-va    Exist          Verbal suffix, “to be..."
-ti    Outward        Agentive or instrumentative suffix, -er
-to    Inward         Patient suffix, -ee
                      Note what for sensory verbs relation is reversed,
                      so “perceiver” is voto

-pi    Certain        Definitines, “the”
-pa    Possible       Indefinitiness, “a”. Note that this is very approximate
                      translation, as the notion of possibilities has a 
                      special meaning in Traumae.
```                      
__*Examples of derivation:*__
```
Adultspeak Childspeak
ya         ya         Person               person/people
yal        yala       Person.Unit          a person
                                           (with emphasis on singular number)
yail       yali       Person.Continuity    society, people
                                           (may be considered plural of ya)
yailli     yalili     Person.Continutity^2 group of societies
yai        yayi       Person.Emergent      institution, emergent human system

xi         xi         Psyche               any thought process, really
txi, tix   tixi       Outward.Psyche       intention, will
toix       toxi       Inward.Psyche        attention
taix       taxi       Stable.Psyche        outlook, mood, mental context
```

## Parts of speech
Depending on final stuctural aeth or it absence, words are subdivided into following:
1. Absent: argument;
2. `no`:  method;
3. `ni`: postposition;
4. `ma`: flow control;
5. *TODO: Personal names*
6. *TODO: Numbers*
Arguments and methods named after object-oriented concepts, for lack of better names. Argument can be thought of as a simple object or quality,  and method is often, but not alwasys, is a verb, and generally a head word of some compound.

## Syntax
The basic structure of simple Limnal text is as following:
```
({argument | method.no } postp.ni)*
```
That is, several (zero or more) postpositional phrases; each consisting  of either argument or method, followed by postposition. For example:
```
*glade tvain [voit toin] *flower tain von  [loin]  (adultspeak)    
*glade tavani voti toni *flower tani vono  loni   (childspeak)
       in     I    do           at   look  (end of text)
-------------|---------|------------
   In a glade, I look at a flower
```
Last postposition after the method joins it with the following text; at the end of text or a logical segment of it, `loni` is used to indicate the absence of connection, which may be elided. *(TBD: Or just `ni`?)* 
First person pronoun is often elided when in relation of Agent or Experiencer.

## Postpositions
Postpositions express [thematic relation](https://en.wikipedia.org/wiki/Thematic_relation) of a preceding argument of method.
Basic thematic relations are covered by aeth of key __Direction__:
```
Stem           Thematic relation
------------------------------------
to   Inward     Patient, Experiencer
ta   Stable     Theme, Stimulus
ti   Outward    Agent, Force
```
By extending postposition stem, thematic relation is stated more precisely:
```
Stem                           Thematic relation
-------------------------------------------------------------
tovo   Inward.Communicate      Experiencer
tavo   Stable.Communicate      Stimuls (passive)
tivo   Outward.Comunicate      Stimulus (active)

tovi   Inward.Act              Patient, Recepient
tavi   Stable.Act              Theme
tivi   Outward.Act             Agent of Force
tixivi Outward.Idea.Act           Agent
tixovi Outward.Matter.Act         Force

tova   Inward.Exist            Purpose, Goal or Direction
tava   Stable.Exist            Manner, Location or Time
taxava Stable.Form.Exist         Manner
taxova Stable.Matter.Exist       Location or Time*
tiva   Outward.Exist           Cause or Origin
```
*TODO \*) Maybe change to Milieu?*

## Pronouns
Personal pronouns are formed aeth __*Communicate*__ and aeths of key __Direction__; the explanation being that they are refer to the participants of current communication act. (Note that direction is reversed in comparison with classical Traumae, because direction is considered relative to the event of communication itself.)
``` 
voti  I, the speaker                 votli  We (exclusive)
                                     votio  We (inclusive)
vota  he/she/it, one spoken about    votali they
voto  you, thou, the listener        votoli you (plural)
```
First-person pronoun is often elided and is assumed to be Agent of Experiencer of an event by default.
*TODO: Idea: maybe Direction-key aeths by themselves mean personal pronouns? But this clashes with their role as thematic relation markers.
TODO: Verb conjugation, determiners, numbers, conjunctions, subordinate clauses...*

## Technical notes on syntax
*TODO: rework*
Most aeth work as modifiers to the previous context. This happen both on morphological (word) and syntactic (sentence) level:
```
xvo
xo.vo
Matter.Communicate
touch, pecreive physically

xo vo
Matter Communicate
perceive physical phenomenon/a
```
Very simple sentence with only one argument noun phrase can be formed without structural aeth, in a pattern
```
NP [postp] verb
```
If postposition is omitted, it is defaulted to `ta` (theme, passive stmulus, or manner).
So the flower example can be simply
```
*flower [ta] vo
```
*TBD: To emulate word order arguments, If there is already ta argument assigned, next default will be ti? But this will force OSV word order. To do SOV with ability to drop subjects, we need to be able to re-assign arguments later, and this complicates things.*
Structural aeths allow to join several arguments to a single verb. Aeth  ni suspends current branch and remembers it for further use; aeth no joins all such suspended branches as a context for the folowing aeth: 
```
voti toin *flower tain nov
voti toni *flower tani no vo
I see the flower

voto tin *flower toin no.*pick
voto tini *flower to ni no *pick
You pick the flower
```
Aeth `ma`, __*Switch*___, preceded by another aeth (which usual sense is discarded), is used to switch to another map of suspended branches, primarily for subordinate clauses. Word `mam(a)` is used to return to main map:
```
voti toin tam voto tin *flower toin no.*pick mam tain nov
voti toni tama voto tini *flower toni no *pick mama tani no vo
I see you picking the flower
```
Sentences are currently connected by `kini`, setting previous sentece as a context for the next. *TODO: find a better way to: Structural aeth `na`, following by a previously used aeth, word, or prefix of word,  refers back to matching word:*
```
Voti toin *flower tain nov. Kin voto tin na*flower.. toin no.*pick.
I see the flower. You pick it. (that is, the flower)

Voto tin *flower toin no.*pick. Kin voti toin na*pick.. tain nov.
You pick the flower. I see it. (That is, the event)
```

## Crazy alternate grammar (IN VERY ROUGH STATE, READ AT YOUR OWN RICK)
1. Any structural aeth gives an empty context to the next content aeth. *(“starts a new branch”)*
2. Space between words is structural token  (“invisible aeth”). If it come after another structural aeth, it is ignored; otherwise, it takes result of the previous content aeth and saves it as **argument**.  *If argument used flag is not set, makes a compound (applies current word to previous argument as verb). Clears the argument used flag.*
3. Aeth na takes the result of previous content aeth and applies it as a verb function to **current event map**. Then it sets **argument** to same value as **current event map**. (Two operations are conflated – do we need them separately? Just not ignore the space after na. No space - current event map is not saved as agrument. But context is reset anyway.* -> `no`
4. Aeth `no` takes the result of the previous content aeth as a thematic role and adds **argument** to **current event map** with this thematic role as a key. *Sets argument used flag.* -> `ni`
5. Aeth `ma` takes the result of previous content aeth as an index and sets **alternate event map** with this index as a **current**.

```
*glade-tvaon  [voit-ton ] *flower-taon voan- (adultspeak)    
*glade tavano [voti tono] *flower tano vona- (childspeak)
------======*------====*---------====*---^-==

voit-ton  tam   vot-tion *flower-ton  *pick.an-ma taon voan-
voti-tono tama voto tino *flower tono *pick.na-ma tano vona-
----====*----!~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~!====*---^-==
              -----====*--------====*-------^-==
```
Vot-tion *flower-ton *pick.na. - Kion voti-ton *pick..-taon voan. -
You pick the flower. I see it. (That is, the event)

***Anomalous structures:***
argument after argument: first argument is overwritten. better to make compounds.
arg postp:no postp:no: same argument is used for different them.role. maybe desirable.  or empty argument.
arg no: empty string is used as postp. maybe useful as neutral relation
event na: empty verb. Just sets argument to the same value as event map. [maybe implicitly reapplies previous verb?]
arg verb:na: same as arg arg, first argument is overwritten.

***Complex noun phrases:***
```
*sun-tini tma *east-kini *sky.no-ma-tovani *rise.no
```

# Writing systems
The language can be written with a suitable real-world writing system (e.g. latin, cyrillic, katakana, or hebrew) or with one of systems designed for Traumae:
https://fontstruct.com/fontstructors/58371/aliceffekt
https://twitter.com/i/web/status/794060596777914369
@heapaepaemnunea adapted Legola script for Limnal: https://merveilles.slack.com/files/heapaepaemnunea/F4DA0HA2V/img_20170306_175330.jpg
