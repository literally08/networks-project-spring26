

1. Which city has the highest inefficiency ratio?
   
From my results, London had the highest inefficiency ratio at about 2.49.
Even though London is much closer than many other cities, its RTT is significantly
higher than the theoretical minimum. 

What cables serve it and how does that explain your result?

Looking at the cable maps, London is connected through many major transatlantic cables such as MAREA, AEConnect, and others that link the US to Europe.
However, these routes do not necessarily follow a perfectly straight path, and traffic is often routed through major exchange points rather than directly 
between cities. Additionally, congestion and routing policies (like peering agreements between ISPs) can cause packets to take longer paths than the theoretical
shortest route. This explains why London has a relatively high inefficiency ratio despite being relatively close to the US compared to many of the other cities, 
and its strong infrastructure.


2. Which city is closest to the theoretical minimum?
   
Mumbai is closest to the theoretical minimum, with a ratio of about 1.02.
This means the measured RTT is very close to the physical distance-based limit.

What does that tell you about routing infrastructure there?

This suggests that routing to Mumbai is highly efficient. The data likely travels along relatively direct 
cable routes with minimal detours or congestion especially compared to London which we just talked about.
It also indicates that there is good infrastructure and peering along the path, allowing packets to travel 
close to the optimal route. In general, a ratio close to 1 indicates the network path is well optimized and 
near the speed-of-light limit.


3. Why does Africa route through Europe?
   
Even though Lagos is in Africa, its traffic is often routed through Europe first. This is because much of Africa’s internet
infrastructure is previously connected through European exchange points rather than directly between regions. Many submarine
cables from Africa land in Europe, and there are fewer direct high-capacity interconnections within Africa itself.

 What would need to change to fix it?

To fix this, Africa would need more direct intercontinental cables, like direct US to Africa cables, and stronger
internal internet exchange points (IXPs) within the continent. Improving regional infrastructure and increasing direct 
peering between African networks would allow traffic to take more direct routes and reduce inefficiency.

Extra***
Some cities (like Singapore and Sydney) had RTT values below the theoretical minimum, likely due to CDN routing, 
where requests are served by geographically closer servers rather than the actual target location.
