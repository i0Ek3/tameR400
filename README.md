# tameR400

> Tame ThinkPad R400(1 GB Mem + 250 GB HHD).

Yesterday, I found a laptop(R400) in our cabinet. First look, I will throw it away, but I give it a chance and it returns me a gift. What a nice thing, I'll use it as a server.


## What R400 Looks Like?

![](https://github.com/i0Ek3/tameR400/blob/main/images/forward.jpeg)

You can find the other pictures under the [images](https://github.com/i0Ek3/tameR400/tree/main/images).


## Configuration

![](https://github.com/i0Ek3/tameR400/blob/main/images/lubuntu-config.jpeg)


## Issues

- The battery was broken, must connect AC adapter all the time
- Low memory
- You tell me


## Hackin


### Hardware Disassembly

Just a simple way: add or remove something, like memory, disk etc.

After I disassemble the R400, I found there are two slots we can use, and one is 1G RAM meomory, another is empty. Nothing can be found about M.2 slot or mSATA interface. So we could remove DVD and replace with SSD in there.




### Setting BIOS

First, upgrade BIOS version if available. Actually R400 is old enough, I didn't find a BIOS software.

Second, setting BIOS configs.




### Install Linux

I just tried so many Linux distros, finnally I choose Lubuntu 18.04 i386/i686 as default system cause of low memory and performance consideration.

If you like, the other Linux distros also be fine.




### Install Packages

Install some common packages like vim, zsh, tmux, git, neofetch/screenfetch, openssh-server etc.




### Setting For A Server

Enable Nginx and SSH first.

TODO(Actually I just want to give up, cause of this stuff's broken battery and low memory, but I will considerate a lot.)




### Relive

Check it out.




## What The Next?

I have no idea.
