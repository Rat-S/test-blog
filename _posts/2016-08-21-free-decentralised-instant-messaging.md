---
layout: post
title: Using a free, open & decentralised messaging.. 
---

{{ page.title }}
================

<p class="meta">21 August 2016 -  Using a free, open & decentralised messaging. </p>

## Move to completely free and open messaging platform

### conveniences of telegram 
We felt quite comfortable with telegram as it kicked butt of many other instant messengers that we had. We had persistant messaging, ability to log in from multiple devices, groups that large number of participants, sharing of media, etc. 
Moreover their clients are *free software* and they have suggested that the entire code will be released as open-source. 
These feautures attracted quite a lot of users especially from the free software communities. There are decent number of users in these so called un-official telegram groups of communities that advocates for free software such as [Mozilla](https://wiki.mozilla.org/Telegram) or [Fedora](http://telegram.me/fedoranews) [project](http://telegram.me/fedoranews). Even the free software communities like [FSFTN](https://fsftn.org) and [FSMK](https://fsmk.org/) has an un-official telegram group which is flocked by good number of users. 
It is going to be quite a difficult job to ditch telegram quickly, but there are very decent alternatives available that can provide most of the feautures that we ask for.

### xmpp and IRC 
Internet Relay Chat Protocol might not be glamorous anymore, but it is still a very important mode of communication. Lot of discussions and meetings for most free software projects happen here and it is where most of us seek help after doing a quick web search. 
So can we use IRC as a primary mode for communication? Yes, we can. But, should we? Hell No. We want persistant chat history and I shouldn't have to stay connected always inorder to get the messages. Internet in here sucks so bad that IRC is almost out of consideration. 
XMPP may cover some limitations that exist in IRC (persistence and identity), but we know that it sucks equally, if not more. 
As far as group chats are concerned we could just bridge the IRC group with XMPP and we can let the users to be where they want. But when we tried XMPP, we didn't have good welcome from our folks. 

### matrix
It is our current hangout. We have good range of clients from weechat plugin to the vector webapp. The lovely guys at matrix host an [IRC bridge](https://github.com/matrix-org/matrix-appservice-irc) [instance that bridges all of freenode](https://matrix.org/blog/2015/06/22/the-matrix-org-irc-bridge-now-bridges-all-of-freenode/), which actually could solve a lot of issues. We already have an IRC channel and we hangout quite often there. Without modifying much, we can start using matrix in addition to that. Or consider matrix like some sort of bouncer for IRC. The freenode bridge allows us to join any channel in the network and you can stay connected this way to IRC even if you close the client or you go offline. Just when you connect back to the matrix using your client, you can get the messages there! Matrix  is [deliberately not pure p2p](https://matrix.org/docs/guides/faq.html#what-is-the-difference-between-matrix-and-tox) in order to provide conversation history. 

For instance, if you want to stay connected to irc://irc.freenode.net and if you want to remain in a channel, let us say [##fsftn](irc://irc.freenode.net), just use your matrix client to join  [#freenode_##fsftn:matrix.org](https://vector.im/beta/#/room/#freenode_##fsftn:matrix.org). 
Vola! You are connected to the IRC channel until you leave the room in matrix. 

Thanks to [prashere](https://discuss.fsftn.org/t/we-should-move-away-from-telegram/789) for pointing it out via the [fsftn discussion forum](https://discuss.fsftn.org/t/we-should-move-away-from-telegram/789). 

#### Keep looking. Of course, we will keep on looking for anything new that may surface.

But again, what's the fucking point. [Let us use facebook messenger, instead](http://blog.deadrat.in/2016/02/10/Is-free-software-required.html). 
