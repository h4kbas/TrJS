# TrJS [![CircleCI](https://circleci.com/gh/h4kbas/TrJS/tree/master.svg?style=svg)](https://circleci.com/gh/h4kbas/TrJS/tree/master)
A Library That Uses Turkish Grammar and Composes Turkish Sentences. It supports all features of Turkish such as consonant harmony and vowel harmony.

This is so simple to use it. Here is a sample

```javascript
const Verb = require('./Verb.js');

let v = new Verb('al');
v.Tense('Genis','Ben','+?');
console.log(v.text);
```
First of all, you have Verb class and while constructing, you give the root of the Turkish verb. Here in this example "al" is the root of the verb which means "buy". Then, you call the Tense function with the parameters (Tensename, Subject, Positive/Negative or Its Question Forms)

### Supported Forms:

* +: Positive
* -: Negative
* +?: Positive Question
* -?: Negative Question

### Supported Tenses and English Equivalents

* Genis: Simple Present Tense
* Simdiki: Present Cont. Tense
* Gelecek: Simple Future Tense
* GGecmis: Simple Past Tense(As interpretation)
* DGecmis: Simple Past Tense(As interpretation)
* Emir: Imperative
* Gereklilik: Necessitative 
* Istek: Optative Mood
* Sart: Conditional Mood 


## Important!
Its new version only supports Verbs for now. However, I am intented to add other features ASAP. If you need them, you can use the old version but please consider that it is no longer developed.

