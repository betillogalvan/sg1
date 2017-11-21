# SG1

SG1 is a wanna be swiss army knife for data encryption, exfiltration and covert communication. In its core SG1 aims to be as simple to use as netcat while maintaining high modularity.

**WORK IN PROGRESS, DON'T JUDGE**

## Installation

    go get github.com/miekg/dns
    go get github.com/evilsocket/sg1

    cd $GOPATH/src/github.com/evilsocket/sg1/
    make

## Examples

Encrypting data in AES and exfiltrate it via DNS requests:
![aes-dns](https://pbs.twimg.com/media/DPG-9C2X4AADFcP.jpg:large)

Quick and dirty AES encrypted chat over TCP:
![aes-tcp](https://pbs.twimg.com/media/DPHAlOXWAAA9kKv.jpg:large)

AES encrypted chat over DNS:
![aes-tcp](https://pbs.twimg.com/media/DPHegHLWsAErZtO.jpg:large)

Just use `sg1 -h` to see a list of available channels and modules, try to pipe them and see what happens, you can also transfer files ^_^
