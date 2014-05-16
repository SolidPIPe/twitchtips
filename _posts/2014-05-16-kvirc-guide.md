---
layout: post
title: KVIRC Setup for Twitch Chat
description: "Connecting to Twitch IRC can be quite the task for those not knowledgeable with IRC client, check out how you can set yourself up connecting to Twitch chats using KVIRC."
tags: [twitch,kvirc,irc,twitch,chat,oauth]
comments: true
get-started: true
---

Connecting to Twitch IRC can be quite the task for those not knowledgeable with IRC client, check out how you can set yourself up connecting to Twitch chats using KVIRC.

#Adding a Network
Navigate to Settings > Configure Servers
 
<figure>
    <a href="/images/kvirc_guide/settings.jpg"><img src="/images/kvirc_guide/settings.jpg"></a>
</figure>
 
Select the **New Network** icon in the top right and create a new network, I've named mine "Twitch".
 
<figure>
    <a href="/images/kvirc_guide/servers.png"><img src="/images/kvirc_guide/servers.png"></a>
</figure>
 
Next Select **New Server** and enter *irc.twitch.tv* in the **Server** field.
 
<figure>
    <a href="/images/kvirc_guide/servers_pt2.png"><img src="/images/kvirc_guide/servers_pt2.png"></a>
</figure>
 
Next click **Advanced** and enter your Twitch user name in the **Nickname** field and your OAUTH token in the **Password** field and click **OK**

>Not sure how to get an OAuth token? Check out this [token generator](http://twitchapps.com/tmi/) created by [@bGeorge](http://www.twitter.com/bgeorge).
 
<figure>
    <a href="/images/kvirc_guide/login.png"><img src="/images/kvirc_guide/login.png"></a>
</figure>
 
*Note* - You may check **Connect to this server at startup** to join the server automatically when you start KVIRC.
 
<figure>
    <a href="/images/kvirc_guide/connection.png"><img src="/images/kvirc_guide/connection.png"></a>
</figure>
 
Now simply click **Connect Now**.
 
<figure>
    <a href="/images/kvirc_guide/servers_pt3.png"><img src="/images/kvirc_guide/servers_pt3.png"></a>
</figure>
 
 
#Joining Channels
Standard IRC context applies here as above.  To join a channel simply type */join #channelname* in the dialogue box.
 
<br>KVIRC can be configured to join channels automatically as well.  To do this select the **Join Channels** tab in your **Server Details** page.  Add channels by typing the channel name in the dialogue box and clicking **Add** (Don't forget the #hashtag).
 
<figure>
    <a href="/images/kvirc_guide/servers_pt4.png"><img src="/images/kvirc_guide/servers_pt4.png"></a>
</figure>

Thank to [@Izlsnizzt](http://www.twitter.com/Izlsnizzt) for writing this guide on connecting to Twitch Chat via KVIRC. 
