---
layout: post
title: "I'm shopping to replace my homelab"
categories: homelab
---

I've come the realization that ... my homelab sucks and I'm going to have to replace my pi cluster for 2 reasons: 
1. I've had to work around only being able to do arm containers
2. I need more power! the pis are great. especially with this cluster setup I have going with the cloverpi... but I need more power! which brings me to my next point
3. There is a pi shortage. I cannot buy any more raspberry pis via the normal retail channel. The only way to get a pi is to pay double the MSRP on ebay This makes it a sellers market... so time to be a pi seller. 

Now my favorite thing about my cluster is the size. I won't be able to achieve that level of compactness but untill I can get more pis, I'm going to be building my new cluster with cheap mini computers. The cheapest I could find are a lot of 10 acer chromeboxes for $130. I didn't want 10 but I had to do it. The next best price was 3 for $90! I looked them up on mrchromebox.tech to see if I can install linux on them and I can. 

Also I bought 20 sticks of 2GB ddr3 SODIMM for another $15. Again, I had to do it. so my plan is to take the 4GB sticks from half of them and pop them into the other half so I'd have 5 boxes with 8GB each. I can run proxmox on those and have them be the main lab. The other half will get the 2 GB sticks and I was thinking of selling them as another proxmox cluster and recover my costs. If I don't sell them I can use some of them as 2 htpc and 3 wireless mesh?

update: 
I have built my lab - the listing didn't actually include power supplies. so I bought another lot of used parts - this time I was able to get these power supplies from a seller for $40. at first none of them worked but I realized that the outside of the barrel was fitting just fine. so maybe the inside wasn't making good contact. So for the cost of fractions of a penny. I took a small sheet of aluminum foil and stuck it down the barrel of each power supply and voila! it worked. 

So I went through the process of overwriting the bios and installed proxmox on 4 of the "servers". They function like servers but I don't have the heart to fully own up to the idea that these chromebooks (essentially). I installed ubuntu on 3 VMs and openmediavault on another VM to server data the docker swarm. 

I had a few more hiccups but I'll save that for another post. 
