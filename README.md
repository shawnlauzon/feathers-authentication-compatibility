# feathers-authentication-compatibility

This module keeps the old client libraries using auth local and socket.io compatible with auk style login.

## Usage

```javascript
const authenticationCompatibility = require('feathers-authentication-compatibility');
// after app.configure(authentication);
app.configure(authenticationCompatibility);
