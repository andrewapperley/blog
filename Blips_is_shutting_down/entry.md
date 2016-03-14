## The Blips Servers will be shutdown

This was the most stressful, yet most intriguing project I have ever worked on

June 16th, 2015

I started Blips back in 2013 when my now Fiancée and I wanted to have a central place to share photos or videos which was secure and easy to use, I also wanted to work on a project. Little did I know it would amass into such a big endeavour. The original designs were horrid compared to the final designs, but that was mostly due to the fact that I didn't think the public would ever see the app and I was more focussed on the engineering side than the design.

![Early Blips Start Screen Mockup](Blog/Blips_is_shutting_down/early_mockup.png "The original designs were horrid compared to the final designs")

A few months had passed since I started the project with a basic understanding of what I wanted to accomplish and the building blocks of a server and client side application to show off to people. Nothing really worked, the designs weren't the greatest, and the server was held together by strings yet a colleague of mine still wanted to join the project to flush out Blips to its fullest potential. Having him join the team was such a blessing as he has an eye for design, knows when something can be better, and brought top notch iOS skills to the table that really helped propell Blips forward for the better. While I mainly focussed on server side development and integration with the client side, Jeremy focussed on polish client side. The beautiful timeline view in the app is all due to his hard work over a few months.

![Blips Timeline View](Blog/Blips_is_shutting_down/timeline_view.png "The beautiful timeline view in the app is all due to his hard work")

The project as a whole is completely over-engineered and covers far too much ground feature wise for such an app in it's first version. We didn't want to launch an incomplete app but also didn't want to keep adding features, even though at the time they made sense but by the end even the features that did make it in were too much. We had private and public timelines, per user timelines, favourite timelines, full profiles, CDN based asset management, load balancers with 4-5 servers waiting to be deployed, dedicated database servers, a robust video creation workflow, a very well thought out database schema setup, multiple CRON jobs setup to handle daily tasks, etc. Not everything was unnecessary but we could have shipped with less and added later, which is one of the reasons it took us over a year and a half to complete the project from inception to ship date. Once it launched we submitted two bug fixes and started discussing next steps. From these discussions we came to the conclusion that we were burnt out and didn't want to touch another personal project for a long time, which I have moved on to other projects but they were mostly experiements or smaller ones. We have learned a lot from this experience but the servers must shutdown soon. At the end of June they will be turned off and the app will be pulled from the App Store. It simply comes down to cost to run the servers vs user traffic, which there is virtually none to speak of. Which is sad but a reality that we have come to terms with. Thank you for everyone that supported the project and to anyone that used it I hope you enjoyed your experience, even if it was brief.

![Blips Banner](Blog/Blips_is_shutting_down/blips_banner.png "Thank you for everyone that supported Blips!")

Until next time, I must get back to work.
