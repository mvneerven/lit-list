# Web Components & Lit Library - a Curated List of documentation

A curated list of great documentation to get frontenders started with **Web Components & Lit**, with or without a framework.

# Web Components basics

Basically, Web Components consist of [three technologies](https://exyte.com/blog/web-components-technology "Overview of the Web components in 2021"): Custom elements, Shadow DOM, and HTML templates.- [Web Components | MDN](https://developer.mozilla.org/en-US/docs/Web/Web_Components "Web Components | MDN")\
  *Simply the best source of truth about all Web Technology*
- [webcomponents.org - Discuss & share web components](https://www.webcomponents.org/ "webcomponents.org - Discuss & share web components")\
  *WebComponents.org aims to make it easy to share, discover, and reuse web components*
- Open Web Components - [Open Web Components](https://open-wc.org/ "Open Web Components")\
  *Well-known and experience-tested recommendations for their web component projects*
- Project Scaffolding [Development: Generator: Open Web Components](https://open-wc.org/docs/development/generator/ "Development: Generator: Open Web Components")
- What are Web Components (video)[](https://www.youtube.com/watch?v=83W63gTVlSk)
- Web Components At Work (Thomas Wilburn)[](https://thomaswilburn.github.io/wc-book/)
  
# In-Depth Web Components

## Rob Eisenberg 

Rob Eisenberg is a respected voice in the Web Components community. He has worked on Angular at Google, on FAST at Microsoft, and is a member of the W3C Web Componnents Community Group.

1. [About Web Components](https://eisenbergeffect.medium.com/about-web-components-7b2a3ed67a78 "About Web Components")
2. [Debunking Web Component Myths and Misconceptions](https://eisenbergeffect.medium.com/debunking-web-component-myths-and-misconceptions-ea9bb13daf61 "Debunking Web Component Myths and Misconceptions")
4. [2023 State of Web Components](https://eisenbergeffect.medium.com/2023-state-of-web-components-c8feb21d4f16 "2023 State of Web Components")
5. [Web Component Engineering Course](https://www.youtube.com/watch?v=Y-Q1WTvPt_8)
  
# Relevant Web Standards

Web Components are an umbrella term. These are the underlying technologies you need to know to make the best of Web Components & Lit.

- ES6 Module - [JavaScript modules - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules "JavaScript modules - JavaScript | MDN")\
  *Module encapsulation, imports, exports*
- String templates (ES6) - [Template literals (Template strings) - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals "Template literals (Template strings) - JavaScript | MDN")\
  *Template-based rendering with variables*
- CSS custom properties/variables - [Using CSS custom properties (variables) - CSS: Cascading Style Sheets | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties "Using CSS custom properties (variables) - CSS: Cascading Style Sheets | MDN")\
  *Isolated styling with defined variables for external influence*
- [customElements.define()](https://developer.mozilla.org/en-US/docs/web/api/customelementregistry/define "CustomElementRegistry.define() - Web APIs | MDN")\
  *How to register a custom HTML element*
- [Shadow DOM](https://developer.mozilla.org/en-US/docs/Web/API/Web_Components/Using_shadow_DOM)
  
# Google's Lit Library

> A really high level view of Lit would be that it's simply filling in the Gaps in the standards.

Lit is a tiny (\<5Kb) library written by **Justin Fagnani** of Google, which was developed to fill a few gaps and make working with Web Components as easy as working with **React UI**, but without the need for expensive indirections like Virtual DOM and JSX.[](https://www.youtube.com/watch?v=ndZ8vcxNp0Q)> *A Lit component renders its template initially when it's added to the DOM on a page. After the initial render, any change to the component's reactive properties triggers an update cycle, re-rendering the component.*

> *Lit batches updates to maximize performance and efficiency. Setting multiple properties at once triggers only one update, performed asynchronously at microtask timing.*
> *During an update, only the parts of the DOM that change are re-rendered. Although Lit templates look like string interpolation, Lit parses and creates static HTML once, and then only updates changed values in expressions after that, making updates very efficient. - from* [*https://lit.dev/docs/components/rendering*](https://lit.dev/docs/components/rendering "Rendering – Lit")

See [Lit for React Developers | Google Codelabs](https://codelabs.developers.google.com/codelabs/lit-2-for-react-devs#1 "Lit for React Developers | Google Codelabs")- [Lit](https://lit.dev/) (Simple. Fast. Web Components)\
  *Lit Homepage*
- [From Web Component to Lit Element | Google Codelabs](https://codelabs.developers.google.com/codelabs/the-lit-path#0 "From Web Component to Lit Element | Google Codelabs")\
  *A course to take you from React to Lit expert*
- [GitHub - web-padawan/awesome-lit: A curated list of awesome Lit resources.](https://github.com/web-padawan/awesome-lit "GitHub - web-padawan/awesome-lit: A curated list of awesome Lit resources.")\
  *A curated list of wonderful Lit-related stuff*
- [The Browser is your Framework: Building a PWA with only Web Components and Lit](https://javascript.plainenglish.io/the-browser-is-your-framework-building-a-pwa-with-only-web-components-and-lit-c91f0f86900d "The Browser is your Framework: Building a PWA with only Web Components and Lit")\
  *My article on creating PWAs with only Web Components and Lit, and the* [*NPM initializer*](https://www.npmjs.com/package/create-lit-pwa "create-lit-pwa") [*Artem Maiorov*](https://www.linkedin.com/in/artem-maiorov-792a7b3a/) *created with me.\
  See also* [*the list of LinkedIn Posts*](https://www.linkedin.com/feed/hashtag/es6pwa/) *around this approach.*
- [Some things to know when developing with Lit](https://open-wc.org/blog/some-things-to-know-when-developing-with-lit/)
  
# Component Libraries & Design Systems

## Design System Tools- Custom Element Manifest 

- [Getting Started: Custom Elements Manifest](https://custom-elements-manifest.open-wc.org/analyzer/getting-started/ "Getting Started: Custom Elements Manifest")
- Storybook - [Storybook: Frontend workshop for UI development](https://storybook.js.org/)
- [Getting Started With Storybook Without a JavaScript Framework | by RayRay | Better Programming](https://betterprogramming.pub/getting-started-with-storybook-without-a-javascript-framework-c2968d3f3d9f)
 
## Web Components Component Libraries

Ready-to-use UI component libraries to use in any project.

- Microsoft Fast - [FAST](https://www.fast.design/ "FAST")
- Shoelace - [Shoelace](https://shoelace.style/ "Shoelace")
- Ionic - [Ionic Framework - The Cross-Platform App Development Leader](https://ionicframework.com/ "Ionic Framework - The Cross-Platform App Development Leader")
- Google Material: [material-components/material-web: Material Design Web Components (github.com)](https://github.com/material-components/material-web)\
  *Note: v3 is currently in development (April 2023)*
- Adobe (Spectrum) - [Spectrum Web Components - Spectrum Web Components](https://opensource.adobe.com/spectrum-web-components/ "Spectrum Web Components - Spectrum Web Components")
- RedHat (Patternfly) - [PatternFly 4](https://www.patternfly.org/v4/ "PatternFly 4")
- AWS (Amplify) - [Amplify UI Components - AWS Amplify Docs](https://docs.amplify.aws/ui/ "Amplify UI Components - AWS Amplify Docs")
- Vaadin - [GitHub - vaadin/web-components: A set of high-quality...](https://github.com/vaadin/web-components "GitHub - vaadin/web-components: A set of high-quality standards based web components for enterprise web applications. Part of Vaadin 20+")
 
## Web Component Design Systems / Discovery

- <https://www.webcomponents.org/>
- <https://webcomponents.dev/>
- <https://github.com/web-padawan/awesome-web-components>


# Web Components Only Approach (not using a framework)

When you decide not to use any existing framework, you have to decide what to use for a few common areas normally taken care of by the framework, such as state management and routing.

## General Web Capabilities

- [What Web Can Do Today](https://whatwebcando.today/ "What Web Can Do Today")
- [What PWA Can Do Today](https://whatpwacando.today/ "What PWA Can Do Today")
- [Project Fugu](https://www.chromium.org/teams/web-capabilities-fugu/ "Web Capabilities (Project Fugu 🐡)")
 
## State Management

State Management is one of the strongest reasons people keep referring to frameworks, but if you look at what people then use, it's a lot of Redux and other libraries, which are combined with their favorite frameworks, sometimes even packaged, but libraries they are.The same libraries and approaches can be combined with Web Components and Lit!- [Using Redux in a LitElement app | Vaadin](https://vaadin.com/blog/using-redux-in-a-litelement-app "Using Redux in a LitElement app | Vaadin")

- [GitHub - gitaarik/lit-state: Simple shared app state management for LitElement.](https://github.com/gitaarik/lit-state "GitHub - gitaarik/lit-state: Simple shared app state management for LitElement.")
- [Valtio, makes proxy-state simple for React and Vanilla](https://valtio.pmnd.rs/ "Valtio, makes proxy-state simple for React and Vanilla")
- [State Management in Javascript Using Proxy | by Greedy Goblin Games | Medium](https://medium.com/@cjhazard.1/state-management-in-javascript-using-proxy-39f9a87cf0a1)
- [gitaarik/lit-state: Simple shared app state management for LitElement. (github.com)](https://github.com/gitaarik/lit-state)
- [MobX](https://mobx.js.org/ "MobX") - *Simple, scalable state management.*
- [The Mediator Pattern in JavaScript — JSManifest](https://jsmanifest.com/the-mediator-pattern-in-javascript/)
- [Zustand](https://docs.pmnd.rs/zustand "Zustand Documentation")
- [Web Components Context Protocol implementation](https://lit.dev/docs/data/context/)
 
## Routing

When not using a framework, routing is not provided as a ready-to-use component. Using browser-native functionality isn't complex (using [History](https://developer.mozilla.org/en-US/docs/Web/API/History_API/Working_with_the_History_API "Working with the History API - Web APIs | MDN")), and lately, the new URLPattern API allows you to do any kind of routing, including complex parameter passing, natively. The Lit PWA (see my [previously mentioned article](<https://The Browser is your Framework: Building a PWA with only Web Components and Lit>)) uses it, including lazy-loading polyfills if needed.- [URLPattern brings routing to the web platform - Chrome Developers](https://developer.chrome.com/articles/urlpattern/ "URLPattern brings routing to the web platform - Chrome Developers")Other router solutions:- [Polymer/pwa-helpers: Small helper methods or mixins to help you build web apps. (github.com)](https://github.com/Polymer/pwa-helpers)
- [tuwrraphael/route-it: dead simple vanilla js spa router (github.com)](https://github.com/tuwrraphael/route-it)
- [A SPA/PWA Router in Pure Vanilla ES6 JavaScript | by Marc van Neerven | JavaScript in Plain English](https://javascript.plainenglish.io/a-spa-pwa-router-in-pure-vanilla-es6-javascript-e8f79cfd0111)
 
# Using Web Components in Frameworks

When you do decide to work with your favorite framework, Web Components can still be a valid choice for everything UI, because you will be able to reuse the components across projects with differing frameworks, and they will work regardless of framework upgrades or switching to other frameworks. This is why many companies, such as Google, Adobe, RedHat, Microsoft, Cisco, SAP and VMWare are already investing heavily in Web Components.

## Generic information on Web Components in frameworks:

- [Create Web Components by using Google Lit, publish them on Npm and use them in React, Angular & JS projects - DEV Community 👩‍💻👨‍💻](https://dev.to/fabiobiondi/create-web-components-by-using-google-lit-publish-them-on-npm-and-use-them-in-react-angular-js-projects-3676)
- [Pairing Web Components with JS frameworks - Ionic](https://ionic.io/resources/articles/building-design-systems-with-web-components#h-pairing-web-components-with-js-frameworks)
- [Custom Elements Everywhere](https://custom-elements-everywhere.com/ "Custom Elements Everywhere")\
  *An overview of Web Component readiness in the popular frameworks*
  
## React

- [Lit for React Developers (google.com)](https://codelabs.developers.google.com/codelabs/lit-2-for-react-devs#0)\
  *E-learning to move from React to Lit*
- [How To Use Web Components in React](https://blog.devgenius.io/how-to-use-web-components-in-react-54c951399bfd#:~:text=How%20To%20Use%20Web%20Components%20in%20React%201,Component%20in%20React%20...%205%20Final%20Thoughts%20 "How To Use Web Components in React")
- [Creating and using Web Components in React](https://www.youtube.com/watch?v=PUGDzA1uP-Y)
- [React hooks reimplemented for Web Components - GitHub](https://github.com/matthewp/haunted)
 
## Angular

- [How To Use Web Components in Angular](https://levelup.gitconnected.com/how-to-use-web-components-in-angular-c5d1d7825ca0 "How To Use Web Components in Angular")
- [Using Web Components in Angular Forms with Element Internals - Angular 16 | 15](https://coryrylan.com/blog/using-web-components-in-angular-forms-with-element-internals "Using Web Components in Angular Forms with Element Internals - Angular 16 | 15")
- [How to integrate Web Components using Lit in Angular - This Dot Labs](https://www.thisdot.co/blog/how-to-integrate-web-components-using-lit-in-angular "How to integrate Web Components using Lit in Angular - This Dot Labs")
- [Master Web Component Forms Integration - with Lit and Angular](https://www.thinktecture.com/en/web-components/web-component-forms-integration-with-lit-and-angular/ "Master Web Component Forms Integration - with Lit and Angular")
- <https://stackoverflow.com/questions/56837900/how-to-import-angular-web-component-in-another-angular-app>
- [Using Web Components in Angular](https://www.youtube.com/watch?v=2Wjp_FsWOXU)
 
## Vue

- [How to Create Reusable Web Components with Lit and Vue](https://dval.dev/blog/lit-web-components-tutorial/ "dval.dev")
- [How to use Web Components in Vue](https://www.youtube.com/watch?v=gp-1LzhSH30)
 

--- 
 

This list is maintained by [Marc van Neerven](https://www.linkedin.com/in/mvneerven/)<br>
