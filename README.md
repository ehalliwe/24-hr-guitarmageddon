# guitarmageddon
1153 - hi i decided to do the hackathon and i'm going to be building some sort of guitar pedal and using this as my brain dump blog\
1208 - originially i was considering designing just a phaser pedal, but now i'm thinking of a multi-effects pedal with some sort of switcher. Distortion, phaser, chorus/flanger, noise gate. maybe more, i'm not sure. i don't see many 3-in one pedals on the market so that could be something cool to dig into.\
1211 - oooo if it's all analog that's kinda different.\
1224 - definitely doing a noise gate in there somewhere. probably just a flat cutoff below certain dB that can be adjusted by a pot, from 0db to -70db or something like that. not sure how to do a decay time circuit though. gonna have to lookup some reference ccts for this.\
1227 - pedal will run off of standard reverse polarity dc 9v input jack, no battery option (pain and hardly used).\
1309 - seeing the same cct over and over again, seems like some kind of bypass thingy. spice time\
1340 - cct understood. i have a design based on BOSS pedals for the on/off stomp switch. will do true bypass later if i have time, otherwise meh. going to work on input and output buffers now\
1403 - block diagram of general cct complete. refining output buffer schematic. have general idea of input buffer schematic. need to find idea on toan zoan (kmac) controls (basic bass mids treble cut/boost pot circuit). effect ccts to come later. going to do true bypass in passive form as i found an easy cct online.\
1433 - input buffer and output buffer schematics complete. working on adding bypass circuit into these\
1440 - power cct with protect diode schematic complete.\
1455 - passive bypass cct complete. that was a headache. 3pdt on-on switch should work fine i think.\
1501 - just kidding i did it wrong. blargh. switches make my head hurt. taking a break to walk the dogs.\
1633 - switch schematic fixed.\
1701 - noise gates are more complicated than i initially expected in terms of design as well as understanding them. the double diodes are throwing me for a loop... not sure what's going on there. i found a schematic online that i'll just plug and chug with. now onto toan zoan\
1710 - made a stupid logo :)\
1743 - decided to do a ripoff of the boss ge7 for equalization, 4 pots controlling 100Hz, 400Hz, 1.6kHz & 6.4kHz channels. that's almost done. effects section next\
1806 - found a github repo with a ge7 spice model already in it. might piggyback on that to create my spice model of this whole thing as it seems like a beast right now.\