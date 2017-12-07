//this/appwhat/src/App.js
import React, { Component } from 'react';
import logo from './logo.svg';
import imgOne from './imgOne.PNG';
import imgTwo from './imgOne.PNG';
import imgThree from './imgOne.PNG';
import imgFour from './imgOne.PNG';
import imgFive from './imgOne.PNG';
import imgSix from './imgOne.PNG';
import './App.css';

class App extends Component {
	render() {
		return (
			<div className="App">
				<div className="App-container">
					<header className="App-header">
						<img src={logo} className="App-logo" alt="logo" />
						<h1 className="App-title">The 5 Key Components of React</h1>
					</header>
					<p className="App-intro">This is a single page web application that provides a brief tutorial on the five key concepts of the React Framework</p>
				</div>
				<div className="Tutorial-wrapper">
				<h3>The 5 Key Components are:  </h3>
				
				<ul>
					<li>Components</li>
					<li>JSX</li>
					<li>Props&State</li>
					<li>The Component API</li>
					<li>Component Types</li>
				</ul>
				
				<h3>React - Components</h3>
				
				<p>React is all about components. Components let you split the UI into independent, reusable pieces, and think about each piece in isolation.
				Conceptually, components are like JavaScript functions. They accept arbitrary inputs (called “props”) and return React elements describing 
				what should appear on the screen. A React component is a single object that not only output HTML like a traditional template would, but also
				includes all the code needed to control that output. Below is an example of a React component, written in an ES6 class(most common way to write React components)
				containing a render method that returns HTML to the DOM.</p>
				
				<img src={imgOne} className="" alt="code image" />
				
				<p>This function is a valid React component because it accepts a single “props” (which stands for properties) object argument with data and returns a 
				React element. We call such components “functional” because they are literally JavaScript functions.</p>
				
				<h3>React - JSX</h3>
				
				<p>React's component approach means that Javascript and HTML live in the same file. Bringing these two together is acheived by using the
				JSX language(X stands for XML), a syntax extension to Javascript. JSX produces React elements. Using JSX with React allows one to describe 
				what the UI should look like. You can embed and Javascript expression is JSX by wrapping it in curly braces.</p>
				
				<img src={imgTwo} className="" alt="code image" />
				
				<h3>React - Props & State</h3>
				
				<p>React attributes are called 'props'(short for properties). Props are how components communicate with each other.
				Because of this, React’s data flow is unidirectional: data can only go from parent components to their children,
				not the other way around. State comes into play when a component needs to react to input data. State is not an
				inherent property like props, it's just the temporary result of user input.</p>
				
				<img src={imgThree} className="" alt="code image" />
				
				<p>Note that a component’s state can also be passed on to its own children as a prop. You can think of this as a
				big river flowing downhill, with the router, data layer, and various components each adding their own little stream
				of data to form the main app state.</p>
				
				<img src={imgFour} className="" alt="code image" />
				
				<h3>React - The Component API</h3>
				
				<p>We’ve already mentioned render and setState, which are both part of a small set of component API methods. Another useful one is the constructor,
				which you can use to initialize your state and bind methods. Apart from these three functions, React also provides a set of callbacks triggered at 
				various points during the component’s lifecycle (before loading, after loading, after unmounting, and so on). Unless you’re doing some advanced React
				voodoo, you’ll probably almost never need to worry about these. If this section seems short, it’s because learning React is actually much more about 
				mastering programming and architectural concepts rather than learning a set of boring API methods. This is what makes it so refreshing!</p>
				
				
				<h3>React - Components Types</h3>
				
				<p>Last but not least, here is the quick and dirty on the two types of React components and how they work. A functional component is a function that
				takes a props object as argument, and returns a bunch of HTML. Almost like a traditional template, with the key difference that you can still use
				whatever JavaScript code you need inside that function: </p>
				
				<img src={imgFive} className="" alt="code image" />			
				
				<p>In addition to Function components, React also has Class components. Take a look at how a function component can be changed into a class component in 
				just a few steps.</p>
				
				<h3>Converting a Function to a Class</h3>
				
				<p>A functional component like Clock can be converted to a class in five steps:</p>
				
				<ul>
				<li>Create an ES6 class, with the same name, that extends React.Component.</li>
				<li>Add a single empty method to it called render().</li>
				<li>Move the body of the function into the render() method.</li>
				<li>Replace props with this.props in the render() body.</li>
				<li>Delete the remaining empty function declaration.</li>
				</ul>
				
				<img src={imgSix} className="" alt="code image" />
				
				<p>Clock is now defined as a class rather than a function.</p>
				
				<h3>Recap</h3>
				
				<p>And now a recap of what you've learned:</p>
				
				<ul>
				<li>A React codebase is made up of components.</li>
				<li>Components are written in JSX.</li>
				<li>Data flows are unidirectional (only flows in one direction - from parent to children), except when it comes to 'state', which originates inside a component.</li>
				<li>Components can also be written as pure functions.</li>
				<li>State is just the temporary result of user input.</li>
				</ul>
		</div>
  
				<footer className="footer">
				<p>Credit for all of the content and images provided in this tutorial goes to the</p> 
				<p><a target="_blank" href="https://reactjs.org/docs/introducing-jsx.html">React Documentation</a> &
				<a target="_blank" href="https://medium.freecodecamp.org/the-5-things-you-need-to-know-to-understand-react-a1dbd5d114a3">Free Code Camp React Tutorial</a></p>
				<p>Check them both out for a deeper dive into the React Framework.</p>
				</footer>
		</div>
		);
	}
}
	
export default App;