# Hey, I'm xertz

![Profile views](https://komarev.com/ghpvc/?username=guno1928&color=blue&style=flat)

Self-taught developer from Australia. I run [ALOS](https://alos.gg), a DDoS protection platform, and I build most of the infrastructure it runs on myself, from the web framework up to the kernel.

I like writing things from scratch to find out how fast they can actually go. Most of my work is in Go, and some of it lives inside the Linux kernel.

## What I'm building

**[ALOS](https://alos.gg)**
A DDoS protection platform. Edge network, mitigation, captcha, the whole stack. This is the main thing I work on every day.

**ALOSWALL**
The in-kernel DDoS firewall behind ALOS. It runs in XDP, the kernel's earliest packet path, and rules on every single packet in around 110 nanoseconds. Fully stateful, SYN cookies in the fast path, live rule changes with zero downtime, and a custom BPF map built to stay fast under attack load instead of collapsing under it.

**alos-http**
A Go web framework written from scratch to be the fastest web framework in the world. Every page ALOS serves goes through it.

## Elsewhere

- Site: [alos.gg](https://alos.gg)
- Contact: [xertz@alos.gg](mailto:xertz@alos.gg)
