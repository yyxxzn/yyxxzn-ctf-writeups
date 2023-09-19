### • Author: Ionut Robert Cojocaru <br>
### • CTF: CyberSoc | Cyber Detective CTF<br>
### • Type: OSINT<br>
### • Date: 19/09/2023<br>
---
# Life Online
## voteforme
*https://twitter.com/jammymarkson
You'd have thought politics was a bit of a dry subject; not for some.
What US political party does James over here support?*

Searching through his Twitter I found this [tweet](https://twitter.com/jammymarkson/status/1226982759794692096) where it's clear he loves Obama, Obama is a democrat.<br>

**Flag: Democrat**

## growingup
*https://twitter.com/jammymarkson
Where did James spend his childhood?*

In his Bio I find the sentence 'Born in ///purple.pulse.force, raised in ///push.asking.barn.'. In his twitter there's a video of [what3words](https://twitter.com/jammymarkson/status/1226982119009914880). After watching the video I understand that ///push.asking.barn is the coordinate of where he spent his childhood.
Searching on their official website I get the [result](https://what3words.com/push.asking.barn), and it's York.<br>

**Flag: York**

## choochoo
*We need to make sure James is far away when we try and break into his house.
In what city does James work?*

From these two tweets [tweet1](https://twitter.com/jammymarkson/status/1226992456635473921) and [tweet2](https://twitter.com/jammymarkson/status/1226989808783888384) I understand that he takes the train to go home after he finished working, this means that to go to his workplace he uses the train.
And with this [tweet3](https://twitter.com/jammymarkson/status/1226997008977866753) I see that he made a photo after getting off the train. I can see on the sign 'Caerdydd Canolog' (I couldn't read well the right part of the sign well) and after a quick search on google maps I find that this is [Cardiff Central](https://www.google.com/maps/place/Cardiff+Central+Railway+Station+(South+Entrance)/@51.4751231,-3.1789006,3a,75y,90t/data=!3m8!1e2!3m6!1sAF1QipPPtO1JjiTr6-_pQexH6PxKjtDn2L8vuVRKgmqv!2e10!3e12!6shttps:%2F%2Flh5.googleusercontent.com%2Fp%2FAF1QipPPtO1JjiTr6-_pQexH6PxKjtDn2L8vuVRKgmqv%3Dw114-h86-k-no!7i4032!8i3024!4m7!3m6!1s0x486e1cb252067a43:0x663b9d68272b469d!8m2!3d51.4751516!4d-3.1789539!10e5!16s%2Fg%2F11dyxg_5q2?entry=ttu)<br>

**Flag: Cardiff**

## suntan
*People love telling the world about their holiday, but is this really a great idea?
What CITY is Sarah going on holiday to at the end of February?*

Looking on https://twitter.com/jammymarkson profile, in the likes tab I find [sarah's tweet](https://twitter.com/sarah_luxton/status/1227572157393309697). I download the image and I do a search using the image on [google](https://lens.google.com/search?ep=gisbubb&hl=en-IT&re=df&p=AbrfA8qFXHunJjT74oJenttTIrgx-eAj8bf-vV838yL0fO1ydVXpETQuAxjqRe_AS25I4r9zMGvR3PitHuS8OCrs3tfMaHd5YeeixJnwhXhPBW1SQ3SKgxIccQYWZuLzu5izlAmGblTGL7z7dsPmjSUKYHm9fGLMrFhRbTENOJOsdIry3-aT3kpHnDX7N3NrEDwnXJ2IHsVKutmXTJZuyWO2Ql65Rhg%3D#lns=W251bGwsbnVsbCxudWxsLG51bGwsbnVsbCxudWxsLG51bGwsIkVrY0tKRFZsTnpBd09UYzNMVEJtTURrdE5EZGxNeTFpTnpBMUxUYzFPREEyTURNd1lUTTROaElmUVRKM1ZHbGlOMFprTXpSVFRVbG5SM0JuU1V4dVVESlpWM2xpY0hGb1p3PT0iXQ==), and I get Elizabeth Quay, that is in Perth, Australia. <br>

**Flag: Perth**

## wagthetail
*The team has been trying to work out where Person of Interest, Sarah, walks her dog. This is part of building up a profile of her movements.
Can you have a look to see if you can find the TOWN in which Sarah tends to take the dog out to?*

 Sarah's bio is 'Postgraduate Geography Student. Love to travel. Buster's favorite place x : 51.947528, -3.393953'. Buster is a popular name for animals. I search the coordinates on [maps](https://www.google.com/maps/place/51%C2%B056'51.1%22N+3%C2%B023'38.2%22W/@51.9438171,-3.3965849,15.25z/data=!4m4!3m3!8m2!3d51.947528!4d-3.393953?entry=ttu) and I find the city: Brecon.<br>

**Flag: Brecon**

## narcissism
*There's a new Person of Interest, George something or other.
Can you find anything interesting on him? Something he perhaps thinks you can't work out?
Take a look.*

Looking through Sarah's twitter I find George Watson's twitter. There's an interesting [tweet](https://twitter.com/GeorgeWatson428/status/1227620834996563968). The password is encrypted in Base64, I decrypt it and I find the flag imamazing123.<br>

**Flag: imamazing123**

## proppedup
*We've obtained what we believe to be an office CCTV camera feed.
We have reason to suspect that it is overlooking one of the work desks belonging to one of our targets.
Can you confirm the COLOUR of the DESK SURFACE and the COLOUR of the DESK LEGS, just so we can be sure of what we're seeing and task the reconnaissance team further.
Enter the flag as:
(SURFACE COLOUR) (SPACE) (LEGS COLOUR)*

Looking through George's replies on twitter I find the [tweet](https://twitter.com/PearceRees/status/1227605069446643713) with the desk. The flag is simply Brown Grey.<br>

**Flag: Brown Grey**

## bluengreen
*https://twitter.com/jammymarkson
James has a habit of getting in the way of things ;).*

I check his tweets, his replies, his retweets and at last I check his profile picture and background and here I see that his profile picture covers the sentence 'iseeyou' in the [header photo](https://twitter.com/jammymarkson/header_photo), that is the flag<br>

**Flag: icanseeyou**

## clockingout
*We're trying to plan when is best to break into James' house to plant a bug.
What time does he start work? (UK time).*

In this [tweet](https://twitter.com/jammymarkson/status/1226989808783888384) he says that he finished working at 23PM, after 8 hours. 23 - 8 = 14, that it's 2PM<br>

**Flag: 2PM**

## meme
*We've been watching a bloke called George recently, you might have already done some work on him.
He's not that smart by the looks of things, could be a good person to look for a social media presence on.
In particular, we're after an access key for a program his company uses so that the team can ex-filtrate information to aid with our ongoing fraud investigations.*

In replies tab on James profile there's this [tweet](https://twitter.com/GeorgeWatson428/status/1227648566316978176). The flag is in one of the messages. CTF3404X71<br>

**Flag: CTF3404X71**

## partytime
*Our intelligence analysts have reported that a whole bunch of our targets are having a party together on a Saturday night soon.
We want to deploy agents to see whats going on, but we can't risk blowing our cover turning up in a car. The road is pretty quiet and the property has very clear view of its surroundings, our reports suggest.
Find the location of the party and the best BUS ROUTE NUMBER to reach the party from Principality Stadium, Cardiff - where the surveillance team will be deployed from.
This sounds silly but we need to blend in with the public. The stakes are high.
Enter the BUS ROUTE NUMBER you think is best for this situation.*

Looking in James tweets, I find the [tweet](https://twitter.com/PearceRees/status/1227617292680298500) and here I put the destination and starting point Principality Stadium, Cardiff, I go in the tab where maps suggest the public transports that I should take and I see the buses are 57 or 58<br>

**Flag: 57**

## leavemessage
*Our analysts have been trying to get proof of a target's phone number.
We want to move ahead with the arrest but we must get evidence that the phone number we've got is indeed theirs. We need to be sure.
Due to the highly sensitive nature of the case, we cannot confirm the target's name with you at this time.
Please have a look to see if you can find their phone number.
When you call the target's number what are the LAST THREE WORDS you hear (you can also just enter the phone number as your answer and that is fine as well)?*

In the party [tweet](https://twitter.com/PearceRees/status/1227617292680298500) there were some people invited, I checked George, Sarah, James and Pearce profiles, but I couldn't find anything. There are two other profiles that I couldn't check @Sophjones77 and @jenmp7 because private or suspended. I tried to look on http://www.infobel.com/uk/ if there's a business in that address, I found a business and its phone number but it wasn't correct. I tried to check the address with Street View on Maps but nothing. I tried to check @Sophjones77 before the suspension with [webarchive](https://web.archive.org/) but it couldn't load the profile. I searched on Google the solution and I found out that the solution was in @Sophjones77 account that is currently suspended. The conclusion is that it's not solvable.<br>

# Evidence Investigation
## dvla
*We've managed to snag a picture of the front of a new Person of Interest's car. We need you to find out the make of the car and the month it was made in!
We've attached the photo from a local CCTV camera, take a look?
Enter as such: (Brand)(SPACE)(Month)*
![alt text](https://github.com/yyxxzn/yyxxzn-ctf-writeups/blob/main/OSINT/CyberSoc%20%7C%20Cyber%20Detective/img/img01.PNG)

I check on the UK government website the vehicles info [https://vehicleenquiry.service.gov.uk/](https://vehicleenquiry.service.gov.uk/). The result is:<br>

**Flag: Ford June**

![alt text](https://github.com/yyxxzn/yyxxzn-ctf-writeups/blob/main/OSINT/CyberSoc%20%7C%20Cyber%20Detective/img/img02.png)

## connectionrefused
*We're trying to access this web address: http://time-traveler.icec.tf/
The server is not responding! It is essential that we find the information contained on this site as we suspect it to be part of a criminal enterprise.
Sources suggest that the site was accessible about 4 years ago, not sure how that is relevant but it might mean something to you?*

I put the link on [https://web.archive.org/](https://web.archive.org/) and I select the snapshot of 1st June 2016 and this is the result:<br>

**Flag: IceCTF{Th3y'11_n3v4r_f1|\|d_m4h_fl3g_1n_th3_p45t}**

![alt text](https://github.com/yyxxzn/yyxxzn-ctf-writeups/blob/main/OSINT/CyberSoc%20%7C%20Cyber%20Detective/img/img03.png)

## chemtrails
*We've been rummaging through a Person of Interest's wheelie bins. We've found this boarding pass; although it looks like whoever had it was a bit paranoid that someone like us would find it.
I think we can still do something with this though... There is one thing in particular on here that may help us.
We really need to find the SEAT NUMBER of this person, in order to connect it with other evidence the team has gathered.
We've attached the boarding pass for you. Please find this out for us.*
![alt text](https://github.com/yyxxzn/yyxxzn-ctf-writeups/blob/main/OSINT/CyberSoc%20%7C%20Cyber%20Detective/img/img04.png)

Initially, I experimented with image manipulation using Photoshop. However, I subsequently noticed the presence of a barcode and decided to utilize an online barcode scanner, which ultimately yielded the desired result. <br>

**Flag: 22B**

![alt text](https://github.com/yyxxzn/yyxxzn-ctf-writeups/blob/main/OSINT/CyberSoc%20%7C%20Cyber%20Detective/img/img05.png)

## bigbrother
*We've intercepted a live camera feed overlooking a public space. The camera owner has not bothered to put a password on it and its open to the world!
An extremely dangerous criminal on the run was recently spotted by our surveillance team using this camera.
It is essential to our investigation that we find out the COUNTRY where this camera is operating from so we know which law enforcement agency to follow up with.
Please find this out for us.
LIVE CAMERA FEED: http://81.82.201.132*

I checked the IP Geolocation with https://www.iplocation.net/ip-lookup<br>

**Flag: Belgium**

![alt text](https://github.com/yyxxzn/yyxxzn-ctf-writeups/blob/main/OSINT/CyberSoc%20%7C%20Cyber%20Detective/img/img06.png)

## balancethebooks 
*We have reason to believe that a particular company, TECHNOLOGY SERVICES LIMITED is complicit in a case we are investigating.
To gain a better understanding of the size and scale of this company, we need you to find out the AMOUNT OF CASH currently held by them.
We've attached a document we acquired from hacking one of their laptops; hopefully this will help you find this information?
Thank you for your continued support.*

I searcged for the register on [https://find-and-update.company-information.service.gov.uk/](https://find-and-update.company-information.service.gov.uk/) using the company number.  I had to sift through multiple instances of 'Total exemption full accounts' to pinpoint the one associated with the year when this CTF was created. The accurate one is dated December 14, 2020. As I scrolled through the document, I was able to locate details regarding assets, specifically the amount of cash held in the bank.<br>

**Flag: 102.3**

![alt text](https://github.com/yyxxzn/yyxxzn-ctf-writeups/blob/main/OSINT/CyberSoc%20%7C%20Cyber%20Detective/img/img07.png)

TO FINISH
---
