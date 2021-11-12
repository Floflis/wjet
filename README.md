Please don't screenshot 📸
🚧 Program is under construction 🚧👷‍♀️🏗

# wjet

[ipget](https://github.com/ipfs/ipget), but faster 🚀

Download files from IPFS like if you were using wget; but safer (and now faster!)

Made after [sh it](https://github.com/Floflis/shit) presented error trying `ipget --progress QmVoGaTVUVzgHEwyyiKsYcQG36AFZezb1kvGEFPwYsyN92 -o /tmp/script.sh`

# The trick: how does it works?

1. First, the CID is sent to the hardcoded IPFS gateway (ipfs.io - soon™ it will change, with gateway options including local go-ipfs)
2. Our program uses the local go-ipfs (you need it installed - automatic install using [Plugz](https://github.com/Plasmmer/Plugz), soon™) to match the CID of the downloaded script with the requested one
3. Done! Your file is moved from /tmp to the desired location
