# F8 Refresh Hackathon Project 2021  "After Hour"
Chris Daniel - https://www.linkedin.com/in/cdaniel2010/
Jenny Lin - https://www.linkedin.com/in/woanchinjennylin/
<img width="1024" alt="cover" src="https://user-images.githubusercontent.com/43097420/117728304-4635e200-b1b7-11eb-8285-64fd68f0533d.png">


# An inclusive VR escape room experience in Oculus Quest 2 leveraging voice command using wit.ai for people with or without visual impairment.

As the convention of accessibility in VR hasn't yet been established, we want to be the pioneer in building inclusive VR experience so that people with visual impairment could also share fun moments and connect in VR. Chris' niece, in her 30's, was born blind, but we believe she deserves to enjoy Oculus as much as we do, which is one of the motivations that prompt us to build this voice-first VR game.
Leveraging Wit.ai, Oculus Quest 2, Unity and TTS(in future) we can enable, enhance, empower, and make VR experiences inclusive. 


# Gameplay
Our NPC is a spirit of the museum. 
Maybe left there from a previous Egyptian exhibit.
It speaks to us via NLP utilizing wit.ai and TTS(future).

Say "Hello Spirit" and they will respond.
Ask them many questions about the museum and they can help you in your hour of need.

Hey Spirit, what can I say? [instruction_get]

“Good evening! I’m your spirit guide. You can ask ‘where am I?’ or  ‘Why am I here?’”

Where am I? [location_get]

“You are at the D&J Museum of Wonders”

Why am I here? [reason_get]

“You are stuck here after the opening hours”

How do I get out of here? [clue1_getPrompt]


Work with the spirit to escape.

<img width="400" alt="clue" src="https://raw.githubusercontent.com/wc-jennylin/afterHour/main/clue3.png">


# Challenges
Quest 2 has its own challenges but our most difficult challenge was to get a wav with 10 seconds of voice to send to wit.ai. Tried at least 4 different methods to access the mic data stream. Microphone works, store data works, send to wit works, rest coming back works.(logcat in files) - mic voice data did not get saved and merged to wav creation. Attempted various methods ie. AudioClip.Create, assign clip to AudioSource. BTW learned you must have an AudioSource with a Microphone. 
We didn't know each other before the hackathon nor did we have a planned app, but Chris knew he'd like to work with VR while Jenny is passionate about inclusive design.
Also both of us during the hackathon had our second dose vaccine.


Going forward, I'd like to work more with the app if time allows to complete and wit.ai. I am an avid VR user, VR dev and am happy to see more folks enjoing this medium. I'd like to show my niece something cool. BTW she is very tech savy.
-- Chris

I've been so passionate about this project - a challenge to be one of the pioneers to build VR games for people with visual impairment as I value inclusivity and believe that everyone deserves to experience all benefits of emerging technologies. 
Learned so much about conversation design whose convention also hasn't been established yet. Would love to have the opportunities to continue working on this. -- Jenny 

# Privacy
We value users' privacy and store no data that has any identifing information. We may utilize some text conversations anonymously to enhance and provide a more enjoyable and inclusive Oculus Quest 2 game experience.
Additionally we utilize Wit.ai and abide by their standards of practice. https://wit.ai/privacy/ccpa/

# APK Link
https://drive.google.com/drive/folders/1Np5InLFOqQX-zI9bWb130DeAIFwxyVRo?usp=sharing

- Many thanks to Aaron Faucher creator of Wit3D for a starting place http://afaucher.me/projects/wit3d/
https://github.com/afauch/wit3d

- Also thanks to FB Hackathon Team 

# Demo/Promo Video Link:
https://vimeo.com/547736374


# Update 6-1-21

Wit.AI and app are connected, re-examining the converstations and overall game design for possible release. - cd 
