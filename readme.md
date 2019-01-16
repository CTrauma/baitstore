## Bait Store

A repository of odds and ends, workarounds, and half baked scripts to help reduce friction..

> _The system's got more bugs than a bait store._
~ TRON (1982) [clip](https://getyarn.io/yarn-clip/fced3611-3bf8-4058-bdc4-06b5c0e16bb6)

## isolated node env

Here is my simple bash script to create isolated node envs. It should work on Linux, OSX, and Windows as long as the requirements are met.

Requirements:

Linux:
  - jq
  - wget

Windows:
  - Bash env: WSL, Gitbash, Cygwin, MSYS2
  - 7zip
  - wget
  - jq

OSX:
  - jq
  - wget

[get it here](https://gist.githack.com/CTrauma/da96abb1301713cb73e609f6fabd650d/raw/bfdaf5cc5082c498bdfde9381dc9f8d294cfc3eb/getnode.sh)

commandline _will download latest_

```
% ./getnode.sh 
```

commandline to get specific version:

```
% ./getnode.sh v10.5.0
```
