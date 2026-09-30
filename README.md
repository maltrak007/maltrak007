# Gonzalo Liñán Aldana — Gameplay Programmer & Technical Designer

*"Lifelong gamer turned creator, dedicated to crafting unique experiences. I aim to contribute to the gaming world by developing titles that offer the same level of immersion and joy that define who I am today."*

**Combat systems · Enemy AI · Game feel** — Unreal Engine 5 · C++ · Blueprints

[LinkedIn](https://www.linkedin.com/in/gonzalo-liñan-aldana-934283221/) · [Steam](https://steamcommunity.com/id/ItsGonso/) · gonza7108@gmail.com

---

## About Me

Gameplay programmer and technical designer with a shipped commercial title on PC and console. I specialise in combat systems — the loop itself, the enemy AI behind it, and the feedback layer that makes it read. Master's Degree in Videogame Programming from U-TAD.

**Engines:** Unreal Engine 5, Unity
**Languages:** C++, C#, Java, PL/SQL
**Specialties:** Combat design, enemy AI and Behavior Trees, Gameplay Ability System, game feel, data-driven architecture

My top 5 games of all time: Fallout New Vegas, The Last of Us, Dark Souls III, Persona 5, The Witcher 3.

---

# 🏆 Featured Projects

## 🐉 The 9th Dragon — Unreleased Commercial Title

**Developer:** FrameOver · **Publisher:** Headup Games
**Platforms:** PC · PlayStation 5 · Xbox Series X|S · Nintendo Switch
**Role:** Gameplay Programmer / Combat Designer (Freelance)
**Tech:** Unreal Engine 5, Blueprints, Behavior Trees, Niagara, Motion Warping

**[▶ Watch the trailer](https://www.youtube.com/watch?v=d5sHUQhCVeY)** · **[View on Steam](https://store.steampowered.com/app/4402330/The_9th_Dragon/)**

[![The 9th Dragon](https://img.youtube.com/vi/d5sHUQhCVeY/maxresdefault.jpg)](https://www.youtube.com/watch?v=d5sHUQhCVeY)

📖 **Description:** A brutal, tactical beat-'em-up set in Kowloon Walled City. Hand-to-hand combat combined with firearms, stamina management and environmental finishers.

🧑‍💻 **What I owned:** The combat pillar, end to end — player mechanics, enemy AI architecture, balancing, tutorials and combat UI — working to publisher milestone feedback through final production.

🛠️ **Key contributions:**

- **Core combat loop** — combo system with input buffering, parry mechanic with unique counterattacks, finisher system gated on enemy state, stamina and vulnerability states.
- **Data-driven ranged architecture** — weapon parameters drive enemy behaviour; a proxy Behavior Tree switches enemies between melee and ranged based on distance and remaining ammunition.
- **Enemy AI refactor** — restructured the Behavior Tree architecture for modularity and centralised subclass logic into a modular enemy base, so any enemy can use any weapon from data tables rather than code. Authored behaviour trees for eight enemy types plus bosses.
- **Game feel layer** — hit-stop on combo enders, camera shake scaled to move strength, slow-motion on finisher impact, variable knockback with chain damage between enemies.
- **Modular spatial detection** — reusable multi-sphere system resolving player, enemy and level geometry, used across combat logic.
- **Balancing** — time-to-kill tuned per enemy type and per level via centralised data tables, producing a progressive difficulty curve.
- **Onboarding** — full tutorial system (15+ tutorials with input validation and completion gating) and collectible-driven combo progression.

---

## 🎮 Ghunter — Best University Game, BIG Conference Bilbao · Second Place, Guerrilla Games Festival

**Role:** AI Programmer & Combat Designer · **Tech:** Unreal Engine 5, C++, GAS, Behavior Trees

**[▶ Official Trailer](https://youtu.be/yjipXpGEbDo)**

[![Ghunter](https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/3156000/5105952d0a260f7972936f0886a1e2f8bd59385f/capsule_616x353.jpg?t=1736967989)](https://youtu.be/yjipXpGEbDo)


📖 An action-adventure cooking game. Uncover the mysteries of Garcosa, hunt your prey, and save the King with your dishes.

🛠️ **Contributions:**
- Architected modular AI using GAS to create scalable enemy abilities and behaviours.
- Implemented Behavior Trees and AI Perception systems for reactive enemy engagement.
- Developed custom behaviour nodes influenced by environmental hazards and enemy stats.
- Created modular library tasks allowing rapid iteration of enemy variants.
- Iterated combat difficulty from structured playtesting, adjusting behaviours, timing windows and stat scaling.

[View Repository](https://github.com/maltrak007/GonzaloLinanGhunterCode) · [Full Project](https://github.com/IsFriskis/ghuntercode)

---

## 🥊 Hobo-League — Solo Project (In Progress)

**Third-Person Multiplayer** · **Tech:** Unreal Engine 5, C++, GAS + Network Replication, Chaos Destruction

📖 Stand up against sadistic machines through the pain of the trials and earn your freedom.

🚩 **Objective:** Deepen architectural skills and multiplayer best practice.

🛠️ **Technical features:**
- Implemented the GAS framework from scratch, building every system around it for seamless iteration between C++ and Blueprints.
- Event-driven architecture applying SOLID principles and explicit C++ memory management.
- Dynamic environments via World Partition and Chaos Destruction, reacting to player actions and physics forces.
- Pre-production planning with Kanban (Miro) and UML diagrams.

[View Repository](#)

---

## 🪄 Monster Evicter — Solo Project

**Third-Person Action** · **Tech:** Unity, C#

📖 A fast-paced game where you play a mage "evicting" enemies by exploiting their weaknesses with spells against the clock.

🛠️ **Technical features:**
- Event-driven component architecture using Singleton, Object Pooling and Flyweight patterns.
- AI state machines built from scratch, linked to animation controllers.
- Custom inspector tools for rapid level design and enemy balancing via ScriptableObjects.
- Modular UI/UX system, JSON save system, and sound manager.
- Full GDD defining pillars, progression, difficulty curve and player engagement systems.

[View Repository](https://github.com/maltrak007/Monster-Evicter)

---

## Educational Projects

[UI Project](https://github.com/maltrak007/Unreal-UI-Project) — Unreal Engine. Industry-standard UI: skill tree, dynamic crosshair, weapon reload bar, ammo indicators, danger warnings.

[Chaos Destruction](https://github.com/maltrak007/Unreal-Physics-Exercises) — Unreal Engine physics experiments.

---

## 🎓 Education

| Qualification | Institution |
|---|---|
| Master's Degree in Videogame Programming | U-TAD, Madrid |
| Programming with Graphic Engine: Unity | RENDR, Seville |
| Higher Technician in Cross-Platform Application Development | CEU San Pablo, Seville |

---

**Open to gameplay programming and combat/technical design roles.** Remote or relocation within the EU.
