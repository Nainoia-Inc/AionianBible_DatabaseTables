# File Name: _README.md
# File Date: 2024-12-05
# File Purpose: Supporting resource for the Aionian Bible project
# File Location: http://AionianBible.org
# File Copyright: Creative Commons Attribution 4.0 International, 2018-2025
# File Generator: ABCMS (alpha)
# File Accuracy: Contact publisher with corrections to file format or content
# Publisher Name: Nainoia Inc
# Publisher Contact: http://www.AionianBible.org/Publisher
# Publisher Mission: http://www.AionianBible.org/Preface
# Publisher Website: http://NAINOIA-INC.signedon.net
# Publisher Facebook: https://www.Facebook.com/AionianBible
#

Thank you for your interest in re-publishing Aionian Bible content. The Aionian Bible is copyrighted with the Creative Commons Attribution 4.0 International license allowing 100% freedom to copy, print, revise, and sell if allowed by the source text copyright. First, third party publishers are granted permission to distribute any unchanged Aionian Bible publication or file for free or commercially, except on or through any Amazon, Lulu, Ingram Spark, or Ingram Lightning Source platform or subsidiary which are our chosen commercial outlets. The Holy Bible Aionian Edition® trademark enforces this rule. Second, you are welcome to create derived works with complete freedom, though you must change the publication title, remove our trademark, and give attribution as follows, "Derived from AionianBible.org by Nainoia Inc." We also request that you give attribution to our original source and even consider deriving your new work directly from our source. The Aionian Bible does not require that your derived work include a ShareAlike copyright in order to allow future publishers greater copyright freedom, though again we request that future copyrights at least require attribution, Creative Commons Attribution 4.0 International, so that the text lineage is documented. If you have any licensing questions please ask.

Aionian Bible text repositories:
AionianBible.org/Read
AionianBible.org Request Custom Formatted Verses
Resources.AionianBible.org
GitHub.com/Nainoia-Inc
drive.google.com/drive/folders/1-5OurcPPEDAPXDfxzjNh2GfZwItSW0yy

Aionian Bible Content Management System (ABCMS):
The Aionian Bible Content Management System (ABCMS) also known as A Basic Content Management System is in production at AionianBible.org. The development philosophy of the first production release was simply to reliably publish as many Bibles as possible in as short a time as possible while being creative with approved programming practices as needed for expediency. For example, we used lots of global variables, very carefully and without shame. Nainoia Inc believes that we are in a spiritual war-time status and we serve accordingly. When duct tape worked and was at hand we did not run for the hammer and nails. And with the Lord's help we have published many Bible translations in many languages both online and in print with a skeleton crew. Having reached our first major milestone, Lord willing, we now plan to rewrite the content management system with the source code being available for comment, collaboration, and additional online applications. And we have a cool plan for our global variables! Watch our progress at GitHub.com/Nainoia-Inc.

We are recruiting volunteers. Contact us to learn more. Also visit NAINOIA-INC.SignedOn.net. 


TABLE and COLUMN DEFINITIONS


====================
BIBLE.txt	Table of all Bible verses
	BIBLE	Unique text key for Bible transation
	INDEX	Unique numberic key for book
	BOOK	Unique numberic key for book
	CHAPTER	Chapter number
	VERSE	Verse number
	TEXT	Verse text


====================
BOOKS.txt	Table of Bible book names
	BIBLE	Unique text key for Bible transation
	BOOKS	Book keys, english text, foreign text, etc


====================
FORPRINT.txt	Table of settings to produce PDFs format Bibles
	BIBLE	Unique text key for Bible transation
	DOIT
	RTL
	NOPDO
	YESJOHN
	YESNEW
	YESKDP
	ISBNLU
	ISBNLU22
	ISBNLUNT
	ISBNLUHARD
	ISBNLUJOHN
	UUID
	LANGUAGE
	LANGSPEED
	VERSION
	VERSIONE
	COLUMN1
	STUDWIDE
	REPLACE
	FONT
	NUDGE
	BIDI
	TSIZE
	TLEADING
	RSIZE
	RLEADING
	BSIZE
	BLEADING
	FOOTSIZE
	BACKVL
	BACKTL
	BACKAL
	BACKLL
	HEADFONT
	PIXTEXT
	PIXLEAD
	COPYFF
	VERSIONFF
	COUNT
	SIZE
	LEADING
	PERCENT
	LESS12
	LEADDIFF
	SIZEST
	LEADINGST
	LEADDIFFST
	PDOEXTENSION
	EXTENSION
	JOHNEXTENSION
	HIST
	PREF
	PREF2
	KEIZER
	READ
	GLOS1
	GLOS2
	GLOS3
	LOF
	VERSES
	STATUS
	W_FONT
	W_HIST
	W_PREF
	W_OLD
	W_NEW
	W_TOC
	W_APDX
	W_READ
	W_GLOS
	W_MAP
	W_ILUS
	W_DESTINY
	W_VERSES
	W_LIFE
	W_WORL
	W_FREE
	W_AKA
	W_PURP
	V_FONT
	W_LIFEX
	W_NUDGE
	JOH3_16
	JOH3_16_B
	GEN3_24
	GEN3_24_B
	LUK23_34
	LUK23_34_B
	REV21_2_3
	REV21_2_3_B
	HEB11_8
	HEB11_8_B
	EXO13_17
	EXO13_17_B
	MAR10_45
	MAR10_45_B
	ROM1_1
	ROM1_1_B
	MAT28_19
	MAT28_19_B


====================
KEY.txt	Table to link unique text and numeric Bible keys
	BIBLE 	Unique text key for Bible transation
	KEY 	Unique numeric key for Bible transation


====================
NUMBERS.txt	Table of numeric display values, English or foreign
	BIBLE	Unique text key for Bible transation
	NUMBERS	1 through 176


====================
SOURCES.txt	Table of sources files for the project
	FILE	Unique text key for Bible transation
	FLAG	Processing control flag
	POST	Processing control flag
	VALUE	Processing control flag
	SOURCE	Source file name and location
	DESTINATION	Destination file name


====================
UNTRANSLATE.txt	Table of Hebrew and Greeks words untranslated / annotated
	INDEX	Unique numberic key for book
	BOOK	Unique numberic key for book
	CHAPTER	Chapter number
	VERSE	Verse number
	WORD	Hebrew or Greek word to untranslation, annotate
	STRONGS	Hebrew or Greek word Strong's number 


====================
UNTRANSLATECUSTOM.txt	Table of Hebrew and Greeks words custom untranslated / annotated
	BIBLE	Unique text key for Bible transation
	INDEX	Unique numberic key for book
	BOOK	Unique numberic key for book
	CHAPTER	Chapter number
	VERSE	Verse number
	WORD	Alternate Hebrew or Greek word to untranslation, annotate
	STRONGS	Alternate Hebrew or Greek word Strong's number 
	UNTRANS	Alternate flag
	TEXT	Alternate verse text


====================
UNTRANSLATEWORDS.txt	Table of words to monitor for questioned translation
	BIBLE	Unique text key for Bible transation
	NOSPACE
	NOETERNAL
	ETERNAL
	NOHELL
	YESHELL
	SHEOL
	GEHENNA
	HADES
	TARTARUS
	ABYSS
	LOF


====================
VERSEMAP.txt	Table of named reversifications
	BIBLE	Unique text key for Bible transation
	MAP		Named reversification


====================
VERSEMAPCOMBINER.txt	Table of settings to combine split verses for standard versification
	BIBLE	Unique text key for Bible transation
	INDEX	Unique numberic key for book
	BOOK	Unique numberic key for book
	CHAPTER	Chapter number
	VERSE	Verse to combine
	TOTAL	Total verses in chapter expected
	COMBINE	Number of verses to combine


====================
VERSIONS.txt	Table of settings for each Bible transation
	BIBLE	Unique text key for Bible transation
	NOTE
	PACK
	SHORT
	NAME
	NAMEENGLISH
	LANGUAGE
	LANGUAGEENGLISH
	COUNTRY
	RTL
	LANGUAGESTYLE
	LANGUAGECSS
	LANGUAGECODE
	LANGUAGECODEISO
	LANGUAGESPELL
	NOPRO
	ABCOPYRIGHT
	COPYRIGHT
	EXTENSION
	WARNING
	TRANSLATOR
	SOURCE
	YEAR
	DESCRIPTION
	SOURCEDOMAIN
	SOURCELINK
	SOURCELINKEXTRA
	DOWNLOAD
	AMAZON
	AMAZONNT
	AMAZONJOHN
	KDP
	KDPNT
	KDPJOHN
	LULU
	LULUNT
	LULUHARD
	LULUJOHN
	LULUX
	LULUNTX
	LULUHARDX
	LULUJOHNX
	BUYOTHER
