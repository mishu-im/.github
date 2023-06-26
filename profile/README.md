# Someone to Argue With

<br />
<p align="center"><img src="https://github.com/mishu-im/.github/assets/30414693/e3e8af91-7c73-4ab6-bafe-9780ecddded4" /></p>
<br />

["Someone to Argue With"](https://mishu.im) takes the idea of ["Chatroulette"](https://chatroulette.com/), a chat between complete strangers, and gives it a unique twist. First choose the side you belong to, and the system will randomly find you someone from the other side to argue with. In a completely anonymous conversation, you can bridge the great gaps in the society or deepen the divide to your pleasure.

<br />

## Background

The website is based on ["Someone to Argue With 2014"](https://www.haaretz.co.il/captain/net/2014-08-11/ty-article/0000017f-e061-d38f-a57f-e6736bb10000) created by Eyal and Asaf Geva after the "Tzuk Eitan" operation. The website of the Geva brothers brought together people from both sides of the political map and provided them with a platform to pour their hearts out, anonymously.

In preparation for the Knesset (the parliament of Israel) elections in November 2022, the 5th election in about 3.5 years, the website relaunched by [Tal Israeli](https://github.com/talisraeli) in order to help those who are looking for a place to vent their anger about another election, and rage on the other side. He renewed the design and user experience to the modern standard of 2022. In addition, He added new features such as viewing and sharing conversations after they was ended.

The website went viral days before the elections and in the week during the elections, the website was recorded with over 60,000 users and 180,000 conversations between rightists and leftists. Articles on the major news sites in Israel and abroad were written on the website.

<br />
<p align="center"><img src="https://github.com/mishu-im/.github/assets/30414693/a4963edc-9555-413d-97f3-5b027e55cae8" /></p>
<p align="center">A conversation between two guests on the website before the elections.</p>
<br />

## Rebranding

At the beginning of 2023, the site was released in a new and expanded version as part of a collaboration between Tal Israeli and [Jonathan Rashi](https://jonathanrashi.com/). The website was expanded to the various topics that can be argued and discussed, such as soccer and religion, and underwent a rebranding and redesign. Also, each user is given a wider range of choices in their self-definition. Today, the user can choose a nickname, gender, profile picture and identify himself according to a preferred topic group: politics, sports or religion.

The current version is developed by Tal Israeli (CEO, Research & Development) and Jonathan Rashi (Partner, Research & Design).

<br />
<p align="center"><img src="https://github.com/mishu-im/.github/assets/30414693/49ab03cc-da9f-451e-8a12-e144ae45ff4b" /></p>
<p align="center">The current home page of the website.</p>
<br />

## Development

Before starting the development of the application, Israeli was planning the creative, functional, structural and architectural patterns of it. He explored the design and function of the original website created by Geva brothers, and made his changes which he thought made it better and match the modern technologies and clients of 2022.

He chose to develop the application as a [Progressive Web App](https://en.wikipedia.org/wiki/Progressive_web_app) (PWA), which he can develop for all platforms: web, desktop and mobile; with a single code base. He followed the SOLID design principles when coding, providing some important benefits to the development. Also, he chose to use automation tools to help him develop the application more productively, such as [GitHub Actions](https://github.com/features/actions) and [Dependabot](https://github.com/dependabot/dependabot-core) to always keep packages up-to-date.

In order to start the development, he designed the look of the application through [Figma](https://www.figma.com/) (Rashi mainly designs the application currently), and chose the technologies which will be used to create it. He chose [ASP.NET](https://www.asp.net/) for the back-end side, along with [Entity Framework Core](https://github.com/dotnet/efcore) and [SQL Server](https://www.microsoft.com/en-us/sql-server/) to manage data, and [SignalR](https://dotnet.microsoft.com/en-us/apps/aspnet/signalr) for the real-time communication. For the front-end side, he chose [Vite](https://vitejs.dev/) [React](https://react.dev/), along with [TypeScript](https://www.typescriptlang.org/) and [Sass](https://sass-lang.com/), and [Redux Toolkit](https://redux-toolkit.js.org/) and [Redux Persist](https://github.com/rt2zz/redux-persist) to manage data. For the hosting provider, he chose to use [Azure](https://azure.microsoft.com/en-us). For the SEO, he chose [Google Analytics](https://analytics.google.com/analytics/web/). For code version control, he uses [GitHub](https://github.com/).

<br />
<p align="center"><img src="https://github.com/mishu-im/.github/assets/30414693/a820cdbe-5e49-4a99-a2b3-60aac52e2901" /></p>
<p align="center">PWA allows cross-platform development with a single code base.</p>
<br />

## Featured Articles

<br />

> The app for letting off steam about the elections: if you are politically active, you have something to say and you don't know to whom, we have found the ultimate app for you. A website created by a guy named Tal Israeli allows you to start a conversation with someone on the other side and have an anonymous conversation. It may sound like curiosity, but this is an addictive app.
>
> -- [Kipa News](https://www.kipa.co.il/%D7%98%D7%9B%D7%A0%D7%95%D7%9C%D7%95%D7%92%D7%99%D7%94/1144459-0/)

<br />

> So, a guy named Tal Israeli built a website called "Someone to Argue With", that allows you to have a conversation with someone on the other side and conduct an anonymous discussion. I think this is the most genius thing I've seen lately. I highly recommend trying it!
>
> -- Rafa Goichman, [TheMarker](https://www.themarker.com/captain-internet/2022-10-31/ty-article/.premium/00000184-2eaf-d8ca-a3ff-bfffffa50000)

<br />

> Tomorrow we will go to vote for the fifth time in three years, and if you have not yet exhausted this matter of debating politics - get to know the website that allows you to do it.
>
> The website is called "Someone to Argue With, 2022 Elections", and it works in a very simple way. You have to choose which side you are on - right or left, then a chat will open for you and a user from the opposite side will join you. From here - the correspondence is in your hands.
>
> -- Dana Guterzon, [mako](https://www.mako.co.il/nexter-news/Article-841ed8bdb4e2481027.htm)

<br />

> The networks have gone crazy when they found out about the existence of "Someone to Argue With", an application in which conflict is sought directly.
>
> Now, thanks to an application that is starting to become fashionable, you can find a partner to do what you usually try to avoid (sometimes without success) in love: argue. An Israeli company has created an app called "Someone to Argue With" in which users can search for opponents with whom to confront their arguments.
>
> -- David Sánchez de Castro, [ABC News](https://www.abc.es/tecnologia/moviles/aplicaciones/mishu-tinder-gente-quiere-discutir-20221101114954-nt.html)
