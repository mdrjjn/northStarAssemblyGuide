# Northstar by Leap Motion Assembly Guide from a first timer

Assembling the North Star Augmented Reality headset by Leap Motion using easily available parts within the United States. I knew nothing about several processes used so this is written from a perspective of someone who learned about it for the first time and aimed manly at those who are curious but have no idea where to begin.

## Introduction

In June 2018 Leap Motion [made public](http://blog.leapmotion.com/north-star-open-source/) their design of an Augmented Reality headset. While the original designs require some parts that are not publicly availible in small batches, enthusiasts all over the world  attempted to modify the design to make it easier to assemble. The most successful to date was the japanese exiii Inc. The main modification they made was the replacement of hard to find LCD screens with raspberry pi touchscreens. They also had to modify some 3D-printer designs to accomodate the new setup. I used their designs and found substitutes readily availible in the US to assemble the headset and would like to share my journey for others to build upon.

## Useful Resources
 - [Official Leap Motion GitHub repo](https://github.com/leapmotion/ProjectNorthStar)
 - [Another Official Repo](https://leapmotion.github.io/ProjectNorthStar/)
 - [The English translation of the exii inc design that contains all the 3d printer files and their BOM](http://exiii.jp/2018/07/25/project_north_star_en/)
 
### Community
Here is how to get in touch with other people around the world working on North Star:
- [North Star Forum on Leap Motion](https://forums.leapmotion.com/t/project-north-star/7071)
- [Discord Channel](https://discord.gg/EhQF54Q)

## Sourcing The Parts

##### STL Files (except for the lenses)
All the 3D printed parts (apart from the lenses) I got from the exii upgraded design. Their main difference form the official design in the shape of the Screen holder—the exii design uses raspberry pi screens. Some parts require a rather sizable printing bed so make sure you have access to one. PLA or ABS should do fine so don't worry too much about it.

##### The Lenses
 Thanks to @Eric in the Discord channel we have a high res mesh for those who want to 3D print the lenses. I have reflected his design to produce the left lense as well. Please find the files in this repo. You can use an SLA 3D printer if you have access to one or you can find a company that can do the prints for you. I took the first route but I have heard people using 3D Hubs. Make sure to use clear resin though!
 
 ##### Screens
 This most difficult hardware part to source. The screens in the original design are impossible to come by for a casual consumer since they are only availible in bulk at reasonable prices. I was, however, able to fijnd a distributor on Alibaba willing to sell samples for 120$/screen in an order of 2 screens. The other advantage of raspberry pi screens is that they do not really need drivers and are easy to connect to the Display ports.
 
 [Link](https://www.amazon.com/OSOYOO-Monitor-Display-instructions-Raspberry/dp/B01N447AEY/ref=sr_1_1?ie=UTF8&qid=1533769748&sr=8-1&keywords=3.5+inch+monitor+hdmi)
 
 ##### Screen Cables
 For these particular screens you would need 2 power cables (micro USB) and two HDMI-DP cables. Pick the length carefully so as to be able to wear the headset comfortably.
 [Link to our HDMI-DP cables](https://www.amazon.com/gp/product/B01EY67S6O/ref=oh_aui_detailpage_o07_s00?ie=UTF8&psc=1)
[micro USB power](https://www.amazon.com/dp/B07DC2HC8Q/ref=cm_sw_r_cp_apip_pln6g172ZyK9Y)

##### Lense Processing Tools

[Sandpaper](https://www.amazon.com/Sandpaper-Precision-Polishing-Sanding-sandpaper/dp/B01M6A7D9A/ref=sr_1_1_sspa?ie=UTF8&qid=1533775121&sr=8-1-spons&keywords=3000+grit+sandpaper&psc=1)
[Novus Pack](https://www.amazon.com/gp/product/B002UCYRZU/ref=oh_aui_detailpage_o00_s00?ie=UTF8&psc=1)
[Reflection Film](https://www.amazon.com/VViViD-One-Way-Bronze-Mirror-Self-Adhesive/dp/B076XHLKC6/ref=sr_1_1?rps=1&ie=UTF8&qid=1533776277&sr=8-1&keywords=window+mirror+film&refinements=p_85%3A2470955011)
## Assembly Tips

##### Processing the lenses


In order to turn our sla-printed translucent lenses into a glass-like lense we will need to polish them. The procedure I used is to begin with wet sandpaper of 1000 grit and move in 500 grit increments up to 2500, taking about 10 minutes at each interval. (Fun fact: It is called "wet sandpaper" because you use water to clean the sanded material off of the sandpaper. the more you know).  
Then move to Novus 3 polishing and spend a gooood time on it. Repeat the process with Novus 2. Welcome to continue to Novus 1 but I notice very little difference. One tip is that when it comes to polishing, all the magic happens at the polishing liquid level, so if you have time, invest it into the Novus-n stage.

Applying the film  

I did not find an easy and good way to use this.
### Video 
Here is the video of how this particular headset was assembled. It is by no means the only way to do it but such material would have helped me a lot when I started out and I hope you find it to be a good refernce point.

[LINK TO THE VIDEO](https://www.youtube.com/watch?v=CKpXE_DHC50&t=3s)

## Software

Currently working on this part. Stay tuned!

## Credits

Ther is no way I could have done this myself and I would like to thank the following people for their contribution:

- The Stanford PRL lab for letting me use their 3D Printers. And specifically TAs Thomas Trzpit and Elliot Helmes.
- PolyBionics Founder, Nicholas Llewellyn-Jones (@BurgersHouse - "Its All About The Bubble" )

Following members of the Discord Channel
- @ChanceTheMaker in discord
- @Youn
- @MojoAR
- @Fazatron
- @DavidH
- @Bryan
- @Eric
