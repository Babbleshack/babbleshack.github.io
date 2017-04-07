---
layout: post
title: "Learn me some tmux"
date: 2017-04-05
catergories: linux
---
# What is tmux?

{% highlight bash %}
    man tmux
{% endhighlight %}
will describe tmux as 'tmux is a terminal multiplexer: it enables a number of terminals to be created, accessed, and controlled from a single screen.  tmux may be detached from a screen and continue running in the background, then later reattached.'

Tmux is therefore a terminal multiplexing programe used to managed multiple terminal sessions. 
Exectuting tmux will create a new tmux session from which multiple clients may connect and control, create and destroy windows. Each window may maintain a number of panes, each pain maintains a single 'pseudo terminal'

## Pseudo Terminal
Psudo terminals are simply bidirectional I/O devices used to provide a communication channel. At each end of the channel a psudo terminal process exists, one end represent the master pseudo terminal device and the other represents the slave pseudo terminal device. 


The master end acts exactly like a regular terminal providing read()/write(), whilst the slave side receives data written to the master.
On the other hand data written to the slave device is delivered to the master device, as though it was writtern there. 

