---
title: Minno
---
*v0.1.1.1*

## Chapter 0 - Preface & Introduction
---
### 0.0 - Introduction: What is Minno?
Minno is a constructed language. What that means is that Minno is a language like English, Korean, Spanish, etc, but instead of being born out of linguistic evolution in the real world, it is created purposefully. Specifically, Minno aims to be an extremely simple, easy, and innovative language. Minno’s purpose is to be a great alternative or secondary language, for anyone who’d like to learn it.

In this document, Minno will often be compared to English, as that’s the author’s primary language. (Also the language the document is written in)

### 0.1 - Versioning
As Minno is not completely created by a single person, and is in occasional development, it uses a version system to keep track of possible changes. A version string contains three numbers, inspired by SEMVER versioning: `Establishing.Breaking.Major.Minor`

As progress is made to the language, the version number changes according to the scale of changes made.

-   Minor changes
    -   Adding a word, compound word, or phrase
    -   Adding a definition to an existing word
-   Major changes
    -   Adding new backwards-compatible grammar
    -   Changing the text of definition in a way that is not breaking changes
-   Breaking changes
    -   Removing words
    -   Changing the meaning of words
-   Establishing changes
    -   Changing the status of the language

> While the Establishing version of Minno is 0, it is still in a developmental mode. The likelihood of Breaking changes will be pretty high. After that, the number will only change with dramatic changes, and Breaking changes will be kept to a minimum.

## Chapter 1 - Language Structure
---
### 1.0 - Letters
Minno phrases can be broken down into words, which can be broken down into letters. Letters can be combined into single syllable chunks, which are words. If you are familiar with Hangul (The Korean script), Minno composition is similar. Read from left to right then top to bottom, each word can be represented with a couple of letters. This differs from English, where letters are placed solely next to each other left-right. Unlike Hanzi or Kanji, where characters, built from radicals, construct meanings, Minno letters represent sounds.

There are 18 letters in Minno, 12 of which are consonants and 6 of which are vowels. Below are shown each letter. The "Minno Script" column is what the letter looks like, visually. The easiest way to record the script digitally is to use Minno's romanization. More on this technique is documented below. In the chart, each letter has its approximated [IPA letter](https://www.ipachart.com), which can help in figuring out how to pronounce it. English speakers can also use the "English Ref" column, where the underlined section of the word matches the pronunciation pretty well.

| Minno Script | IPA Approx. | English Ref | Romanization |
|:------------:|:-----------:| ----------- |:------------:|
|      ㅣ      |      a      | Vietn**a**m |      a       |
|      ㅡ      |      ə      | D**u**mb    |      w       |
|      ㅜ      |      e      | Sp**e**ll   |      e       |
|      ㅗ      |      u      | M**oo**n    |      u       |
|      ㅏ      |      i      | S**ee**     |      i       |
|      ㅓ      |      o      | R**o**le    |      o       |
|      ㅇ      |      s      | **S**ad     |      s       |
|      v       |      f      | **F**un     |      f       |
|      ㅁ      |      ʃ      | **Sh**ed    |      x       |
|      ㄱ      |      m      | **M**int    |      m       |
|      ⊓       |      p      | **P**ool    |      p       |
|      ㄴ      |      ŋ      | Pi**ng**    |      q       |
|      ㄷ      |      t      | **T**in     |      t       |
|      𖼇       |      k      | **K**ill    |      k       |
|      ⊔       |      b      | **B**in     |      b       |
|      ⅃       |      n      | **N**ame    |      n       |
|      ⊐       |      ɾ      | Sad**l**y   |      l       |
|      ㅅ      |      χ      | **H**orse   |      h       |

^letters

[minno.birla.io](https://minno.birla.io) <- This is legacy as long as there is no version on the page

To represent digitally, Minno can be written in certain characters from the Latin Alphabet, called romanization.

***Minno has no concept of capitalization.***

### 1.1 - Romanization
Minno romanization looks quite awkward to English eyes, as words are short and simple, so to those unfamiliar with Minno, it may appear to be quite unwieldy.

#### Romanization Examples
| English (translation)      | Romanization        |
| -------------------------- | ------------------- |
| I am here.                 | mo li no.           |
| How many dogs do you have? | ti luo pe nu xu ne? |
| Where is your friend!?     | po sat ti li ne!?   |

The sounds that romanized Minno represents are, for the most part, fairly accurate. By using the [[#^letters|chart in section 1.0]], each letter can be mapped to both their Minno script counterpart and how to pronounce them.

***Ignore the following section if you don't want your mind to explode from shenanigans***

There exists a more "stylish" romanization of Minno, which can also help those who don't know what certain characters sound like use the right sounds. For example, "x" and "q" could easily be mistaken as "ks" and "ck", not "sh" and "ng". As long as there is a vowel in the word, these combos can be swapped:

| Romanization | Character | Example                                                  |
| ------------ | --------- | -------------------------------------------------------- |
| oh           | o         | "I'm me" (mo ma mo - moh ma moh)                         |
| ng           | q         | "When's the test?" (qol te ne - ngol te ne)              |
| sh           | x         | "I like water" (mo sat xei - moh sat shei)               |
| uh           | w         | "What's the hour?" (tsw ne - tsuh ne)                    |
| wa           | ua        | "What's this about?" (no ua ne - noh wa ne)              |
| oo           | u         | "Did you solve it?" (sum la ne - soom la ne)             |
| ee           | i         | "It was smaller" (um ki la - oom kee la)                 |
| wi           | ui        | "He's evil" (nal uim - nal weem)                         |
| y            | i         | "Hey!" (ia! - ya!)                                       |
| we           | ue        | "Why are you here?" (ti li no ue ne - tee lee noh we ne) |
| wo           | uo        | "How many do you have?" (ti luo xu ne - tee lwo shoo ne) |
| ow           | ou        | "Get more" (bo luo tou - boh lwo tow)                    |

### 1.2 - Hangul-ization
For decorative purposes, it’s also possible to use Hangul to represent Minno. It’s quite tricky and cheeky, and has little point, but it tries to represent words as characters instead of longer constructions.

| Romanization | Hangul-ization |
| ------------ | -------------- |
| a            | 아             |
| w            | 으             |
| e            | 에             |
| u            | 우             |
| i            | 이             |
| o            | 오             |
| s            | ㅅ             |
| f            | ㅊ             |
| x            | ㅈ             |
| m            | ㅁ             |
| p            | ㅍ             |
| q            | ㅇ/ㅌ (틍=qwq) |
| t            | ㄷ             |
| k            | ㄱ             |
| b            | ㅂ             |
| n            | ㄴ             |
| l            | ㄹ             |
| h            | ㅎ             |
| au           | 애             |
| ou           | 어             |
| oa           | 와             |
| ue           | 웨             |
| uo           | 워             |
| ia           | 야             |
| ai           | 예             |
| oi           | 오*            |
| ei           | 에*            |
| io           | 요             |
| iu           | 유             |
| ts           | ㅆ             |
| tx           | ㅉ             |

### 1.3 - Words
As previously mentioned, all Minno words are single syllables. Words roughly follow the scheme shown below, where the italic text is required for every word.

**consonant cluster - _vowel_ - vowel - vowel - consonant**

There are a few consonant clusters that are made up by multiple consonants, notably `ts` and `tx`. Other consonant clusters are lone consonants. While each word is only one syllable, there are many concepts that use multiple words to achieve a meaning. Another way to visualize this is `mmAaam`, where `a` is a vowel, `m` is a consonant, and uppercase is required. The minimum number of letters in a word is 1, and the maximum is 6. However, many concepts are made up of multiple words.

| English  | Romanization |
| -------- | ------------ |
| location | li           |
| this     | no           |
| here     | li no        |
| time     | te           |
| now      | te no        |

### 1.4 - Punctuation
Minno sentences usually end with punctuation, to separate complete thoughts. The two punctuation symbols that end sentences are "." and "!". The period punctuation is similar to periods in other languages, that is technically used in the "!" marker, as the "!" marker is a combination of "ㅣ" and "." Exclamation in Minno is spoken, as an "a" at the end of exclaimed sentences.

The "?" punctuation isn’t needed, as instead sentences only use a single "." and include the question word ("ne") within the phrase. However, sometimes "ne" isn't needed and is inferred by tone of voice, so the "?" can be useful.

| English       | Romanization |
| ------------- | ------------ |
| I am good!    | mo pa mat!   |
| You are good. | ti pa mat.   |
| How are you?  | pa mat ne.   |

Punctuation to outline names, titles, similarly to quotation marks, are "<" and ">". They are also used as brackets to contain separate ideas, sometimes.

| English          | Romanization    |
| ---------------- | --------------- |
| My name is Ippo. | mo nom \<ip po\>. |

The ":" symbol can be used as side-notes within phrases, and also formatting within writing.

| English                | Romanization        |
| ---------------------- | ------------------- |
| 1. Cat 2. Dog          | s: muei nu f: pe nu |
| I am (sometimes) here. | mo li :ten men: no  |

- [ ] **TODO**: Figure out what “..”, “...”, “,” “=”, “+”, “/”, “\”, etc. things do, if any at all.

## Chapter 2 - Grammar
---
### 2.0 - Parts of Speech
Minno words can generally have two states: Entities and Modifiers (mods). The exception to this are marker words, e.g “a”, “o”, “i”, “e”, Etc. Most words are both entities and mods, changing use based on context but with very similar meaning.

Entities are most similar to nouns of English. They represent objects, places, items, pretty much any “thing”. Mods are most similar to verbs of English, but can be treated very similarly to adjectives. Markers aren’t either of these, and have special purposes.

### 2.1 - Entities
Entities are similar to english nouns. They represent any kind of “thing”.

| English   | Romanization |
| --------- | ------------ |
| you       | ti           |
| food      | fam          |
| occurence | ten          |

#### 2.1.1 - Entity Structure
Entities in sentences can have the following structure:
1.  Entity Marker (o)
2.  Word _(the word itself)_
3.  Entity **used** by this entity
4.  Mod of the entity
5.  Mod of the entity...

| English      | Romanization    | Structure                                                                             | Structure with English                                            |
| ------------ | --------------- | ------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Here         | li no           | (Entity word) (mod of entity)                                                         | (location) (is this)                                              |
| My dog       | pe nu mo        | (entity word) (entity used by entity) (mod of entity)                                 | (dog = (four) (animal)) (is mine)                                 |
| My large cat | o muei nu um mo | (entity marker) (entity word) (entity used by entity) (mod of entity) (mod of entity) | (this is an entity) (cat = (sound) (animal)) (is large) (is mine) |

Usually, when an entity is used by another entity, it creates a different concept. Often these combinations are obvious even if you've never heard them, but not always. For example, the words "dog" and "cat" are not obvious, but words like "student" are.

These are called compound words.

| English | Romanization |
| ------- | ------------ |
| Person  | po           |
| Learn   | sem          |
| Student | po sem       |
| Animal  | nu           |
| Four    | pe           |
| Dog     | pe nu        |
| Sound   | muei         |
| Cat     | muei nu      |

### 2.2 - Mods
Mods can be seen as a blend of English verbs and adjectives. In Minno, mods act as "modifications" for entities (or mods, sometimes even phrases).

| English | Romanization |
| ------- | ------------ |
| to make | kan          |
| to end  | tak          |
| your    | ti           |

#### 2.2.1 - Mod Structure
Mods in sentences can have the following structure:
1.  Entity/mod/phrase modified by word
2.  Mod Marker (i)
3.  Word _(the word itself)_
4.  Mod of the mod
5.  Mod of the mod...
6.  Entity used by this mod
7.  Mod of the mod
8.  Mod of the mod...

| English                        | Romanization                 | Structure                                                                                                                                     | Structure with English                                                                                   |
| ------------------------------ | ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| I like you                     | mo sat ti                    | (entity) (mod of entity) (entity used by mod)                                                                                                 | (me) (is liking) (you)                                                                                   |
| I will explore everywhere      | sim ka li ta                 | \<omitted entity\> (mod of entity) (mod of mod) (entity used by mod) (mod of entity)                                                          | \<me\> (is exploring) (is in the future) (location) (is all of them)                                     |
| That red dog changes sometimes | pe nu piq en nal nem ten men | (entity a) (entity used by entity a) (mod of entity a) (entity used by mod) (mod of entity a) (mod of entity a) (mod b of mod) (mod of mod b) | (dog = (four) (animal)) (is colored) (red) (is that one) (is changing) (sometimes = (occurs) (multiple)) |

### 2.3 - Markers
Markers are all single vowel words that are like mods but do not function within the normal effects of mods.

Read more: [Markers](markers/Markers.md)

## Chapter 3 - Common Concepts
---
### 3.1 - Numbers
- [ ] Todo

**ENTITY**
-   none*
    -   *Numbers often use other items to form independent ideas: for example, _pe nu_ means dog, but _pe_ means 4.

**MOD**

- \[entity\] has quantity \<number\>
	- _e.g "mo luo nu xw" | "I have 2 animals"_
	- This can also be more explicit by using _xu_, a word that means "number" and "has quantity", similar to numbers.
- \[entity\] _u_ is index \<number\>
    - _e.g_ _"mo u tu" | "I'm sixth"_
    - This other meaning relies on the marker _u_, which changes the meaning of the number from "quantity" to "index".

Minno uses a base-12 number system, but when in close proximity to english, the letter `z` can be used in front to indicate base-10.

There is also a way to say base-10 numbers aloud, TODO

## 3.2 - Questions
All questions surround the marker word "ne". While in the place of an entity, it indicates that the audience should answer what the entity is. While as a mod of a mod, it puts the mod word in to question, asking for details or if it happened. While as a mod of an entity, it needs to use another entity and asks whether they are the same.

**ENTITY**
- \<what\>
    - _e.g "ti sat ne?" | "what do you like"_

**MOD**
- \[mod\] \<is a question\>
	- _e.g "ti li no ne?" | "are you here?"_
- \[entity\] <is?> \[entity\]
	- _e.g "ti ne nal?" | "are you him?"_

Questions don't necessarily need "ne" sometimes, but really only when it's very very obvious to be a question.

## Chapter 1000 - Dump

**<mark style="background: #FF5582A6;">The murder</mark> <mark style="background: #FFF3A3A6;">hornet</mark> <mark style="background: #CACFD9A6;">was</mark> <mark style="background: #BBFABBA6;">disappointed</mark> <mark style="background: #D2B3FFA6;">by</mark> <mark style="background: #FFB8EBA6;">the preconceived ideas</mark> <mark style="background: #ADCCFFA6;">people</mark> <mark style="background: #FFB86CA6;">had</mark> <mark style="background: #FF5582A6;">of</mark> <mark style="background: #ABF7F7A6;">him</mark> .**
	<mark style="background: #FFF3A3A6;">누비허갈움</mark> <mark style="background: #FF5582A6;">닥엔</mark> <mark style="background: #BBFABBA6;">파귿왈</mark> <mark style="background: #CACFD9A6;">라</mark> <mark style="background: #D2B3FFA6;">웨</mark> <mark style="background: #FFB8EBA6;">오왈윔</mark> <mark style="background: #FFB86CA6;">워</mark> <mark style="background: #ADCCFFA6;">포멘</mark> <mark style="background: #FF5582A6;">둘</mark> <mark style="background: #ABF7F7A6;">날</mark> .
	<mark style="background: #FFF3A3A6;">nu bi hou kal um</mark> <mark style="background: #FF5582A6;">tak en</mark> <mark style="background: #BBFABBA6;">pa kwt ual</mark> <mark style="background: #CACFD9A6;">la</mark> <mark style="background: #D2B3FFA6;">ue</mark> <mark style="background: #FFB8EBA6;">o ual uim</mark> <mark style="background: #FFB86CA6;">uo</mark> <mark style="background: #ADCCFFA6;">po men</mark> <mark style="background: #FF5582A6;">tul</mark> <mark style="background: #ABF7F7A6;">nal</mark> .

**She did a happy dance because all of the socks from the dryer matched.**
	날럄왕솨삳쪼라웨맆핟대렘다개볼릳뭐이롤.
	nal liam uaq soa sat txo la ue lip hat tau lem ta kau bol lit muo i lol.

**Twin 4-month-olds slept in the shade of the palm tree while the mother tanned in the sun.**
	멩추엔잎들댬ㅍ짜라리혼나워루러찰딘웸보핑힘.
	meq fu en ip twl tiam p txa la li hon na uo lu tou fal tin uem bo piq him.

**Wisdom is easily acquired when hiding under the bed with a saucepan on your head.**
	알파만마보뤄촫기딘칟파링웽두팔짜뤄팝보참웩차핟대앚.
	al pa man ma bo luo foat ki tin fit pa liq ueq tu pal txa luo pab bo fam uek fa hat tao ax.

**Honestly, I didn't care much for the first season, so I didn't bother with the second.**
	터상, 앚라나냔레차, 에웨복라나냔즈.
	qou saq, ax la na nian le fa, e ue bok la na nian xw.

**I’m alive like you are!**
	모엔둘릭디!
	mo en tul lik ti!

**I’m also alive!**
	모잎릭엔!
	mo ip lik en!

**I covered my friend in baby oil.**
	mo miwt la muo en fun san meq tul po saq.
	모믇\*라뭐엔춘산멩둘포상.