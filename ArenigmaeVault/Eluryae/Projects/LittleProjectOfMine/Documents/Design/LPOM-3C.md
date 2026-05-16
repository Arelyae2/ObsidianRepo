## Character

### Narration

The character played by the player is **androgynous**, they don't have **pronouns** or defined **names**, the player can choose both when starting the game.

---

It is important that the player never has an official name, the default one is **CP**, for "Character Played" 
The player has an **empty entry point** when starting.

![[nameRegistrationOOT.png|400]]

---

They **don't talk,** **not a mute**, we can only choose dialogue option.


In the **world of the game**, the character is a child of the followers of the **Golden Corruption**
[[LPOM-Narrative Design#Golden Corruption]]

![[GoldenCorruption_1.png|300]]


But they are only half-blood, as the other side was not known to others, but they are child of the **The Greater Ones**
[[LPOM-Narrative Design#Greater Ones]]

![[GreaterOnes_1.png|200]]

**The Greater Ones** decided to act upon seeing that the prophecy of the **Golden Corruption** was being formed with the help of the **Nine Hells**
[[LPOM-Narrative Design#Nine Hells]]

CP was then raised in a small village, learning to **sherp [[LPOM-Narrative Design#Salted Cows|Salted Cows]]**, and defend the village from stealers and other monsters (see more in [[LPOM-Narrative Design#Races & Factions]])

Around **20-25 years old**, they will gladly **help** anyone, especially their loved ones.

They lose their **left arm** at the end of the [[LPOM-Narrative Design#Prologue|Prologue]], and their **right eye** at the end of the [[LPOM-Narrative Design#First Act|First ACT]]

![[LinkLoseArmTPManga.png|400]]

The arm is soon **replaced by a metallic one** made by [[LPOM-Narrative Design#Brennan The Malenaian Traveler|Brennan]] the [[LPOM-Narrative Design#Malenaians|Malenaians]]. And then adapted to contain their first gun during the first temple.

The eye is **later replaced** by the **[[LPOM-Player Design#Eye of truth|Eye of truth]]** found in a temple.

---

For the mecanics, see [[LPOM-Player Design]]

## Camera

We will use the [Cinemachine](https://docs.unity3d.com/Packages/com.unity.cinemachine@3.1/manual/index.html) Unity Package. It is a **Third Person game**, with the ability of targeting enemies and object.

![[OkamiThirdCamera.png|400]]

The camera behavior can also be **modified on certain part of the level** design (see [[#Specific Cases]] for examples).
### General

![[CinemachineFreeLook.png|300]]

The general system will be of a **free look camera** of [Cinemachine](https://docs.unity3d.com/Packages/com.unity.cinemachine@3.1/manual/index.html), the players will be able to freely look around them.

The player move according to the **direction** of the camera.

### Targeting

*Horizontal Offset*

The player has the ability to target enemies and object. This will focus the camera on an **offset either right or left** (depending on the entity position).
![[TargetingAngle1.png|400]]

---

*Circular Offset*

If the player **move to their right**, (see below how), the camera offset will move to the side to put the **player at the right of the screen** sideways, and the entity at the left.
![[TargetingAngle5.png|400]]

If the player **move to their left**, they will be at the left of the screen, and the **entity at the right**.
![[TargetingAngle2.png|400]]

If they **move backward**, they will be at the **center of the screen**, in front of the entity (the *[[#Horizontal Offset]]* still applies).
![[TargetingAngle3.png|400]]

If they move **forward**, they will be at the center of the screen, **behind the entity**.
During this, unless the player applies control over the camera, it will smoothly go **back towards a better angle**.
![[TargetingAngle4.png|400]]

The player will still be **able to control the camera** around them and the entity they target.

---

*Depth Offset*

A third offset will apply as well, the target point will not be the player themselve, but a **point equidistancial to the entity** and the player (with a desired offset itself, playtets will show results).
![[TargetingAngle5.png|400]]

---

In case the player and the entity are far, the camera will concentrate on the **player first and dezoom**.

If they are **too afar**, the targeting will break.

---

**During targeting**, the player will **move in the direction of the camera** still, but will dodge in a **circular shape around the entity** they are targeting.

![[Z-targeting.png|300]]

---
If there is no entity or object to target, the camera will simply focus on the player's back if they turned it around.

### Specific Cases

During certain parts of Dungeon or level design, the architecture and zone will **force** the camera in a certain behavior (spline, static and follow...)

During this time, the player has **no control** over the camera, and still move according to it's direction.

If the player **applies a Targeting** during this time, the camera, will apply the *Depth Offset*, but **nothing more**.

Still during a **targeting**, the camera will **apply a Zoom** if the player is too afar from it.

![[TwilightPrincessCamera.png|600]]
In this example, the camera is set in a **circular motion** according to the stairs to accompany the player.

## Controls

![[ControlsSchemeV1.png|600]]

This scheme is a V1, still to define and test during playtest, there is the *Gang sign* flaw still present, putting the player in a difficult position when they need to orientate the camera, and use one of the main actions button.