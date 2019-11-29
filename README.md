# [SymfonyCon - Amsterdam 2019](https://amsterdam2019.symfony.com/) talks

- All talks are in **english**.
- You can send feedback and love to speakers on their twitter account

## Keynote

~~Slides~~  
~~Video~~

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## HTTP/3: It's all about the transport!

<dl>
  <dt>Description</dt>
  <dd>The announcement of HTTP/3 at the start of November 2018 may have come as a surprise for a lot of us.

Indeed, compared to the 8 years that separated HTTP/1.1 et HTTP/2, this announcement came only 4 years after the release of HTTP/2.

But the biggest surprise is under the hood, with a replacement of the transport layer.

In this talk, we will explain why this version 3 of the HTTP protocol has been designed, especially around the latency topic.

We will cover as well how technically this version works, and what it will bring to our applications, and what are the challenges that will need to be addressed, in order to fully benefit from this new version of the protocol that runs the Web.</dd>
</dl>

[Slides](https://speakerdeck.com/bitone/3)  
~~Video~~

By [Benoit Jacquemont](https://connect.symfony.com/profile/bit_one)  
![github](icon/github.png) [@BitOne](https://github.com/BitOne)  
![twitter](icon/twitter.png) [@BJacquemont](https://twitter.com/BJacquemont)

---

## How to contribute to Symfony and why you should give it a try

<dl>
  <dt>Description</dt>
  <dd>I started contributing actively to Symfony three years ago. Not only is it a way to thank the project, but it's also an immense source of knowledge and communication for me. I would like to share my experience and to encourage contributions to Symfony.

What we'll discuss:

- how participation in an open-source project makes you a better developer;
- easy steps to join the Symfony ecosystem;
- where to get an idea for a pull request;
- branches and roadmap;
- coding standards, conventions and backward compatibility;
- rebase flow;
- review process.
</dd>
</dl>

[Slides](https://speakerdeck.com/vudaltsov/how-to-contribute-to-symfony-and-why-you-should-give-it-a-try)  
~~Video~~

By [Valentin Udaltsov](https://connect.symfony.com/profile/vudaltsov)  
![github](icon/github.png) [@vudaltsov](https://github.com/vudaltsov)  
![twitter](icon/twitter.png) [@vudaltsov](https://twitter.com/vudaltsov)

---

## A view in the PHP Virtual Machine

<dl>
  <dt>Description</dt>
  <dd>This talk is about how PHP works. We'll learn together how PHP compiles, optimizes then executes your scripts, both in the Web environment and CLI apps. We'll dive into PHP's source code - written in C - to extract some parts of interest and study them to better understand PHP's behaviors as well as best practices in terms of performances (CPU cycles and memory allocations).</dd>
</dl>

[Slides](https://www.slideshare.net/jpauli/php-engine/)  
~~Video~~

By [Julien Pauli](https://connect.symfony.com/profile/jpauli)  
![github](icon/github.png) [@jpauli](https://github.com/jpauli)  
![twitter](icon/twitter.png) [@julienPauli](https://twitter.com/julienPauli)

---

## How Doctrine caching can skyrocket your application

<dl>
  <dt>Description</dt>
  <dd>When people talk about Doctrine (or any ORM for that matter), the performance issue always comes up fairly quickly. Besides the fact that Doctrine will help you develop faster, so a little overhead doesn't really matter, there are numerous options to increase the performance of the application.

By understanding how the system works in the first place, a lot of issues can be avoided right away.

When you have done everything to avoid these pitfalls, you can bring in the big guns: caching. Doctrine has several caching mechanism and since Doctrine 2.5 "Second Level Cache" was added to our toolbox. After this talk, you should know what the impact is of every cache and how to use them.</dd>
</dl>

[Slides](https://speakerdeck.com/coudenysj/how-doctrine-caching-can-skyrocket-your-application-symfonycon-amsterdam-2019)  
~~Video~~

By [Jachim Coudenys](https://connect.symfony.com/profile/coudenysj)  
![github](icon/github.png) [@coudenysj](https://github.com/coudenysj)  
![twitter](icon/twitter.png) [@coudenysj](https://twitter.com/coudenysj)

---

## Using the Workflow component for e-commerce

<dl>
  <dt>Description</dt>
  <dd>We got the task to make an order API, from open order, to delivered, with payments in between and after. So there are naturally a lot of states, and a lot of transitions where we needed to calculate the prices correctly and handle credit card transfers. Keeping track of all of this, and when we need to do what, ensuring that an order is always up to date, and that it has the data it needs, and that we send good error messages when a user can not do an action, was a challenge for us until we discovered the workflow component.

This is a real happy use case story where I will show you how we did this, and how much more straightforward it was for us to build an otherwise complex system using the workflow component.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Michelle Sanver](https://connect.symfony.com/profile/michellesanver)  
![github](icon/github.png) [@michellesanver](https://github.com/michellesanver)  
![twitter](icon/twitter.png) [@michellesanver](https://twitter.com/michellesanver)

---

## Crazy Fun Experiments with PHP (Not for Production)

<dl>
  <dt>Description</dt>
  <dd>I’ll show you the crazy things you can do in PHP with streams and autoloader overloading to write your own language features. I’ll also show you how you can supercharge your Symfony applications using aspect-orientated programming or encrypt source code on-the-fly using only PHP. As if that wasn’t enough, we’ll go even further and make PHP a polyglot language by importing esoteric language scripts! These aren’t your average hacks and shouldn’t be run in production... but let’s explore these concepts as fun experiments so you’ll never think of PHP as boring again!</dd>
</dl>

[Slides](https://docs.google.com/presentation/d/1cTDYd4tNHH37MKbNEm1jqdMW-NcqaVU2MLIsUWtCs7k/)  
~~Video~~  
[Code](https://github.com/zanbaldwin/sfcon19)

By [Zan Baldwin](https://connect.symfony.com/profile/zanbaldwin)  
![github](icon/github.png) [@zanbaldwin](https://github.com/zanbaldwin)  
![twitter](icon/twitter.png) [@ZanBaldwin](https://twitter.com/ZanBaldwin)

---

## Hexagonal Architecture with Symfony

<dl>
  <dt>Description</dt>
  <dd>Symfony offers many excellent components for your web and console applications. But of course, you still have to implement your own application logic, create your own domain models, and write your own tests. So Symfony has its place, but it's not going to be everywhere in your application.

In this talk I will explain an architectural style called "Hexagonal Architecture", which will help you structure your applications in such a way that you can focus most of your development effort on the core of your application, designing it in a way that makes its production code sustainable and easy to test.</dd>
</dl>

[Slides](https://www.slideshare.net/matthiasnoback/hexagonal-symfony-symfonycon-amsterdam-2019)  
~~Video~~

By [Matthias Noback](https://connect.symfony.com/profile/mnoback)  
![github](icon/github.png) [@matthiasnoback](https://github.com/matthiasnoback)  
![twitter](icon/twitter.png) [@matthiasnoback](https://twitter.com/matthiasnoback)

---

## Crawling the Web with the New Symfony Components

<dl>
  <dt>Description</dt>
  <dd>When developing an application, a common feature we need to implement is gathering data from other sources. These data are available in various forms, usually unstructured, and behind some JS application, making them harder to reach.

To make things worse, as the application evolves, we need to get more data, from even more sources. But don't worry, things can be easier!

In this talk we'll use the Symfony's HttpClient, Messenger and Panther to build a crawler, first as a simple console application, then evolving to a distributed one.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Adiel Cristo](https://connect.symfony.com/profile/arcristo)  
![github](icon/github.png) [@adielcristo](https://github.com/adielcristo)  
![twitter](icon/twitter.png) [@adielcristo](https://twitter.com/adielcristo)

---

## Adding Event Sourcing to an existing PHP project (for the right reasons)

<dl>
  <dt>Description</dt>
  <dd>"Event Sourcing", along with "CQRS", have recently become trending terms, and now there is so much theory, blog posts and talks about them.

However, most of these deal with the problem starting from an utopian assumption: having to write a project from scratch, but at the same time with a high domain complexity right from the start, enough to justify the use of a complex technique like event sourcing and CQRS, which carry a fair amount of inherent complexity. But the reality greatly differs: projects are born from small and simple prototypes, and they accumulate complexity only with time, growth and evolution of specifications and features.

This talk is a case history in which I will tell you (with little theory and a lot of practical examples) how we decided to add event sourcing to an already existing project (without eradicating the rest or rewriting it), to solve a specific problem (reporting and its history) for which this methodology proved to be the perfect solution.</dd>
</dl>

[Slides](https://alessandrolai.dev/slides/2019-11-event-sourcing-symfonycon/)  
~~Video~~

By [Alessandro Lai](https://connect.symfony.com/profile/jean85)  
![github](icon/github.png) [@Jean85](https://github.com/Jean85)  
![twitter](icon/twitter.png) [@AlessandroLai](https://twitter.com/AlessandroLai)

---

## HYPErmedia: leveraging HTTP/2 and Symfony for better and faster web APIs

<dl>
  <dt>Description</dt>
  <dd>Over the years, several formats have been created to fix performance bottlenecks of web APIs: the n+1 problem, over fetching, under fetching… The current hipster solution for these problems is GraphQL. It’s a very smart network hack for HTTP/1, but a hack that is not necessary anymore with HTTP/2 and HTTP/3.

The new versions of the protocol of the web now have native capabilities allowing to create fast and idiomatic web APIs: multiplexing, server push, headers deduplication, compression, persistent connections (Mercure)… Leveraging HTTP/2 and HTTP/3 unveils the true powers of the web (hypermedia architecture) with no compromises with performance.

During this presentation, we’ll learn how to design our APIs to be able to maximize the benefits provided by HTTP/2. Better, Symfony already contains all the tools you need to create (WebLink, API Platform) and consume (HttpClient) such APIs. We will discover these gems together.

HATEOAS is the new hype!</dd>
</dl>

[Slides](https://speakerdeck.com/dunglas/2-server-push-and-the-rise-of-client-driven-rest-apis)  
~~Video~~

By [Kévin Dunglas](https://connect.symfony.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)

---

## PHP, Symfony and Security

<dl>
  <dt>Description</dt>
  <dd>Have you ever tried talking to someone about using PHP in secure applications? It's nothing new that we deal with prejudice against PHP every day and the situation is even worse when we talk about security. The latest versions of PHP provide security tools and modern cryptography and Symfony itself make its efforts to deliver robust security features that are simple to implement. We'll learn about the latest language and framework initiatives in this regard and check out short and quick tips for boosting you application's security.</dd>
</dl>

[Slides](https://speakerdeck.com/dianaarnos/php-symfony-and-security)  
~~Video~~

By [Diana Ungaro Arnos](https://connect.symfony.com/profile/dianaarnos)  
![github](icon/github.png) [@dianaarnos](https://github.com/dianaarnos)  
![twitter](icon/twitter.png) [@dianaarnos](https://twitter.com/dianaarnos)

---

## What happens when I press enter?

<dl>
  <dt>Description</dt>
  <dd>As a technical interviewer, one of the questions I like to ask the most is "what happens when I write www.example.com in the browser and then press enter?". The answer reveals a lot about the interviewee's understanding of a vast number of technologies that fringes web development.

In this talk, I will go through exactly what happens, down to excruciating detail, so that you will be better prepared for your future job interview.</dd>
</dl>

[Slides](https://www.slideshare.net/tobiassjosten/what-happens-when-i-press-enter)  
~~Video~~

By [Tobias Sjösten](https://connect.symfony.com/profile/tobiassjosten)  
![github](icon/github.png) [@tobiassjosten](https://github.com/tobiassjosten)  
![twitter](icon/twitter.png) [@tobiassjosten](https://twitter.com/tobiassjosten)

---

## Configuring Symfony - from localhost to High Availability

<dl>
  <dt>Description</dt>
  <dd>All apps need configuration: the database host, background color of your client's theme, API token to some service, number of items per page on the blog, etc. Where should all this configuration live? Operating systems, PHP and Symfony provide many options: environment variables, .env files, plain PHP constants, dependency injection parameters, key-value databases, "secrets" vaults, etc. You have many choices! And with great choices comes great responsibility... and complexity!

In this talk, we'll review all the ways to store configuration, which is best for each "type" of configuration and the benefits and drawbacks of each. We'll also talk about Symfony 4.4's new "secrets vault" as one of the ways to store sensitive settings. By the end, you'll be ready to configure anything from localhost up to a cluster of high resiliency microservices.</dd>
</dl>

~~Slides~~  
~~Video~~  

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

---

## HTTP Caching with Symfony 101

<dl>
  <dt>Description</dt>
  <dd>HTTP caching is a powerful technique to improve response times for site visitors, make more efficient use of bandwidth and reduce server load. We will have a look at the basic concepts, the different caching strategies and HTTP headers used to implement them. I will then show you a few ways how to implement HTTP level caching in your Symfony application, how to leverage the HTTP Cache included in the framework and resolve the mystery around ESI.

My hope is that when you return to work on monday, you will bring some new tools to your project that you can start using right away.</dd>
</dl>

~~Slides~~  
~~Video~~  
[Code](https://github.com/webfactory/symfony-http-caching-demo)

By [Matthias Pigulla](https://connect.symfony.com/profile/mpdude)  
![github](icon/github.png) [@mpdude](https://github.com/mpdude)  
![twitter](icon/twitter.png) [@mpdude_de](https://twitter.com/mpdude_de)

---

## How fitness helps you become a better developer

<dl>
  <dt>Description</dt>
  <dd>We often think of technical skills as the way to level up as developers, but we're not (yet) brains-in-a-vat. Our body and physical health are crucial to be able to work well as developers.

In this talk I speak both about the science behind fitness and nutrition, and my personal journey of losing over 70 kgs, starting to go to the gym, how it affected me as a developer, as well as the shocking secret behind what happened to the Sound of Symfony podcast.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Magnus Nordlander](https://connect.symfony.com/profile/magnusnordlander)  
![github](icon/github.png) [@magnusnordlander](https://github.com/magnusnordlander)  
![twitter](icon/twitter.png) [@drrotmos](https://twitter.com/drrotmos)

---

## PHPUnit Best Practices

<dl>
  <dt>Description</dt>
  <dd>While PHPUnit is not difficult to set up and writing tests with it is easy, you will get better results and save development time if you know the tips and tricks to leverage PHPUnit more effectively. This session, presented by the creator of PHPUnit, teaches best practices you can use to ensure that your unit testing effort is efficiently implemented.</dd>
</dl>

[Slides](https://thephp.cc/presentations/2019-symfonycon-phpunit-best-practices.pdf)  
~~Video~~

By [Sebastian Bergmann](https://connect.symfony.com/profile/sebastian_bergmann)  
![github](icon/github.png) [@sebastianbergmann](https://github.com/sebastianbergmann)  
![twitter](icon/twitter.png) [@s_bergmann](https://twitter.com/s_bergmann)

---

## Using API Platform to build ticketing system

<dl>
  <dt>Description</dt>
  <dd>Why is API platform a way to go and the new standard in developing apps? In this talk, I want to show you some real examples that we built using API platform including a ticketing system for the world’s biggest bicycle marathon and a social network that is a mixture of both Tinder and Facebook Messenger.

We had to tackle problems regarding the implementation of tax laws in 18 different countries, dozens of translations (including Arabic), multiple role systems, different timezones, overall struggle with a complicated logic with an infinite number of branches, and more. Are you interested? Sign up for the talk.</dd>
</dl>

[Slides](https://speakerdeck.com/antonioperic/using-api-platform-to-build-ticketing-system-number-symfonycon)  
~~Video~~

By [Antonio Peric-Mazar](https://connect.symfony.com/profile/antonioperic)  
![github](icon/github.png) [@antonioperic](https://github.com/antonioperic)  
![twitter](icon/twitter.png) [@antonioperic](https://twitter.com/antonioperic)

---

## Make the Most out of Twig

<dl>
  <dt>Description</dt>
  <dd>Twig is the most powerful templating engine in the PHP world that enables us to create highly complex projects with hundreds of multi-level extended templates, thousands of blocks, functions, filters, tests, and macros. It also offers a sandbox, a unique but not a widely used feature that is creating secure user-editable templates. In addition, there are a number of handy built-in and external debugging tools available in the Twig ecosystem to simplify the day-to-day work process for a Twig designer.

In this presentation, I will talk about how extensively we use Twig in a complex open-source e-commerce project.</dd>
</dl>

[Slides](https://www.slideshare.net/AndreyYatsenco/make-the-most-of-twig-196422158)  
~~Video~~

By [Andrii Yatsenko](https://connect.symfony.com/profile/andrey)  
![github](icon/github.png) [@anyt](https://github.com/anyt)  
![twitter](icon/twitter.png) [@Yatsenco](https://twitter.com/Yatsenco)

---

## Mental Health in the Workplace

<dl>
  <dt>Description</dt>
  <dd>Mental health is an important part of life, yet mental illness is big. Perhaps bigger than you might think when looking around you. In this talk, you'll be introduced to some basics on mental health and mental illness, and given some tips and handholds on how to handle mental illness on the work floor.</dd>
</dl>

[Slides](https://speakerdeck.com/skoop/mental-health-in-the-workplace-symfonycon-2019-amsterdam)  
~~Video~~

By [Stefan Koopmanschap](https://connect.symfony.com/profile/skoop)  
![github](icon/github.png) [@skoop](https://github.com/skoop)  
![twitter](icon/twitter.png) [@skoop](https://twitter.com/skoop)

---

## Importing bad data - Outputting good data with Symfony

<dl>
  <dt>Description</dt>
  <dd>The role of our API in Switzerland is to consume a lot of data that was not meant for a digital age and to transform it into beautiful output, for one of the biggest retailer in Switzerland. This is a journey of consuming a lot of data and APIs from different sources and in different formats. Some of them made us laugh, some of us got migraines. We built a smooth architecture to consume and output data. I am proud of our architecture that we seamlessly upgraded to keep the latest versions, now Symfony 4 along the way. I want to share with you how we managed to keep this API up to date for over 5 years and the architecture that we use to make it happen.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Michelle Sanver](https://connect.symfony.com/profile/michellesanver)  
![github](icon/github.png) [@michellesanver](https://github.com/michellesanver)  
![twitter](icon/twitter.png) [@michellesanver](https://twitter.com/michellesanver)

---

## Symfony Serializer: There and back again

<dl>
  <dt>Description</dt>
  <dd>When developing APIs you sometimes need to return the same object with different representations. Furthermore, an object can be complex due to its relationships with other objects, making the serialization process such a hard task.

The Symfony Serializer Component makes it possible to manage how you want to serialize objects for JSON, XML or other formats. Also, you can manage responses using serialization groups, choosing which properties you want, handling serialization depth and much more.</dd>
</dl>

[Slides](https://speakerdeck.com/jucabrera/symfony-serializer-component)  
~~Video~~

By [Juciellen Cabrera](https://connect.symfony.com/profile/jucycabrera)  
![github](icon/github.png) [@jucabrera](https://github.com/jucabrera)  
![twitter](icon/twitter.png) [@jucycabrera](https://twitter.com/jucycabrera)

---

## Eeek, my tests are mutating!

<dl>
  <dt>Description</dt>
  <dd>Writing tests is nice, but how are you sure that your tests cover all use cases? Code coverage can give false positive metrics. A new way of working that goes by the name of mutation testing has gained a lot of popularity lately. This talk will explain you what it is, how you can integrate it and contains a demo over the basics of mutation testing with infection and phpspec.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Lander Vanderstraeten](https://connect.symfony.com/profile/landerstraeten)  
![github](icon/github.png) [@Landerstraeten](https://github.com/Landerstraeten)  
![twitter](icon/twitter.png) [@landerstraeten](https://twitter.com/landerstraeten)

---

## Integrating performance management in your development cycle

<dl>
  <dt>Description</dt>
  <dd>Good performance is crucial for online businesses and it should be taken very seriously. While this is common knowledge, it is usually not prioritized in development cycles. This leads to higher development cost as teams found themselves in situations of fire-fighting. By integrating performance management early in the development process, the cost are reduced, chances of performance regression are lessened, same as the business risks. Using Blackfire, we will see why performance management should be integrated in a SymfonyCloud project early in every environments from development to testing to production.</dd>
</dl>

~~Slides~~  
~~Video~~  

By [Marc Weistroff](https://connect.symfony.com/profile/futurecat)  
![github](icon/github.png) [@marcw](https://github.com/marcw)

---

## Demystifying React JS for Symfony developers

<dl>
  <dt>Description</dt>
  <dd>The world of Javascript is vast and exciting... but it can also be quite scary! It is an innovative world in which new technologies appear all the time, which can make it difficult for developers to keep up to date. One of the most famous of these technologies is probably React JS. It changed the way we conceive User Interfaces, both in the browser and in mobile applications. But understanding it can be challenging. Let's demystify it together so that you can enter the world of Javascript with confidence!</dd>
</dl>

[Slides](https://speakerdeck.com/tgalopin/demystifying-react-for-symfony-developers)  
~~Video~~

By [Titouan Galopin](https://connect.symfony.com/profile/tgalopin)  
![github](icon/github.png) [@tgalopin](https://github.com/tgalopin)  
![twitter](icon/twitter.png) [@titouangalopin](https://twitter.com/titouangalopin)

---

## Head first into Symfony Cache, Redis & Redis Cluster

<dl>
  <dt>Description</dt>
  <dd>Symfony Cache has been around for a few releases. But what is happening behind the scenes? Talk focuses on how is it working, down to detail level on Redis for things like datatypes, Redis Cluster sharding logic, how it differs from Memcached and more.

Hopefully you’ll learn how you can make sure to get optimal performance, what opportunities exists, and which pitfalls to try to avoid.</dd>
</dl>

[Slides](https://www.slideshare.net/andreromcke/symfonycon-2019-head-first-into-symfony-cache-redis-redis-cluster)  
~~Video~~

By [Andre Rømcke](https://connect.symfony.com/profile/andrerom)  
![github](icon/github.png) [@andrerom](https://github.com/andrerom)  
![twitter](icon/twitter.png) [@andrerom](https://twitter.com/andrerom)

---

## Prime Time with Messenger: Queues, Workers & more Fun!

<dl>
  <dt>Description</dt>
  <dd>In Symfony 4.4, Messenger will lose its experimental label and officially become stable! In this talk, we'll go through Messenger from the ground-up: learning about messages, message handlers, transports and how to consume messages asynchronously via worker commands. Everything you need to make your app faster by delaying work until later.

We'll also talk about the many new features that were added to Messenger since Symfony 4.3, like retries, the failure transport and support for using Doctrine and Redis as transports.

Let's get to work with Messenger!</dd>
</dl>

[Slides](https://speakerdeck.com/weaverryan/prime-time-with-messenger-queues-workers-and-more-fun)  
~~Video~~

By [Ryan Weaver](https://connect.symfony.com/profile/weaverryan)  
![github](icon/github.png) [@weaverryan](https://github.com/weaverryan)  
![twitter](icon/twitter.png) [@weaverryan](https://twitter.com/weaverryan)

---

## SymfonyCloud: the infrastructure of the Symfony ecosystem

<dl>
  <dt>Description</dt>
  <dd>You don't know it yet but you are already using SymfonyCloud every day! Since 2017, the infrastructure of the Symfony community gradually migrated to SymfonyCloud. Let me show you what happens behind the scene and how we leverage every SymfonyCloud features to move faster.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Tugdual Saunier](https://connect.symfony.com/profile/tucksaun)  
![github](icon/github.png) [@tucksaun](https://github.com/tucksaun)  
![twitter](icon/twitter.png) [@tucksaun](https://twitter.com/tucksaun)

---

## Together towards an AI, NEAT plus ultra

<dl>
  <dt>Description</dt>
  <dd>You've heard about AI for some time. But it remains obscure for you. How does it work, what is behind this word? If for you, reading white papers or doctoral papers is not your thing, that the Tensorflow doc is just a big pile of words for you, and if you've seen unclear presentations using the same vocabulary without really giving you an idea of how it works and how to implement an AI at home... This presentation is for you. At its end, you will be able to play with an AI, simple, but that will serve as a gateway to the beautiful world of machine-learning.</dd>
</dl>

[Slides](https://speakerdeck.com/gregoirehebert/together-toward-an-ai-plus-ultra)  
~~Video~~

By [Grégoire Hébert](https://connect.symfony.com/profile/gregoirehebert)  
![github](icon/github.png) [@GregoireHebert](https://github.com/GregoireHebert)  
![twitter](icon/twitter.png) [@gheb_dev](https://twitter.com/gheb_dev)

---

## Building really fast applications

<dl>
  <dt>Description</dt>
  <dd>Let us talk about performance. What can we do to make an application run faster? What should we be considering when starting a new application? There are some quick fixes that I will quickly cover. But to get down to really fast response times requires hard work. I will give my best ideas and tricks for fast apps.

I will show how we can build applications that responds in less that 15ms and then work towards even faster than that.

No, this is not a Varnish talk.</dd>
</dl>

[Slides](https://nyholm.tech/media/building-really-fast-applications/sfcon-amsterdam.pdf)  
~~Video~~

By [Tobias Nyholm](https://connect.symfony.com/profile/tobias)  
![github](icon/github.png) [@Nyholm](https://github.com/Nyholm)  
![twitter](icon/twitter.png) [@TobiasNyholm](https://twitter.com/TobiasNyholm)

---

## Everything you wanted to know about Sylius, but didn’t find time to ask

<dl>
  <dt>Description</dt>
  <dd>Sylius is an open-source eCommerce platform based on Symfony 4, which reached version 1.6 last September. Is there any reason why should you check Sylius if you are not developing eCommerce websites? What are the reasons to choose Sylius? For who is Sylius designed for? I will answer these questions and give some insight over the newest changes in the platform.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Łukasz Chruściel](https://connect.symfony.com/profile/lchrusciel)  
![github](icon/github.png) [@lchrusciel](https://github.com/lchrusciel)  
![twitter](icon/twitter.png) [@lukaszchrusciel](https://twitter.com/lukaszchrusciel)

---

## DevCorp: Choose Your Own Adventure

<dl>
  <dt>Description</dt>
  <dd>You’re a software development consultant called into DevCorp with a mission. What started as a hip, informal startup now has investor demands to meet. And they’re counting on you to help them become a scale-up. How do you grow the existing team and maintain the codebase?

This interactive talk, intended for any developer of any level, will give you some valuable technical and soft skills to take with you on your real-life professional journey. Using a voting system, the audience decides… and has to live with the consequences. Based on a mix of personal experience, agile methodology, and software design principles, this story has several possible endings.

Will you help lift your team’s performance or run DevCorp into the ground?</dd>
</dl>

[Slides](http://pauline-vos.nl/dev-corp/)  
~~Video~~

By [Pauline Vos](https://connect.symfony.com/profile/paulinevos)  
![github](icon/github.png) [@paulinevos](https://github.com/paulinevos)  
![twitter](icon/twitter.png) [@vanamerongen](https://twitter.com/vanamerongen)

---

## One Year of Symfony

~~Slides~~  
~~Video~~

By [Zan Baldwin](https://connect.symfony.com/profile/zanbaldwin)  
![github](icon/github.png) [@zanbaldwin](https://github.com/zanbaldwin)  
![twitter](icon/twitter.png) [@ZanBaldwin](https://twitter.com/ZanBaldwin)

And [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)


---

---

---

# Unconf Talks

--- 

## A love story starring Symfony and Domain-Driven Design

<dl>
  <dt>Description</dt>
  <dd>This is the story of how I discovered Domain-Driven Design, what happened when I tried to apply it to a Symfony framework project, and what are the key takeaways.</dd>
</dl>

[Slides](https://speakerdeck.com/romaricdrigon/a-love-story-starring-symfony-and-domain-driven-design)

By [Romaric Drigon](https://connect.symfony.com/profile/romaricdrigon)  
![github](icon/github.png) [@romaricdrigon](https://github.com/romaricdrigon)  
![twitter](icon/twitter.png) [@romaric](https://twitter.com/romaricdrigon)


--- 

## 10 lessons from symfony ecosystem that you can apply to your team/project

<dl>
  <dt>Description</dt>
  <dd>What I want to show you? That you can benefit not only from the symfony code itself or presentations on SymfonyCon. There's more.</dd>
</dl>

[Slides](https://www.slideshare.net/jerzyzawadzki/10-lessons-from-symfony-ecosystem-that-you-can-apply-to-your-team-project)

By [Jerzy Zawadzki](https://connect.symfony.com/profile/jzawadzki)  
![github](icon/github.png) [@jzawadzki](https://github.com/jzawadzki)  
![twitter](icon/twitter.png) [@jerzy_zawadzki](https://twitter.com/jerzy_zawadzki)

--- 

## Schema Design for E-Commerce

<dl>
  <dt>Description</dt>
  <dd>Replacing Transactions with MongoDB</dd>
</dl>

[Slides](https://speakerdeck.com/alcaeus/schema-design-for-e-commerce)

By [Andreas Braun](https://connect.symfony.com/profile/alcaeus)  
![github](icon/github.png) [@alcaeus](https://github.com/alcaeus)  
![twitter](icon/twitter.png) [@alcaeus](https://twitter.com/alcaeus)
