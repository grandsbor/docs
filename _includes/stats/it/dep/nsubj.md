

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Italian)

This relation is universal.

12434 nodes (4%) are attached to their parents as `nsubj`.

9441 instances of `nsubj` (76%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.83971368827409.

The following 42 pairs of parts of speech are connected with `nsubj`: [it-pos/VERB]()-[it-pos/NOUN]() (5666; 46% instances), [it-pos/VERB]()-[it-pos/PRON]() (2646; 21% instances), [it-pos/VERB]()-[it-pos/PROPN]() (1752; 14% instances), [it-pos/ADJ]()-[it-pos/NOUN]() (620; 5% instances), [it-pos/PRON]()-[it-pos/NOUN]() (496; 4% instances), [it-pos/NOUN]()-[it-pos/NOUN]() (398; 3% instances), [it-pos/NOUN]()-[it-pos/PROPN]() (167; 1% instances), [it-pos/PRON]()-[it-pos/PROPN]() (148; 1% instances), [it-pos/NOUN]()-[it-pos/PRON]() (138; 1% instances), [it-pos/ADJ]()-[it-pos/PRON]() (109; 1% instances), [it-pos/ADJ]()-[it-pos/PROPN]() (70; 1% instances), [it-pos/PROPN]()-[it-pos/NOUN]() (40; 0% instances), [it-pos/VERB]()-[it-pos/NUM]() (33; 0% instances), [it-pos/PRON]()-[it-pos/PRON]() (23; 0% instances), [it-pos/NUM]()-[it-pos/NOUN]() (19; 0% instances), [it-pos/VERB]()-[it-pos/ADJ]() (19; 0% instances), [it-pos/ADV]()-[it-pos/NOUN]() (12; 0% instances), [it-pos/VERB]()-[it-pos/VERB]() (11; 0% instances), [it-pos/NOUN]()-[it-pos/NUM]() (9; 0% instances), [it-pos/AUX]()-[it-pos/NOUN]() (7; 0% instances), [it-pos/PROPN]()-[it-pos/PRON]() (7; 0% instances), [it-pos/ADV]()-[it-pos/PRON]() (5; 0% instances), [it-pos/PROPN]()-[it-pos/PROPN]() (4; 0% instances), [it-pos/VERB]()-[it-pos/SYM]() (4; 0% instances), [it-pos/AUX]()-[it-pos/PROPN]() (3; 0% instances), [it-pos/NOUN]()-[it-pos/VERB]() (3; 0% instances), [it-pos/VERB]()-[it-pos/ADV]() (3; 0% instances), [it-pos/ADJ]()-[it-pos/NUM]() (2; 0% instances), [it-pos/ADV]()-[it-pos/PROPN]() (2; 0% instances), [it-pos/NOUN]()-[it-pos/ADJ]() (2; 0% instances), [it-pos/NOUN]()-[it-pos/ADV]() (2; 0% instances), [it-pos/NUM]()-[it-pos/PRON]() (2; 0% instances), [it-pos/VERB]()-[it-pos/X]() (2; 0% instances), [it-pos/X]()-[it-pos/NOUN]() (2; 0% instances), [it-pos/ADJ]()-[it-pos/ADJ]() (1; 0% instances), [it-pos/ADJ]()-[it-pos/SYM]() (1; 0% instances), [it-pos/AUX]()-[it-pos/PRON]() (1; 0% instances), [it-pos/PRON]()-[it-pos/ADJ]() (1; 0% instances), [it-pos/PRON]()-[it-pos/NUM]() (1; 0% instances), [it-pos/PRON]()-[it-pos/VERB]() (1; 0% instances), [it-pos/PUNCT]()-[it-pos/NOUN]() (1; 0% instances), [it-pos/SYM]()-[it-pos/NOUN]() (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 3 nsubj	color:blue
1	Tutti	tutto	DET	T	Gender=Masc|Number=Plur|PronType=Predet	3	det:predet	_	_
2	gli	il	DET	RD	Definite=Def|Gender=Masc|Number=Plur|PronType=Art	3	det	_	_
3	esseri	essere	NOUN	S	Gender=Masc|Number=Plur	5	nsubj	_	_
4	umani	umano	ADJ	A	Gender=Masc|Number=Plur	3	amod	_	_
5	sanno	sapere	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
6	di	di	ADP	E	_	9	mark	_	_
7	poter	potere	AUX	VM	VerbForm=Inf	9	aux	_	_
8	essere	essere	VERB	V	VerbForm=Inf	9	cop	_	_
9	più	più	ADV	B	_	5	xcomp	_	_
10	di	di	ADP	E	_	11	case	_	_
11	ciò	ciò	PRON	PD	Gender=Masc|Number=Sing|PronType=Dem	9	nmod	_	_
12	che	che	PRON	PR	PronType=Rel	13	nsubj	_	_
13	sono	essere	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	11	acl:relcl	_	SpaceAfter=No
14	.	.	PUNCT	FS	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 13 12 nsubj	color:blue
1	Tutti	tutto	DET	T	Gender=Masc|Number=Plur|PronType=Predet	3	det:predet	_	_
2	gli	il	DET	RD	Definite=Def|Gender=Masc|Number=Plur|PronType=Art	3	det	_	_
3	esseri	essere	NOUN	S	Gender=Masc|Number=Plur	5	nsubj	_	_
4	umani	umano	ADJ	A	Gender=Masc|Number=Plur	3	amod	_	_
5	sanno	sapere	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
6	di	di	ADP	E	_	9	mark	_	_
7	poter	potere	AUX	VM	VerbForm=Inf	9	aux	_	_
8	essere	essere	VERB	V	VerbForm=Inf	9	cop	_	_
9	più	più	ADV	B	_	5	xcomp	_	_
10	di	di	ADP	E	_	11	case	_	_
11	ciò	ciò	PRON	PD	Gender=Masc|Number=Sing|PronType=Dem	9	nmod	_	_
12	che	che	PRON	PR	PronType=Rel	13	nsubj	_	_
13	sono	essere	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	11	acl:relcl	_	SpaceAfter=No
14	.	.	PUNCT	FS	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 3 nsubj	color:blue
1	"	"	PUNCT	FB	_	5	punct	_	SpaceAfter=No
2	La	il	DET	RD	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	3	det	_	_
3	Pivetti	Pivetti	PROPN	SP	_	5	nsubj	_	_
4	ha	avere	AUX	VA	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	5	aux	_	_
5	fatto	fare	VERB	V	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	0	root	_	_
6	benissimo	bene	ADV	B	Degree=Abs	5	advmod	_	_
7	a	a	ADP	E	_	8	mark	_	_
8	decidere	decidere	VERB	V	VerbForm=Inf	5	xcomp	_	_
9	di	di	ADP	E	_	10	case	_	_
10	testa	testa	NOUN	S	Gender=Fem|Number=Sing	8	nmod	_	_
11	sua	suo	DET	AP	Gender=Fem|Number=Sing|Poss=Yes|PronType=Prs	10	det:poss	_	SpaceAfter=No
12	.	.	PUNCT	FS	_	5	punct	_	_

~~~


