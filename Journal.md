title: "Macropad"
author: "Ryaan"
description: "A wireless macropad with insane haptics!!, comes with 11 switches and 2 rotary encoders."
created_at: "2024-05-07"


# May 8th: Began working on my macropad idea

Today, i decided to start working on a macropad, as i submitted my other project and am impatient:)
I have no clue on how to build one, just heard its very popular. I mainly went around looking for inspiration, and how to start with the fundamentals like the schematics.
I imported a few libraries of symbols and foot prints to kicad. Now i have to figure out how to make a switch matrix, as im planning on using 11 switches along with 2 rotart encoders and a display, and the SEEED xiao MC barely has pins!! so yea.

https://public.lapse-hackclub.link/timelapses/Jx6Lpbg7D-ae/timelapse-Jx6Lpbg7D-ae.mp4

<img width="1635" height="1007" alt="image" src="https://github.com/user-attachments/assets/ac9dccfd-2d4d-45ec-afbe-3eca195e4a39" />
<img width="1561" height="846" alt="image" src="https://github.com/user-attachments/assets/773432a7-963a-4904-8459-6c0972733ff3" />
<img width="1258" height="879" alt="image" src="https://github.com/user-attachments/assets/0e292fee-5d95-4d9e-8864-5eb5f63d21c1" />
<img width="805" height="130" alt="image" src="https://github.com/user-attachments/assets/b1f49d80-e18e-4350-87f0-c4551d3a1266" />
<img width="972" height="446" alt="image" src="https://github.com/user-attachments/assets/99b5a1e0-b1f1-49df-b200-65c1fb06cbf9" />

**Total time spent: 1h**


# May 9th: Continued working on schematics

I continued making the schematics. I went thru a few hackpads others made for inspirations, and to see if i can understand better by goin thru those schematics. I made the switch matrix, and added the rotary encoder sign. I also did a bit of research and am gonna go with the 0.91inch oled display. I also added diodes to the switches. Well im not sure how this goes, its my first time making a macropad:)

https://public.lapse-hackclub.link/timelapses/vdwkVHPgRyA7/timelapse-vdwkVHPgRyA7.mp4

<img width="286" height="317" alt="image" src="https://github.com/user-attachments/assets/43999892-5379-4dd3-b226-713543e948ce" />

**Total time spent: 1h 18m**


# May 10th: Continued working on schematics

i continued working on the schematics. I added and wired the switch matrix, rotary encoders, the oled display and the rgb led's. I just realised i wanna make the macropad wireless too, so im gonna add a raspbery pico W later.

https://public.lapse-hackclub.link/timelapses/AWpfal8JZQ22/timelapse-AWpfal8JZQ22.mp4

<img width="867" height="472" alt="image" src="https://github.com/user-attachments/assets/43b09136-5e00-4bce-abb2-c9fb1b3f620b" />
<img width="482" height="488" alt="image" src="https://github.com/user-attachments/assets/7654edcf-1627-455d-9e33-b18d1f04a86a" />
<img width="1030" height="535" alt="image" src="https://github.com/user-attachments/assets/4e0fe174-9834-4501-96fb-c01c81f5b248" />

**Total time spent: 1h 32m**


# May 10th: Continued working on schematics

i continued working on my schematics:)
I finished re arranging all the components, and then wired them up, (colour coded obv). Then a random idea js struck my mind: why not make it wireless!
so i went ahead with a raspberry pi pico W, and started researching on how to make it wireless and functional.
I decided on like a 1000mah 3.7v battery(might change later tho..), and a TP4056 module for charging:)

https://public.lapse-hackclub.link/timelapses/nB5B7usA8Ic8/timelapse-nB5B7usA8Ic8.mp4

<img width="1026" height="526" alt="image" src="https://github.com/user-attachments/assets/0f961a7b-7278-4480-9047-1a2ba8d3d8df" />
<img width="828" height="498" alt="image" src="https://github.com/user-attachments/assets/c25f4894-7821-440b-a27c-ccac08b1e91e" />
<img width="837" height="439" alt="image" src="https://github.com/user-attachments/assets/72c41f26-b1e2-44a1-83d2-40332b2280c4" />

**Total time spent: 1h 3m**


# May 10th: Continued working on schematics

I am still continuing on my schematics lmaoo:)
As i thought of using whatever module im adding to my pcb as daughter modules, i had to find their symbols, which ofc were not there, so i just decided to use connectors instead. I then changed the name and labelled the pins on these connectors to math the TP4056. Then i added 2 connectors similarly for the battery pads and labelled them. I repeated the same for the MT3608 buck boost converter too. Then i added a spdt slide switch and wired them all up!. The main idea was that; there woul be two modes which the switch can toggle: one was the wired one, where the macropad gets connected via usb and doesn't use battery power, and the 2nd is wireless, where the macropad connects via bluetooth, utilizing the power of the battery.

https://public.lapse-hackclub.link/timelapses/LJAMLVG_SWli/timelapse-LJAMLVG_SWli.mp4

<img width="800" height="419" alt="image" src="https://github.com/user-attachments/assets/6fe93a12-8292-4764-8a92-6160a00a559b" />

**Total time spent: 1h 1m**


# May 10th: Continued working on schematics

i forgot to save my kicad sch, and left the pc on. there was a power cut and almost all my work was gone:((, literally the 3rd time this is happening!!
So yea, i had to redo everything again:(((
This time i made the wiring neater ofc:)

https://public.lapse-hackclub.link/timelapses/aa1d4ZVKxRlv/timelapse-aa1d4ZVKxRlv.mp4

<img width="772" height="382" alt="image" src="https://github.com/user-attachments/assets/bea4dba9-5796-41e9-b14b-7c849ceb1c63" />
<img width="772" height="382" alt="image" src="https://github.com/user-attachments/assets/8e87a59e-70f4-49fb-b7a9-a55eff1709bc" />
<img width="687" height="389" alt="image" src="https://github.com/user-attachments/assets/0a30b395-e3bf-4c29-9de8-4f7ace27e43a" />
<img width="782" height="475" alt="image" src="https://github.com/user-attachments/assets/134caa82-9c00-4146-b378-ebfec840aa1e" />

**Total time spent: 1h 3m**


# May 10th: Continiued working on schematics (assigned footprints etc)

I did some final touches and started working on assigning the foot prints to each.
i had a bit of trouble figuring out how to make like pads where i can solder the battery to, so i used mounting holes instead. I also got the idea of adding haptics:), i don't think any1 has done that b4 so should be fun:)). Im planning on using a drv2605l module for precisely controlling the haptics, and customising it for each mode. Like a different intensity and style while gaming, or while working, or while changing profiles.

https://public.lapse-hackclub.link/timelapses/4v5Tm7YbSgqZ/timelapse-4v5Tm7YbSgqZ.mp4

<img width="940" height="446" alt="image" src="https://github.com/user-attachments/assets/95346b1c-ffb2-4190-a8e2-aa5fcea0e76d" />

**Total time spent: 1h 12m**


# May 11th: Made some changes to original idea

I researched and added a new module for the haptics!!
I think this is the first hackpad with haptics too:)
Im gonna go with the Adafruit DRV2605L Haptic Motor Controller, this is insane for controlling vibrations precisely. It can do multiple types too, like a quick i phone like one, or bit more detailed like the psg controllers, this is ofc customizable and can be changed depending on your profiles:). I then opened the pcb editor for the first time and tried to dump the footprints, but there was some error: it turns out i cant use mounting holes to solder wires onto, so i just swapped it out for some pin headers, which should do the job just fine. now the error got fixed and i dumped the components, Im new to this stuff, so i just arranged the switches, and am gonna do the rest later. I wanna hide the pico or somehow mount it smd style so its huge footprint doesnt make the the entire macropad bigger. I think i might rather use a different MC if the pico won't be able to mount on the underside of the pcb.

https://public.lapse-hackclub.link/timelapses/szlrLOvkwOXQ/timelapse-szlrLOvkwOXQ.mp4

<img width="1012" height="491" alt="image" src="https://github.com/user-attachments/assets/fd6e8038-e2a8-49a8-80c2-b0573284a90e" />
<img width="1043" height="517" alt="image" src="https://github.com/user-attachments/assets/c8afe77b-796b-4ac8-96b9-2e60e9d983e2" />
<img width="1229" height="734" alt="image" src="https://github.com/user-attachments/assets/3e882072-2991-461e-a37f-3eaa90545a25" />
<img width="335" height="392" alt="image" src="https://github.com/user-attachments/assets/ee3b0735-b997-4e4d-853c-291a29318abc" />
<img width="1026" height="510" alt="image" src="https://github.com/user-attachments/assets/ff53641b-f49a-498b-83ca-079a26a54e6c" />
<img width="652" height="504" alt="image" src="https://github.com/user-attachments/assets/2639a0e5-53b4-4bf8-92eb-89992b3abfba" />
<img width="960" height="479" alt="image" src="https://github.com/user-attachments/assets/7f86e45d-9d4f-4e7e-b821-16203fc07ce1" />

**Total time spent: 1h 41m**


# May 14th: Continued working on schematics

I made the schematics much neater. Aryan introduced me to global labels on Kicad which is a lifesaver. I also used a better looking symbol for the switches. I then made a new switch matrix, and wired everything up using global labels. I also rearrranged every symbol and labelled everything neatly so that my schematics could look more professional:). I also redumped all my footprints onto the pcb editor as ive edited each of the them in the footprint assigner thingy. Im still not sure about the pcb part tho, and am on the fence about choosing a raspberry pi pico w or not, due to its HUGE footprint.

https://public.lapse-hackclub.link/timelapses/0GBBIOc-dRC7/timelapse-0GBBIOc-dRC7.mp4

<img width="583" height="403" alt="image" src="https://github.com/user-attachments/assets/80ed1282-8369-43a2-8f8d-2b8cb3d15cd2" />
<img width="574" height="394" alt="image" src="https://github.com/user-attachments/assets/77b2299d-bbc9-4717-a14f-892bca66b572" />
<img width="236" height="338" alt="image" src="https://github.com/user-attachments/assets/56271e7d-3d7f-4637-9c8c-cbbb966f4ebe" />
<img width="211" height="347" alt="image" src="https://github.com/user-attachments/assets/14547195-7e8c-437b-9cfe-e02e8cdbd7b3" />
<img width="807" height="330" alt="image" src="https://github.com/user-attachments/assets/72ea25c4-9908-4186-b267-43de901ec782" />

**Total time spent: 1h 30m**


# May 21nd: Started working on the pcb

I started working on the pcb finally. Well this is my forst time making a pcb, so yea
I just imported all the footprints onto the editor. I then arranged them roughly, i have no clue if its correct or not. I will def change them later. I arranged only the switches, rotary encoder and pico for now.

https://lapse.hackclub.com/timelapse/G3J0O8FZEjo2

<img width="1068" height="536" alt="image" src="https://github.com/user-attachments/assets/10e3cad5-ed6e-49d6-8811-e7a2e921f130" />
<img width="1065" height="526" alt="image" src="https://github.com/user-attachments/assets/2661a52c-0084-409f-ba0b-98e9cd5a3830" />
<img width="1053" height="534" alt="image" src="https://github.com/user-attachments/assets/9d734e5e-081a-49a6-a641-54fb62b3a81c" />

**Total time spent: 30m**


# May 22nd: Transferred all the journals to horizons

I just transferred all the journals from fallout to horizons neatly. I ensured each journal correctly alligned with the guidelines for horizons.

https://lapse.hackclub.com/timelapse/SRcNPL15U1K1

<img width="1087" height="548" alt="image" src="https://github.com/user-attachments/assets/ac4a2b93-f272-4caa-ab89-53fa4c0e9aaa" />

**Total time spent: 40m**


# May 23rd: Continued working on pcb

i continued working on the schematics. I thought of placing the pico underneath the pcb but realised that wont work cuz if the switches. I then tried doing some research on some other module with a smaller footprint like a xiao or a rp2040 or an esp32 etc, but everything was either too big or too small, didnt have enough gpios or had too many etc etc. I went through lots of datasheets etc and still no luck. I decided to give the esp32 s3 a try, not sure tho...

https://lapse.hackclub.com/timelapse/vrI20fQrQSxk

<img width="964" height="514" alt="image" src="https://github.com/user-attachments/assets/33072000-4638-44b0-8293-a64f79fc3207" />
<img width="663" height="426" alt="image" src="https://github.com/user-attachments/assets/5420371d-bb5e-4b5e-82f6-1522c8d7690f" />
<img width="867" height="462" alt="image" src="https://github.com/user-attachments/assets/22d5a030-c723-4fbc-afd4-4a7557400c5e" />
<img width="859" height="352" alt="image" src="https://github.com/user-attachments/assets/78a440be-f99e-4284-b51e-03ad23f46ec9" />

**Total time spent: 2h 15m**


# June 4th: Worked on the schematica

I did most of my work on the schematics today. I decided to ditch the esp32 mc or any other mcu idea as i didnt wanna over complicate anything for my first pcb, and my first macropad. Im gonna stick with the pico only. I made some changes to the connections of the power switch and all the daughter modules.

https://lapse.hackclub.com/timelapse/ZglHSRn_m3mC

<img width="1054" height="512" alt="image" src="https://github.com/user-attachments/assets/81c5d4e0-241f-4d19-b027-47ece1f35aa4" />
<img width="931" height="481" alt="image" src="https://github.com/user-attachments/assets/a72545a6-d2d1-4243-b0a9-22fca2551497" />

**Total time spent: 40m**


# June 14th: Continued working on the pcb

I continued working on the pcb. I arranged the diodes near each key, and placed the leds under each key. I also flipped the leds. I tried different positions for the pico so it can be compact, but gave up:), i then made the pico foortprint from smd to pin header one. I also moved around the pin headers for the daughter modules, and then decided to ditch the pin headers and instead connect the modules with jst connectors as then i can place the modules on the bottom of the case and it will be easier to wire too.

https://lapse.hackclub.com/timelapse/cCD02lNH7a1F

<img width="990" height="835" alt="image" src="https://github.com/user-attachments/assets/f530dfd6-ab49-4ceb-9646-f7b69a3174ad" />
<img width="1049" height="596" alt="image" src="https://github.com/user-attachments/assets/2fdc8c53-3b19-4793-a506-9eff7d820757" />
<img width="942" height="650" alt="image" src="https://github.com/user-attachments/assets/8670921e-94d7-471f-8689-86706e33d3fd" />


**Total time spent: 3h 30m**


# June 14th: Continued working on pcb

I continued working on the pcb. I went thru the schematics once more. I then downloaded some cherry mx key switches 3d models and added them to the foot print properties. I also added the keycaps too. I did added the ec11 encoder cad but culdnt finda suitable knob yet. I then started setting the editor with defferent track widths etc, and netclass, to start routing the pcb, as this is my first time. I somehow routed all the switches and the encoder and the oled disp. Im yet to do the rest. As of now the routing is insanely messy, with like a ton of vias everywhere.

https://lapse.hackclub.com/timelapse/yGzgsLiheN3N

<img width="1018" height="552" alt="image" src="https://github.com/user-attachments/assets/751a26c9-3fcb-4a9b-a3f1-5b08e05f69f6" />
<img width="820" height="739" alt="image" src="https://github.com/user-attachments/assets/862016f2-c93b-4e7c-beac-7821ae85fc5f" />
<img width="752" height="555" alt="image" src="https://github.com/user-attachments/assets/b2d8e949-5b9e-40c2-afa5-be922cbc593e" />
<img width="706" height="427" alt="image" src="https://github.com/user-attachments/assets/266c8a15-123b-4d6b-979a-2ca04e65d809" />

**Total time spent: 3h 30m**


# June 17th: Continued working on pcb

I continued working on the pcb. I deleted all tracks and vias cuz they were too ugly.
I started routing it again from scratch after a few yt videos. Soon into routing i realised that i had to rearrange switches and the leds accoording to their matrix ro the routing will get messed up. That was confusing and took a while. I then connected the diodes, then the switches according to the matrix, then the leds. I also connected all these to the MC, including the pins and everything for the daughter modules and the rotary encoders. I only have to route the gnd later.

<img width="922" height="576" alt="image" src="https://github.com/user-attachments/assets/63675d9b-1a8b-413e-acc6-55f36bf6f786" />
<img width="916" height="650" alt="image" src="https://github.com/user-attachments/assets/689e4cd3-23e7-4b7a-9622-16188e038cf3" />
<img width="1310" height="922" alt="image" src="https://github.com/user-attachments/assets/8473f36b-c3de-48c3-a45b-f79ea2b62c77" />


**Total time spent: 3h 5m**


# June 8th: Got the screen to work!

[actual journal content - what did you do?]

[insert pictures of what you're working on!]

**Total time spent: 2h**


# June 8th: Got the screen to work!

[actual journal content - what did you do?]

[insert pictures of what you're working on!]

**Total time spent: 2h**


# June 8th: Got the screen to work!

[actual journal content - what did you do?]

[insert pictures of what you're working on!]

**Total time spent: 2h**
