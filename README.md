node-couchbase-users
====================

Sample login/logout app that uses couchbase to store users

You shouldn't use eval() in any part of your code but, if you need access to a global variable in any file different from app.js, you can use this lousy method to import your files in your main app.js. The files themselves will be evaluated and the code will be accessible all around your app.

See:

- app.js lines 22-23 
- /routes/users.js (no module exports)
- /models/User.js (no module exports)

Requesting your comments on this.