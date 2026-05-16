
https://arelyae.itch.io/kunnin-gun
## 1. High-Level Pitch

**Kunnin Gun** is a tension-driven, cinematic 1v1 quick-draw western game. Players face a roster of increasingly deadly gunslingers. Success relies on millisecond reflexes and precise timing. The game heavily emphasizes audio-visual feedback, dynamic music, and cinematic camera work to emulate the classic "Spaghetti Western" standoff.

## 2. Design Pillars

1. **Tension & Release:** The core emotional loop. Agonizing, unpredictable waiting periods (tension) violently interrupted by a split-second action (release).
    
2. **Millisecond Precision:** Gameplay must feel perfectly fair and hyper-responsive. The difference between victory and defeat is measured in fractions of a second.
    
3. **Cinematic Authenticity:** Every duel should feel like a movie scene. The camera acts as an invisible director, cutting to close-ups on eyes, hands, and boots, culminating in a slow-motion climax.
    
4. **Flow State Progression:** Menus and transitions must not break the immersion. Retries and progressing to the next enemy should feel instantaneous.
    

---

## 3. The 3Cs (Character, Camera, Controls)

### Character

- **The Player:** An unnamed gunslinger. Physically rooted in place during the duel. The focus is entirely on mental readiness and physical reaction.
    
- **The Enemies:** A roster of distinct opponents. Each has a unique identity, variable reaction speeds (Fastest/Slowest draw), unpredictable patience (Min/Max wait time), and unique visual/outfit traits.
    

### Camera (The Director)

The camera is entirely automated and acts as a dynamic storyteller.

- **Pre-Duel (Tension):** The camera cuts sequentially through a "Playlist" of cinematic shots (e.g., Wide Shot -> Low Angle Boots -> Extreme Close-Up Eyes). Cuts are driven by either time limits or synchronized to musical beats/markers.
    
- **The Draw (Action):** Snaps to a functional, clear view of the opponent so the player has perfect visual clarity for the cue.
    
- **Resolution (Kill Cam):** Upon a successful hit, the camera violently punches in for a Kill Cam, accompanied by heavy slow-motion (TimeScale drop) to emphasize the impact.
    

### Controls

Inputs are deliberately restricted to hyper-focus the player's attention.

- **The Trigger (Action):** A single input (e.g., Gamepad RT, Keyboard Space/Click) executes the draw/shoot.
    
- **Menu Navigation:** Handled via face buttons (e.g., A to Continue, Y to Retry, X for Hard Restart) to keep the player's hands in the "ready" position rather than navigating UI cursors.
    
- **Haptics:** Controller rumble is strictly tied to the heartbeat of the tension phase, the gunshot, and the rapid counting of the final score screen.
    

---

## 4. Core Gameplay Loop

The loop consists of sequential duels against a predefined roster.

1. **The Standoff:** Player and Enemy face off. Music intensity builds. Camera cuts between dramatic angles.
    
2. **The Wait:** An unpredictable timer (based on the enemy's profile) ticks down.
    
3. **The Signal:** A definitive audio-visual cue fires.
    
4. **The Reaction:** Player must press the Trigger.
    
5. **The Resolution:** Time slows down. The game calculates the outcome.
    
6. **Progression:** The player chooses to Continue (next enemy) or Retry (same enemy).
    

### The Math of the Gunfight

Performance is divided into two distinct metrics:

- **Reflex Time:** How fast the player reacted to the signal.
    
- **Draw Speed:** The mechanical execution of the shot.
    
- **Total Rating:** `Reflex Time + Draw Speed`. Lower is better.
    

---

## 5. Fail States & Rules of Engagement

To prevent players from "spamming" the trigger or guessing, strict penalties are enforced:

- **Death:** The player's Total Rating was slower than the Enemy's Draw Speed. _"Shot through the heart."_
    
- **Dishonorable:** The player pulled the trigger _before_ the signal. Instant failure. _"You fired before the draw."_
    
- **Fumble / Misfire:** The player inputted multiple commands, pressed the wrong button, or mechanically failed the draw. Instant failure. The cinematic camera permanently locks its position to highlight the mistake.
    

---

## 6. Progression & The Roster

Enemies are defined by Enemy Profiles. The game plays as a "Boss Rush."

- **Scaling Difficulty:** Early enemies have slow draw speeds and predictable wait times. Late enemies have boss-level reflexes and agonizingly long or terrifyingly short standoff times.
    
- **Continuous Audio Tension:** As the player defeats enemies, the global "Music Intensity" rises. Defeating an enemy doesn't stop the music; it adds a layer of tension for the _next_ enemy.
    

---

## 7. Audio Design

Audio is half of the game's mechanics.

- **Dynamic Soundtrack:** The music drives the cinematic cuts. The game listens to the music track for specific "Markers" (e.g., a drum beat) to automatically switch camera angles.
    
- **Victory Stingers:** Upon winning, the background music dynamically dips, a triumphant "Stinger" plays (randomized so it doesn't repeat sequentially), and then the music swells to a higher intensity for the next round.
    
- **Typewriter UI:** Enemy names are revealed letter-by-letter, paired with a heavy mechanical typewriter sound to emphasize the "Bounty Poster" aesthetic.
    

---

## 8. Endgame: The Final Score & Leaderboard

Upon defeating the final enemy on the roster, the game enters the Resolution Phase.

1. **The Tally:** The HUD disappears. A cinematic camera takes over.
    
2. **Stat Reveal:** The game calculates the player's **Average Reflex** and **Average Draw** across all valid rounds (excluding fumbles/dishonorable shots).
    
3. **Sensory Reward:** The numbers count up dynamically, accompanied by rapid ticking audio and synchronized controller haptics.
    
4. **The Leaderboard:** Once the final rating is revealed, an online leaderboard appears. The player inputs their name to rank their speed against global gunslingers (Lowest Time = Rank 1). While typing, all reset/gameplay inputs are strictly blocked to prevent accidental loss of score.