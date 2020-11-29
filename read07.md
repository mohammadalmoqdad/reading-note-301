*  The first part when writing the URL ia the protocol which is HTTP for the most websites on the internet and when writting it there that means you are telling te browser to use HTTP protocol.

#### REST
* rchitectural style provides a definition of a “resource”, which is what those things point to.

--------------
* The URL tells the browser to ask for a specific representation of the information that stored in somewhere 
--------------
#### API or Web Servers:
* a lot of different things to a lot of different people but the basic concept is that machines could use the web just like people do like use same protocols to send messages back and forth to each other.

#### Redirect: 
* simply it is a conversation between machines to know where is the resource that the fisr machine is loolkng for aross the URL 

-------------
* when you go to a web page, the browser does an HTTP GET on the URL you type in and back comes a web page.

*  when you're using a web browser because browsers pretty much just GET stuff. They don't do a lot of other types of interaction with resources. This is a problem because it has led many people to assume that HTTP is just for GETing. But HTTP is actually a general purpose protocol for applying verbs to nouns.

*  Machine can not understand a normal web page Because web pages are designed to be understood by people. A machine doesn't care about layout and styling. Machines basically just need the data. Ideally, every URL would have a human readable and a machine readable representation. When a machine GETs the resource, it will ask for the machine readable one. When a browser GETs a resource for a human, it will ask for the human readable one.

* **HTTP GET**: Each of the systems would retrieve information from each other using it.
* **HTTP POST**: If one system needs to add something to another system, it would use it.
* **HTTP PUT**: If a system wants to replace something in another system, it uses it.
* **PATCH**: If a system wants to do a partial update, it'll hopefully use it.


* Deciding how to best model the data called ***Data modelling*** and what the web developers are using to do that is  `RESTful` web frameworks like *Ruby* on *Rails*.


