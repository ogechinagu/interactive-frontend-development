name: outro
class: middle, center

# Interactive Front-end Development

## Urmas Talimaa
## _Glia Inc_

???

<!-- Dummy notes to check presenter display  -->

Presenter display slide notes

Pre-lecture checklist

* Switching between mirroring and non-mirroring works
* Unrelated tabs and windows closed or minimized
* Do not disturb mode **ON**
* Slides cloned, one has presenters mode on
* Dependencies installed and scripts are working for lecture example code
* Terminal(s) open with code and window to run scripts

---

# Redux

It is about time we made a Redux application!

[Code example](https://github.com/urmastalimaa/interactive-frontend-development/blob/master/lecture_8/src/components/ReduxApp.js)

---

# But developing in the back end is so much nicer!

* 100% agree
* Immutability and pure functions (reducers) are so powerful that it is
  possible to **move** application logic out of the browser and execute it
  server side, which is a very powerful paradigm shift.
* One option for this is React's server side rendering, but Elixir's Phoenix
  LiveView is even more impressive.

---

# But developing in the back end is so much nicer!

https://youtu.be/U_Pe8Ru06fM?t=1143

Notice the
  * pure render function,
  * initial state being calculated upon start-up,
  * handle_event functions (reducers) which return new state based on previous state
    and an action and
  * changes to the DOM are applied using diffs.

???

Having the same pattern being put into good use across many contexts reinforces
its value.

---

# Thanks for hanging on

I hope you

* learned something
* had a bit of fun
* got angry at least once (need to have some emotion to be memorable)

---

# Thanks for hanging on

You now have an idea about techniques for building arbitrary user interfaces

Actual projects are never clean examples, but good guidelines nudge towards a
maintainable application

---
 
# Front end development

* Often regarded as an afterthought - just hack it together
* Front-ends tend to influence back-end design
* Front-end applications need logs and error reports too
* Just because it is JavaScript does not mean that the code should be garbage

---
 
# Front end development

* Keep it **simple**

  Composition! Pure functions!

* Keep it **declarative**

  Easy to read and understand!

* Keep it **testable**

  Less bugs!

---

# Front end development

* Keep it **traceable**

  Logs! Reproducible behaviour!

* Keep **concerns separated**

  Business logic, presentation

---
 
# Exam

* TODO Details
* Multiple choice questions
* One/two written questions
* All questions from slides + lecture chapters in course repository
* 21.05 16:15 - Please try to make this one
* 28.05 16:15 - Let me know if you absolutely need this timeslot

---
 
# Sample exam questions

Following sample question list is **not comprehensive**


If you understand the **core concepts**, **principles** and **terminology** of
the technologies/techniques discussed on the slides you will have little problem
answering the questions

---
 
# Sample question

What is a _transpiler_?

---
 
# Sample question

Identify/characterize a

* Pure function
* Stateful function
* Stateless function

---
 
# Sample question

Characterize
* State
* Identity
* Shared mutable state

---
 
# Sample question

Identify/write a pure function React component
 
---

# Sample question

Identify/characterize a

* reducer function
* selector function
 
---

# Sample question

Which of the following characterizes `fetch` / `WebSocket`?

---
 
# Sample question

What is the `history` API in the context of web applications?
 
---

# Sample question

How to pause JavaScript execution at a specific line in JavaScript in a web browser?

---
 
# Sample question

Write a React component named `Names`, that when provided array of arbitrary
names ({names: [‘foo’, ‘bar’]}) as props will output the following HTML
equivalent 

```html
<ul id="names">
  <li>foo</li> 
  <li>bar</li>
</ul>
```