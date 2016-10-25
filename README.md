# NLP
1. 术语解释
Phonetics and phonology - the study of sounds
– Morphology - the study of word components
– Syntax - the study of sentence and phrase structure
– Lexical semantics - the study of the meanings of words
– Compositional semantics - how to combine words
– Pragmatics - how to accomplish goals（语言实用学）
– Discourse conventions - how to deal with units larger than utterances
part of speech tagging 词性标注（名词/动词/..）
parse 语法解析
pronouns 前置名词定语
determiner 限定词
Coordinating conjunctions – and, or, but
Subordinating conjunctions – if, because, that, although

Verb
The dog sleeps (intransitive)
The dog chased the cat (transitive)
Mary gave the dog a bone (ditransitive)

NN /* singular noun */
IN /* preposition */
AT /* article */
NP /* proper noun */
JJ /* adjective */
, /* comma */
NNS /* plural noun */
CC /* conjunction */
RB /* adverb */
VB /* un-inflected verb */
VBN /* verb +en (taken, looked (passive,perfect)) */
VBD /* verb +ed (took, looked (past tense)) */
CS /* subordinating conjunction */ 


2.text similarity
Many types of text similarity exist:
–Morphological similarity (e.g., respect-respectful)
– Spelling similarity (e.g., theater-theatre)
– Synonymy (e.g., talkative-chatty)
– Homophony (e.g., raise-raze-rays)
– Semantic similarity (e.g., cat-tabby)
– Sentence similarity (e.g., paraphrases)
– Document similarity (e.g., two news stories on the same
event)
– Cross-lingual similarity (e.g., Japan-Nihon)

Morphologocal similarity:(stemming)
To stem a word is to reduce it to a base form,called the stem, after removing various sufxesand endings and sometimes, performing some additional transformations

Porter’s Algorithm:
The measure of a word is an indication of the number of syllables in it
- Each sequence of consonants is denoted by C
– Each sequence of vowels is denoted as V
– The initial C and the final V are optional
– So, each word is represented as [C]VCVC ... [V],or [C](VC){k}[V], where k is its measure

• The initial word is then checked against a sequence of transformation patterns, in order.
• Whenever a pattern matches, the word is transformed and the algorithm restarts from the beginning of the list of
patterns with the transformed word.
• If no pattern matches, the algorithm stops and outputs the most recently transformed version of the word.









 






