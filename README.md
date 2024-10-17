# Instagram-API-request-response
API Request methods and its details

<h2>Let us first know What are Response / Request and API methods.</h2>

<h3>Request</h3>
You request the API for some data or for any kind of reason this is request .You request the the API to give you that data or anything.

<h3>Response</h3>
After doing request now you will get any response .Response can be in form of error or in form of status code.

<h3>API request methods</h3>
1. GET
2. POST
3. PUT
4.PATCH
5.DELETE

<h3>Get request</h3>
You want to recieve something from the API .You want to get some thing we use GET method .It contains only head.

<h3>POST request</h3>
You want to send something through the API you will use post method it is used to send something new .It contains both head and body.

<h3>PUT request</h3>
You send some object if it contain that it will replace it and if this object is not there it will add that object .It also contain both head and body.

<h3>PATCH request</h3>
If you want to change some specific thing from that object so you will use PATCH request.It also contain boht head and body.

<h3>DELETE request</h3>
It will DELETE the whole object and it also only contain head.

<h2>Now lets talk about These topics related to upper topics </h2>

<h3>Login</h3>
Login involves authorization .For this thet will use POST Request because you are sending data so that at backend the data can be compared so it uses POST and then get response if that user found login succesfully if not response error.

<h3>After Login</h3>
After login the token which you Get in response is now send through get method the token is placed in that header to see this user is logged in to do authorization.

<h3>Actions on Instagram</h3>
Actions like comments and likes also uses post request because they are sending some like and comment to the other person DB through BE API.

<h3>Post Pictures or Contant</h3>
As you can see in this that you are posting some thing so it will use POST Request and if you then edit that POST now it will use PATCH Request and if you want to Delete that post that will use DELETE Request.

<h3>Change or edit comment post or Profile Data</h3>
These all will use PATCH Request because these all are changing some specific thing .

<h3>Search Bar</h3>
Searching some one account or any thing from the search bar.

<h3>If want to replace all Object </h3>
If you want to update the entire post or your profile not a specific thing you will use PUT Request in that .
<h3>Content Feed</h3>
For Content Feed and friends post its used get method because you are getting something from the API.