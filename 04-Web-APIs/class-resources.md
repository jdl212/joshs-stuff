# 🏕 Class resources
**04 Web APIs**
​
**Table of contenets**
(click section to jump to it)
<!-- TOC -->

- [:star2: Topic Specific](#star2-topic-specific)
  - [Traversing the DOM](#traversing-the-dom)
  - [Modifying and Creating Elements](#modifying-and-creating-elements)
  - [Javascript Timing Tools](#javascript-timing-tools)
  - [JavaScript Events](#javascript-events)
  - [HTML Form/Input elements](#html-forminput-elements)
  - [Local Storage](#local-storage)
  - [JSON Managing](#json-managing)
  - [JavaScript Arrays and Array Methods](#javascript-arrays-and-array-methods)
- [:file_folder: General Reference](#file_folder-general-reference)

<!-- /TOC -->
----
​
### :star2: Topic Specific

#### Traversing the DOM
- **getElementById()** -  getting **ONE** element by **ID**
  - [MDN Definition](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById)
  - [w3 Schools Definition](https://www.w3schools.com/jsref/met_document_getelementbyid.asp)
- [**getElementsByClassName()**](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementsByClassName) (MDN) - getting a **HTMLCollection** of ALL matching elements by **CLASS NAME**
- [**getElementsByTagName()**](https://developer.mozilla.org/en-US/docs/Web/API/Element/getElementsByTagName) (MDN) - getting a **HTMLCollection** of ALL matching by **TAG NAME**
- [**querySelector()**](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector) (MDN) - getting **THE FIRST** matching element by **QUERY SELECTOR**
- [**querySelectorAll()**](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll) (MDN) - getting a **HTMLCollection** of ALL matching elements by **QUERY SELECTOR**
​
#### Modifying and Creating Elements
- [**setAttribute()**](https://developer.mozilla.org/en-US/docs/Web/API/Element/setAttribute) (MDN) - **SETTING** the **ATTRIBUTE** of an element
- [**createElement()**](https://developer.mozilla.org/en-US/docs/Web/API/Document/createElement) (MDN)- **CREATING** an **ELEMENT** to later insert into the DOM
- [**appendChild()**](https://developer.mozilla.org/en-US/docs/Web/API/Node/appendChild) (MDN) - **INSERTING** an **ELEMENT** into the DOM
- [**someNode.textContent**](https://developer.mozilla.org/en-US/docs/Web/API/Node/textContent) (MDN) - Changing the **text content** of a **Node** object *Note: Elements are types of nodes so this works on them too*
​
#### Javascript Timing Tools
- [**setTimeout()** and **clearTimeout()**](https://www.w3schools.com/jsref/met_win_settimeout.asp) (W3 Schools) - **wait** a specified amount of time and **run a function ONCE** when the time is up
- [**setInterval()** and **clearInterval()**](https://www.w3schools.com/jsref/met_win_setinterval.asp) (W3 Schools) - **wait** a specified amount of time, **run a specified function**, **wait** the same amount of time, **run** the same function, **wait** the same amount of time, **run** the same function, **wait** the same amount of time, **run** the same function, **wait** the same amount of time, **run** the same function, **wait** the same amount of time, **run** the same function and **repeat** until **clearInterval()** is called
​
#### JavaScript Events
- [Event Bubbling](https://en.wikipedia.org/wiki/Event_bubbling) (wikipedia)
- [**addEventListener()**](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener) (MDN) - setting up an **event listener** to execute a function when an **event** occurs
- [General info on **JavaScript Events**](https://developer.mozilla.org/en-US/docs/Web/Events) (MDN)
- [Specific info on mouse **click** events](https://developer.mozilla.org/en-US/docs/Web/Events#Mouse_events) (MDN)
- [EventTarget.removeEventListener()](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/removeEventListener) - disabling or **removing** an **event listener**
- [what is **event default** behavior and why do we need to **preventDefault()**](https://javascript.info/default-browser-action) (javascript into) - "A click on a form submit button – initiates its submission to the server." We prevent this when we aren't using that behavior.

#### HTML Form/Input elements
- [General types of html element input reference](https://www.w3schools.com/html/html_form_elements.asp) (W3)
- [`<select>` tag](https://developer.mozilla.org/en-US/docs/Web/API/HTMLSelectElement) (MDN)

#### Local Storage
- [General **local storage** reference](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) (MDN)
- [**storage.setItem()**](https://developer.mozilla.org/en-US/docs/Web/API/Storage/setItem) (MDN)
- [**storage.getItem()**](https://developer.mozilla.org/en-US/docs/Web/API/Storage/getItem) (MDN)

#### JSON Managing
- [**JSON.stringify(*JSON to convert to a string*)**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify) (MDN)
- [**JSON.parse(*javascript obj or value to convert to JSON*)**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse) (MDN)

#### JavaScript Arrays and Array Methods
- [General JAvaSCript Arrays and methods](https://www.w3schools.com/js/js_arrays.asp) (W3)
- [**`Array.prototype.splice()`**](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice) (MDN)

### :file_folder: General Reference
- [what is a javascript function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions) (MDN)
- [DOM Introduction](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction) (MDN)
- [JS Comparison and Logical Operators (e.g. `===` `&&` `||` `!=` )](https://www.w3schools.com/js/js_comparisons.asp) (W3 Schools)
- **Numbers** in JavaScript
  - [W3 Definition](https://www.w3schools.com/js/js_numbers.asp)
  - [MDN Definition](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number)
- **Incrementing and Decrementing** in JavaScript with `a++` and `a--`
  - [Incrementing `a++`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Increment) (MDN)
  - [Decrementing `a--`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Decrement) (MDN)
  - [Difference between using `++` and `--` operators in postfix (`a++` or `a--`) vs. prefix (`++a` or `--a`)](https://codeburst.io/javascript-increment-and-decrement-8c223858d5ed) (coddeburst)
