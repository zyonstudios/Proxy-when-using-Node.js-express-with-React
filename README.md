# Proxy-when-using-Node.js-express-with-React
To create a proxy when you using Nodejs and express with react to avoid CORS issues 

The easiest way to overcome this in your development localhost.
lets say you running your front end in http://localhost:3000 & your server running on http://localhost:5050
Go to your client app
in the package.json file in your frontend app
add following
"proxy":"http://localhost:5050/api/",
