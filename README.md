# 22 State Homework: Redux Store

## Links:
Git repo: https://github.com/Gopika2514/redux-store

Git site: https://gopika2514.github.io/redux-store/

Heroku: https://peaceful-fjord-50507.herokuapp.com/

## Description

E-commerce website that allows user to login and purchase items,also see their order history.




## User Story

```md
AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem
```

## Acceptance Criteria

```md
GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API
```

## Mock-Up

This section reviews the web application's general appearance and functionality.

The following animation shows how a user can register using the Signup page and then navigate to the Products page:

![A user registers on the Signup page and then navigates to the Products page, which displays images and descriptions of products.](./Assets/22-state-homework-demo-01.gif) 

The following animation shows how the user can select a category, choose a product, view details about it on the product page, and add and remove it from their shopping cart:

![The user selects a category, chooses a product, views details about it on the product page, and adds it to and removes it from their shopping cart.](./Assets/22-state-homework-demo-02.gif)

Finally, the user can check out by going to their shopping cart, as shown in the following animation:

![The user checks out by going to their shopping cart.](./Assets/22-state-homework-demo-03.gif)

## Getting Started

For instructions to add Redux to your application, refer to the [Redux Fundamentals basic tutorial](https://redux.js.org/basics/basic-tutorial). Note that the documentation will refer to additional packages that you'll need to complete this implementation.

**Important**: Be sure to review ALL of the documentation, because there are newer methods that can make these tools much easier to implement. React has gone through several iterations; as such, some React-and-Redux tutorials will assume that you aren't using Hooks.


