# Laravel Toronto meet-up, December 14, 2023
- food and beverages sponsored by [YTZ International, Inc](https://ytz.com)
- thank you to Nuno Souto, and to YTZ International, for making this meet-up happen!
- washrooms
- GitHub organization: "local-toronto-php-groups"
- each meet-up has its own repo.. for general itinerary and notes, for post-meet-up notes and pics
- our January 25th meet-up is at Microsoft Canada. Go to our meetup.com for the link to Microsoft to register.
- I asked meetup.com to change our Group's privacy setting from "private" to "public"

##
Meetup.com listing: [https://www.meetup.com/gta-php-user-group-toronto/events/296531813/](https://www.meetup.com/gta-php-user-group-toronto/events/296531813/)

##
New from Laravel:
- [https://laravel-news.com/announcing-laravel-pulse](https://laravel-news.com/announcing-laravel-pulse)

##
Unfortunately, due to time pressures, Astrid Bailey and Katrina James are unable to do the preparation for their "Laravel Application From Scratch" presentation.

Lukasz Zagroba emailed me with a great question, and a tremendous inspiration. THANK YOU! Why not try out "Mob Programming"? Even though I have never tried it, nor Lukasz, and none of our Groups have tried it, why not go for it anyways? 

I know that the Guelph PHP User Group, run by Canada's only Laravel Partner, Vehikl, who helped get Laravel Toronto off the ground in the early days with SoapBox, uses Mob Programming, and does it from time to time at GPUG. I know this because Colin gave me a personal tour at Vehikl's offices in Waterloo and described what they did. 

Ah.. here are the GPUG meetups:
- [Laracon Special - Mob Programming with Vehikl](https://www.meetup.com/_gpug_/events/288382468/)
- [Laracon Special - Mob Programming with Vehikl](https://www.meetup.com/_gpug_/events/283489764/)

I thought that the way to go about doing this would be to, basically, plan the shit out of it. Divide the meet-up into 15 minute segments, assign roles, and dictate the basic app to be done. Except that this is pretty much contrary to the "soul" of Mob Programming.

Instead, I think that this thing needs to have a "life of its own". We'll see what happens!

I think that the one thing that makes this Mob Programming session different from what I've learned so far about it, is that we are doing it at our meet-up. The purpose, ultimately, is for people new to the Laravel Framework, to see how a Laravel Framework based web application is created and developed. The purpose, ultimately, is learning, not doing the app! A big attraction about trying out Mob Programming in our meet-up is that it is, by its very nature, highly interactive. 

This is a rare opportunity to ask your questions!

We need one computer for development. Is there someone who is ok for providing this computer? And to correspond through email with me about the set-up?

At the meet-up, better that I monitor the time segments, greet late-comers, be available for side-questions, and gently guide the overall process. Nuno did provide popcorn at YTZ International's first meet-up, so if there is popcorn on the 14th I will be enjoying it, watching this process play out. 

We need someone to "drive" the computer, and someone to "navigate" the driver. Meaning, the "driver" types, but is not supposed to take part in what they are typing. When the "driver" has an issue, they need to raise it. The "navigator" is quite a role. There is supposed to be, or can be, a third hard role, of someone representing the user side of the app being developed. However, I think the "navigator" should lead the discussion, perhaps in a chaotic kind of way. For once, at a meet-up, everyone talking at once might be acceptable! Again, Nuno, will there be popcorn?

I feel strongly that we have one "navigator". The role, for the purposes of our meet-up, is more a leader of the discussion. Who guides the discussions into decisions. Easier said than done, eh!

There are many ways to go about bootstrapping a Laravel Framework based app. You can create a project from the [https://github.com/laravel/laravel](https://github.com/laravel/laravel) repo. You can [https://github.com/laravel/breeze](https://github.com/laravel/breeze). I think the group should decide.

My one caveat is to be reasonable about introducing complexity. The main thing is for devs that are new to the Laravel Framework get a sense of how to do a Laravel based web app from scratch. For example, the goal is not to demonstrate Livewire, so if using Livewire is complex, then let's not use it. I really do not know where the demarcation line is, but keep it in mind, and be open to the vocalizations about where the boundaries might be. 

I do not know what app to build. I think a "To Do" app is perhaps too simple. It is certainly too cliche. And perhaps will not hold attendees' attention enough. So this will be the first thing to "Mob" about.

I think the initial segment or two, we should plan who is doing the "driver" and "navigator". Then, let the group decide on who does these roles. 






##
- [Mob Programming and the Power of Flow • Woody Zuill • GOTO 2019 (YouTube video)](https://www.youtube.com/watch?v=28S4CVkYhWA)
- [Mob Programming Surprised Me (YouTube video)](https://www.youtube.com/watch?v=ikilHGYk5Fs)
- [A day of Mob Programming 2016 (YouTube video](https://www.youtube.com/watch?v=dVqUcNKVbYg)
- [A day of Mob Programming (YouTube video)](https://www.youtube.com/watch?v=p_pvslS4gEI)

## Post Meet-up Comments
Thank you to Nuno Souto and to YTZ International for hosting our meet-up. We had a dozen Artisans attend. This time of year, it is very hard to guage attendence. The weather held up, and we did well.

Our first try with Mob Programming went well, mostly. The active participation, and willingness to give it a try, is what really made it successful. 

The ultimate purpose of the exercise was to give developers who are new to the Laravel Framework a chance to see an app built from the ground up. Along with the opportunity to ask questions each step of the way. The more seasoned artisans got a lot out of it, if not more, as it was a refresher of doing an app from scratch. 

One seasoned Artisan said that back-in-the-day it was much simpler bootstrapping a Laravel app. Now, there are more decisions that you have to make up-front, before doing a ```composer update```.

One lesson that was re-learned is that you absolutely need to set up your local development first. Nuno gave us a wonderful real-time demonstration of [Laravel Valet](https://laravel.com/docs/10.x/valet). Personally, I decided to finally try Docker for local development, and am glad that I did. Which is to say that there are various ways to go about local development. 

The Laravel Project offers many starter packages. Deciding which to use requires understanding your use case. And, deciding on what front-end framework you want to use. And, being familiar with the starter packages that the Laravel Project offers. 

It was decided that doing a "to do" app was just too pedestrian an app to do. Instead, we should do something more exciting. The assumption was that we would race through doing a basic CRUD app using the classic "MVC" structure, and so would need something more intensive to keep the Mob Programming exercise going. 

Oh... how wrong we were! First of all, no one person was familiar with all the various Laravel Starter Packages. So we had to look those up in real-time. Mainly between Jetstream and Breeze. Then, there was a brief, but intense, back-and-forth about which front-end framework to use. Naturally, I eschewed them all, wanting to stick with basic Blade. Consensus went with Livewire, so Livewire it was. And, it turns out, no one quite knew Livewire enough to do real-time live coding. Or, maybe more accurately, we are used to our toys, and without those installed, we ground to a big ol' halt! Ah.... getting back to "First Principles" is not so easy!

This was an issue with coding routes, controllers, models, and views from scratch. Someone new to the Laravel Framework is not going to know how. But... we found out that some of using Laravel might not remember either. There is more looking-things-up than we thought. Hand crafting a database migration file took some effort, especially the foreign key ID field. 

There is an Artisan command to create CRUD files at the same time. There is a route method that short-cuts having to list all the controller "action" methods individually. All these conveniences may contribute, I think, possibly, to not quite understanding the nauances of some things. 

We ran out of time before we knew it. Getting bogged down in shockingly basic stuff.

Lukasz is spot-on, saying that for the next time, we need to arrange Artisans of varied skills to attend -- and then participate. Yes!

I do want to give "Mob Programming" another try, now that we have our first one under our belt. To organize it, maybe I should be like a General Contractor. Have an architect design the overall thing. Then, bring in sub-contractor trades to do the work. The cememt company to do the concrete forms and pour the concrete. The carpenters to frame it. The plumbers, dry-wallers, electricians, etc. 

What I really enjoyed about this meet-up was how participatory it was. A nice break from presentations!



##
![YTZ International's entrance @ Graffiti Alley](/2012dec14_laravel_toronto_ytz_intl_entrance_graffiti_alley.png)
![Bob introducing the meet-up](/2023dec14_laravel_toronto_bob_introduction.png)
![Mob Programming with local Artisans](2023dec14_laravel_toronto_artisans1.png)
