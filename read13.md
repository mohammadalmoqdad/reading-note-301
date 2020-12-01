# Client/server architecture
* The Idea of it is 
  1. client (usually a web browser) sends a request to a server (most of the time a web server like Apache, Nginx, IIS, Tomcat, etc.), using the HTTP protocol. The server answers the request using the same protocol.
  2. An HTML form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server. This enables the user to provide information to be delivered in the HTTP request.

### On the client side: 
  * The `<form>` element
    - defines how the data will be sent and that is either  done by **GET** or **POST** method and that is going to be clarifies in the *action* atribute in te form and the method itself is performing how the HTTP Request will be sent.
1. The *GET* method:
  * The GET method is the method used by the browser to ask the server to send back a given resource: "Hey server, I want to get this resource." In this case, the browser sends an empty body. Because the body is empty, if a form is sent using this method the data sent to the server is appended to the URL.
2. The POST method:
  * The POST method is a little different. It's the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: "Hey server, take a look at this data and send me back an appropriate result." If a form is sent using this method, the data is appended to the body of the HTTP request.

##### Viewing HTTP requests:
* HTTP requests are never displayed to the user (if you want to see them, you need to use tools such as the Firefox Network Monitor or the Chrome Developer Tools). As an example, your form data will be shown as follows in the Chrome Network tab. After submitting the form:
  1. Open the developer tools.
  2. Select "Network"
  3. Select "All"
  4. Select "foo.com" in the "Name" tab
  5. Select "Headers"
  6. You can then get the form data.


### On the server side
* The data will be retrieved as a key-value pairs 
* there are several languages and frameworks to use it.
