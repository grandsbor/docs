

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Latin)

This relation is universal.

5326 nodes (11%) are attached to their parents as `nmod`.

2859 instances of `nmod` (54%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.50563274502441.

The following 33 pairs of parts of speech are connected with `nmod`: [la-pos/VERB]()-[la-pos/NOUN]() (2713; 51% instances), [la-pos/NOUN]()-[la-pos/NOUN]() (1638; 31% instances), [la-pos/VERB]()-[la-pos/PRON]() (390; 7% instances), [la-pos/ADJ]()-[la-pos/NOUN]() (203; 4% instances), [la-pos/VERB]()-[la-pos/VERB]() (65; 1% instances), [la-pos/ADV]()-[la-pos/NOUN]() (63; 1% instances), [la-pos/PRON]()-[la-pos/NOUN]() (43; 1% instances), [la-pos/VERB]()-[la-pos/ADJ]() (41; 1% instances), [la-pos/ADJ]()-[la-pos/PRON]() (36; 1% instances), [la-pos/PUNCT]()-[la-pos/NOUN]() (20; 0% instances), [la-pos/VERB]()-[la-pos/ADV]() (18; 0% instances), [la-pos/NOUN]()-[la-pos/PRON]() (13; 0% instances), [la-pos/NUM]()-[la-pos/NOUN]() (10; 0% instances), [la-pos/VERB]()-[la-pos/INTJ]() (10; 0% instances), [la-pos/ADJ]()-[la-pos/VERB]() (9; 0% instances), [la-pos/CONJ]()-[la-pos/NOUN]() (9; 0% instances), [la-pos/NOUN]()-[la-pos/VERB]() (7; 0% instances), [la-pos/SCONJ]()-[la-pos/NOUN]() (6; 0% instances), [la-pos/VERB]()-[la-pos/X]() (6; 0% instances), [la-pos/ADV]()-[la-pos/VERB]() (4; 0% instances), [la-pos/CONJ]()-[la-pos/VERB]() (3; 0% instances), [la-pos/INTJ]()-[la-pos/NOUN]() (3; 0% instances), [la-pos/PRON]()-[la-pos/PRON]() (3; 0% instances), [la-pos/PRON]()-[la-pos/VERB]() (2; 0% instances), [la-pos/SCONJ]()-[la-pos/VERB]() (2; 0% instances), [la-pos/X]()-[la-pos/NOUN]() (2; 0% instances), [la-pos/ADJ]()-[la-pos/X]() (1; 0% instances), [la-pos/CONJ]()-[la-pos/PRON]() (1; 0% instances), [la-pos/NOUN]()-[la-pos/ADJ]() (1; 0% instances), [la-pos/SCONJ]()-[la-pos/PRON]() (1; 0% instances), [la-pos/VERB]()-[la-pos/CONJ]() (1; 0% instances), [la-pos/VERB]()-[la-pos/NUM]() (1; 0% instances), [la-pos/X]()-[la-pos/PRON]() (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 8 nmod	color:blue
1	Curris	curro1	VERB	v2spia---	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
2	,	comma1	PUNCT	u--------	_	1	punct	_	_
3	stupes	stupeo1	VERB	v2spia---	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	1	conj	_	_
4	,	comma1	PUNCT	u--------	_	1	punct	_	_
5	satagis	satago1	VERB	v2spia---	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	1	conj	_	_
6	,	comma1	PUNCT	u--------	_	8	punct	_	_
7	tanquam	tamquam1	ADV	d--------	_	8	mark	_	_
8	mus	mus1	NOUN	n-s---mn-	Case=Nom|Gender=Masc|Number=Sing	1	nmod	_	_
9	in	in1	ADP	r--------	_	10	case	_	_
10	matella	matella1	NOUN	n-s---fb-	Case=Abl|Gender=Fem|Number=Sing	8	nmod	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 10 nmod	color:blue
1	Curris	curro1	VERB	v2spia---	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
2	,	comma1	PUNCT	u--------	_	1	punct	_	_
3	stupes	stupeo1	VERB	v2spia---	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	1	conj	_	_
4	,	comma1	PUNCT	u--------	_	1	punct	_	_
5	satagis	satago1	VERB	v2spia---	Mood=Ind|Number=Sing|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	1	conj	_	_
6	,	comma1	PUNCT	u--------	_	8	punct	_	_
7	tanquam	tamquam1	ADV	d--------	_	8	mark	_	_
8	mus	mus1	NOUN	n-s---mn-	Case=Nom|Gender=Masc|Number=Sing	1	nmod	_	_
9	in	in1	ADP	r--------	_	10	case	_	_
10	matella	matella1	NOUN	n-s---fb-	Case=Abl|Gender=Fem|Number=Sing	8	nmod	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 nmod	color:blue
1	Si	si1	SCONJ	c--------	_	5	mark	_	_
2	quid	quis2	PRON	p-s---na-	Case=Acc|Gender=Neut|Number=Sing	5	dobj	_	_
3	ab	ab1	ADP	r--------	_	4	case	_	_
4	illa	ille1	PRON	p-s---fb-	Case=Abl|Gender=Fem|Number=Sing	5	nmod	_	_
5	petii	peto1	VERB	v1sria---	Aspect=Perf|Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin|Voice=Act	9	advcl	_	_
6	,	comma1	PUNCT	u--------	_	5	punct	_	_
7	nunquam	numquam1	ADV	d--------	_	9	advmod	_	_
8	mihi	ego1	PRON	p-s---md-	Case=Dat|Gender=Masc|Number=Sing	9	dobj	_	_
9	negatum	nego1	VERB	v-srppnn-	Aspect=Perf|Case=Nom|Gender=Neut|Number=Sing|Tense=Past|VerbForm=Part|Voice=Pass	0	root	_	_

~~~




--------------------------------------------------------------------------------

## Treebank Statistics (UD_Latin-ITTB)

This relation is universal.

37913 nodes (13%) are attached to their parents as `nmod`.

20505 instances of `nmod` (54%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.06156199720413.

The following 42 pairs of parts of speech are connected with `nmod`: [la-pos/VERB]()-[la-pos/NOUN]() (10217; 27% instances), [la-pos/NOUN]()-[la-pos/NOUN]() (10177; 27% instances), [la-pos/NOUN]()-[la-pos/PRON]() (8481; 22% instances), [la-pos/VERB]()-[la-pos/PRON]() (4228; 11% instances), [la-pos/ADJ]()-[la-pos/NOUN]() (1010; 3% instances), [la-pos/NOUN]()-[la-pos/PROPN]() (740; 2% instances), [la-pos/ADJ]()-[la-pos/PRON]() (662; 2% instances), [la-pos/PRON]()-[la-pos/PRON]() (417; 1% instances), [la-pos/PRON]()-[la-pos/NOUN]() (412; 1% instances), [la-pos/VERB]()-[la-pos/PROPN]() (376; 1% instances), [la-pos/ADV]()-[la-pos/NOUN]() (252; 1% instances), [la-pos/NUM]()-[la-pos/NOUN]() (223; 1% instances), [la-pos/NUM]()-[la-pos/X]() (129; 0% instances), [la-pos/NUM]()-[la-pos/PRON]() (90; 0% instances), [la-pos/ADV]()-[la-pos/PRON]() (86; 0% instances), [la-pos/PROPN]()-[la-pos/PRON]() (75; 0% instances), [la-pos/X]()-[la-pos/X]() (72; 0% instances), [la-pos/NUM]()-[la-pos/PROPN]() (41; 0% instances), [la-pos/PRON]()-[la-pos/PROPN]() (38; 0% instances), [la-pos/ADJ]()-[la-pos/PROPN]() (37; 0% instances), [la-pos/NOUN]()-[la-pos/X]() (25; 0% instances), [la-pos/PROPN]()-[la-pos/NOUN]() (24; 0% instances), [la-pos/CONJ]()-[la-pos/NOUN]() (21; 0% instances), [la-pos/PROPN]()-[la-pos/PROPN]() (20; 0% instances), [la-pos/X]()-[la-pos/NOUN]() (14; 0% instances), [la-pos/ADP]()-[la-pos/NOUN]() (6; 0% instances), [la-pos/DET]()-[la-pos/PRON]() (6; 0% instances), [la-pos/NOUN]()-[la-pos/ADP]() (6; 0% instances), [la-pos/PRON]()-[la-pos/X]() (5; 0% instances), [la-pos/X]()-[la-pos/PRON]() (5; 0% instances), [la-pos/ADP]()-[la-pos/PRON]() (4; 0% instances), [la-pos/CONJ]()-[la-pos/PRON]() (2; 0% instances), [la-pos/NOUN]()-[la-pos/SCONJ]() (2; 0% instances), [la-pos/PUNCT]()-[la-pos/NOUN]() (2; 0% instances), [la-pos/AUX]()-[la-pos/NOUN]() (1; 0% instances), [la-pos/NOUN]()-[la-pos/ADJ]() (1; 0% instances), [la-pos/NOUN]()-[la-pos/CONJ]() (1; 0% instances), [la-pos/PRON]()-[la-pos/CONJ]() (1; 0% instances), [la-pos/PROPN]()-[la-pos/X]() (1; 0% instances), [la-pos/VERB]()-[la-pos/ADP]() (1; 0% instances), [la-pos/VERB]()-[la-pos/X]() (1; 0% instances), [la-pos/X]()-[la-pos/PROPN]() (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 4 nmod	color:blue
1	et	et	CONJ	O4|stRL	_	7	cc	_	_
2	circa	circa	ADP	S4|stRL	AdpType=Prep	4	case	_	_
3	eius	is	PRON	F1|grn1|casB|gen2|vgr2|stPV	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing|PronType=Dem,Prs	4	nmod	_	_
4	considerationem	consideratio	NOUN	C1|grn1|casD|gen2|vgr1|stAC	Case=Acc|Degree=Pos|Gender=Fem|Number=Sing	7	nmod	_	_
5	principaliter	principalis	ADJ	C1|grn1|casG|stAN	Case=Loc|Degree=Pos|Number=Sing	7	advmod	_	_
6	sapientiam	sapientia	NOUN	A1|grn1|casD|gen2|vgr1|stAC	Case=Acc|Degree=Pos|Gender=Fem|Number=Sing	7	nsubj	_	_
7	insistere	insisto	VERB	L3|modH|tem1|stAV	Tense=Pres|VerbForm=Inf|Voice=Act	0	root	_	_
8	.	.	PUNCT	Punc	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 nmod	color:blue
1	oportet	oportet	VERB	K3|modA|tem1|gen6|stAV	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
2	igitur	igitur	ADV	O4|stRL	_	1	advmod	_	_
3	ultimum	ulterior	ADJ	B1|grn3|casD|gen1|stAN	Case=Acc|Degree=Sup|Gender=Masc|Number=Sing	4	amod	_	_
4	finem	finis	NOUN	C1|grn1|casD|gen1|stRS	Case=Acc|Degree=Pos|Gender=Masc|Number=Sing	7	nsubj	_	_
5	universi	universus	ADJ	B1|grn1|casB|gen1|stAN	Case=Gen|Degree=Pos|Gender=Masc|Number=Sing	4	amod	_	_
6	esse	sum	VERB	N3|modH|tem1|stAV	Tense=Pres|VerbForm=Inf|Voice=Act	7	cop	_	_
7	bonum	bonum	NOUN	B1|grn1|casD|gen3|stAN	Case=Acc|Degree=Pos|Gender=Neut|Number=Sing	1	csubj	_	_
8	intellectus	intellectus	NOUN	D1|grn1|casB|gen1|stAC	Case=Gen|Degree=Pos|Gender=Masc|Number=Sing	7	nmod	_	_
9	.	.	PUNCT	Punc	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 nmod	color:blue
1	finis	finis	NOUN	C1|grn1|casA|gen1|stRS	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	4	nsubj	_	_
2	enim	enim	ADV	O4|stRL	_	4	advmod	_	_
3	est	sum	VERB	N3|modA|tem1|gen6|stAV	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	4	cop	_	_
4	bonum	bonum	NOUN	B1|grn1|casA|gen3|stAN	Case=Nom|Degree=Pos|Gender=Neut|Number=Sing	0	root	_	_
5	uniuscuiusque	unusquisque	PRON	F1|grn1|casB|gen3|vgr1|stPV	Case=Gen|Degree=Pos|Gender=Neut|Number=Sing|PronType=Ind	4	nmod	_	_
6	.	.	PUNCT	Punc	_	4	punct	_	_

~~~




--------------------------------------------------------------------------------

## Treebank Statistics (UD_Latin-PROIEL)

This relation is universal.

21932 nodes (13%) are attached to their parents as `nmod`.

11719 instances of `nmod` (53%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.05735910997629.

The following 54 pairs of parts of speech are connected with `nmod`: [la-pos/NOUN]()-[la-pos/PRON]() (5282; 24% instances), [la-pos/VERB]()-[la-pos/NOUN]() (5126; 23% instances), [la-pos/NOUN]()-[la-pos/NOUN]() (3892; 18% instances), [la-pos/NOUN]()-[la-pos/ADJ]() (2375; 11% instances), [la-pos/VERB]()-[la-pos/PRON]() (1175; 5% instances), [la-pos/NOUN]()-[la-pos/PROPN]() (948; 4% instances), [la-pos/VERB]()-[la-pos/PROPN]() (439; 2% instances), [la-pos/ADJ]()-[la-pos/PRON]() (369; 2% instances), [la-pos/ADJ]()-[la-pos/NOUN]() (350; 2% instances), [la-pos/VERB]()-[la-pos/ADJ]() (216; 1% instances), [la-pos/PRON]()-[la-pos/ADJ]() (213; 1% instances), [la-pos/PRON]()-[la-pos/NOUN]() (210; 1% instances), [la-pos/PRON]()-[la-pos/PRON]() (197; 1% instances), [la-pos/ADV]()-[la-pos/NOUN]() (190; 1% instances), [la-pos/NUM]()-[la-pos/NOUN]() (138; 1% instances), [la-pos/PROPN]()-[la-pos/PRON]() (116; 1% instances), [la-pos/ADJ]()-[la-pos/ADJ]() (98; 0% instances), [la-pos/PROPN]()-[la-pos/ADJ]() (72; 0% instances), [la-pos/PROPN]()-[la-pos/NOUN]() (69; 0% instances), [la-pos/PROPN]()-[la-pos/PROPN]() (60; 0% instances), [la-pos/VERB]()-[la-pos/NUM]() (40; 0% instances), [la-pos/ADV]()-[la-pos/PRON]() (37; 0% instances), [la-pos/ADJ]()-[la-pos/PROPN]() (33; 0% instances), [la-pos/NUM]()-[la-pos/PRON]() (31; 0% instances), [la-pos/X]()-[la-pos/PRON]() (31; 0% instances), [la-pos/NUM]()-[la-pos/ADJ]() (27; 0% instances), [la-pos/NUM]()-[la-pos/NUM]() (21; 0% instances), [la-pos/X]()-[la-pos/ADJ]() (20; 0% instances), [la-pos/PRON]()-[la-pos/PROPN]() (18; 0% instances), [la-pos/ADV]()-[la-pos/PROPN]() (16; 0% instances), [la-pos/X]()-[la-pos/NOUN]() (15; 0% instances), [la-pos/ADP]()-[la-pos/NOUN]() (14; 0% instances), [la-pos/ADV]()-[la-pos/ADJ]() (14; 0% instances), [la-pos/PRON]()-[la-pos/VERB]() (10; 0% instances), [la-pos/NOUN]()-[la-pos/VERB]() (8; 0% instances), [la-pos/X]()-[la-pos/PROPN]() (8; 0% instances), [la-pos/CONJ]()-[la-pos/NOUN]() (7; 0% instances), [la-pos/INTJ]()-[la-pos/NOUN]() (6; 0% instances), [la-pos/SCONJ]()-[la-pos/NOUN]() (6; 0% instances), [la-pos/CONJ]()-[la-pos/PRON]() (5; 0% instances), [la-pos/NOUN]()-[la-pos/NUM]() (4; 0% instances), [la-pos/NUM]()-[la-pos/VERB]() (4; 0% instances), [la-pos/PRON]()-[la-pos/NUM]() (4; 0% instances), [la-pos/SCONJ]()-[la-pos/PRON]() (4; 0% instances), [la-pos/ADP]()-[la-pos/PROPN]() (3; 0% instances), [la-pos/ADJ]()-[la-pos/VERB]() (2; 0% instances), [la-pos/INTJ]()-[la-pos/ADJ]() (2; 0% instances), [la-pos/ADJ]()-[la-pos/NUM]() (1; 0% instances), [la-pos/ADP]()-[la-pos/PRON]() (1; 0% instances), [la-pos/ADV]()-[la-pos/NUM]() (1; 0% instances), [la-pos/ADV]()-[la-pos/VERB]() (1; 0% instances), [la-pos/NOUN]()-[la-pos/ADV]() (1; 0% instances), [la-pos/PRON]()-[la-pos/X]() (1; 0% instances), [la-pos/SCONJ]()-[la-pos/ADJ]() (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 nmod	color:blue
1	nam	nam	ADV	Df	_	8	discourse	_	_
2	omnis	omnis	PRON	Px	Case=Nom|Gender=Fem|Number=Sing	3	nmod	_	_
3	civitas	civitas	NOUN	Nb	Case=Nom|Gender=Fem|Number=Sing	8	nsubjpass	_	_
4	Helvetia	Helvetia	PROPN	Ne	Case=Nom|Gender=Fem|Number=Sing	3	appos	_	_
5	in	in	ADP	R-	_	7	case	_	_
6	quattuor	quattuor	NUM	Ma	_	7	nummod	_	_
7	pagos	pagus	NOUN	Nb	Case=Acc|Gender=Masc|Number=Plur	8	iobj	_	_
8	divisa	divido	VERB	V-	Aspect=Perf|Case=Nom|Gender=Fem|Number=Sing|Tense=Past|VerbForm=Part|Voice=Pass	0	root	_	_
9	est	sum	VERB	V-	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	8	cop	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 nmod	color:blue
1	reductos	reduco	VERB	V-	Aspect=Perf|Case=Acc|Gender=Masc|Number=Plur|Tense=Past|VerbForm=Part|Voice=Pass	5	advcl	_	_
2	in	in	ADP	R-	_	4	case	_	_
3	hostium	hostis	NOUN	Nb	Case=Gen|Gender=Masc|Number=Plur	4	nmod	_	_
4	numero	numerus	NOUN	Nb	Case=Abl|Gender=Masc|Number=Sing	5	nmod	_	_
5	habuit	habeo	VERB	V-	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 nmod	color:blue
1	reductos	reduco	VERB	V-	Aspect=Perf|Case=Acc|Gender=Masc|Number=Plur|Tense=Past|VerbForm=Part|Voice=Pass	5	advcl	_	_
2	in	in	ADP	R-	_	4	case	_	_
3	hostium	hostis	NOUN	Nb	Case=Gen|Gender=Masc|Number=Plur	4	nmod	_	_
4	numero	numerus	NOUN	Nb	Case=Abl|Gender=Masc|Number=Sing	5	nmod	_	_
5	habuit	habeo	VERB	V-	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_

~~~


