# UI Engineer Pairing Assessment

To get a feel for how you build UI, we'd like to you approach 2 separate problems which demonstrate your understanding of design, HTML, CSS, accessibility and JavaScript.

Our short timeframe will probably not allow you to code as if it were production-ready, however, we'd like you to demonstrate the thought processes and implementation details required assuming you were building this for production.

While there are small-screen and wider-screen layout designs provided for each task, it's important to note that they are simply design suggestions. No colours or sizes will be provided, because part of being a great UI Engineer is your "feel" for UI design and system design as a whole. You're free to implement or suggest changes that you feel creates a better experience.

To complete the tasks, you can choose to use either React or Vue. In the [react](/react) directory, you will find a basic project scaffolded with [Create React App](https://facebook.github.io/create-react-app/), and in the [vue](/vue) directory, you'll find a basic [Vue CLI](https://cli.vuejs.org/) scaffolded project. Both have Sass as a dependency, should you wish to use it.

---

## Tasks

### 1. Responsive masthead with navigation

We'd like you to create a typical responsive header and navigation menu.

See [task-1.png](/designs/task-1.png) for a suggested design approach.

#### Requirements:

* On narrow screens, the header will consist of a logo and "hamburger" button.
* Upon pressing the hamburger, the navigation menu will open, which lists the various options.
* On wider screens, the menu options are visible by default and right-aligned within the width-constrained header.
* When a user has shown intent to activate a particular item, it should be indicated as such.
* Use the provided SVGs in `/assets/images` for the logos and icons.

The menu options are:

* Dashboard
* Search
* Bookings
* Job Board
* How to Guide

#### Things we're looking for:

* Imagine this is the very first thing to be built in our re-platforming project. What "foundations" would need to be set up to start?
* While there are only 3 SVGs here, how might we best accommodate a system of 50 SVGs?
* Which HTML elements should be used to accommodate the requirements?
* What accessibility considerations are there?

### 2. "How we can help"

We'd like you to list 8 ways Hireup can help people seeking support, and translate them in to a striking, responsive layout.

See [task-2.png](/designs/task-2.png) for a suggested design approach.

#### Requirements:

* Each item has a consistent gutter around it
* On narrow screens, the items are stacked vertically, and no "decorative" images are displayed.
* At an appropriate screen size, the items are displayed in a disjointed, 3-column grid-like pattern.
* The images must not appear squashed at any time.
* The responsive behaviour between narrow and wide screens is up to your discretion.
* Use the provided placeholder image in `/public/images`.

The item content is available at [task-2-content.md](/task-2-content.md)

#### Things we're looking for:

* Which HTML elements should be used to accommodate the requirements?
* What should the maximum grid width be?
* What performance considerations are there?
* What is the best way to produce the different colour tiles?
* How do you envisage the responsive behaviour?
