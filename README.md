# Remote-Commands
these are some commands to scare your friend without even touching their computer!


## Open a website on their computer!
Just run this file on your computer:
`wmic /node:(your friend's ip) process call create "cmd.exe /c start https://geekprank.com/virus/"`
make sure to replace (your friend's ip)!

### Open multiple of these:
`for /l %x in (1,1,20) do wmic /node:(your friend's ip) process call create "cmd.exe /c start https://geekprank.com/virus/"`
