# instant(1)

Spawn a http server in the current directory that instantly notifies
all connected devices as soon as a HTML, CSS, or JavaScript file is modified.

See https://github.com/fgnass/instant-server for all the awesome.  This fork is purely to strip out linger because I want to run the instant server in the background, and linger makes that problematic.

```
git clone git@github.com:deBhal/instant-server.git
cd instant-server
npm link
```

This'll give you the server with:
```
instant
```

## License

MIT
