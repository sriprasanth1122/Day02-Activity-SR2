Differences between Document and Window Objects

In this blog, we will see the Document object & Window object, their various properties & methods, along with knowing their implementation & the differences between them.

Document Object:

The document object represent a web page that is loaded in the browser. By accessing the document object, we can access the element in the HTML page. With the help of document objects, we can add dynamic content to our web page. The document object can be accessed with a window.document or just document.

Syntax:
document.property_name;
The properties of document objects that are commonly used are listed in the below table:

Properties of document:

activeElement: It returns the currently active elements in the document.

body: It returns the contents of the body element.

anchors: It returns all <a> elements that have a name attribute.

baseURI: It returns a string value that represents the base URI of the document.

cookie: It returns the cookie of the current document.

charSet: It returns a string, representing the document’s character encoding.

Methods of Document:

Syntax:
document.method_name;
The lists of most commonly used methods are listed below:

addEventListener(): It is used to attach an event handler to the specified element.

adoptNode(): It is used to adopt a node from another document and it returns a node object, representing the adopted node.

close(): It is used to close the output stream.

createAttribute(): It is used to create an attribute node with the specified name and returns the attribute object.

createComment(): It is used to create a comment node with some text.


Window Object: 

The window object is the topmost object of the DOM hierarchy. It represents a browser window or frame that displays the contents of the webpage. Whenever a window appears on the screen to display the contents of the document, the window object is created. 

Syntax:
window.property_name;
The properties of Window objects that are commonly used are listed in the below table:

Properties of the window:

Closed: It holds a Boolean value that represents whether the window is closed or not.

console: It returns a reference to the console object which provides access to the browser’s debugging console.

defaultStatus: It is used to define the default message that will be displayed in the status bar when no activity is carried on by the browser.

controllers: It returns the XUL controller objects for the current Chrome window.

customElements: It returns a reference to the CustomElementRegistry object, which can be used to register new custom elements and also get information about already registered custom elements.

crypto: It returns the browser crypto object.

Methods of Window:

Syntax:
window.method_name;
The methods of Window objects that are commonly used are listed in the below table:

alert(): It is used to display an alert box. It displays a specified message along with an OK button and is generally used to make sure that the information comes through the user.

atob(): It is used for decoding a base-64 encoded string. It is used to decode a string of data that has been encoded using the btoa() method.

blur(): It is used to remove focus from the current window.

btoa(): It is used for encoding a string in base-64 format.

clearInterval(): It clears the interval which has been set by the setInterval() function before that.

clearTimeout(): It clears the timeout which has been set by the setTimeout()function before that.
