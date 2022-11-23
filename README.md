# gedo
Get HTML document and headers from a list of URLs.

## Usage

This command will create a folder called "out" in the current directory you are located in.
```bash
$ gedo list-of-urls.txt
```

This command takes input from *stdin*
```bash
$ cat list-of-urls.txt | gedo
```

This command will create a folder to whatever location you choose.
```bash
$ gedo list-of-urls.txt path/to/my/output-folder
```

Sample output:
```bash
$ cat list-of-urls.txt | gedo
...<SNIP>

$ lsd --tree
.
├── out
│   ├── 2a03b98e7637081e05c94e825b4c3e2d
│   ├── 3c6c5b81a0e721b982fae174b460d1a2
│   ├── 4acdbaedb72d8d579af3b91b7b343b45
│   ├── 5c3261f7529665d4eddd976b025bceb9
│   ├── 5dcccfe7f50c55face9b3405ee66ddb2
│   ├── 5e86f57ff1d77e740c653cbf6b5ca682
│   ├── 6148f156cabec68de3054a5af36d73e3
│   ├── 6b233b04632913c49d205a7ddd555dbf
│   ├── 7d01eea06aa7e6fcfc55c246f6e7fcf7
│   ├── 8af39e4ff22eedf8c52afe20546c6094
│   ├── 8c17e30c76b435619808a25d954c1deb
│   ├── 901863c06f8897b64906fd30cfb08826
│   ├── 9182ddb59e216b73b96052477f7d6e75
│   ├── 96189cc0179960bb0a603c46428f5496
│   ├── 9fb8c114db06f4a5a85b2ee1abaa0068
│   ├── a8cce4879fa12fa3f304f0a2d1a2e575
│   ├── b27c7d0d348472e459ff84db06e3a47c
│   ├── c1aac77a76b355a35a22dd47810228bb
│   ├── ce514b719c3e67efff6113269bf3f6de
│   ├── ce9d688323b9fac5fdff2bd1ff5b2eba
│   ├── db54fe7e3f21b2517eabed01c3709826
│   ├── df27eb1396329a98798cbe967ac16856
│   ├── df5039b5d3df1abb5092ce20da88538c
│   ├── ef8648f8cdc8e474ae72c33e468a08e4
│   ├── f718af60519a492f5570d8ec360282f1
│   └── f8dbad7ab40b5555763cb43a876b7bda
├── output.txt

```
