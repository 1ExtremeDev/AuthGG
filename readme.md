# AuthGG

AuthGG is a Python library for dealing with Auth.gg apis

## Installation

<h3>Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requests</h3>
<h3>Add the auth.py file in your application folder</h3>

## Usage

```python
from auth import *

# Adds the application information to the base
AuthGG.__init__(
    aid="AID",
    apikey="API_KEY",
    secret="SECRET_KEY"
)

# Returns the output of the request
response: str = AuthGG.Action(
    _type="login",
    username="Username", password="Password",
    hwid="hwid"
)
print(response, end='', flushed=True)
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Credits
The code has been done by [ExtremeDev](https://github.com/1extremedev), using the [Auth.GG](https://auth.gg/) apis.

## Links / Socials

### ExtremeDev
```
Discord: str = "ExtremeDev#5865"
Github: str = "https://github.com/1extremedev"
```
### Auth.GG
```
Website: str = "https://auth.gg/"