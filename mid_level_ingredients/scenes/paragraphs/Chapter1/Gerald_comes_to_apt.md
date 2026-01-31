# Paragraph: Gerald Comes To Apt

@tag: Paragraph_Gerald_Comes_To_Apt

# Gerald asks to come to Nicolas's apartment.

@tag: Paragraph_Gerald_Asks_To_Come_To_Apt

%Short: Gerald asks to come to Nicolas's apartment.

In: Scene 1.1 (Texting Friends Section)

## Description
Nicolas has been feeling lonely and bored, so he decides to reach out to his friend Gerald via text message. He asks Gerald how he's been doing and tells of a crazy idea he has about talking to people he finds interesting. Gerald responds positively and suggests they meet up the next day.

## Includes
- Section_Linear
- Line_ForcedChoice

- Character: Char_Nicolas
- Character: Char_Gerald

## Script
**(SELECTION)** Player selects the contact "Big Bull Gerald".

n_thought "Sigh… Gerald… My big bull guy… Erm… Friend?"
n_thought "Has he forgotten me?"
n_thought "I… think I still crush on him…"
n_thought "Well… There’s only one way to find out…"

<!--- TODO: Include Flashback? Explanation? -->

**% SFX:** phone_typing
n_sms "Hi, I am doing... nothing"

- Nicolas pauses a bit before typing again.

**% SFX:** phone_typing, phone_typing_backspacing
Nicolas types: "What’s up" adding ", Big Bull?" before backspacing
n_thought "No... That's too... uhh..."
n_sms "What’s up?"
n_narrate "_(Surprisingly, after a little bit, he answers me.)_"
n_narrate "_(He must not be very busy.)_"

**% SFX:** sms_received
**% Show:** split screen, Nick left, Gerald right
g_sms "Hey!"
g_sms "Long time no see, my eagle pal }:8"
g_sms "I’ve been doing great, and you?"

**% SFX:** phone_typing
n_sms "Uhh… I'm… okay, I guess"
n_sms "I’ve been doing nothing all day, everyday"
n_sms "I don’t know what to do with myself! Help me!"

- Nicolas pauses a bit before typing again.

**% SFX:** phone_typing
n_thought "I have to tell him… Tell him about my idea"
n_sms "What if I did this crazy idea of just talking to anybody that I see that I find interesting???"
n_sms "But that’s just a crazy idea…"
n_sms "There's no way anyone would be willing to talk to me…"
n_sms "Much less become friends with me…"

**% SFX:** sms_received
g_sms "You’ve always been kind of crazy to me, no offense [Smiling and blushing emoji]😊"
g_sms "I’d tell you to just be careful"
g_sms "Tell you what, why don't we meet up tomorrow and talk more about it?"
g_sms "After all, I could use some company and I am not far from you"

**% SFX:** phone_typing
n_sms "I… don't know…"
n_thought "Meet up later and talk more about it?"

- Mini Section: Gerald Comes To Apt Choice

**(MENU)** Player chooses if Gerald comes.

**(OPTION)** Agree to meet up.
n_sms "Sure! That sounds good"
g_sms "Great! I'll see you tomorrow then, big bird"

**(OPTION)** Unsure…
n_sms "Uhh… Maybe???"
g_sms "What do you mean maybe???"
g_sms "Come on, it'll be alright! Just say yes!"
g_sms "I promise I won't bite }:8"
(Go back to yes/no choice, remove maybe option.)

**(AFTER CHOICE)**

**% SFX:** sms_received
g_sms "Anything is better than you just rotting in bed all day, right?"
g_sms "Well, that's it for now"
g_sms "Unless you have anything else to add?"

**% SFX:** phone_typing
- Nicolas thinks for a moment.
n_thought "Should I tell him how I feel?"
Nicolas types: "I think I'm in love with you..." before backspacing.
Nicolas types: "I have a cr..." before backspacing it all.
n_thought "No no no no no… Can't say that… Not yet…"

**(NATHAN NOT TEXTED BEFORE)**
n_sms "All good on my end… See you tomorrow."

**(NATHAN TEXTED BEFORE)**
n_sms "Actually, Nathan said hi, btw."
n_sms "We could visit his shop…"

**% SFX:** sms_received
g_sms "Oh, nice!"
g_sms "He's a great guy."
g_sms "Sounds like a plan!"

**(NATHAN FORK END)**

**% SFX:** sms_received
g_sms "Last thing..."
g_sms "Instead of just rotting in bed, just walk around, okay? See you tomorrow"
g_sms "Cya then, big bird!"

n_thought "He's right…"
n_thought "I guess…"

n_thought "Gerald will be here tomorrow."

(go to choose friends choice.)



# Gerald Comes To Apt

@tag: Paragraph_Gerald_Comes_To_Apt

%Short: Gerald comes to Nicolas's apartment.

In: Scene 1.2

## Description
Per Nicolas's acceptance of Gerald's offer, Gerald arrives at Nicolas's apartment the next day. They greet each other warmly, and Nicolas feels a mix of excitement and nervousness about spending time with Gerald.

## Includes
- Section_Linear

- Character: Char_Nicolas
- Character: Char_Gerald

## Script
**% SFX:** door_knock
g "Hey, Nicolas!"
n_narrate "_(He hugs me, embraces me ever so tightly)_"
n_narrate "_(His burly frame presses against mine, and I can feel his warmth.)_"
n_narrate "_(His warm breath tickles my ear as he speaks.)_"
n_narrate "_(I can't help but notice how attractive he has become since we last met.)_"

n_thought "OMG… When did he get so… hot?"

g "Long time no see, huh?"
n "Yeah, I've been avoiding you. Scared of what you think of me."

n "Yeah…"
n_thought "I'm such a coward…"

g "Nicolas, you don’t have to be scared of me. I’m your friend."
g "I’m just happy you reached out."
g "Tell me what’s on your mind."
g "What's with this crazy idea of yours?"

- Gerald sits down on the couch, patting the seat next to him.
- Nicolas hesitates for a moment before sitting down beside him.

n "Well… I’ve been feeling kinda lost lately."
n "I don’t have a job… I was literally fired!"
n "I don’t have any purpose…"

n "So I thought… maybe I should just try talking to people I find interesting."
n "See if I can make new friends…"

g "That’s actually a pretty good idea."
g "I know a few people who might be interested in meeting you."
g "Nathan, for one. You mentioned him, right?"
n "Yeah, Nathan seems nice."

g "Let's head to his shop later, then."
n "Sure, that sounds good."
n "Erm… Yeah…"

n_thought "I can’t believe I’m actually hanging out with Gerald…"
n_thought "My hand would be inching to touch his… but I guess I'm too cautious for now…"

n_thought "Maybe… just maybe… this could be the start of something new."

g "Nick? You okay? You seem a bit… distracted?"
n "Oh, yeah… Sorry. Just… thinking."

g "No worries. Take your time."
n "Thanks, Gerald. I appreciate it."

- They both smile at each other