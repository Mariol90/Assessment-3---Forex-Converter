Answer the following questions below:

    1-What are important differences between Python and JavaScript?

    Javascript is run in the front end browser and is what the user sees, and the result of a http get request.

    Python is the backend, it is setting up routes to handle and respond with http requests.

    2-Given a dictionary like {"a": 1, "b": 2}: , list two ways you can try to get a missing key (like "c") without your programming crashing.

    using the get() function or setdefault()

    3-What is a unit test?

    testing one section or unit of code in an a larger applicataion

    4-What is an integration test? 
    
    integratino test is testing how well units of code work togeather for the overall project of the file.

    5-What is the role of web application framework, like Flask?

    to simplifly the route making process. We can write routes using @app.route decorators instead of writing many lines of code to do the same thing with plane old python

    6-You can pass information to Flask either as a parameter in a route URL (like '/foods/pretzel') or using a URL query param (like 'foods?type=pretzel'). How might you choose which one is a better fit for an application?

    using a parameter in a route URL is benificial for a static page that is set up by the developer.

    using a URL query param is best for pages like reddit where the users are creating the wepage dynamically.

    7=How do you collect data from a URL placeholder parameter using Flask? 
    
    by creating name placeholders You would get url placeholder parameters using flask from mportoing request from flask and then saving it to a variable using request.args[]

    8-How do you collect data from the query string using Flask? 
    
    The same way as the placeholder parameters, using request imported from flask. Then using request.args.get()

    9-How do you collect data from the body of the request using Flask? 
    
    request.args.get()

    10-What is a cookie and what kinds of things are they commonly used for? 
    
    A cookie gives state to an http request. It can be useed to rember if a user is loggd in, or a shopping cart history. It is very limited in space that it can store and is considerd to be low level.

    11-What is the session object in Flask? 
    
    Sessions also gives state by storing data in the browser. The data is also signed to keep the data secure.

    12-What does Flask's jsonify() do?

    It turns data into json friendly data
