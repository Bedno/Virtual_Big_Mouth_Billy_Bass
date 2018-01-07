Seeding a repository for planned recreational coding project of developing a *Virtual* Big Mouth Bill Bass.

Modifying the popular "Big Mouth Billy Bass" toy to speak from external inputs has been a standard hacking project for decades.
These days however, would could skip the hardware and simulate the entire experience on any convenient monitor.

Though talking parrot apps were around since late 80s and Max Headroom, and virtual newscasters were a thing by the late 90s, in recent searches on the topic I was unable to find any modern examples.

I case an open source generalized simple talking animated character framework does not yet exist, I hearby establish this space as a place to spread notes on the idea.

IDEAS:

Idea 1: Native App (limited platforms): I could see doing this easily as a Visual Basic app, which could readily monitor audio streams and render animations from sets of partial images.  However I haven't compiled a local executing application in years, and dislike the operating system dependence of it.

Idea 2: Browser Based (must use text-to-speech): I could see implementing the animations fairly eaily in Javascript, however browser don't currently implement audio input that I know of.  But text-to-speach is well implemented in modern browsers.  I don't think however that one can capture the phoneme expansion nor total duration of the speech, so animation would be approximate.  But I think this is workable.

Compromise idea: Browser based, aopproximate animations, text to speech, limited to standard announcements such as weather, time, random words of wisdom...

EXAMPLES:

Analog talking Billy Bass "modding" implementation:
http://www.instructables.com/id/Animate-a-Billy-Bass-Mouth-With-Any-Audio-Source/

Browser-based text-to-speech weather forecast:
http://bedno.com/iwall

3D talking head virtual narrator newscaster sofwtare:
https://en.wikipedia.org/wiki/Ananova

