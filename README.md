# <h1>T-s_BareBonesComputing
Welcome to my GitHub! Here I  showcase personal projects where I do proof of concept and apply new technologies I may be curious about
# <h2>Hardware
Planning for this lab I wanted to find devices that were relatively small, versatile, energy efficient and didnt require a lot of space.
Having researched a variety of computer and network devices that would be able to handle a lab of the size I had in mind, I decided on using Intel BareBones NUC's, a Netgear managed switch, GLI.NET router and a Zyxel firewall. In the instance I need to physically move my lab this will be a lot easier to do when everything can fit in a small box. Respectively of course!
 

## <h3>Intel NUC's
Intel NUC's (Next Unit of Computing) have been available for many years and come in different configurations. As they are released they identify a new generation in their product line (to compare, similiar to apple and iphones), I went for the 7th and 8th generation. Each one being capable of 32gb of RAM, an M.2 SSD Slot, available with multiple processors (i3, i5, i7) and a 2.5 SSD/HDD Bay.

Below is a picture and specifications of the 3 NUC's I will be using throughout my lab
![IMG_0285](https://user-images.githubusercontent.com/67407192/115975104-c6e9b280-a516-11eb-9f60-9742850b5acc.JPG)


 * NUC7i5BNH
   *  Processor:  i5-7260U CPU @ 2.20GHz
   *  RAM: 32gb
   *  Storage: 500gb M2 SSD & 1TB HDD
  
 * NUC8i7BEH
   *  Processor:  i7-8559U CPU @ 2.70GHz
   *  RAM: 64gb 
   *  Storage:  500gb M2 SSD & 500 SSD Sata
  
 * NUC7i7DNHE
   *  Processor:  i7-8650U CPU @ 1.90GHz
   *  RAM: 32gb
   *  Storage:  500gb M2 SSD & 500 SSD Sata

Reading multiple articles online, I found come claiming the 8th generation NUC's actually support 64gb of RAM instead of the advertised 32gb. I decided to test this out and astoundigly found this to be true. RAM being the most utilized resource in most of the computing world, next to storage and lastly CPU. I was happy to find this out. Below is a list of the articles I came upon through google.
   *  https://www.virtuallyghetto.com/2019/03/64gb-memory-on-the-intel-nucs.html
   *  https://kacangisnuts.com/2019/04/yes-intel-nuc-8i5beh-accepts-64-gb-ram/
   *  https://cloerner.github.io/posts/64gb_intel_nuc7i3/

## <h3>Managed Switch
* GS108PEv3
  *  Searching for a fully managed Layer 3 switch, I couldnt find one that kept that small factor size and low cost so I settled on this small Layer 2 switch
  *  Having planned to use less than 8 physically attached devices this switch had a sufficient amount of ports for what I was looking to do!
  *  8 ports with 4 POE capable of 10m/100m/1000m
  *  Dimensions: 10.79x9.29x2.2
  *  Quality of Service
  *  Port Management
  *  VLAN tagging
  *  Mirroring

Pictured below is the switch stacked on top of a Firewall
  
![IMG_0294](https://user-images.githubusercontent.com/67407192/116057101-4ff60c00-a633-11eb-88e0-dbe94f065865.JPG)

## <h3>The Holy Grail of Routers!
The excitement I had upon finding this little router is unreal! This router is the Perfect tavel size and I've actually used it on many trips and throughout my home network. Whether your looking for a wireless access point to connect to your modem, add an access point to your WIFI or create a WWAN (Wireless Wide Area Network) like I do in my lab. This device does it all! I will only be covering a small amount of features this device is capable of. I highly encourage you to check it out on their site. https://www.gl-inet.com/products/gl-ar750s/
 
* GL-AR750S-Ext
  *  DualBand WIFI (2.4ghz 300Mbps & 5ghz 433Mbps)
  *  Slightly larger than a credit card
  *  SD Card Support (up to 128gb)
  *  VPN Capabilities
  *  3 Gigabit Ports
  *  OpenWRT
     

![IMG_0296](https://user-images.githubusercontent.com/67407192/116059292-87fe4e80-a635-11eb-86a4-dd598ccf368c.JPG) ![IMG_0297](https://user-images.githubusercontent.com/67407192/116059294-8896e500-a635-11eb-904b-97dc6741f0d5.JPG) ![IMG_0295](https://user-images.githubusercontent.com/67407192/116059290-8765b800-a635-11eb-9407-c071b23b815f.JPG) 


## <h3>The Zyxel! Firewall?
Searching for a firewall my main goal was finding a physical system I could physically place within the infrastructure of the lab. Having the option of using the firewall from one of the previous devices I have mentioned already or create a virtual firewall and virtual network to direct traffic accordingly. One of my favorite features being this firewall has the ability to be managed through CLI. It even included a console cable!


* USG20-VPN
  *  4 Ethernet & 1 SFP Port
  *  VPN
  *  DMZ  
![1616192852684](https://user-images.githubusercontent.com/67407192/116201819-c73ca600-a6ee-11eb-9972-493d9768f413.jpg)

##<h2> What does all this eqate to?
 Well....this. 


![IMG_0299](https://user-images.githubusercontent.com/67407192/116202637-ac1e6600-a6ef-11eb-8637-613e69afe153.JPG) ![IMG_0300](https://user-images.githubusercontent.com/67407192/116202656-afb1ed00-a6ef-11eb-9a25-996ed03e605e.JPG)
