# E2E Browser Tests

## 🧠You will learn

✅ How to test a web application with functional browser tests (aka E2E tests)

## ⚙️ Setup

Check if you have an app running on `http://localhost:3000/`. If so, you are ready.

If not, then

Open a terminal

```bash
cd web-testing-2022/
npm start
```

Open application at http://localhost:3000/

## ❓Let's define Our Test Strategy

[Software under test](http://localhost:3000/)

[Test strategy](https://docs.google.com/spreadsheets/d/1bFqZIvzbrjjQuWsMVvRKSq7J-Dog8q8ocixXAonnjxk/edit?usp=sharing)

- ❓What is the most basic test that we can code for our application?
- ❓What other tests can we code?

## Cypress Overview

"Fast, easy and reliable testing for anything that runs in a browser."([Cypress.io](https://www.cypress.io/))

In new terminal, without stopping the web app

```bash
npx cypress open
```

💡 Tests live in `cypress/e2e` folder

### 🏋️‍♀️ Code a Cypress test to make sure that our app opens.

1. In your IDE open `cypress/e2e/exercise.cy.js`
2. Follow instructions to implement `it('loads')` test

### 🏋️‍♀️Code a test to ensure that the link will go to the correct location

1. In your IDE open `cypress/e2e/exercise.spec.js`
2. Follow instructions to implement `it('link goes to ultimateqa')` test

### 🏋️‍♀️Write a functional ui test to validate that the link opens in a new tab

- Follow instructions in this test `it('should open link in new tab')`

---

### ❓What are some challenges of functional UI tests?

---

<br/>
  <details>
    <summary>
      <strong>Click here</strong> to see answer.
    </summary>

1. Need a browser
2. Need a server
3. Need to deal with network issues
4. Test will be slower
5. Need an extra dependency (Cypress)
6. Need to learn extra dependency API

  </details>

</br>

---

### ❓Can we test the same thing more efficiently❓

---

<br/>
  <details>
    <summary>
      <strong>Click here</strong> to see answer.
    </summary>

Using component tests

- Cypress 10 component testing workshop by Gleb Bahmutov on Oct 19th 10AM EST.
- [How to run a component test w/ Jest](https://youtu.be/VQLf1pLWDjc?t=166) followed by
- [How to create a componet test for a link w/ Jest](https://youtu.be/VQLf1pLWDjc?t=821)
- [Cypress 10 component testing tutorial](https://youtu.be/aNqLTG1fya4)
- [Examples of using component tests](https://github.com/nadvolod/testing-best-practices#testing-a-button)

  </details>

</br>

---

### ❓What risks remain in our web app?

---

## 📝Summary

✅ E2E UI testing with Cypress allows us to do functional testing of the web app

✅ We can test a link by checking the `href` attribute

✅ We can test that a url opens a new tab with `target='_blank'`

## ⏭️ [Let's continue to expand our coverage](VISUAL.md)

## 🧠Expand your knowledge

[Coding and testing web applications tutorial](https://www.youtube.com/playlist?list=PLSRQwlkmpdj5ak1Rxahdo6mguhbcCOePR)
