# **VISUAL NOVEL OPENING ROOM – FUNGUS VERSION**

**Characters:** Kitty Pryde, Illyana Rasputin
**Room:** X-Mansion Common Room
**Flow:** All dialogue organised into **BLOCKS** for Fungus

---

# **BLOCK 0 — ENTRY**

**KITTY:**
“Hey! You must be the new student everyone’s talking about. Welcome to Xavier’s School for Gifted Youngsters!”

**ILLYANA:**
“Don’t worry. The name sounds dramatic, but most of us are mostly normal. On a good day.”

**KITTY:**
“If you want to ask questions or head to another room, just let us know!”

**PLAYER CHOICES:**

1. **“Could you repeat that?”** → **BLOCK 1**
2. **“What’s in this room?”** → **BLOCK 2**
3. **“What should I do next?”** → **BLOCK 3**
4. **“I think I’ll look around on my own.”** → **BLOCK 4 (Exit)**

---

# **BLOCK 1 — REPEAT INTRO**

**KITTY:**
“Of course! Welcome to Xavier’s School. Illyana and I are here to help you settle in.”

**ILLYANA:**
“You can ask about the room, the school, or what to do next.”

→ **Return to BLOCK 0 Choices**

---

# **BLOCK 2 — WHAT’S IN THIS ROOM?**

**KITTY:**
“This is the main common room! Students chill here between training sessions and classes.”

**ILLYANA:**
“There’s also a teleport circle behind the bookshelf. Avoid it unless you enjoy surprise trips to another dimension.”

**KITTY:**
“Don’t worry, nothing in here bites. Usually.”

**PLAYER CHOICES:**

1. **“Tell me more about training sessions.”** → **BLOCK 2A**
2. **“What’s on the bulletin board?”** → **BLOCK 2B**
3. **“Thanks, that helps.”** → Return to **BLOCK 0**

---

## **BLOCK 2A — TRAINING SESSIONS INFO**

**ILLYANA:**
“Training includes combat drills, teamwork exercises, danger simulations… the usual.”

**KITTY:**
“And sometimes I phase everyone through walls! For tactical education. Mostly.”

→ **Return to BLOCK 0**

---

## **BLOCK 2B — BULLETIN BOARD INFO**

**KITTY:**
“It has schedules, announcements, and about twenty complaints about stolen snacks.”

**ILLYANA:**
“Someone keeps taking my energy bars. If you see anything, tell me.”

→ **Return to BLOCK 0**

---

# **BLOCK 3 — WHAT SHOULD I DO NEXT?**

**KITTY:**
“You should explore! Get a feel for the place.”

**ILLYANA:**
“Other students are around. Each room has someone interesting to talk to.”

**KITTY:**
“You can head to the **Training Wing**, the **Library**, or the **Courtyard**.”

**ILLYANA:**
“And please don’t blow anything up. That’s usually someone else’s job.”

**PLAYER CHOICES:**

1. **“Where’s the Training Wing?”** → **BLOCK 3A**
2. **“What’s the Library like?”** → **BLOCK 3B**
3. **“Who’s in the Courtyard?”** → **BLOCK 3C**
4. **“Okay, I’ll explore.”** → **BLOCK 4 (Exit)**

---

## **BLOCK 3A — TRAINING WING INFO**

**KITTY:**
“It’s down the hall to the left — huge metal doors, dramatic lighting. Very ‘superhero school’.”

**ILLYANA:**
“If you hear explosions, ignore them.”

→ **Return to BLOCK 0**

---

## **BLOCK 3B — LIBRARY INFO**

**ILLYANA:**
“The Library is super chill.”

**KITTY:**
“It’s a great place to study and meet students who take learning seriously.”

**ILLYANA:**
“Pffft... Nerds.”

→ **Return to BLOCK 0**

---

## **BLOCK 3C — COURTYARD INFO**

**KITTY:**
“The Courtyard is great for relaxing.”

**ILLYANA:**
“...But sometimes the teachers get too competetive in their basketball practice. Best to give it a miss if you hear a fight break out”

**KITTY:**
“She’s joking. Mostly.”

→ **Return to BLOCK 0**

---

# **BLOCK 4 — EXIT ROOM**

**KITTY:**
“Have fun exploring! If you need us again, we’ll be right here.”

**ILLYANA:**
“Good luck, new student.”

→ **Transition to Room Selection**

---

# **FUNGUS FLOW SUMMARY**

```
BLOCK 0: Intro
 ├─ BLOCK 1: Repeat Intro → back
 ├─ BLOCK 2: What's in this room?
 │     ├─ BLOCK 2A: Training Info → back
 │     └─ BLOCK 2B: Bulletin Info → back
 ├─ BLOCK 3: What should I do next?
 │     ├─ BLOCK 3A: Training Wing → back
 │     ├─ BLOCK 3B: Library → back
 │     └─ BLOCK 3C: Courtyard → back
 └─ BLOCK 4: Exit
```
