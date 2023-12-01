#HTML Symbols
Symbols or letters that are not present on your keyboard can be added to HTML using entities.

HTML Symbol Entities
HTML entities were described in the previous chapter.

Many mathematical, technical, and currency symbols, are not present on a normal keyboard.

To add such symbols to an HTML page, you can use the entity name or the entity number (a decimal or a hexadecimal reference) for the symbol:

Example
Display the euro sign:

<p>I will display &euro;</p>
<p>I will display &#8364;</p>
<p>I will display &#x20AC;</p>
Will display as:
I will display €
I will display €
I will display €
Some Mathematical Symbols Supported by HTML
Char	Number	Entity	Description	
∀	&#8704;	&forall;	For all	
∂	&#8706;	&part;	Partial differential	
∃	&#8707;	&exist;	There exists	
∅	&#8709;	&empty;	Empty sets	
∇	&#8711;	&nabla;	Nabla	
∈	&#8712;	&isin;	Element of	
∉	&#8713;	&notin;	Not an element of	
∋	&#8715;	&ni;	Contains as member	
∏	&#8719;	&prod;	N-ary product	
∑	&#8721;	&sum;	N-ary summation	

#Some Greek Letters Supported by HTML
Char	Number	Entity	Description	
Α	&#913;	&Alpha;	GREEK ALPHA	
Β	&#914;	&Beta;	GREEK BETA	
Γ	&#915;	&Gamma;	GREEK GAMMA	
Δ	&#916;	&Delta;	GREEK DELTA	
Ε	&#917;	&Epsilon;	GREEK EPSILON	
Ζ	&#918;	&Zeta;	GREEK ZETA	

#Some Other Entities Supported by HTML
Char	Number	Entity	Description	
©	&#169;	&copy;	COPYRIGHT	
®	&#174;	&reg;	REGISTERED	
€	&#8364;	&euro;	EURO SIGN	
™	&#8482;	&trade;	TRADEMARK	
←	&#8592;	&larr;	LEFT ARROW	
↑	&#8593;	&uarr;	UP ARROW	
→	&#8594;	&rarr;	RIGHT ARROW	
↓	&#8595;	&darr;	DOWN ARROW	
♠	&#9824;	&spades;	SPADE	
♣	&#9827;	&clubs;	CLUB	
♥	&#9829;	&hearts;	HEART	
♦	&#9830;	&diams;	 DIAMOND	

#Using Emojis in HTML
Emojis are characters from the UTF-8 character set: 😄 😍 💗

Emoji	Value	
🗻	&#128507;	
🗼	&#128508;	
🗽	&#128509;	
🗾	&#128510;	
🗿	&#128511;	
😀	&#128512;	
😁	&#128513;	
😂	&#128514;	
😃	&#128515;	
😄	&#128516;	
😅	&#128517;	
Full HTML Emoji Reference

HTML Emojis Examples
🚀🚁🚂🚃🚄
HTML Emoji Transport Symbols

💺💻💼💽💾
HTML Emoji Office Symbols

👮👯👰👱👲
HTML Emoji People Symbols

🐂🐃🐄🐅🐆
HTML Emoji Animals Symbols

What are Emojis?
Emojis look like images, or icons, but they are not.

They are letters (characters) from the UTF-8 (Unicode) character set.

UTF-8 covers almost all of the characters and symbols in the world.

The HTML charset Attribute
To display an HTML page correctly, a web browser must know the character set used in the page.

This is specified in the <meta> tag:

<meta charset="UTF-8">
If not specified, UTF-8 is the default character set in HTML.

UTF-8 Characters
Many UTF-8 characters cannot be typed on a keyboard, but they can always be displayed using numbers (called entity numbers):

A is 65
B is 66
C is 67
Example
<!DOCTYPE html>
<html>
<meta charset="UTF-8">
<body>

<p>I will display A B C</p>
<p>I will display &#65; &#66; &#67;</p>

</body>
</html>
Example Explained
The <meta charset="UTF-8"> element defines the character set.

The characters A, B, and C, are displayed by the numbers 65, 66, and 67.

To let the browser understand that you are displaying a character, you must start the entity number with &# and end it with ; (semicolon).

#Emoji Characters
Emojis are also characters from the UTF-8 alphabet:

😄 is 128516
😍 is 128525
💗 is 128151
Example
<!DOCTYPE html>
<html>
<meta charset="UTF-8">
<body>

<h1>My First Emoji</h1>

<p>&#128512;</p>

</body>
</html>
Since Emojis are characters, they can be copied, displayed, and sized just like any other character in HTML.

Example
<!DOCTYPE html>
<html>
<meta charset="UTF-8">
<body>

<h1>Sized Emojis</h1>

<p style="font-size:48px">
&#128512; &#128516; &#128525; &#128151;
</p>

</body>
</html>

#HTML Encoding (Character Sets)
To display an HTML page correctly, a web browser must know which character set to use.

The HTML charset Attribute
The character set is specified in the <meta> tag:

Example
<meta charset="UTF-8">
The HTML5 specification encourages web developers to use the UTF-8 character set.

UTF-8 covers almost all of the characters and symbols in the world!

Unicode Web growth
Full UTF-8 Reference

The ASCII Character Set
ASCII was the first character encoding standard for the web. It defined 128 different characters that could be used on the internet:

English letters (A-Z)
Numbers (0-9)
Special characters like ! $ + - ( ) @ < >.
The ANSI Character Set
ANSI (Windows-1252) was the original Windows character set:

Identical to ASCII for the first 127 characters
Special characters from 128 to 159
Identical to UTF-8 from 160 to 255
<meta charset="Windows-1252">
The ISO-8859-1 Character Set
ISO-8859-1 was the default character set for HTML 4. This character set supported 256 different character codes. HTML 4 also supported UTF-8.

Identical to ASCII for the first 127 characters
Does not use the characters from 128 to 159
Identical to ANSI and UTF-8 from 160 to 255
HTML 4 Example
<meta http-equiv="Content-Type" content="text/html;charset=ISO-8859-1">
HTML 5 Example
<meta charset="ISO-8859-1">
The UTF-8 Character Set
is identical to ASCII for the values from 0 to 127
Does not use the characters from 128 to 159
Identical to ANSI and 8859-1 from 160 to 255
Continues from the value 256 to 10 000 characters
<meta charset="UTF-8">

#Differences Between Character Sets
The following table displays the differences between the character sets described above:

Numb	ASCII	ANSI	8859	UTF‑8	Description
32					space
33	!	!	!	!	exclamation mark
34	"	"	"	"	quotation mark
35	#	#	#	#	number sign
36	$	$	$	$	dollar sign
37	%	%	%	%	percent sign
38	&	&	&	&	ampersand
39	'	'	'	'	apostrophe
40	(	(	(	(	left parenthesis
41	)	)	)	)	right parenthesis
42	*	*	*	*	asterisk
43	+	+	+	+	plus sign
44	,	,	,	,	comma
45	-	-	-	-	hyphen-minus
46	.	.	.	.	full stop
47	/	/	/	/	solidus
48	0	0	0	0	digit zero
49	1	1	1	1	digit one
50	2	2	2	2	digit two
51	3	3	3	3	digit three
52	4	4	4	4	digit four
53	5	5	5	5	digit five
54	6	6	6	6	digit six
55	7	7	7	7	digit seven
56	8	8	8	8	digit eight
57	9	9	9	9	digit nine
58	:	:	:	:	colon
59	;	;	;	;	semicolon
60	<	<	<	<	less than
61	=	=	=	=	equals sign
62	>	>	>	>	greater than
63	?	?	?	?	question mark
64	@	@	@	@	commercial at
65	A	A	A	A	Latin A
66	B	B	B	B	Latin B
67	C	C	C	C	Latin C
68	D	D	D	D	Latin D
69	E	E	E	E	Latin E
70	F	F	F	F	Latin F
71	G	G	G	G	Latin G
72	H	H	H	H	Latin H
73	I	I	I	I	Latin I
74	J	J	J	J	Latin J
75	K	K	K	K	Latin K
76	L	L	L	L	Latin L
77	M	M	M	M	Latin M
78	N	N	N	N	Latin N
79	O	O	O	O	Latin O
80	P	P	P	P	Latin P
81	Q	Q	Q	Q	Latin Q
82	R	R	R	R	Latin R
83	S	S	S	S	Latin S
84	T	T	T	T	Latin T
85	U	U	U	U	Latin U
86	V	V	V	V	Latin V
87	W	W	W	W	Latin W
88	X	X	X	X	Latin X
89	Y	Y	Y	Y	Latin Y
90	Z	Z	Z	Z	Latin Z
91	[	[	[	[	left square bracket
92	\	\	\	\	reverse solidus
93	]	]	]	]	right square bracket
94	^	^	^	^	circumflex accent
95	_	_	_	_	low line
96	`	`	`	`	grave accent
97	a	a	a	a	Latin small a
98	b	b	b	b	Latin small b
99	c	c	c	c	Latin small c
100	d	d	d	d	Latin small d
101	e	e	e	e	Latin small e
102	f	f	f	f	Latin small f
103	g	g	g	g	Latin small g
104	h	h	h	h	Latin small h
105	i	i	i	i	Latin small i
106	j	j	j	j	Latin small j
107	k	k	k	k	Latin small k
108	l	l	l	l	Latin small l
109	m	m	m	m	Latin small m
110	n	n	n	n	Latin small n
111	o	o	o	o	Latin small o
112	p	p	p	p	Latin small p
113	q	q	q	q	Latin small q
114	r	r	r	r	Latin small r
115	s	s	s	s	Latin small s
116	t	t	t	t	Latin small t
117	u	u	u	u	Latin small u
118	v	v	v	v	Latin small v
119	w	w	w	w	Latin small w
120	x	x	x	x	Latin small x
121	y	y	y	y	Latin small y
122	z	z	z	z	Latin small z
123	{	{	{	{	left curly bracket
124	|	|	|	|	vertical line
125	}	}	}	}	right curly bracket
126	~	~	~	~	tilde
127	DEL	 	 	 	 
128	 	€	 	 	euro sign
129	 				NOT USED
130	 	‚	 	 	single low-9 quotation mark
131	 	ƒ	 	 	Latin small f with hook
132	 	„	 	 	double low-9 quotation mark
133	 	…	 	 	horizontal ellipsis
134	 	†	 	 	dagger
135	 	‡	 	 	double dagger
136	 	ˆ	 	 	modifier letter circumflex accent
137	 	‰	 	 	per mille sign
138	 	Š	 	 	Latin S with caron
139	 	‹	 	 	single left-pointing angle quotation mark
140	 	Œ	 	 	Latin capital ligature OE
141	 				NOT USED
142	 	Ž	 	 	Latin Z with caron
143	 				NOT USED
144	 				NOT USED
145	 	‘	 	 	left single quotation mark
146	 	’	 	 	right single quotation mark
147	 	“	 	 	left double quotation mark
148	 	”	 	 	right double quotation mark
149	 	•	 	 	bullet
150	 	–	 	 	en dash
151	 	—	 	 	em dash
152	 	˜	 	 	small tilde
153	 	™	 	 	trade mark sign
154	 	š	 	 	Latin small s with caron
155	 	›	 	 	single right-pointing angle quotation mark
156	 	œ	 	 	Latin small ligature oe
157	 				NOT USED
158	 	ž	 	 	Latin small z with caron
159	 	Ÿ	 	 	Latin Y with diaeresis
160	 	 	 	 	no-break space
161	 	¡	¡	¡	inverted exclamation mark
162	 	¢	¢	¢	cent sign
163	 	£	£	£	pound sign
164	 	¤	¤	¤	currency sign
165	 	¥	¥	¥	yen sign
166	 	¦	¦	¦	broken bar
167	 	§	§	§	section sign
168	 	¨	¨	¨	diaeresis
169	 	©	©	©	copyright sign
170	 	ª	ª	ª	feminine ordinal indicator
171	 	«	«	«	left-pointing double angle quotation mark
172	 	¬	¬	¬	not sign
173	 	­	­	­	soft hyphen
174	 	®	®	®	registered sign
175	 	¯	¯	¯	macron
176	 	°	°	°	degree sign
177	 	±	±	±	plus-minus sign
178	 	²	²	²	superscript two
179	 	³	³	³	superscript three
180	 	´	´	´	acute accent
181	 	µ	µ	µ	micro sign
182	 	¶	¶	¶	pilcrow sign
183	 	·	·	·	middle dot
184	 	¸	¸	¸	cedilla
185	 	¹	¹	¹	superscript one
186	 	º	º	º	masculine ordinal indicator
187	 	»	»	»	right-pointing double angle quotation mark
188	 	¼	¼	¼	vulgar fraction one quarter
189	 	½	½	½	vulgar fraction one half
190	 	¾	¾	¾	vulgar fraction three quarters
191	 	¿	¿	¿	inverted question mark
192	 	À	À	À	Latin A with grave
193	 	Á	Á	Á	Latin A with acute
194	 	Â	Â	Â	Latin A with circumflex
195	 	Ã	Ã	Ã	Latin A with tilde
196	 	Ä	Ä	Ä	Latin A with diaeresis
197	 	Å	Å	Å	Latin A with ring above
198	 	Æ	Æ	Æ	Latin AE
199	 	Ç	Ç	Ç	Latin C with cedilla
200	 	È	È	È	Latin E with grave
201	 	É	É	É	Latin E with acute
202	 	Ê	Ê	Ê	Latin E with circumflex
203	 	Ë	Ë	Ë	Latin E with diaeresis
204	 	Ì	Ì	Ì	Latin I with grave
205	 	Í	Í	Í	Latin I with acute
206	 	Î	Î	Î	Latin I with circumflex
207	 	Ï	Ï	Ï	Latin I with diaeresis
208	 	Ð	Ð	Ð	Latin Eth
209	 	Ñ	Ñ	Ñ	Latin N with tilde
210	 	Ò	Ò	Ò	Latin O with grave
211	 	Ó	Ó	Ó	Latin O with acute
212	 	Ô	Ô	Ô	Latin O with circumflex
213	 	Õ	Õ	Õ	Latin O with tilde
214	 	Ö	Ö	Ö	Latin O with diaeresis
215	 	×	×	×	multiplication sign
216	 	Ø	Ø	Ø	Latin O with stroke
217	 	Ù	Ù	Ù	Latin U with grave
218	 	Ú	Ú	Ú	Latin U with acute
219	 	Û	Û	Û	Latin U with circumflex
220	 	Ü	Ü	Ü	Latin U with diaeresis
221	 	Ý	Ý	Ý	Latin Y with acute
222	 	Þ	Þ	Þ	Latin Thorn
223	 	ß	ß	ß	Latin small sharp s
224	 	à	à	à	Latin small a with grave
225	 	á	á	á	Latin small a with acute
226	 	â	â	â	Latin small a with circumflex
227	 	ã	ã	ã	Latin small a with tilde
228	 	ä	ä	ä	Latin small a with diaeresis
229	 	å	å	å	Latin small a with ring above
230	 	æ	æ	æ	Latin small ae
231	 	ç	ç	ç	Latin small c with cedilla
232	 	è	è	è	Latin small e with grave
233	 	é	é	é	Latin small e with acute
234	 	ê	ê	ê	Latin small e with circumflex
235	 	ë	ë	ë	Latin small e with diaeresis
236	 	ì	ì	ì	Latin small i with grave
237	 	í	í	í	Latin small i with acute
238	 	î	î	î	Latin small i with circumflex
239	 	ï	ï	ï	Latin small i with diaeresis
240	 	ð	ð	ð	Latin small eth
241	 	ñ	ñ	ñ	Latin small n with tilde
242	 	ò	ò	ò	Latin small o with grave
243	 	ó	ó	ó	Latin small o with acute
244	 	ô	ô	ô	Latin small o with circumflex
245	 	õ	õ	õ	Latin small o with tilde
246	 	ö	ö	ö	Latin small o with diaeresis
247	 	÷	÷	÷	division sign
248	 	ø	ø	ø	Latin small o with stroke
249	 	ù	ù	ù	Latin small u with grave
250	 	ú	ú	ú	Latin small u with acute
251	 	û	û	û	Latin small with circumflex
252	 	ü	ü	ü	Latin small u with diaeresis
253	 	ý	ý	ý	Latin small y with acute
254	 	þ	þ	þ	Latin small thorn
255	 	ÿ	ÿ	ÿ	Latin small y with diaeresis
