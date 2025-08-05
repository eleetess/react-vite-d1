# React + Vite
## Clear the Example UI

Delete all files inside src/components/ (or remove any starter components).

In src/App.jsx, replace any JSX with a single empty <div />.

Create a Fresh Component
Inside src/components/, create a file named Greeting.jsx with the following:

export default function Greeting() {
  return <h1>Hello, React world!</h1>;
}
Import and Render Your Component
In App.jsx, replace the content with:

import Greeting from "./components/Greeting";

export default function App() {
  return <Greeting />;
}
#Set up instructions/bash commands and returns
-erica@EricaSchoolcomp MINGW64 ~
-$ npm create vite@latest react-vite-d1 -- --template react
-Need to install the following packages:
-create-vite@7.0.3
-Ok to proceed? (y) y


-> npx
-> create-vite react-vite-d1 --template react

-|
-o  Scaffolding project in C:\Users\erica\react-vite-d1...
-|
-—  Done. Now run:

 - cd react-vite-d1
 - npm install
 - npm run dev


-erica@EricaSchoolcomp MINGW64 ~
$ cd react-vite-d1

-erica@EricaSchoolcomp MINGW64 ~/react-vite-d1
$ code .

-erica@EricaSchoolcomp MINGW64 ~/react-vite-d1
$

