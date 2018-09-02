README.md

Eduapp is used to educate technical people.

Installation:

create ubuntu account [if needed]

```
sudo useradd -m -s /bin/bash -G sudo ubuntu
sudo passwd ubuntu
```

login
```
If on local laptop with X-windows:
ssh -AY ubuntu@localhost
or
ssh ubuntu@some-aws-ip
```

clone the repo

```
git clone https://github.com/roomf4/eduapp1
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
