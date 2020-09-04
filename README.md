# DOM II - Event Exploration

Fun Bus wants you to make their site more interactive. They are relying on you to provide 10 unique events to enhance their site. Explore the many events available to you by using the [MDN events reference](https://developer.mozilla.org/en-US/docs/Web/Events).

## Instructions

### Task 1: Project Set Up

#### Set Up The Project With Git

**Follow these steps to set up and work on your project:**

* [ x] Create a forked copy of this project.
* [ x] Add your team lead as collaborator on Github.
* [ x] Clone your OWN version of the repository (Not Lambda's by mistake!).
* [ x] Create a new branch: git checkout -b `<firstName-lastName>`.
* [ x] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
* [x ] Push commits: git push origin `<firstName-lastName>`.

#### Launch the project with npm

* [ ] Navigate to the root of the project with your command line.
* [ ] Run `npm install` to download any dependencies listed in the `package.json` file.
* [ ] Run `npm start` to compile your project and launch a development server.
* [ ] Navigate Chrome to the URL indicated in the output of the `npm start` command.

### Task 2a: Create listeners for 10 types of events

* [ ] Using your [index.js file](js/index.js), create [event listeners](https://developer.mozilla.org/en-US/docs/Web/Events) of at least 10 _different_ types. You must Use your creativity to make the Fun Bus site more interactive. For example you could change colors, animate objects, remove objects, etc. Here are some event types you could try to use:
  * `mouseover`
  * `keydown`
  * `wheel`
  * `load`
  * `focus`
  * `resize`
  * `scroll`
  * `select`
  * `dblclick`
  * `drag / drop`

Note: Drag and drop is a bit more advanced than the others: it's not actually a single type of event but several types that need to work together.

* [ ] Nest two similar events somewhere in the site and prevent the event propagation properly. Remember not all event types bubble.
* [ ] Stop the navigation items from refreshing the page by using `preventDefault()`

### Task 2b: Exit Ticket

Once you begin, you will have 15 minutes to answer the questions [here](https://app.codesignal.com/public-test/Xy9i8nGP4uiLbHrWT/yqgv5hmhcCLcen).

The completion of these questions is mandatory for MVP. However, passing the quiz doesn't affect your standing as a Lambda School student whatsoever. This is Lambda School testing itself! Please answer honestly and to the best of your ability without using external references.

### Task 3: Stretch

* [ ] Go look at [GSAP](https://greensock.com/) and implement the animations found in that library with your custom events.

#### Stretch assignment

* [ ] Take a look at the [stretch assignment](stretch-assignment) and follow the instructions in the read me file.

## Submission Format

**Follow these steps for completing your project.**

* [ ] Submit a Pull-Request to merge `<firstName-lastName>` Branch into `main` (student's  Repo). **Please don't merge your own pull request**
* [ ] Add your team lead as a reviewer on the pull-request
* [ ] Your team lead will count the project as complete by merging the branch back into `main` branch.
