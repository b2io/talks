# NetJets User Group

Presented by:

 * Brad Pearson (NetJets)
 * Caitlin Steinert (Base Two)
 * Drew Miller (Base Two)

---

## Outline

 1. Introduction
 2. Building a Living Styleguide
 3. Improving the Developer Experience

---

## Introduction

> Brad has some deep thoughts.

----

### One more thing...

> What did he just say?!

---

## Building a Living Styleguide

 - Using a Styleguide to create a common design language
 - Composing a UI from the ground up
 - What does Styleguide-driven development mean for NetJets

----

### Using a Styleguide

> Caitlin has some deep thoughts.

----

### Composing a UI

> Thoughts, we've got them.

----

### Styleguide-driven development

> The thrilling conclusion!

---

# Improving the Developer Experience

----

## Developer Experience (DX)

Your productivity is a precious commodity; use it wisely.

1. Focus on the task at hand <!-- .element: class="fragment" -->
2. Use purpose-built tools <!-- .element: class="fragment" -->
3. Reduce ambient complexity <!-- .element: class="fragment" -->

Note: 
We talk a lot about UX, but let's talk about DX.

----

## Component-driven Development

![Lioness Stalking](images/dx--focus.gif)

> Focus on the task at hand

----

### How does a _Styleguide_ focus us?

- Styleguide components are just markup and styles <!-- .element: class="fragment" -->
- Behavior comes from the platform implementation <!-- .element: class="fragment" -->
- We get to focus on the behavior, not the presentation <!-- .element: class="fragment" -->

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

----

### Angular 2

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
- We import the SASS,
- We re-use the HTML,
- And we wrap it in an Angular 2 component

----

### React

```js
import '@netjets/styleguide/icon.scss';
import React from 'react';

const Icon = ({ name }) => (
  <span className={`netjets-${name}`}></span>
);

export default Icon;
```

Note:
- And in React,
- We import the SASS,
- We re-euse the HTML,
- And we wrap it in a React component

----

### Wait... what?!

```ts
@Input()
public name: string;
```
<!-- .element: class="fragment" -->

```js
import '@netjets/styleguide/icon.scss';
```
<!-- .element: class="fragment" -->

```js
<span className={`netjets-${name}`}></span>
```
<!-- .element: class="fragment" -->

Note:
- Annotations syntax?
- Importing SASS?
- HTML in our JS?
- How can we get that into our project?

----

## Front-end Tooling

![Flux Capacitor](images/dx--tools.gif)

> Use purpose-built tools

----

### Chrome DevTools

![Chrome DevTools](images/dx--chrome-devtools.png)

----

### Visual Studio Code

![Visual Studio Code](images/dx--vscode.png)

----

## Unidirectional data flow

![Not that Flux](images/dx--flux.gif)

> Reduce ambient complexity

---

## Conclusion

> We're around, come say hi (and ask questions)