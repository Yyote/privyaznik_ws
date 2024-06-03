# Installation

```bash
cd ~
git clone https://github.com/Yyote/privyaznik_ws.git
pip3 install vcstool
cd privyaznik_ws
mkdir src
```

## For ssh

```
vcs import < ssh.repos
colcon build
```

## For https

```
vcs import < https.repos
colcon build
```

