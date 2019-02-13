[![profie image](http://kyagrd.github.io/images/kya_face.jpg)](https://www.dropbox.com/s/t5l62rtlmsac6q1/kyagrd_tumblr_cv.pdf) [![Facebook](http://kyagrd.github.io/images/fb_icon32.png)](http://facebook.com/kyagrd) [![Instagram](http://kyagrd.github.io/images/instagram-logo-32x32.png)](https://www.instagram.com/kyagrd/) [![Flickr](http://1.bp.blogspot.com/-9o6calUfmPs/UgyeZ-68XrI/AAAAAAAAJ3U/2_2xcaZoNg0/s1600/flickr-icon.png)](https://www.flickr.com/photos/23489589@N03/) [![Google+](http://kyagrd.github.io/images/gplus_icon32.png)](https://plus.google.com/+안기영) [![Twitter](http://kyagrd.github.io/images/twitter_icon32.png)](https://twitter.com/kyagrd) [![LinkedIn](http://kyagrd.github.io/images/linkedin_icon32.png)](https://linkedin.com/in/kyagrd) [![Logdown](http://kyagrd.github.io/images/logdown_icon32.png)](http://kyagrd.logdown.com/) [![ResearchGate](http://kyagrd.github.io/images/resgate_icon32.png)](https://www.researchgate.net/profile/Ki_Yung_Ahn) [![Google Scholar](http://media.mybrowseraddon.com/icons/google-scholar32.png)](https://scholar.google.com/citations?user=n-GwE98AAAAJ) [![DBLP](http://acsicpersonal.uib.es/mkhouja/wp-content/themes/zeebizzcard/images/icons/dblp.png)](http://dblp.uni-trier.de/pers/hd/a/Ahn:Ki_Yung) [![ORCID](https://orcid.org/sites/default/files/images/orcid_32x32.png)](http://orcid.org/0000-0002-7171-7979) [![GitHub](http://kyagrd.github.io/images/octocat-logo.png)](https://github.com/kyagrd/) [<img alt="Hackage" src="http://www.vectorlogo.zone/logos/haskell/haskell-icon.svg" width="32" height="32">](https://hackage.haskell.org/user/KiYungAhn) 

Assistant Professor (`kya AT hnu DOT kr` +82 42 629 7492) <br />
Office: 9-07-03 (engineering bldg. 7th floor room #03) <br />
[Department of Computer, Communication and Unmanned Technology](http://dccut.hannam.ac.kr/) <br />
[College of Engineering](http://int.hnu.kr/eng/sub.php?menuIdx=21),
[Hannam University](http://int.hnu.kr/eng/), Daejeon, Korea 34430

* Ph.D. in [Computer Science](http://cs.pdx.edu/)
  at [Portland State University](http://www.pdx.edu/), Dec, 2014
(advisor: [Tim Sheard](http://cs.pdx.edu/~sheard/))
* B.S. in [Computer Science](http://cs.kaist.ac.kr/),
  at [KAIST](http://www.kaist.ac.kr/), Feb, 2002

# Teaching (2019 Spring)
 * [객체지향프로그래밍(OOP)](https://kyagrd.github.io/oop2019spring)
 * [인터넷응용및실습(HTML/CSS/JS)](https://kyagrd.github.io/htmlcss2019spring)
 * [자기계발(Freshman Inquiry)](https://kyagrd.github.io/fresh2019spring)
 * [창업의이해(Understanding Entrepreneurship)](https://kyagrd.github.io/bs2019spring)

[see more, including previous lectures]

# Research

## Security and Process Calculi

Joined [Alwen Tiu](http://www.ntu.edu.sg/home/atiu/)'s research group in 2016 summer, have been working on security protocol verification based on pi-calculi. Our result in year 2017 on the modal logic for open bismulation has been presented in CONCUR 2017 and awarded as the best paper:
 * Ki Yung Ahn, [Ross Horne](http://www.ntu.edu.sg/home/rhorne/) and [Alwen Tiu](http://www.ntu.edu.sg/home/atiu/). [*A Characterisation of Open Bisimilarity using an Intuitionistic Modal Logic.*](http://drops.dagstuhl.de/opus/volltexte/2017/7789/pdf/LIPIcs-CONCUR-2017-7.pdf) 28th International Conference on Concurrency Theory (CONCUR 2017). September 5-8, 2017. Berlin, Germany. Editors: Roland Meyer and Uwe Nestmann; [ISBN 978-3-95977-048-4; LIPICS Volume 85](http://drops.dagstuhl.de/opus/portals/lipics/index.php?semnr=16046); Article No. 7; pp. 7:1-7:15. Leibniz International Proceedings in Informatics. ISSN 1868-8969. DOI: [10.4230/LIPIcs.CONCUR.2017.7](http://dx.doi.org/10.4230/LIPIcs.CONCUR.2017.7)
   - [Slides](http://www.ntu.edu.sg/home/rhorne/concur17.pdf) presented by Ross at CONCUR 2017.
   - An [Extended Version](https://www.researchgate.net/publication/312550567) including Abella formalization of proofs and Bedwyr test of examples.
   - A certificate of the Best Paper Award <br /><a href="http://www.ntu.edu.sg/home/rhorne/bestpaper.jpg">![CONCUR2017BestPaper](http://kyagrd.github.io/images/concur2017bestpaper_small.jpg)</a>
   - [A News Article](http://scse.ntu.edu.sg/NewsnEvents/Pages/News-Detail.aspx?news=6fe26396-875a-4172-b006-dc1c624f6aed) about the award from the homepage of School of Computer Science & Engineering @ NTU.


## [TIPER](http://kyagrd.github.io/tiper/)
Another research interest of mine is developing relational specifications
of polymorphic type systems that can be automatically executed as working
implementations. I am planning to initiate a project called [TIPER](http://kyagrd.github.io/tiper/),
which aims to designe and develope a tool that automatically generates
Type Inference Prototyping Engines from Executable Relational specifcations.
By combining the theriteical and techincal advances in the Functional Programming
and the Logic Programming communities, I believe we could realize a missing peice
of the language frontend construction toolset. We already have lexer/parser geneartors
(e.g. Lex/Yacc) but missing static type system generators. What we lack is
a tool that could automate static type system implemetations supports
both type checking and type inference over polymorphic types.
See the [TIPER hompage](http://kyagrd.github.io/tiper/) for further
details on this prospective project.


## [Nax](http://kyagrd.github.io/mininax/)
My thesis research was about theories and language design for
a logically consistent system that is convenient for both
functional programming and logical reasoning, based on the Curry--Howard correspondence.
In my thesis I designed a language called Nax, proved theoretic properteis about
the language by studing its underlying calclulus (which is also my conribution).
I've also implemted [a subset of Nax](http://kyagrd.github.io/mininax),
which motivated the TIPER proejct mentioned previously because
the added complexity makes it difficult to keep track of
whether the implementation is faithful to the design written on paper.


# Additional information
In addtion, I am generally intereseted on programming languages related subjects:
type systems, automated testing (using solvers), formal verification,
subtyping for algebraic datatypes, and other aspects of functional languages.

Further details about me are summarized in
my [CV (resume)](http://kyagrd.github.io/cv/cv.pdf); most recent change of position at Hannam University not yet updated in the CV.
<!-- and
the list of my publications are also available on
my [Google Scholar profile](http://scholar.google.com/citations?user=n-GwE98AAAAJ&view_op=list_works&sortby=pubdate)
and
on my [ResearchGate profile](https://www.researchgate.net/profile/Ki_Yung_Ahn/publications).
-->


# [Korean ver. of "Programming in Haskell"](http://kyagrd.github.io/haskell/)
One of my favorate programming language is [Haskell](http://haskell.org/).
So, I've translated Graham Hutton's "Programming in Haskell" into Korean,
first Korean print published in 2009.
You can click on the book cover image to go to their homepages.

<a title="Click to move to the Korean version hompage" href="http://kyagrd.github.io/haskell/">
<img alt="한글판 표지" src="http://kyagrd.github.io/haskell/images/pihko_front_small.jpg" /></a> is
a Korean translation of
<a title="Click to move to the orignal English version homepage" href="http://cs.nott.ac.uk/~gmh/book.html">
<img alt="원서 표지" src="http://kyagrd.github.io/haskell/images/pih_front_small.gif" /></a>.
