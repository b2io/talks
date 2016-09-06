<!-- .slide: data-background="./images/intro-slide-bg.png" data-background-size="cover" -->
# NetJets User Group

Presented by: <!-- .element: class="presented-by" -->

 - Brad Pearson (NetJets) <!-- .element: class="presenter" -->
 - Caitlin Steinert (Base Two) <!-- .element: class="presenter" -->
 - Drew Miller (Base Two) <!-- .element: class="presenter" -->

---

## Introduction

- Future of web development at NetJets <!-- .element: class="fragment" -->
- Web Center of Excellence <!-- .element: class="fragment" -->
- ETM Redesign / Trip Management <!-- .element: class="fragment" -->

Note:
- Hello everyone, thanks for coming to the user group meeting today
- My name is Brad Pearson - For those who don't know me, I'm a tech lead and I've been working at NJ 4+ years on ETM
- Today, we're going to be talking about the future of web development at NetJets
- Included in that is a new group called the Web CoE
- Web CoE is a group of people who are working to move the state of web development forward
- One of the ways to do that is identifying projects to POC new tools and techniques
- Current project is a partial ETM redesign where we are 'reinventing' trip management part of ETM

----

## Web App Development

- 'Web Apps' is a broad category <!-- .element: class="fragment" -->
- 'Single Page Apps' are the complex web apps we develop <!-- .element: class="fragment" -->
- Complexity comes from combination of technologies <!-- .element: class="fragment" -->
- JavaScript isn't JavaScript anymore, CSS isn't CSS anymore, HTML is HTML anymore <!-- .element: class="fragment" -->
- Today's web app development is unique <!-- .element: class="fragment" -->

Note:
- web development is a broad category
- historically it's been lots of different things
- single page apps are the complex apps we spend most time on
- Complexity = JS, TypeScript, ES5, ES6, babel, LESS, SASS, directives and components defined in app syntax
- Web app development is a unique niche of software engineering  

----

## Web UI CoE

- Why? <!-- .element: class="fragment" -->
  - Because of the unique aspect of web dev <!-- .element: class="fragment" -->
- What? <!-- .element: class="fragment" -->
  - Commit to improvement and staying current <!-- .element: class="fragment" -->
- How? <!-- .element: class="fragment" -->
  - Everything is on the table <!-- .element: class="fragment" -->
  - Today is just a starting point <!-- .element: class="fragment" -->
  - Wiki, user group meetings, ad hoc meetings <!-- .element: class="fragment" -->

Note:
- The web CoE is about trying to research and implement things here at NJ to make web development better and stay current
- This work is just the starting point - the web CoE goal is to continue to develop better tools and processes in the web dev space
- Everything is on the table when it comes to how we make web development better
- Ongoing communication about the web CoE initiatives will be via the wiki, future user group meetings as well as ad hoc department meetings

----

## Base Two

- Expertise in web development <!-- .element: class="fragment" -->
- JavaScript, HTML, CSS, build process, best practices <!-- .element: class="fragment" -->
- Caitlin - styleguide and implementation <!-- .element: class="fragment" -->
- Drew - web app development <!-- .element: class="fragment" -->

Note:
- There's a lot of work and we decided to try and find someone outside of NetJets to help us with this effort
- We found and have enlisted the help of a company called Base Two
- Software development agency here in Columbus and they also bought the pizza for today
- The have expertise in core client side web development technologies
- Things like JS, HTML, styling, build processes, best practices
- Today we have two developers from base two who are working on our styleguide as well as the client side app development for etm redesign project
- Introduce Caitlin Steinart and Drew Miller
- Caitlin has been working more with the style side of the project and Drew on the app development side
- I'll hand it over to Caitlin

---

# NetJets Style Guide

> Create a consistent visual language of UI components for use by designers and
developers during the discovery and design phases of NetJets applications.

----

### Internal Systems Audit:
### Visual Language

![Styles](images/ux/styles-zoomed.png)

Note:
For this audit, Contrail, ETM, Flight Control/Flight Release, Line Planning,
MXNet, OCMS, Online Payments, Pulse, and Subscription Center were examined for
usage and styling of the following items.

----

### Internal Systems Audit:
### User Interactions
Consistency and Standards

----

> "Users should not have to wonder whether different words, situations, or
actions mean the same thing."
>
> Jakob Nielson

![User Interactions](images/ux/user-interactions.png)

----

### Implementation Examples

#### Clear Visual Language / Consistent Patterns and Interactions

![Implementations](images/ux/implementations.png)

----

## Process & Workflow

#### Ongoing and Cross Disciplinary

![Process & Workflow](images/ux/process-workflow.png)

----

## UX/UI Efficiency Gains

How and where will a styleguide help with efficiency?

* Designing from known patterns
* Cross project design
* Streamline QA process

----

## Style Guide
#### Scope & Timeline

![Scope & Timeline](images/ux/scope-timeline.png)

---

![Image of a bear waving hello](images/hello.gif)

Note:
- Hello!
- I am a UX developer on the Center of Excellence team
- One of my goals as part of this team is to facilitate collaboration and communication between designers and developers as we work together

----

## Living Styleguide

Note:
- One way I'm accomplishing this feat is by spearheading the Living Styleguide initiative

----

## Living Styleguide

 - Creates a common design language

Note:
- Communication is tough, especially across disciplines
- The way that we as developers think of UI components can often differ wildly from how designers think about them
- Lots of emails fly back and forth about padding, font sizes, and colors
- This effects our productivity and can cause friction between teams

----

![Image of UX/Marketing team's work](images/user-experience-team.png)

Note:
- The UX/Marketing team is hard at work generating new and unified designs for the components across applications
- There are a *lot* of components in the suite of applications, so this is an evolving piece of work
- The comps from UX/Marketing won't be the finished product, however...

----

## Living Styleguide

- Creates a common design language
- Compose a UI from the ground up

Note:
- As they create guidelines, we are simultaneously translating them into the Living Styleguide

----

![Image of styleguide button](images/button.png)

Note:
- This is a screenshot of the Living Styleguide that shows the default styles for a basic button element

----

![Image of colors](images/colors.png)

Note:
- The Living Styleguide is built entirely in HTML, Sass, and Javascript
- The Sass that is applied to the styleguide is the same Sass that can be used in any company app
- The whole package will live on the CDN eventually so that it's accessible to all teams

----

![Image of styleguide icon](images/icon.png)

Note:
- The HTML that it's built from is also pulled into the Styleguide so that developers can see what attributes are required...

----

![Image of styleguide inventory list](images/inventory-list.png)

Note:
- ...which becomes especially useful as we group elements into more complex components

----

## Living Styleguide

- Creates a common design language
- Compose a UI from the ground up
- Styleguide-driven development

Note:
So I hear you say, Ok lady, that sounds cool and all, but how's this going to help me in my job, and NetJets in general? How am I even going to use this thing?
Goals of this project include, but are not limited to...

----

![Image of styleguide flight pair](images/flight-pair.png)

Note:
...creating markup and styles that are custom-tailored to the NetJets brand and apps...

----

![Image of HTML5 and CSS3 logos](images/shiny-web-toys.svg)

Note:
...promoting and facilitating the use of the latest and greatest features in HTML and CSS...

----

#### Less of this

![Image of machine mass producing crayons](images/crayons.gif)

Note:
...reducing the amount of repeated work required as apps begin to switch over to the new design...

----

#### More of this

![Image of a pit crew](images/pit-crew.gif)

Note:
...and facilitating teamwork and speed.

---

# Improving the Developer Experience

----

## Developer Experience (DX)

Your productivity is a precious commodity; use it wisely.

1. Focus on the task at hand
2. Use purpose-built tools
3. Reduce cognitive overhead

Note:
- We talk a lot about UX, but let's talk about DX.
- Let's talk about three concepts that help us be better developers.

----

## Focus on the task at hand

![Lioness Stalking](images/dx__focus.gif)

Note:
- First, let's talk about focus...

----

### How does a Styleguide focus us?

- Styleguide components are just markup and styles
- Behavior comes from the platform implementation
- We get to focus on the behavior, not the presentation

Note:
- Consume the published styleguide artifacts we can,
- Replicate what we can't consume,
- Enhance with our framework of choice  

----

### Icon Component

```html
<span class="netjets-close"></span>
```

```scss
[class^="netjets-"], [class*=" netjets-"] {
	font-family: 'netjets-icons';
	font-style: normal;
	font-variant: normal;
	font-weight: normal;
	line-height: 1;
	speak: none;
	text-transform: none;
}

.netjets-close::before {
	content: "\e045";
}
```

Note:
- Here's some markup/styles from our Styleguide
- Basic HTML for structure and CSS for presentation

----

### In Angular 2?

```ts
import '@netjets/styleguide/icon.scss';
import { Component, Input } from '@angular/core';

@Component({
  selector: 'nj-icon',
  template: '<span class="netjets-{{name}}"></span>',
})
class IconComponent {
  @Input()
  public name: string;
}

export default IconComponent;
```

Note:
- Implementing that in Angular 2,
- We import the SASS directly,
- We re-use the HTML indirectly

----

### In React?

```js
import '@netjets/styleguide/icon.scss';
import React from 'react';

const Icon = ({ name }) => (
  <span className={`netjets-${name}`}></span>
);

export default Icon;
```

Note:
- And again in React,
- We import the SASS directly,
- We re-use the HTML indirectly
- Someone (Caitlin) has done the heavy lifting for us!

----

### But wait... what?!

```ts
// Annotations?!
@Input()
public name: string;
```

```js
// Importing SASS files?!
import '@netjets/styleguide/icon.scss';
```

```js
// HTML-ish in our JS?!
<span className={`netjets-${name}`}></span>
```

Note:
- Those things aren't normal JavaScript!
- You can't just do that... can you?

----

## Use purpose-built tools

![Rube Goldberg Machine](images/dx__tools.gif)

Note:
- So now let's talk a bit about tools...
- When we talk about tools, especially front-end tooling, you may be imaging something like this...

----

### webpack

![webpack module bundler](images/dx__tools--webpack.jpg)

Note:
- There is an amazing diversity of awesome tools out there
- Let's talk about one in particular, webpack
- It's a very _powerful_ tool; which generally means useful and complicated

----

### webpack

```js
var path = require('path');

module.exports = {
  entry: {
    app: './src/app.js',
    vendor: './src/vendor.js',
    polyfills: './src/polyfills.js',
  },
  output: {
    path: path.join(__dirname, 'dist'),
    filename: '[name].[chunkhash].bundle.js',
  },
  // ...
};
```

Note:
- So what do we have going on here?
- We point webpack at some entry points,
- And we tell it how we want to output them,
- webpack figures out the dependency graph for us.

----

### webpack

```js
module.exports = {
  // ...
  module: {
    loaders: [
      {
        test: /\.jsx?/, // Match files with `.js` or `.jsx` extensions.
        loader: 'babel', // Convert them from ES6 to our target.
      },
      {
        test: /\.tsx?$/, // Match files with `.ts` or `.tsx` extensions.
        loader: 'babel!ts', // Convert them from TypeScript to ES6, etc.
      },
    ],
  },
};
```

Note:
- Now we're in another section of our webpack.config.js file.
- We're telling webpack what types of files we expect to see,
- And what to do with them once we find them.

----

### webpack

- webpack is purpose-built to efficiently build web apps
- It unlocks an entire ecosytem of tools for us to use

Note:
- SASS, TypeScript, ES6, and more...

----

## Reduce cognitive overhead

![Flux Capacitor](images/dx__data.gif)

Note:
- Cognitive overhead? That's a little vague...
- What are we talking about here?

----

### Cognitive overhead

> Logical connections or jumps your brain has to make in order to understand or contextualize the thing you’re looking at.

-David Demaree, Product Manager at Adobe

Note:
- This quote is in the context of UX.
- But let's talk about DX.
- How much do you have to hold in your head to implement a feature? How about to fix a bug?

----

### In the beginning...

![Simple Data Flow](images/dx__data--simple.png)

Note:
- So you're starting a greenfield project,
- You've got straightforward use cases,
- Things are going to be great this time!
- Let's describe the flow of data in our system.

----

### In the end...

![Complex Data Model](images/dx__data--complex.png)

Note:
- And then, innevitably, we get here...
- Anyone used a lot of two-way data-binding in Angular 1?
- You have a bug over here, but the actual cause is waaaay over there....

----

<!-- .slide: data-background="./images/slide-content-bg.png" data-background-size="1320px" -->
### Unidirectional data flow

- A lot of complexity is in the flow of our data
- If we can describe that flow more simply, we can reduce cognitive overhead

Note:
- A lot of thought and research has gone into this problem.
- One of the popular solutions is a pattern called Flux; which is Facebook taking an old idea and pretending it's new.

----

### Flux Architecture

![Flux Architecture Diagram](images/dx__data--flux-1.png)

Note:
- To sum it up, we have the state of our app in our Store
- That drives how we render our View(s)
- Actions are dispatched which cause mutations in our Store

----

### Flux Architecture

![Flux Architecture Diagram](images/dx__data--flux-2.png)

Note:
- You might have Actions coming from a View, or from a background-job, etc
- So whether or not this is really _new_, it's useful.
- If we implement this, we have to hold much less in our heads to make a change.

----

### "But we're not using Flux!"

- This is just one way to reduce cognitive overhead
- Improve the DX on your project when you can

Note:
- Over the lifetime of a product, maintenance costs dramatically outweigh initial investment.
- Do that developer 2 years from now a favor and make your project easy to reason about, easy to enhance, easy to fix.

---

## Conclusion

- We're here to help!
- Please let us know if you're interested in getting involved in the CoE

----

#### Drop us a line!

> Brad Pearson
> [bpearson@netjets.com](mailto:bpearson@netjets.com)

> Caitlin Steinert
> [csteinert@base2.io](mailto:csteinert@base2.io)

> Drew Miller
> [dmiller@base2.io](mailto:dmiller@base2.io)

----

# Questions?
