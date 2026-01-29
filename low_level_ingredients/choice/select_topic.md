# Choice: Select Topic

@tag: Choice_Select_Topic

%Short: Choose a topic for X character to discuss with a character Y.

## Description
This unit represents a single conversational interaction in which the player selects a topic from a predefined list. Once a topic is chosen, a thread of dialogue unfolds between the player character and another character, potentially revealing information, affecting relationships, or influencing flags.
**Input**: List of selectable topics
**Process**: Player chooses a topic → triggers associated dialogue branch → optional updates to character state or flags
**Output**: Dialogue lines displayed, events or flags modified

## Notes
- Can be mocked independently using placeholder topics and dialogue lines
- Sequence or repetition (choosing multiple topics) is considered a higher-level ingredient built from multiple instances of this unit
- Supports branching: each topic may trigger different dialogue outcomes, but the core mechanic is selection → dialogue thread → optional consequence

# Mock Example

## Job: Select Topic - Nicolas talks to Gerald

**Context**: 
Nicolas is talking to Gerald in his apartment. The player can choose a topic for Nicolas to bring up.

**Choice**: 
Nicolas "What have you been up to lately?"

**Dialogue**:
Nicolas: "Hey Gerald, what have you been up to lately?"
Gerald: "I got a new job at the fish market! It's been great so far."
Nicolas: "That's awesome! I'm happy for you."
Gerald: "Placeholder dialogue continues..."
Nicolas: "Placeholder dialogue continues..."

**Effect**:
- Relationship with Gerald +5
- Flag "Gerald_New_Job" set to True
- Unlock location "Fish Market" in map
- End of interaction
