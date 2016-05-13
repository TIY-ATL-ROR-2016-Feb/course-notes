# To New Beginnings

> Brit Butler, TIY Atlanta

My dearest students, y'all, congratulations.

First of all, I'm proud of your hard work and how far you've come.
But you probably knew that. Keep being patient with yourselves,
curious about the magic of computing, and respectful of your peers.

## Now What?

Keep in mind the following:

1. Your focus should probably be the job hunt,
   marketing yourself (i.e. portfolio), and
   improving your Ruby/Rails chops for a bit.

2. As graduates of this course, my door is always open to you.
   I'll respond to emails and slack messages as best I'm able.
   I'm also happy to help you dig into new topics that interest you.

3. Keep learning and be wary of impostor syndrome.
   You'll never know it all, neither will anyone else, and that's good.

## Disclaimer

What comes out of my mouth is not gospel.

I'm going to suggest some things to look into to broaden your horizons over
the next **year or so**. These suggestions are open ended and you should chase
what you're curious or excited about. If that's none of this stuff, that's fine.

Whatever your goals, I hope you have a discovered a love for programming.
Don't view the below as an exhaustive task list to complete, look at it as
a jumping off point to interesting destinations and adventures. **Do what interests you.**

## The Guide

There are three broad categories I'll group these suggestions into:

> R) Keep **reinforcing** your Ruby/Rails chops.
>    * Write more Rails apps, practice unit testing, dip your toes in ops or frontend.
>
> F) Work on your **fundamentals**.
>    * Take the magic out of programming, push the language further, etc.
>
> P) Gain a greater appreciation for programming **paradigms** and new ways of problem solving.
>    * What does OO programming really mean? What are alternatives?

All these things share one commonality: You'll learn the most by getting your hands dirty. :)

## Suggestions

### 1-3 months post-graduation

At this point, you'll primarily be focused on practicing what you've already learned
and finding paid work. Rather than showing you *entirely* new concepts, this period is
about reinforcing and building on your knowledge.

#### Book: POODR (R, F, and P!)

First and foremost, *please, please, please* read
[**Practical Object-Oriented Design in Ruby**][poodr] by the fantastic Sandi Metz.
It's worth reading through twice, it's cheap ($30), and it has the wonderful benefit
of ticking off all my boxes:

  * It builds on and reinforces your existing knowledge of plain old Ruby.
  * It isn't focused on Rails apps, it's focused on *fundamentals*, good problem solving,
    decomposition, and how to write **elegant, good code**.
  * It will deepen your understanding of the whys and hows of Object Orientation.
  * It ends with a wonderful chapter on how to approach **testing**.

[poodr]: http://www.poodr.com

#### Book: Objects on Rails (R, P)

I lack a religious fervor about this, but try reading Avdi's [Objects on Rails][oor].
It's insanely cheap ($5) and shows how to apply OO Design to an example Rails app.

It will help you critically think through how you write Rails apps and the book walks
you nicely through Avdi's thought process including testing! On the down side, the
versions of Ruby and Rails used are a *wee* bit old and Avdi's style is slightly unusual.
That said, there's much to learn here.

If you enjoy this, you may also want to look at [Rails As She Is Spoke][rasis]
by Giles Bowkett. I haven't had the opportunity to go through it but Giles,
while controversial, tends to have valuable perspectives. It's nice to see
someone address the non-Object Orientedness of Rails directly.

[oor]: http://objectsonrails.com/
[rasis]: http://railsoopbook.com/

#### Project: Unit Testing Practice (R)

A couple ideas:

* Go back and try to write a tested, terminal version of checkers, battleship, or
  another terminal game. (Games have a wonderful way of forcing you to focus on careful logic.)

* Try adding tests to your final project with *Rspec*. We didn't cover it in class but there
  are a healthy number of companies that enjoy using it. The syntax is different from MiniTest
  but the core concepts and approach to testing are the same. There are plenty of blog articles
  about using Rspec with Rails and some good talks on [confreaks](http://confreaks.tv/tags/5).

#### Smorgasborg (R)

There are countless other useful resources that are worth taking a swing at if you're looking
for ways to practice keeping your skills fresh. Here are a few:

* Complete the [Ruby Koans](http://rubykoans.com/) (ruby, testing)
* The awesome [Justin Herrick][jah] at TIY Austin wrote a [Final Assessment][final].
  Take it! (and hit me up if you're stuck or unsure about anything)
* Might be good to sign up for [exercism.io](http://exercism.io) and just do a half
  dozen problems every day or two.

[jah]: https://twitter.com/jah2488
[final]: https://github.com/tiy-austin-ror-jan2015/postwork/blob/master/FinalAssessment.pdf

### 3-6 months post-graduation

At this point you should be employed (hopefully happily!) in the tech industry.
It is totally reasonable at this point to just be keeping up with your job and
enjoying some well deserved rewards. If you want to broaden your horizons,
here are a few night projects worth looking at.

#### Book: SICP (At least Chapters 1 and 2) (F)

[SICP][sicp] is the book that got me started on programming. If you'll excuse the
appeal to authority, just google about it and see how many best programming books
lists it pops up on! Even in the last week when one of my favorite hackers,
[Luke Gorrie tweeted about it][books-tweet]. Oh, and here's a
[glowing endorsement of SICP][sicp-review] from Google's Director of Research.

I have to admit I haven't finished SICP. I only read Chapters 1 and 2. SICP is pretty
challenging but I cannot think of a better source for getting comfortable with the
fundamentals of programming. It's free online and there are countless resources (including
[MIT's video lectures][sicp-lectures]) for it. Additionally, I would super love to be in a
study group or talk through any of the exercises with you! :heart:

You're missing a huge amount if you don't do some of the exercises. You don't have to do *all*
of them but make sure to do some in each section to stretch your brain. They are amazing.
You'll want a version of Scheme to work through them. Try [Racket][racket].

[books-tweet]: https://twitter.com/lukego/status/632450443566780416
[sicp-review]: http://www.amazon.com/review/R403HR4VL71K8/ref=cm_cr_dp_title?ie=UTF8&ASIN=0262510871&channel=detail-glance&nodeID=283155&store=books

[sicp]: https://mitpress.mit.edu/sicp/
[sicp-lectures]: http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/
[racket]: http://racket-lang.org

#### Book: Eloquent Javascript (At least Chapters 1-6) (R+)

[Eloquent Javascript][elojs] is written by an incredible hacker, [Marijn Haverbeke][marijn].
It is, in my opinion, the best current book for learning Javascript from scratch. Better yet,
it's free. Being knowledgeable about both Ruby and JS is a *huge* buff to your resume. While
the first 6 chapters teach you the core of Javascript, it's later chapters that teach
how it interacts with the browser and how to meaningfully use it in web apps.

If you're really feeling excited about Javascript after this, try reading the source code
to the [Backbone.js][backbone] framework front to back. It's only about 1500 lines of code.
It's super readable, clean code, and you'll get a solid understanding of many problems
MVC Frontend frameworks are trying to solve.

[elojs]: http://eloquentjavascript.net/
[marijn]: http://marijnhaverbeke.nl/
[backbone]: http://backbonejs.org/docs/backbone.html

#### Project: Read Some Good Code (R, P)

I feel very strongly that reading other code by good programmers is one of the best ways
to learn. There aren't a ton of Rails projects I can recommend but three do come to mind:

* [lobste.rs][lobsters]: A *real* reddit-like site focused on good programmer discussion.
* [med-link][medlink]: An app used by the Peace Corps to coordinate supply shipments.
  (And written by TIY's own James Dabbs :heart_eyes: We go way back.)
* [toot][toot]: A command line twitter client written in a nice, tested Object/Functional style.

It would be worthwhile to watch [this RailsConf talk][rgc] and browse [their site][rcg]
or [awesome-rails][a-rails] for interesting projects to try reading. Try to rope in
some other students for a reading group!!!

If you are looking for some interesting non-ruby code bases to read, well ...
I've got an ever-evolving list of recommendations. Hit me up! :)

[rgc]: https://www.youtube.com/watch?v=mW_xKGUKLpk
[rcg]: http://www.readingcodegood.com/
[a-rails]: https://github.com/ekremkaraca/awesome-rails
[lobsters]: https://github.com/jcs/lobsters
[medlink]: https://github.com/peacecorps/medlink
[toot]: https://github.com/bf4/toot

### 6+ months post-graduation

At this juncture, you are hopefully settled comfortably at a job you enjoy,
learning and challenged but "beyond the terror". At this point, you may want
something different and weird to play with at night to explore the wide world of code.

It's around this point that it would be reasonable to start playing with a new
programming language or two. Here are a few suggestions...

#### Deeply Understand OOP

I have heard nothing but amazing things for years about Smalltalk Best Practice Patterns.
But who writes Smalltalk anymore? It doesn't matter. A huge thing I've learned during
my career is that great tech books are only really written about 2 or 3 times a *decade*.
I finally started reading this and it is amazing. You'll be able to apply the concepts
to Ruby just fine, since Smalltalk was a big inspiration for it.

Watch this 10 minute [Smalltalk Demo][small-avdi] by the awesome Avdi Grimm.
Then, get a copy of [Smalltalk Best Practice Patterns][sbpp]. I've heard it's
also available free online but haven't tracked down a link. I like paperbacks and it's cheap.

I'm happy to explain any Smalltalk syntax questions. It's true that not many folks
use Smalltalk these days but Avdi is right that [Pharo][pharo] is free to download
and very cool to play around with!

[pharo]: http://pharo-project.org
[sbpp]: http://www.amazon.com/Smalltalk-Best-Practice-Patterns-Kent/dp/013476904X

(Free draft: http://stephane.ducasse.free.fr/FreeBooks/BestSmalltalkPractices/Draft-Smalltalk%20Best%20Practice%20Patterns%20Kent%20Beck.pdf)

#### Book: Functional Programming in Scala (P)

There is no easy road to a completely new programming paradigm. Everything will
seem alien at first but that's good. It's the sound of your brain stretching.

I think an excellent place to start is [Functional Programming in Scala][fps] and my friend
[Paul Snively's review][psr] speaks to why. It's a bonus that Scala is ultimately a
hybrid Object/Functional language and that its usage in industry is growing.

If you're still hooked and want more after that, or Scala is completely
unappealing to you, maybe get a look at programming in a
more "pure" Functional language and read [Real World Ocaml][rwo] or [Learn You A Haskell][lyah].

[fps]: http://www.amazon.com/Functional-Programming-Scala-Paul-Chiusano/dp/1617290653
[psr]: http://www.amazon.com/review/R8P9W8Z7QXLWW/ref=cm_cr_dp_title?ie=UTF8&ASIN=1617290653&channel=detail-glance&nodeID=283155&store=books
[lyah]: http://learnyouahaskell.com/chapters
[rwo]: https://realworldocaml.org/v1/en/html/

#### Smorgasborg (P+)

Here's a scattering of other excellent texts, mostly with a stronger CompSci bent if
you want to get deeper into specific areas.

Read **good** code, thoughtfully and carefully explained, meditate on software *design*:
* Thinking Forth
* Paradigms of AI Programming (see [this review][paip-review])

Learn about Algorithms for that R&D position you've been wanting:
* Algorithm Design by Kleinberg/Tardos

Figure out how the OS and the machine work "under the hood":
* Computer Systems: A Programmer's Perspective by Bryant/O'Hallaron

Figure out how the hell programming languages work and how to make one:
* Essentials of Programming Languages by Friedman/Wand

[paip-review]: http://www.amazon.com/Paradigms-Artificial-Intelligence-Programming-Studies/product-reviews/1558601910/ref=cm_cr_dp_synop?ie=UTF8&showViewpoints=0&sortBy=bySubmissionDateDescending#R26TS0X19V6HJ4

## Happy Hacking

Welp, that's it. Every strong jumping off point I could think of.

I'll likely add a few videos and blog posts to this over the next week but
what's most important is a starting point and I think this is a good one.

I haven't done everything on this list myself and that is okay! We've all
got to pay the bills and get away from computers too. Remember to
have a beer and some time in the sun with loved ones.
I'm here if you have questions or feedback.

Thank you for being my students. :beers: :balloon: :tada: :heart:
