---
layout: post
title: Barcamp Mumbai 2006
---

To start with I must say BarCampMumbai was as coOL as its theme ‘Bindaas
Geeks | Hackin over Vada Pav' Some highlights :

-   3 simultaneous tracks named 'VadaPav, Bhaji on the Beach and … don't
    remember the name (?)
-   I just loved the wiki-like scheduler at the venue. Stick a note with
    ur name and topic on the board. I moved my my note thrice ;-) .
    Finally I just let it be….. and then [Tarique][] moved it to the
    best slot (first on after the lunch break)
-   Loads of people who I knew but never seen/met in person.
    [http://barcamp.org/BarCampMumbai\#ConfirmedParticipants][]
-   The food… :p
-   Some thoughtful sessions
-   My talk (…LoL! Now I can say Been there | Done that! … a nice
    experience for me)
-   … Lots more… check the [BarCampMumbai][] wiki for what others had to
    say.
-   The conference extended after sessions too. Mahesh Murthy from
    [Pinstorm][] decided to drop me and [Barkha][] home. We ended up at
    his office and him showing us around his coOL work place. By the way
    his was one of the coOLest talks at BarCampMumbai. (Don't tell me
    you missed it :p)

What I presented @ BarCamp ? Topic:

> TagSurfer - Extending the TagCloud

Motivation:

> Unlike categories which are strict in nature tags are flexible.
> Flexibility of tags also comes from the fact that we use multiple
> words (keywords) to define a single item. eg: barcamp barcampmumbai
> tagsurfer hacks Now I would love to have a mechanism by which I could
> actually find some related content or may be just digg through the
> right content. TagClouds is a good way of doing it. Its intuitive and
> looks good. But seriously its just 1D… I click on one tag and I am jst
> shown entries tagged with that particular tag. As the number of tags
> entries (or no. of entries in your blogs or photoblogs ) increase one
> would surely need more intuitive UIs than TagClouds I did give
> examples of del.icio.us and flickr in my talk. I also commented that
> deli.icio.us doesnt allow me to search for entries tagged with 'ajax
> and css'. Here is what I meant.
> If I search for '[ajax css][]' in the search box on del.icio.us I am
> given with links that are tagged with 'ajax
> or css' and not necessarily
> with 'ajax and css'. Try '[ajax
> on my bookmarks][]‘… you wud be shown links and on the right presented
> with 'related tags' links . Now this is interesting. If I click on the
> small ‘+' sign beside scriptalous I get all the links tagged with
> 'ajax and scriptalous' only. (…
> correct me if i m wrong :) Newways…. more importantly TagClouds are
> jst 1D! and there is a lot we can do to improve them…!

Proposed ‘TagSurfer':

> TagSurfer is a TagCloud with added functionality of
> surfing through the tags. Its
> more like getting deeper and deeper within the tagcloud. Here is a
> small limited demo: [~~http://akshay.zeeblo.com/soc~~/][] \*Check the
> right panel with heading tagsurfer.
>
> -   Just hover your mouse over any of the tags… \* DO Not Click :d
> -   Number in brackets show the no. of entries you would find after
>     surfing that tag
> -   Superscripts show the order in which you surfed
> -   Top panel with images resembling ‘<' - Back and ‘o' reload
> -   Lots of functionality could be added like if you surfed through a
>     few tags and then clicked on one then you would be shown entries
>     within that path only. eg: ‘barcamp -\> barcampmumbai' is what you
>     surfed through and finally click on ‘hacks' you would be shown
>     entries tagged with barcamp and
>     barcampmumbai and
>     hacks

What it used:

> PHP + Prototype ( ;-) Ajax ) Yup this was my first attempt to
> incorporate Ajax. TagSurfer needed Ajax and thats why I used it. It
> wasnt redundant at all.

Acknowledgements:

> Pradeep for allowing me to make a presentation for [TagSurfer][] on
> his laptop. And Mohit, Abhishek, Atul, Ajay, Hitesh, Ajay, Narain,
> Kiruba, Murli and everyone who attended for making BarCampMumbai a
> reality and offcourse RocKiNg!!!

Download:

> ~~[http://akshay.zeeblo.com/tagsurfer.zi][]~~

  [Tarique]: http://tariquesani.net/
  [http://barcamp.org/BarCampMumbai\#ConfirmedParticipants]: http://barcamp.org/BarCampMumbai#ConfirmedParticipants
  [BarCampMumbai]: http://barcamp.org/BarCampMumbai#Bloggers
  [Pinstorm]: http://www.pinstorm.com/
  [Barkha]: http://spaces.msn.com/barkha/
  [ajax css]: http://del.icio.us/search/?all=ajax+css
  [ajax on my bookmarks]: http://del.icio.us/ak47surve/ajax
  [~~http://akshay.zeeblo.com/soc~~/]: http://akshay.zeeblo.com/soc/
  [TagSurfer]: http://barcamp.org/f/TagSurfer.ppt
  [http://akshay.zeeblo.com/tagsurfer.zi]: http://akshay.zeeblo.com/tagsurfer.zip
