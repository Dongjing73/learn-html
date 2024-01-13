## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
   The action attribute in the HTML <form> tag specifies the URL where the form data should be submitted when the user clicks the submit button. It defines the endpoint on the server where the form data is sent for processing.
2. What is the purpose of the _method_ attribute in the _form_ tag?
   The method attribute in the <form> tag specifies the HTTP method used when sending form data to the server. It tells the browser how to send the form data to the server when the user submits the form.
3. What is the purpose of the _name_ attribute in the _input_ tag?
   The name attribute in the <input> tag is used to define a name for the input control. This name is then used by the server to identify the fields in the form data that are sent to the server when the form is submitted.
4. What is the purpose of the _type_ attrbute in the _input_ tag?
   The type attribute in the <input> tag is used to specify the type of input control that should be displayed. It defines the kind of user input the field is designed for.
5. What is the purpose of the _label_ tag?
   The <label> tag in HTML is used to associate a label with a form control. It provides a user-readable description for the corresponding form element, making it more accessible and user-friendly.
6. What is the purpose of the _required_ attribute?
   The required attribute is used in HTML to specify that a user must fill out a form field before submitting the form. 
