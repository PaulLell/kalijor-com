title:		Mediawiki:Common
desc:		
date:		2019/01/25
version:	1.0.0
template:	
nav:		Mediawiki:Common
percent:	100
authors:	
/\* Hide Category Links at bottom of pages \*/ .catlinks { display:
none; }

/\* body
{

`       background: #660099 url(/images/Kalijor-Background.jpg) center center no-repeat;`

}

  - /

/\* CSS placed here will be applied to all skins \*/ /\* This is the CSS
for all skins (for all users) on MediaWiki.org.

SECTIONS: 1. Indication of namespaces 2. Color classes for content 3.
Special pages 4. Main page styling 5. Sidebar external links 6.
Extension:Matrix stuff 7. Wikitables, infobox templates, warnings, and
other such stylings 8. Some other small things

  - /

/\* .ns-12 \#bodyContent
{

`   background-image: url(http://upload.wikimedia.org/wikipedia/mediawiki/6/67/PD-icon-faded.png);`
`   background-repeat: no-repeat;`
`   background-position: right 5em;`

}

/\*\*\*\*\* 2. COLOR CLASSES FOR CONTENT \*\*\*\*\*/

/\* Border colors \*/ .borderc1 { border-color: \#e9e9e9; border-width:
thin; } .borderc2 { border-color: \#aaaaaa; border-width: thin; }
.borderc3 { border-color: \#777777; border-width: thin; } .borderc4 {
border-color: \#000000; border-width: thin; } .borderc5 { border-color:
\#c00000; border-width: thin; } .borderc6 { border-color: \#025e9d;
border-width: thin; } .borderc7 { border-color: \#008040; border-width:
thin; } .borderc8 { border-color: \#ffcc00; border-width: thin; } /\*
Used by: [Template:Welcome](Template:Welcome "wikilink"). \*/

/\* Background colors \*/ .backgroundc1 { background-color: \#ffffff; }
/\* Used by: [Template:Welcome](Template:Welcome "wikilink"). \*/
.backgroundc2 { background-color: \#f9f9f9; } .backgroundc3 {
background-color: \#eeeeee; } .backgroundc4 { background-color:
\#e0e0e0; } .backgroundc5 { background-color: \#d2d2d2; } .backgroundc6
{ background-color: \#b7b7b7; } .backgroundc7 { background-color:
\#a3a3a3; } .backgroundc8 { background-color: \#444455; }

/\*\* 3. SPECIAL PAGES \*\*/

/\* Consistent special page navigation \*/ .SpecialPageInfo
{

`   background-color: #f9f9f9;`
`   background-image: url(http://upload.wikimedia.org/wikipedia/commons/thumb/8/89/Exquisite-khelpcenter.png/35px-Exquisite-khelpcenter.png);`
`   background-position: 0.8em 0.5em;`
`   background-repeat: no-repeat;`
`   padding: 0.3em 0.5em 0.3em 5.0em;`
`   border-color: #025e9d; `
`   border-width: 1px; `
`   border-style: solid;`
`   border-bottom-width: medium;`
`   margin-bottom: 1em;`

}

.mw-viewprevnext {

`   display: block;`
`   border: 1px solid #cccccc;`
`   background-color: #f9f9f2;`
`   padding: 0.2em 0.4em;`

}

/\*\* 4. MAIN PAGE STYLING \*\*/

1.  mainpage_topbox {

`   background: #f9f9f9;`
`   padding: 0px;`
`   border: 1px solid #aaaaaa;`
`   margin: 0.2em 10px 10px;`

} .mainpage_boxtitle, .mainpage_hubtitle, \#mainpage_pagetitle {

`   font-size: 105%;`
`   padding: 0.4em;`
`   background-color: #eeeeee;`
`   border-bottom: 1px solid #aaaaaa;`

} .mainpage_boxtitle {

`   line-height: 120%;`

}

1.  mainpage_pagetitle {

`   color: #cf7606;`
`   font-size: 200% !important;`

}

1.  mainpage_sitelinks {

`   padding: 0.2em;`
`   text-align: center;`
`   background-color: white;`

} .mainpage_hubtitle {

`   text-align: center;`

} .mainpage_boxcontents, .mainpage_boxcontents_small {

`   background: #ffffff;`
`   padding: 0.2em 0.4em;`

} .mainpage_boxcontents_small {

`   font-size: 95%;`

} .mainpage_hubbox, \#mainpage_newscell, \#mainpage_downloadcell {

`   padding: 0;`
`   border: 1px solid #aaaaaa;`

} .mainpage_hubbox {

`   margin-bottom: 0;`

}

1.  mainpage_newscell {

`   margin-bottom: 15px;`
`   margin-top: 0 !important;`

}

1.  mainpage_newscell .mainpage_boxtitle
{

`   background-image: url(http://upload.wikimedia.org/wikipedia/commons/thumb/8/89/Exquisite-khelpcenter.png/20px-Exquisite-khelpcenter.png);`
`   background-repeat: no-repeat;`
`   background-position: 99% 0.3em;`
`   padding-right: 25px;`

}

1.  mainpage_downloadcell {

`   width: 17em;`
`   margin-bottom: 5px;`

}

1.  mainpage_downloadcell .mainpage_boxtitle
{

`   background-image: url(http://upload.wikimedia.org/wikipedia/commons/thumb/5/5d/Crystal_Clear_action_build.png/18px-Crystal_Clear_action_build.png);`
`   background-repeat: no-repeat;`
`   background-position: 96% 0.33em;`
`   padding-right: 25px;`

}

1.  mainpage_mwtitle { color: \#005288; } /\* The words 'MediaWiki.org'
    in the title. \*/

/\* The "mainpage" class is added to the body with JavaScript for the
main page in all \*/ /\* languages, so we can style things that apppear
on the main page and also elsewhere. \*/ .mainpage \#lastmod, .mainpage
\#siteSub, .mainpage h1.firstHeading {

`   display: none !important;`

} .mainpage \#content {

`   padding-top: 1em;`

}

/\*\* 5. SIDEBAR EXTERNAL LINKS \*\*/

1.  n-blog-text a, \#n-browse-svn a, \#n-Statistics-for-SVN a,
    \#n-phpdoc a, \#n-svn-statistics a
{

`   background: url(/skins-1.5/monobook/external.png) center right no-repeat;`
`   padding-right: 13px;`
`   color: #3366bb;`

}

/\*\* 7. WIKITABLES, INFOBOX TEMPLATES, WARNINGS AND OTHER SUCH STYLINGS
\*\*/

/\* Give wikitables blue headings \*/ .wikitable th, .wikitable td.hl3,
.wikitable th.hl3 {

`   background: #8da7d6;`

} .wikitable td.hl1, .wikitable th.hl1 {

`   background: #c5d8fc;`

} .wikitable td.hl2, .wikitable th.hl2 {

`   background: #a7c1f2;`

}

/\*\*

`* Make entire table valign=top,`
`* To replace the |valign=top| on every cell.`
`*/`

.vatop tr, tr.vatop, .vatop td, .vatop th {

`   vertical-align: top;`

}

/\* General purpose "pretty (data) tables" \*/ table.datatable {

`   background-color: transparent;`

}

table.datatable th, table.datatable td {

`   padding: 4px;`

}

table.datatable th {

`   text-align: left;`
`   background-color: #999999;`

}

table.datatable tr {

`   background-color: #cccccc;`

}

table.datatable tr:hover {

`   background-color: #ffffcc;`

}

/\* SideBox styling \*/ div.sideBox {

`   position: relative;`
`   float: right;`
`   background: white;`
`   margin-left: 1em;`
`   border: 1px solid gray;`
`   padding: 0.3em;`
`   width: 200px;`
`   overflow: hidden; `
`   clear: right;`

} div.sideBox dl {

`   padding: 0;`
`   margin: 0 0 0.3em 0;`
`   font-size: 96%;`

} div.sideBox dl dt {

`   background: none;`
`   margin: 0.4em 0 0 0;`

} div.sideBox dl dd {

`   margin: 0.1em 0 0 1.1em;`
`   background-color: #f3f3f3;`

}

/\* Extension infobox styling \*/ .ext-infobox {

`   border: 2px solid #aaaaaa;`
`   width: 272px;`
`   float: right;`
`   margin: 0 0 0.5em 0.5em;`
`   border-collapse: collapse;`
`   background-color: white;`

} .ext-infobox td {

`   border: 2px none #aaaaaa;`
`   padding: 0.2em 0.5em;`
`   border-bottom: 1px solid #f0f0f0 !important;`

} .ext-header {

`   background-color: #aaaaaa;`
`   color: white;`
`   text-align: left;`

} .ext-header td { padding-top: 0.5em; } .ext-header img { padding: 0
0.2em 0 0.5em; } .ext-status-unstable, .ext-status-unstable td {
border-color: \#990000; } .ext-status-unstable .ext-header {
background-color: \#990000; color: \#ffff00; } .ext-status-experimental,
.ext-status-experimental td { border-color: \#ff4500; }
.ext-status-experimental .ext-header { background-color: \#ff4500; }
.ext-status-beta, .ext-status-beta td { border-color: \#ffba01; }
.ext-status-beta .ext-header { background-color: \#ffba01; }
.ext-status-stable, .ext-status-stable td { border-color: \#32cd32; }
.ext-status-stable .ext-header { background-color: \#32cd32; }

/\* Version box on [Manual:Downloading
MediaWiki](Manual:Downloading_MediaWiki "wikilink") \*/

1.  DownloadVersionBox {

`   border: 2px solid black;`
`   border-collapse: collapse; `
`   margin: auto;`
`   width: 50%;`
`   color: black;`

}

1.  DownloadVersionBox td {

`   border: 2px solid black;`
`   padding: 20px;`

}

/\* Major warning - used on the main page template to warn against
editing carelessly, but can be used elsewhere as well \*/ .majorwarning
{

`   background: yellow; `
`   padding: 0.3em; `
`   text-align: center; `
`   font-size: 125%; `
`   border: 2px solid red;`

}

/\* Page headings used throughout the wiki (though not very much at the
time of writing…) \*/ .page-notice, .page-warning {

`   border-width: 1px; `
`   border-style: solid;`
`   padding: 0.3em 0.5em;`
`   margin-bottom: 1em;`
`   width: 95%; `
`   margin-left: auto; `
`   margin-right: auto; `
`   text-align: center;`

}

/\* Informative notices at the top of pages (blue) \*/ .page-notice {

`   background-color: #f9f9f9;`
`   border-color: #025e9d; `
`   text-align: left;`

}

/\* Warning information at the top of pages (red) \*/ .page-warning {

`   background-color: #ffffff;`
`   border-color: #c51919;`
`   border-width: 2px;`

} .pw-head {

`   color: #c51919;`
`   font-weight: bold;`

}

/\* Used in Template:Notice \*/ .block-note
{

`   background-image: url(http://upload.wikimedia.org/wikipedia/commons/thumb/6/60/Bulbgraph.png/18px-Bulbgraph.png);`
`   background-position: top left;`
`   background-repeat: no-repeat;`

}
/\*

`  Using block-contents in the hope that it can apply to all block-level warning templates, `
`  with different images applied as backgrounds to the wrapping DIV.`

  - /

.block-contents {

`   display: block;`
`   padding-left: 20px;`

}

/\* Template documentation
([Template:Documentation](Template:Documentation "wikilink")) \*/
.template-documentation {

`   clear: both;`
`   margin: 1em 0 0 0;`
`   border: 1px solid #aaa; `
`   background-color: #ecfcf4; `
`   padding: 5px;`

}

/\*\* 8. SOME OTHER SMALL THINGS \*\*/

/\* Give a bit of space to the TOC \*/

1.  toc { margin: 1em 0; }

/\* Allow limiting of which header levels are shown in a TOC;

<div class="toclimit-3">

, for instance, will limit to

`  showing ==headings== and ===headings=== but no further.`
`  Used in `[`Template:TOCright`](Template:TOCright "wikilink")
`*/`

.toclimit-2 .toclevel-1 ul, .toclimit-3 .toclevel-2 ul, .toclimit-4
.toclevel-3 ul, .toclimit-5 .toclevel-4 ul, .toclimit-6 .toclevel-5 ul,
.toclimit-7 .toclevel-6 ul {

`   display: none;`

}

/\* make the list of references look smaller and highlight clicked
reference in blue \*/ ol.references { font-size: 100%; }
.references-small { font-size: 90%; } ol.references \> li:target {
background-color: \#ddeeff; } sup.reference:target { background-color:
\#ddeeff; }

/\* extra buttons for edit dialog (from commons:MediaWiki:Common.css)
\*/ .my-buttons {

`   padding: .5em;`

} .my-buttons a {

`   color: black;`
`   background-color: #cde !important;`
`   font-weight: bold;`
`   font-size: .9em;`
`   text-decoration: none;`
`   border: thin #069 outset;`
`   padding: 0 .1em .1em;`

} .my-buttons a:hover, .my-buttons a:active {

`   background-color: #bcd;`
`   border-style: inset;`

}

/\* from [User:Splarka/Help:Linked
images](User:Splarka/Help:Linked_images "wikilink") \*/
.imagelink_wikilogo a
{

`   width: 135px;`
`   height: 135px;`
`   display: block;`
`   text-decoration: none;`
`   background-image: url("`<http://upload.wikimedia.org/wikipedia/mediawiki/b/bc/Wiki.png>`");`

}

/\*\* reduced subset of the mbox styles from enwiki, mainly for the nice
boxflow \*\*/ table.mbox {

`   margin: 4px 10%;`
`   border-collapse: collapse;`
`   border: 1px solid #aaa; /* Default "notice" gray */`
`   background: #f9f9f9;`

} table.mbox-wide {

`   margin: 4px 0;`

}

th.mbox-text, td.mbox-text { /\* The message body cell(s)
\*/

`   border: none;`
`   padding: 0.25em 0.9em;       /* 0.9em left/right */`
`   width: 100%;    /* Make all mboxes the same width regardless of text length */`

} td.mbox-image { /\* The left image cell \*/

`   border: none;`
`   padding: 2px 0 2px 0.9em;    /* 0.9em left, 0px right */`
`   text-align: center;`

} td.mbox-imageright { /\* The right image cell \*/

`   border: none;`
`   padding: 2px 0.9em 2px 0;    /* 0px left, 0.9em right */`
`   text-align: center;`

} td.mbox-empty-cell { /\* An empty narrow cell \*/

`   border: none;`
`   padding: 0px;`
`   width: 1px;`

}

/\* These mbox-small classes must be placed after all other

`  ambox/tmbox/ombox etc classes. "body.mediawiki" is so `
`  they override "table.ambox + table.ambox" above. */`

body.mediawiki table.mbox-small { /\* For the "small=yes" option. \*/

`   clear: right;`
`   float: right;`
`   margin: 4px 0 4px 1em;`
`   width: 238px;`
`   font-size: 88%;`
`   line-height: 1.25em;`

} body.mediawiki table.mbox-small-left { /\* For the "small=left"
option. \*/

`   margin: 4px 1em 4px 0;`
`   width: 238px;`
`   border-collapse: collapse;`
`   font-size: 88%;`
`   line-height: 1.25em;`

}

/\* These are the same colours as the enwiki

`  'cmbox' styles; just with different names. */`

table.mbox-critical {

`   border: 4px solid #b22222;    /* Red */`
`   background: #FFDBDB;          /* Pink */`

} table.mbox-important {

`   background: #FFDBDB;    /* Red */`

} table.mbox-warning {

`   background: #FFE7CE;    /* Orange */`

} table.mbox-caution {

`   background: #FFF9DB;    /* Yellow */`

} table.mbox-notice {

`   background: #D8E8FF;    /* Blue */`

} table.mbox-move {

`   background: #E4D8FF;    /* Purple */`

} table.mbox-protection {

`   background: #EFEFE1;    /* Gray-gold */`

}

/\*\*

`* Infoboxes`
`*/`

.infobox {

`   float: right;`
`   clear: right;`
`   margin-bottom: 0.5em;`
`   margin-left: 1em;`
`   padding: 0.2em;`
`   border: 1px solid #AAA;`
`   background: #F9F9F9;`
`   color: black;`

}

.infobox td, .infobox th {

`   vertical-align: top;`

}

.infobox caption {

`   margin-left: inherit;`
`   font-size: larger;`

}

.infobox.bordered {

`   border-collapse: collapse;`

}

.infobox.bordered td, .infobox.bordered th {

`   border: 1px solid #AAA;`

}

.infobox.bordered .borderless td, .infobox.bordered .borderless th {

`   border: 0;`

}

/\* Apparently the namespaces parameter

` for inputbox forces a checkbox.`
` Let's hide it in the API sidebar */`

.mw-inputbox-hideapicheck label\[for=mw-inputbox-ns104\],

1.  mw-inputbox-ns104 {

`   display: none;`

}

/\*\* Testing for code review \*\*/ div.mw-wordcloud {

`   width: 100%;`
`   text-align: justify;`

}

.mw-wordcloud-size-1 {

`   color: #222;`
`   font-size: 2.4em;`

} .mw-wordcloud-size-2 {

`   color: #333;`
`   font-size:2.2em;`

} .mw-wordcloud-size-3 {

`   color: #444;`
`   font-size: 2.0em;`

} .mw-wordcloud-size-4 {

`   color: #555;`
`   font-size: 1.8em;`

} .mw-wordcloud-size-5 {

`   color: #666;`
`   font-size: 1.6em;`

} .mw-wordcloud-size-6 {

`   color: #777;`
`   font-size: 1.4em;`

} .mw-wordcloud-size-7 {

`   color: #888;`
`   font-size: 1.2em;`

} .mw-wordcloud-size-8 {

`   color: #999;`
`   font-size: 1em;`

} .mw-wordcloud-size-9 {

`   color: #aaa;`
`   font-size: 0.8em;`
`   letter-spacing: 3px;`

} .mw-wordcloud-size-10, .mw-wordcloud-size-0 {

`   color: #bbb;`
`   font-size: 0.8em;`

}

/\* Styling for related links and disambiguation links \*/ .rellink,
.dablink {

`   font-style: italic;`
`   margin-bottom: 0.5em;`
`   padding-left: 2em;`

}

/\* @todo FIXME: document me :) \*/

1.  signuptopbox li {

`   float: left;`
`   list-style: none;`
`   font-family: sans-serif;`

}

1.  signuptopbox li {

`   color: #3ca7d4;`
`   background: #c2e1f9;`
`   line-height: 2.8em;`
`   margin-right: .25em;`
`   padding-right: .5em;`

}

1.  signuptopbox li.pr-active, \#signuptopbox li.pr-active div {

`   color: #67ca36;`
`   background: #d4f9c2;`
`   border-color: #fff #fff #fff #67ca36;`

}

1.  signuptopbox li div{

`   width: 0;`
`   height: 0;`
`   border-color: #fff #fff #fff #3CA7D4;`
`   border-style: solid;`
`   border-width: 1.4em .3em 1.4em 1.4em;`
`   float: left;`

}

1.  signuptopbox li span.pr-number{

`   display: block;`
`   width: 1.8em;`
`   line-height: 1.8em;`
`   background: #3ca7d4;`
`   color: #c2e1f9;`
`   text-align: center;`
`   margin: .5em;`
`   -webkit-border-radius: 50%;`
`   -moz-border-radius: 50%;`
`   -ms-border-radius: 50%;`
`   -o-border-radius: 50%;`
`   border-radius: 50%;`
`   font-weight: 600;`
`   float: left;`

}

1.  signuptopbox li.pr-active span.pr-number {

`   background: #67ca36;`
`   color: #d4f9c2;`

}

1.  signuptopbox li span {

`   float: left;`

}

1.  signuptopbox li.pr-spacer {

`   padding: 0;`

}

/\* BREADCRUMB CODE \*/

.breadcrumb {

`       list-style: none;`
`       overflow: hidden;`
`       font: 14px Helvetica, Arial, Sans-Serif;`

} .breadcrumb li {

`       float: left;`
`       margin-bottom: 0;`

} .breadcrumb li a {

`       color: white;`
`       text-decoration: none;`
`       padding: 10px 0 10px 45px;`
`       position: relative;`
`       display: block;`
`       float: left;`

}

.breadcrumb li a:after
{

`       content: " ";`
`       display: block;`
`       width: 0;`
`       height: 0;`
`       border-top: 50px solid transparent;           /* Go big on the size, and let overflow hide */`
`       border-bottom: 50px solid transparent;`
`       position: absolute;`
`       top: 50%;`
`       margin-top: -50px;`
`       left: 100%;`
`       z-index: 2;`

}

.breadcrumb li a:before {

`       content: " ";`
`       display: block;`
`       width: 0;`
`       height: 0;`
`       border-top: 50px solid transparent;`
`       border-bottom: 50px solid transparent;`
`       border-left: 31px solid white;`
`       position: absolute;`
`       top: 50%;`
`       margin-top: -50px;`
`       margin-left: 1px;`
`       left: 100%;`
`       z-index: 1;`

}

.breadcrumb li:first-child a {

`       padding-left: 20px;`

}

.currentcrumb a {

`       background: #069;`

}

.currentcrumb a:after {

`       border-left: 30px solid #069;`

}

.currentcrumb a:hover, .prevcrumb a:hover, .nextcrumb a:hover {

`       background: #002d44;`

}

.currentcrumb a:hover:after, .prevcrumb a:hover:after, .nextcrumb
a:hover:after { border-left-color: \#002d44 \!important; }

.prevcrumb a {

`       background: #396;`

}

.prevcrumb a:after {

`       border-left: 30px solid #396;`

}

.nextcrumb a {

`       background: #999;`

}

.nextcrumb a:after {

`       border-left: 30px solid #999;`

}

/\* bug 27375, To go in ext.codereview \*/ .mw-codereview-diff ins {

`   background: #EDFFED;`

} .mw-codereview-diff del {

`   background: #FFEDED;`

} /\* bug 29307, awaiting deployment \*/ pre {

`   line-height: 1.3em;`

}

/\* To facilitate rtl translations \*/

1.  bodyContent .table-RTL a{

background:none; padding-right:0; }

1.  bodyContent .table-RTL UL{

margin-right:10px; display:table; }

.rtl { direction: rtl; font-family: Tahoma; text-align: right; }

1.  bodyContent .rtl a, \#bodyContent .rtl a.external {

background:none; padding-right:0; }

.rtl \#toctitle { direction:ltr; }

.rtl .toclevel-1, .rtl .toclevel-2, .rtl .toclevel-3, .rtl .toclevel-4 {
text-align:right; }

.rtl .toclevel-2 { margin-right:10px; }

.rtl .toclevel-3 { margin-right:20px; }

.rtl .toclevel-4 { margin-right:30px; }

.rtl .editsection { float:left; }

.rtl UL { margin-right:16px; display:table; }

.rtl OL { margin-right:16px; display:table; }

  - /---
title: MediaWiki:Common.css
permalink: /MediaWiki:Common.css/
---

