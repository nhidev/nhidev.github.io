---
title: JavaScript - Pluralsight questions
image: /assets/img/pluralsight.jpg
---

<details> 
  <summary> What is the difference between a property and a method on a class?</summary>
  	A property is an association between a name and a value; a method is when a function is the value of a property.
 </details>
<details> 
  <summary> What built-in browser object can you use to perform an AJAX request to a server? </summary>
	XMLHttpRequest 
</details>
<details>
<summary> What is the correct syntax for declaring an object literal?</summary>
	const obj = {}
</details>
<details>
	<summary> Which of these is equivalent to the following for loop?</summary>
  <pre><code>
	do {
	  i++;
	  ...
	} while ((i < x)
</code></pre>
</details>
<details>
	<summary> Which keyword would be best to hold a userId that is loaded from the server and never changes?</summary>
	const
</details>
<details>
<summary> What is one function you can use to determine whether a value is an illegal number or not?</summary>
isNaN()
</details>
<details>
<summary> How can you use a DOM method to create a new HTML element?</summary>
	var myNewListItem = document.createElement("li");
</details>
<details>
<summary> How can you instantiate an object with a custom type Person using the new keyword?</summary>
	By defining the object with a constructor function, then instantiating the object using that function and the new keyword:
<pre><code>
	function Person(name, age, etc){
	  this.name = name;
	  this.age = age;
	  this.etc = etc;
	}
	let newPerson = new Person("Bob", 35, "etc");
</code></pre>
</details>
<details>
<summary> Generally, where is the best place to put script tags?</summary>
	At the end of the body tag.
</details>
<details>
<summary> What is the array prototype method that changes the contents of an array by removing existing elements and/or adding new elements?</summary>
	[].splice()
</details>
<details>
<summary> After the following code is executed, what is printed to the console?</summary>
<pre><code>
	let iterable = [10];
	for (let value of iterable) {
	  console.log(value);
	}

	//10
</code></pre>
</details>
<details>
<summary> Which answer correctly shows a function being invoked with the value of another function as an argument?</summary>
	getScore(latestScore())
</details>
