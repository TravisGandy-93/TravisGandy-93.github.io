---
layout: post
title:      "Sinatra can get CRUDdy"
date:       2020-08-25 17:01:19 +0000
permalink:  sinatra_can_get_cruddy
---


I've literally just finished this Sinatra portfolio project so emotions are high right now. Sinatra on its own is a Domain Specific Language used for writing web applications. It has some pre-written methods in it that can make an app into a Ruby web app. The web app I created needed to interact with a database however so I called in good ole Active Record to help his buddy Sinatra out. The way im framing it in my mind so I hold on to it is this: 
Models, Views, and Controllers aka MVC. 
"Activerecord is the M to Sinatra's V you C".
All the data in the Models goes to the data tables at Active Record's House. All the app logic goes to erb files in Sinatra's view. Finally You(the programmer) connect the data to the logic with routes in the Controller.
With that being said this was still pretty tough. I blame most of my struggle on personal stuff but I'd be lying if i said i didnt get tripped up a lot. I created a Module to slugify object names to be compatible with how url's are written after realizing my app would crash from a simple blank space. For some reason i could only get it to work on one of my models when they looked almost identical. I ended up finding an ugly work around after a day of desperately staring at the terminal so here's looking forward to refactoring. 
