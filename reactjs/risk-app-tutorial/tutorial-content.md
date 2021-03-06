# React js Tutorial - Build a risk log app

## What we will build
We are going to build a risk log app that will allow user to add, edit and delete risks. To each risk user can associate task.
![alt text](https://github.com/andreagulp/JS-Playground/blob/master/reactjs/risk-app-tutorial/img/risk-log-app-001.png)

We are going to build the initial prototype by using setState only. In a later stage we will re-factor to use a more robust and flaxible state management solution. This approach is usefull as it makes you face the reason why you want to complicate (apparently) your life by using redux.

## Who should read this tutorial
The tutorial is suited for beginner react developer that have already a basic (even if very basic) knowledge of react.
I always found hard to find good tutorial in between a complete beginner and a more advanced use case. This tuturial tries to fill this gap.

## Road map
The tutorial will be published in episode.
in each episode, we will try to details all the steps required.
The approach is to introduce as little concept at the time as possible.
In some cases, we will use the most straith forward solution and then refactor for more "smart" approach.

## Environemt setup

### IDE - code editor
I personally use Atom to code with react. Atom is a good editor. Below I'll provide my Atom configuration. 
Most of modern IDEs will be good, that's really your preference. In many cases you will be able to find also similar plugin.
My Atom packages list (on top of the Atom default packages):
  - atom-ternjs
  - auto-detect-indentation
  - autocomplete-modules
  - autoupdate-packages
  - file-icons
  - fold-functions
  - language-babel
  - open_in_cmd
  - pigments

### Developers Environment
You need to have installed globally node.js / npm. 
To start up my react application I use [create-react-app](https://github.com/facebookincubator/create-react-app).
Before using create-react-app, install it globally
```sh
npm i g create-react-app
```

## Plan the App
React is all about components. It make sense to start plan our up by understanding the different components that we will need to form our app.
My personal suggestion is to avoid to create too big components as it becomes more difficult to reuse them.
As you can see, I'm yet not taking opportunity to reuse the components that I create. In a future episode of this tutorial we will re-factor the app so that we maximize the usability of the components making up the app.
![alt text](https://github.com/andreagulp/JS-Playground/blob/master/reactjs/risk-app-tutorial/img/risk-log-app-components-002.png)


## Create the App and install the dependencies
use create-react-app to scaffold your initial project
Open a cmd (I personally use gitBash) and use create-react-app to get your app up and running.
```sh
create-react-app risk-log-001
```
after the setup is completed
```sh
cd risk-log-001
```
and
```sh
npm start
```

The app uses [material-ui](http://www.material-ui.com) for the UI element, so we will install and configure material-ui to be used in our app.

```sh
npm i --save material-ui react-tap-event-plugin
```





