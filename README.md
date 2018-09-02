README.md

Eduapp is used to educate technical people.

Installation:

create eduapp account

```
useradd -m -s /bin/bash -G sudo eduapp
```

login
```
ssh -AY eduapp@localhost
```

clone the repo

```
git clone git@github.com:eduapp1
```

call start.bash

```
cd eduapp1
./start.bash
```

That should bring up a server

```
curl localhost:8080/index.html
```
