### 1\. addEventListener()

`addEventListener()` is a JavaScript method used to attach an event handler to an HTML element.

It allows developers to execute a specific function when a particular event occurs.

It supports different types of events, such as clicks, keyboard actions, mouse movements, and form interactions.

### 2\. Event Info (Event Object)

The Event Object contains information about an event that occurs in the browser.

It is automatically passed to the event handler when an event occurs.

It provides useful properties and methods that allow developers to identify the event type, access the element that triggered it, and interact with the event.

Some important properties:

* `event.type`: Returns the type of event.

* `event.target`: Refers to the element that triggered the event.

* `event.currentTarget`: Refers to the element whose event handler is currently executing.

### 3\. preventDefault()

`preventDefault()` is a method used to prevent the browser's default behavior associated with a particular event.

It does not stop the event from propagating through the DOM. It only prevents its default action.

It is commonly used when developers need to control the default behavior of forms, links, and other interactive elements.

### 4\. Form Events

### A. onSubmit

The `submit` event occurs when a form is submitted.

It is commonly used to handle form data, validate user input, and control the form submission process.

### B. onChange

The `change` event occurs when the value of an input element has been changed and the change is committed.

For text inputs, it generally fires when the user leaves the input after changing its value.

### C. onInput

The `input` event occurs whenever the value of an input element changes due to user interaction.

Unlike the `change` event, it fires immediately as the user modifies the value.


Official MDN References:

* [addEventListener()](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener?utm_source=chatgpt.com)

* [Event Object](https://developer.mozilla.org/en-US/docs/Web/API/Event?utm_source=chatgpt.com)

* [preventDefault()](https://developer.mozilla.org/en-US/docs/Web/API/Event/preventDefault?utm_source=chatgpt.com)

* [Submit Event](https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement/submit_event?utm_source=chatgpt.com)

* [Change Event](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/change_event?utm_source=chatgpt.com)

* [Input Event](https://developer.mozilla.org/en-US/docs/Web/API/Element/input_event?utm_source=chatgpt.com)
*