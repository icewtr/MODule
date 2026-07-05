# march 16: the idea 
<img width="1038" height="672" alt="a" src="https://github.com/user-attachments/assets/baea21d6-9a52-4d6d-a65c-54db3a527285" />
after losing badly in states (48th out of 48 teams) i knew we had to do something. our old mecanum drivetrain took up so much space we ended up not having enough space for a functional robot 😭
so i was thinking "hm lets make swerve, we can reference other good designs and just make them smaller than a mecanum drivetrain."
and so it started, me drawing out a bad sketch to present to others my concept, the black box being an approximate sizing of one mecanum wheel's size and what i think we can do.

- time spent: ~30 mins

# march 17: what. am. i. doing.
<img width="1188" height="807" alt="b" src="https://github.com/user-attachments/assets/22c79bdf-baa8-473f-b6db-0edbaac7fca2" />
WHAT AM I DOING NO WAY I DONT KNOW HOW TO MAKE THIS 😔
WHY IS IT SO COMPLEX
WHY
makes me wonder, why gears? 
i checked one of the best swerve teams ik's mosules and theyre using 2mm gt2 belts so might be interesting? 
im so used to frc it might be getting to me lol
5000000 million gear sizes, and some of the strongest bldc motors ive seen, which kinda explains why no gt2 belts, so yeah belts...

- time spent: ~1.5 hours

# March 12: still gears?
<img width="792" height="696" alt="c" src="https://github.com/user-attachments/assets/2c901bf7-dfb8-4f93-a0cf-cc286c884b85" />
idk why, i feel like gears is the move but like its so complicated 

also *big issue* its bigger than the mecanum drivetrain so there really isnt a definitive answer. 
well, we gotta do something. i cant be this fixated on a swerve module with FRC season going on and exams afterward. ill take a break and see if that helps.

- time spent: ~1 hour

# may 4: THEY COME OFF?
<img width="661" height="848" alt="d" src="https://github.com/user-attachments/assets/c272d02e-ee2f-4c39-b8c4-f680f241389d" />
yo no way i just now found out the motor sleeves come off 🤯 this is gonna help so much!
with that the motors diameter gonna be smaller by a tad bit meaning i COULD fit it in a smaller foorprint than 70*140???
the break definitely helped tho i came to my senses that a belt IS the play, talking to seattle solvers helped me greatly.

- time spent: ~30 mins

# may 11: finally an organic idea?
<img width="1043" height="905" alt="e" src="https://github.com/user-attachments/assets/a544e2e4-2cac-41c3-94fa-a9db4beaed0c" />
since axon bevels (THE swerve bevel that everyone uses) is out of stock permenantly, i have to 3dp or use the massive gobilda bevels. 

yea. the gobilda bevels are too big. screw it. im making it myself.
so since im 3d printing it, i think making it helical might be the play here, cuz the force is distributed across multiple teeth rather than just one tooth, making the gears stronger and more resistant to teeth snapping.
and yeah, more exams. time to dip for a bit and come back to lock in. 

- time spent: ~30 mins


# june 13: 3 dimension?? what is that???
<img width="824" height="872" alt="f" src="https://github.com/user-attachments/assets/aab209fe-6798-49b7-83e6-ffcce5ab5042" />

finally with something that looks like a swerve module somewhat, i went in, boom. locked in, zero regrets. WE are winning state championships with this. 
but yeah, length and width wise its finally somewhat small and usable, so now its time tp make it short cuz its still too tall. the goal is 64mm * 140mm * 110mm so lets get it done.

- time spent: ~2 hours

# june 17: time to reinvent the wheel 
<img width="914" height="674" alt="g" src="https://github.com/user-attachments/assets/3a58ad45-ad92-4359-9f85-495dc25dd055" />
so yeah now i need to make a wheel for my swerve module and yeah i dont know hoe to make one 😔
i mean I do, cuz like frc swerve, but this is FTC where everything is so small!¡¡  yeah this is small the wheel is 2 inches tall and 1/2" wide lol

- time spent: ~1 hour

# june 25: going through ratio hell
<img width="1129" height="808" alt="h" src="https://github.com/user-attachments/assets/345f23fd-1d49-4116-899d-5c0c81856a62" />

i loove back when i didnt know anything about cad and used to vibe guess all my ratios... well now i have to. 
so my ideal is the speed of a 435 rpm motor, which is like the commonplace ftc drive motor for mecanums. and my old ratio was like 377 rpm. wayyyyyyyyyyy too slow.
bro im boutta have snail speeds on this robot 😭
i did calculate something, but might need a custom pulley so we'll have to see cuz i didnt really wanna go to custom  pully gang and wanted to stay with cots gobilda pulleys.

My calculated ratios: approximately 855-860 rpm, with a free speed slightly higher than that of the 435 RPM drivetrain motor, a popular FTC choice. although this has a higher surface speed and as a result lower theoretical torque, since the mecanum drivetrains use passive rollers, the grip of these 3D printed swerve tread would more than overpower standerd mecanums. 

- time spent: ~1 hour

# june 26: whoops.
<img width="1625" height="954" alt="i" src="https://github.com/user-attachments/assets/68bad6e2-d271-4ff6-ae39-ba45471f978c" />
*[tape scratch] yeah thats me. your probably wondering how i got here*
but apart from that, i had an idea.

currenty my servo is mounted perfectly horizontal. but why tho? if i mpount it diagonally, ill get tons more space and ill be able to make this even smaller 

brains thinging now watch out

- time spent: ~30 mins

# june 29: A swerve module that finally follows the meta?
<img width="1402" height="1057" alt="j" src="https://github.com/user-attachments/assets/aed95db4-3872-499e-b010-3ce025941b4f" />
he is so small 😆

he only need one popcorn 🍿

jokes aside its finally small, time to make it functional. this means make it sompetitive and better than other modules available in FTC. we got the size down, time to make it good and small, not just small.

- time spent: ~1 hour

# june 30: encoder??? whats that???
<img width="820" height="772" alt="k" src="https://github.com/user-attachments/assets/92a9a94a-cb9d-4def-99e6-7f929b2eca1b" />

yo no way i forgot we needed an encoder 😭
so im gonna have to change up a few things:
make the coaxial pulley and gear somewhat deadaxle so there is an encoder shaft
ik most teams drop the encoder, but if we want to have the most accurate angle sensing, this is a MUST. we NEED this to have a better swerve module. theres a reason every frc swerve module has this.
<img width="1326" height="1093" alt="l" src="https://github.com/user-attachments/assets/721b526a-2571-4b0a-adbb-4cadf9c9c7d6" />
other than that tho, its coming together nicely (hes herringbone like i said previously because force spead across multiple teeth)

- time spent: ~30 mins

# July 1: NEW FORKS!
<img width="903" height="669" alt="m" src="https://github.com/user-attachments/assets/8458921f-433d-44c2-aef0-b8833e58f3b9" />
omg these new forks look so good😍
genuinely idk what i did, but it cooked lol
gonna be a bit of a pain to manufacture but ehh its fiiineee trust
<img width="1239" height="922" alt="n" src="https://github.com/user-attachments/assets/3b41bc91-4160-468e-bc47-d5942f45dd4c" />
other than that, boom even smaller, genuinely looks like a sandwich atp its actually beautiful

- time spent: ~45 mins

# July 3: swerve tread and pocketing
<img width="741" height="674" alt="o" src="https://github.com/user-attachments/assets/3b3cc5ba-0b6b-490d-b6b4-32046476e890" />
so a smooth wheel isnt gonna work i had to actually make tread
i tried doing a few different things, ranging from a bunch of triangles and an extrude to contemplating giving up and using neoprene
i ended uo just taking the pulley profile of a gt2 2mm pulley and extruding it so yea lol

<img width="1274" height="693" alt="p" src="https://github.com/user-attachments/assets/e37d3ff6-de95-480f-b215-acbe0980250a" />
(and yeah now the plates are both light and beautiful)

- time spent: ~1 hour

# july 4: Hold up! His writing is this fire?
<img width="1985" height="990" alt="r" src="https://github.com/user-attachments/assets/d412daf5-373c-4838-8a9d-cd7a51f7c8f6" />
<img width="1265" height="1080" alt="q" src="https://github.com/user-attachments/assets/dba3da89-878a-4bea-809a-3fe234ec244e" />

genuinely a beautiful swerve module 
truly a piece of art 
cant wait to build it!

- time spent: ~15 mins

#TOTAL TIME (AS PER HACKATIME): 12 Hours 57 minutes
#TOTAL TIME (AS PER JOURNAL): ~12 Hours

# KEY TAKEAWAYS:
- When comparing swerve to mecanum drivetrains, performance is less constrained by wheel vectoring and more by torque and speed for both propulsion and steering, packaging, and controllability
  
- having a module thats competitive is good, but having something equally reliable is even better
  
- usage of a deadaxle encoder helps in steering despite the increased complexity
  
- coaxial gear assembly is so densely packed, accessibility and ease for repairs is key
  
- 2mm belt is a lot more finicky and sensitive to over-tensioning than 5mm belt



(im sorry for whoever has to read this journal lol)
