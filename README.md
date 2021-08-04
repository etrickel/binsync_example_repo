# BinSync Example Repo 
## What is a Sync Repo
A Sync Repo is a repo that BinSync connects to and saves reversing artifacts. Every sync repo needs 2 things:
1. a binsync/__root__ branch 
2. binay_hash: a md5 hash of the thing you are reversing (in that root branch)

## Good practice
1. Put the binary people are reversing in the `main` branch
2. ALWAYS when you work on the binary in your decompiler, first copy it out of here so files like ida files dont polute the repo


