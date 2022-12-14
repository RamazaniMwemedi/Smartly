<!-- About Input element in HTML -->

# Input element in HTML

## What is Input element in HTML?

Input element is used to create interactive controls for web-based forms in an HTML document. It is used to create different types of input controls like text fields, checkboxes, radio buttons, submit buttons, etc.

## Syntax

```html
<input type="type" name="name" value="value" />
```

## Attributes

| Attribute | Description                             |
| --------- | --------------------------------------- |
| type      | Specifies the type of input element     |
| name      | Specifies the name of an input element  |
| value     | Specifies the value of an input element |

## Types of Input element

| Type     | Description                                                                                          |
| -------- | ---------------------------------------------------------------------------------------------------- |
| text     | Specifies a single-line text input field                                                             |
| password | Specifies a single-line password input field                                                         |
| radio    | Specifies a radio button                                                                             |
| checkbox | Specifies a checkbox                                                                                 |
| submit   | Specifies a submit button                                                                            |
| reset    | Specifies a reset button                                                                             |
| button   | Specifies a clickable button                                                                         |
| file     | Specifies a file-select field and a "Browse" button (for file uploads)                               |
| hidden   | Specifies a hidden input field                                                                       |
| image    | Specifies an image as the submit button                                                              |
| email    | Specifies a field for an e-mail address                                                              |
| number   | Specifies a field for entering a number                                                              |
| range    | Specifies a control for entering a number whose exact value is not important (like a slider control) |
| search   | Specifies a text field for entering a search string                                                  |
| tel      | Specifies a field for entering a telephone number                                                    |
| url      | Specifies a field for entering a URL                                                                 |

## Example

````html
<!DOCTYPE html>
<html>
  <head>
    <title>Input element in HTML</title>
  </head>
  <body>
    <form>
      <input type="text" name="name" value="Enter your name" />
      <input type="password" name="password" value="Enter your password" />
    </form>
    </body>
</html>
````

````

<!-- About form inn HTML -- />

# Form in HTML

## What is form in HTML?

Form is a section of a document containing interactive controls that allow users to submit information to a web server.

## Syntax

```html
<form action="action" method="method">
  <!-- form elements -->
</form>
```

## Attributes

| Attribute | Description                                                                 |
| --------- | --------------------------------------------------------------------------- |
| action    | Specifies where to send the form-data when a form is submitted              |
| method    | Specifies how to send the form-data (which HTTP method to use)              |
| target    | Specifies where to display the response that is received after submitting the form |

## Example

````html
<!DOCTYPE html>
<html>
  <head>
    <title>Form in HTML</title>
  </head>
  <body>
    <form action="https://www.google.com/search" method="GET" target="_blank">
      <input type="text" name="q" value="Enter your query" />
      <input type="submit" value="Search" />
    </form>
  </body>
</html>
````
````
[...]
````
