# Notes

# Set up environment 

The documentation on how to set up the latest version of react can be found [here](https://reactjs.org/docs/create-a-new-react-app.html)

1. Inside of an empty directory/folder run the following command to create a new react project `npx create-react-app running-w-recoil` 
2. Run `cd running-w-recoil`
3. Finally, to run your react server you could either run `npm start` or `yarn start`

<TimeStamp start="0:00" end="0:02">

Instructions to set up a brand new React project [here](https://reactjs.org/docs/create-a-new-react-app.html)

To follow along with the instructor, you need the following code in your `App.js` file:

```jsx
<div className="App">
    <h1>Recoil!</h1>
</div>

```
</TimeStamp>

<TimeStamp start="0:09" end="0:15">

To download recoil, run in your terminal  `yarn add recoil` or `npm add recoil` 

</TimeStamp>

<TimeStamp start="0:39" end="0:42">

In recoil `atoms` represents a piece of state. `Atoms` are the source of truth in your application state. If you want to know more about `atoms` refer to this [documentation](https://recoiljs.org/docs/basic-tutorial/atoms/)

</TimeStamp>

<TimeStamp start="1:42" end="1:46">

The best part of having atoms is that we can use the same state in multiple components.

</TimeStamp>
