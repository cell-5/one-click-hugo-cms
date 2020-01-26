---
title: "Tools and Techniques"
image: /img/about-jumbotron.jpg
tools:
  - heading: "Collaboration and Communication"
    text: >
      We use [Slack](https://slack.com), organized into per-client rooms as our primary means of communication. We allow clients to join our Slack for their specific room and general chat and can happily join their own Slack or IM system, but we do encourage one to exist.
      

      For team meetings and project meetings we use [Google Hangouts](https://hangouts.google.com/) and we expect all team members to sort out a working decent quality mic, and webcam. 
      

      We store our documents and client documents on our [Google Drive](https://www.google.com/drive/). We have a shared team drive, and a company exec drive.
      

      Everyone on the team gets a cell5 gmail account for registering with Saas products and client communication.
      

      We **dislike** Zoom as too slow / heavy on memory.
      We watch Discord but its not as good for managing our channels or integrations. 

    imageUrl: "/img/about-shade-grown.jpg"
  - heading: "Software Project Management"
    text: >
      We like to have regular project cycles lasting one or two weeks at most. These cycles are started and finished by a single short meeting of communicating what has changed, and planning who will change what, next. Change here is meant broadly, deployments, process, business goals, can all change and need communicating. 
    

      We use [Trello](https://trello.com) where possible for light weight task tracking and prioritzation.


      We like the [XP values](http://www.extremeprogramming.org/values.html), and we use some of the practises, our favourites being **Continuous Integration** and **small releases**. We **pair program** for two purposes. For coaching, and for troubleshooting. We encourage a culture of asking for help, and giving it when asked.


      We like the Work-In-Progress limits, and focus on finshing things from [Kanban](https://en.wikipedia.org/wiki/Kanban_(development)) and its tendancy to result in greater teamwork, as no-one is left behind.


      We like small batches and attention to derisking releases and automation of deployments from [Continous Delivery](https://continuousdelivery.com/principles/).


      We release often, more often than our planning cycle, usually weekly, but as much as multiple times a day. We make judgements based on our level of risk, test automation, deployment control and what is actually a discrete piece of value. 
      

      Usually weekly is about right for start-ups.


      We **dislike** JIRA, though we can use it if we keep it really simple. It is just too bloated and has too many features which people get tempted to use. 
      
    imageUrl: "/img/about-single-origin.jpg"
  - heading: "Software Product Design"
    text: >

      We prefer to use a design system such as [Polaris](https://polaris.shopify.com/),  [Material](https://material.io/) or [Bootstrap](https://getbootstrap.com/) for most of the application and focus design flair on specific areas. Having a common design system just makes the communication and delivery that much faster, and they have sensible out of box defaults incorporating usability research and tooling integration which makes mobile-first easier. 


      We highly recommend [Figma](https://www.figma.com/) as a collaborative design and rapid protoyping tool. [Invision](https://www.invisionapp.com) is marginally more powerful and a great tool too, but Figma suits our remote collaboration goals better.


      We do think it is worth designing and spec-ing before development for main journies and new features, but Just-In-Time ideally as otherwise the business direction changes while the designs are still wet. 


      Once a design system is in place and main journies are mapped out, there is less need for design inputs. In our experience the development team can usually progress well after this and should not be blocked on waiting for the designer to pick a colour. 


      After this initial period, we would then treat UX and Designers more as adivsory specialists dipping in adhoc.


    imageUrl: "/img/about-sustainable-farming.jpg"
  - heading: "Development Practises & Tooling"
    text: >
      We insist source code for development is versioned in a version control system. At this point git and Github or GitLab are fairly ubiqutous and we would need a strong reason not to use them. git is almost a must these days.
      
      We encourage trunk based development, merging early and often. 

      We expect Pull Requests to be small, and where possible to include a PR deployment or a showcase screen cast and evidence of testing attached.

      We like unit testing but are not dogmatic, depending on the size of the app and the amount of pure UI code we are flexible provided risk is being managed thoughfully.

      We insist every change that is planned to be deployed has a roll back plan, and usually a feature-toggle to make the revert instant.

      For development each language has its best tools but we like VSCode for front end technologies and the Jetbrains suite of tools like GoLand, PHPStorm, Intellij for most back end work.
      
      We prefer medium sized services or well layered monoliths to microservices for the core start-up product but welcome a set of ancillary microservices, usually deployed as docker containers in the ecosystem.

    imageUrl: "/img/about-direct-sourcing.jpg"
  # - heading: "Runtime & Deployment Practises & Tooling"
  #   text: >
  #     For microservices we recommend javascript (node), golang, python or java.
  #     For monolithic backends we recommend PHP, java, golang or python.
  #     For front end development we recommend javascript for most work but TypeScript for important core models
  #   imageUrl: "/img/about-reinvest-profits.jpg"
  # - heading: "Front End Web Technologies"
  #   text: >
  #     We recommend ReactJs, VueJs, or AngularJs for large applications
  #     We recommend Jquery or template rendering for smaller sites. 
  #   imageUrl: "/img/about-reinvest-profits.jpg"
  # - heading: "Mobile Technologies"
  #   text: >
  #     We recommend ReactNative for startups
  #     we do not recommend D.I.Y native as too expensive to manage for startups.
  #   imageUrl: "/img/about-reinvest-profits.jpg"  
  # - heading: "Web Services Technologies"
  #   text: >
  #     We recommend ReactNative for startups
  #     we do not recommend D.I.Y native as too expensive to manage for startups.
  #   imageUrl: "/img/about-reinvest-profits.jpg"    
  # - heading: "Digital Marketing Tools & Experience"
  #   text: >
  #     Our favourite approach to digital marketing is to focus on sharing value and not focusing on selling, as this fits with out own believe in long-term value creation and brand-building.  


  #     We usually seek external partners for advanced marketing strategies, but we are familiar with the basics. 


  #     We can optimize web products for on-site S.E.O, and we integrate Google Analytics and Tag Manager, as well as Facebook Pixel. 
      
      
  #     We can configure funnels and provide live recording from HotJar integration to help assess journey success. 


  #     We understand the basics of Keyword ads and Facebook Ad manager. We can run the campaigns operationally, and we can provide CopyWriters and Social Media Managers, but we would seek advise on campaign strategy until we gain more knowledge in this area. 

  #   imageUrl: "/img/about-reinvest-profits.jpg"  

  # - heading: "Ecommerce Tools & Experience"
  #   text: >
  #     We can and have  integrated payment systems like Stripe which we recommend.  

  #     We can and have build Shopify shop sites and Facebook shops for simple FBA or Dropshipping or Print On Demand shops or those with custom inventory. 

  #     We recommend Etsy for more bespoke inventory, and Ebay for second hand, and Amazon for commodity inventory. 

  #     For ecommerce strategy we would seek advise from experts, while we do have the knowledge to build the shops and can supply Product Sourcers if required.

  #   imageUrl: "/img/about-reinvest-profits.jpg"  
---
