<h1> Session Traveler </h1>

<h3>Objective</h3>
<p>A simple exercise to demonstrate using and viewing lifecycle methods via console log.</p>
<br>

<h3>USING LIFECYCLE METHODS TO SAVE DATA BETWEEN SESSIONS</h3>
<h4>Three steps to make data available after a user closes and reopens the UI:</h4>
<ol>
  <li>Save state to the browser’s storage after each re-render</li>
  <li>Pull the saved value when the UI is reopened</li>
  <li>Set state to the value from the previous session</li>
</ol>

<br>
<h3>Process</h3>
<h4>Viewing Lifecycle Methods via Console Log:</h4> 
<p>In App.js, log messages to the console log in the componentDidMount and componentDidUpdate phases, so the console will show saved data between UI sessions.</p> 

<h4>Actions:</h4>
<p>In the componentDidUpdate phase, save the state to the browser’s local storage, and in the componentDidMount phase, log messages to the console to show the values retrieved from local storage.</p> 
