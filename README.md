# Migrating to React Hooks Minishop

[![Maintenance Status](https://img.shields.io/badge/status-maintained-brightgreen.svg)](https://github.com/benmvp/migrate-react-hooks-minishop/pulse)
[![Build Status](https://github.com/benmvp/migrate-react-hooks-minishop/workflows/CI/badge.svg)](https://github.com/benmvp/migrate-react-hooks-minishop/actions)
[![license](https://img.shields.io/badge/license-GPL%20v3-blue)](#license)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

[![Watch on GitHub](https://img.shields.io/github/watchers/benmvp/migrate-react-hooks-minishop.svg?style=social)](https://github.com/benmvp/migrate-react-hooks-minishop/watchers)
[![Star on GitHub](https://img.shields.io/github/stars/benmvp/migrate-react-hooks-minishop.svg?style=social)](https://github.com/benmvp/migrate-react-hooks-minishop/stargazers)

An exercise-based minishop by Ben Ilegbodu to learn how to migrate to React Hooks from classes for a better way to develop components and manage state in React applications. Best if accompanied with [live facilitation](https://www.benmvp.com/minishops/migrating-to-react-hooks/) by me 🙂.

## Pre-Minishop Instructions

In order to maximize our time _during_ the minishop, please complete the following tasks in advance:

- [ ] Set up the project (follow [setup instructions](#system-requirements) below)
- [ ] Install and run [Zoom](https://zoom.us/) on the computer you'll be developing with
- [ ] Install React Developer Tools for [Chrome](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) (recommended) or [Firefox](https://addons.mozilla.org/en-GB/firefox/addon/react-devtools/)
- [ ] Install a JSX-friendly code editor, such as [Visual Studio Code](https://code.visualstudio.com/)
- [ ] Brush up on modern [ES.next](http://www.benmvp.com/learning-es6-series/) features, if they are unfamiliar to you
- [ ] Have experience building React applications using class components

The more prepared you are for the minishop, the better it will go for you! 👍🏾

## System Requirements

- [git](https://git-scm.com/) v2 or higher
- [Node.js](https://nodejs.org/en/) v12 or higher
- [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) v6 or higher

All of these must also be available in your `PATH` in order to be run globally. To verify things are set up properly, run:

```sh
git --version
node --version
npm --version
```

If your node version is version 9 or lower, you can [install `nvm`](https://github.com/creationix/nvm#install-script) to manage multiple versions of node.

If you have trouble with any of these, learn more about the `PATH` environment variable and how to fix it here for [Windows](https://www.howtogeek.com/118594/how-to-edit-your-system-path-for-easy-command-line-access/) or [Mac/Linux](http://stackoverflow.com/a/24322978/971592).

## Setup

After you have verified that you have the proper tools installed (and at the proper versions), getting setup _should_ be a breeze. Run the following commands:

```sh
git clone https://github.com/benmvp/migrate-react-hooks-minishop.git
cd migrate-react-hooks-minishop
npm run setup
```

This will likely take a **few minutes** to run. It will clone the repo, verify the environment, and install all of the JavaScript dependencies needed to build our app.

If it fails, please read through the error logs and see if you can figure out what the problem is. Double check that you have the proper [system requirements](#system-requirements) installed. If you are unable to figure out the problem on your own, please feel free to [file an issue](https://github.com/benmvp/migrate-react-hooks-minishop/issues/new) with _everything_ (and I mean everything) from the output of the commands you ran.

## Running the app

We will go through several exercises converting components written in classes to hooks. To get started and verify that everything has been installed correctly, run:

```sh
npm start
```

The app should pop up in your default browser running at http://localhost:3000/. The app should display an index page with links to the steps in the minishop.

For those interested, the app is a standard app bootstrapped by [Create React App](https://create-react-app.dev/).

## Minishop Outline

Let's learn about React Hooks! ⚛️

### 🧔🏾 About Me

Hiya! 👋🏾 My name is Ben Ilegbodu. 😄

- Christian, Husband, Father of 3️⃣
- Pittsburg, California
- Principal Frontend Engineer at [Stitch Fix](https://www.stitchfix.com/) (and yes [we're hiring](https://www.stitchfix.com/careers/jobs)!)
- [@benmvp](https://twitter.com/benmvp)
- [www.benmvp.com](https://www.benmvp.com/)
- Go Rockets! 🚀🏀

### 🕘 Schedule

Each step in the minishop contains exercises to apply what you just learned. You will be migrating classes to new code using hooks. There are also bonuses if you've got extra time. The **exercises are intended to be a lot**, so don't worry if you don't finish them all.

If at any point you get stuck, you can find the answers in the `answers/` directory of the step.

- 🛠️ Setup / Logistics / Intro
- [Step 1 - State](src/01-state/)
- [Step 2 - Effects](src/02-effects/)
- 😴 10 minutes
- [Step 3 - Context](src/03-context/)
- [Step 4 - Custom hooks](src/04-custom-hooks/)
- ❓ Q & A
- [Final Quiz!](src/quiz/)
- 👋🏾 Goodbye!

### ❓ Asking Questions

- Please **interrupt me** and ask questions! Others likely will have the _same question_.
- However, unrelated questions are best sent to [Twitter](https://twitter.com/benmvp).

### 🖥️ Zoom Hygiene

- Keep your **video on** (if possible) to make it feel more human and lively
- Keep your **microphone muted** unless your talking to avoid background noise distractions
- Answer each other's questions in the chat
- Use breakout rooms for help

### ⭐ Concepts

Here is what you'll come away knowing at the end of the minishop...

- Defining function components ([Step 1](src/01-state/))
- Rules of hooks (throughout)
- Maintaining UI state with the `useState` hook instead of `setState` ([Step 1](src/01-state/))
- Managing side effects with/without cleanup using the `useEffect` hook instead of lifecycle methods ([Step 2](src/02-effects/))
- Passing down and updating context with the `useContext` hook ([Step 3](src/03-context/))
- Sharing component logic by creating custom hooks ([Step 4](src/04-custom-hooks/))

## 🧠 Elaboration & Feedback

Each step has an Elaboration & Feedback form link at the end. After you're done with the exercise and before jumping to the next step, please take a few minutes to fill out the form to **solidify your learning**.

At the end of the minishop, I would greatly appreciate your overall feedback. [Share your minishop feedback](https://bit.ly/to-hooks-ms-feedback).

### 🤝 Code of Conduct

All attendees, speakers, sponsors and volunteers at this minishop are required to agree with the [code of conduct](https://www.benmvp.com/minishops/conduct/). Organizers will enforce this code throughout the event. We expect cooperation from all participants to help ensure a safe environment for everybody.

## License

All of the minishop material is available for **private, non-commercial use** under the [GPL version 3](http://www.gnu.org/licenses/gpl-3.0-standalone.html) license. If you would like to use this minishop to conduct your own minishop, please contact team@benmvp.com.

### 👉🏾 First Step

Go to [Step 0 - Begin](src/00-begin/).
