## Starting a new project

A different kind of project than I'm used to

February 7th, 2015

Blips has been completed for sometime now yet with existing changes I still want to make but I needed a break from that
app. I had been working on Blips for roughly a year and a half by the time we launched it and put out our first update.
I was at the point of exhaustion even when thinking about working on it, so I took a break and didn't work on anything.
Knowing me though I eventually was needing a project to work on, that's just how I am. I genuinely love working through
problems, solving complex issues, designing experiences, and being innovative. This must be why I'm a software developer.

![Blips website capture](Blog/Starting_a_new_project/blips1.png "Blips was the largest project that I ever had the pleasure of working on")

While I was driving one day I noticed that my music had stopped playing, I ran out of music. This is my fault because
when I got my iPhone 5 I never transferred the music from my iPod onto it or didn't make sure I had the iPod on me.
Regardless of those two facts, the truth remains the same: I don't have enough room on my iPhone to store all my music,
have a nice selection of apps, and develop new apps. What I've come up with to remedy my situation is slightly backwards
thinking but it also presents me with a unique opportunity to develop a service I might not have thought of otherwise.

![Early drawing of CloudMusic](Blog/Starting_a_new_project/earlydrawings1.jpg "Early concepts of what I wanted the CMS to look like")

I wanted to create a service or a tool rather that lets you store your music in a central location, have be secure,
easy to use, and work on any device(the streaming portion, not the CMS which I wanted to be desktop only). What I am
calling *CloudMusic* is just that, or at least it will be. It's essentially a self-maintained iTunes in the cloud, it actually
uses iTunes' servers to gather some extra metadata when you upload music files. I've only just begun the process of building
CloudMusic out and have a long journey ahead but I have the same feelings that I had when I started writing Blips, back then
it was called *Video-a-day* or *VAD* for short, which is joy and wonder and excitement.

I'm taking a lot of risks with this project but that's what makes it so exciting. It's not a project for others, while it
sure could be at some point, but it's for me and will solve a real problem in my life. I'm writing the client in Dart,
the server in Python using Flask+Tornado which is the same server technology the Blips server is built on, and it will
run on a Raspberry Pi. I want to also incorporate a physical aspect to it beyond simply running the server on an embedded
system in my car. I'm thinking of showing basic information on a heads up display using an LCD that connects to the Pi's
GPIO pins, they are inexpensive and will let me see what's playing without having to look at my phone, or I might use the
display to tell me when the server is up and running and some stats about what's going on under the hood.

I'll keep producing updates on this blog as I make progress with the project, which is why I started the blog in the first
place. Until then I must get back to work.