⚔️ Santhosh Lukka 🔱 Unreal Engine 5 C++ Developer | Gameplay Programmer 🩸 Building AAA-grade combat, traversal, and AI systems from scratch — 500+ commits deep.

💀 About Me

3rd year CSE student at MANIT Bhopal, on a self-directed path to becoming a Gameplay Programmer at AAA studios.

My work is engine-level, architecture-first C++ — not surface-level Blueprint scripting. I build systems the way studios actually build them: data-driven, event-driven, ownership-conscious.

🎯 Long-term: AAA studio (Rockstar / Ubisoft / Larian) → DigiPen MSCS → international studio → my own 3D game studio.

🗡️ Projects
⚔️ CombatLearning — Flagship

A full GAS Action RPG combat framework in UE5 C++. 450+ commits. Every system built from scratch.

Combat & Abilities

Full damage pipeline — GameplayEffectSpecHandle with curve-based damage scaling
Directional hit-react system
Ability cooldown system with UI integration
Hero special abilities with data-driven ability info (icons, tags, input bindings)
Block / counter system, target lock-on
Posture & rage systems — rage invincibility via ActivationBlockedTags
Motion warping integrated into combat
Weapon-socket-driven hit VFX pipeline via GameplayCueNotify_Static + Niagara parameters

Traversal & Locomotion

Custom climbing movement mode built on UCharacterMovementComponent — surface-normal snapping, cross-product-derived wall-space movement axes, dot-product exit detection
Direction-agnostic hop system — single generic probe function covering all four directions, dot-product classification, motion-warped traversal to traced impact points
Procedural hand/foot IK through Control Rig — per-effector hit gating with offset reset, no stale-target artifacts

Enemy AI & Boss Fights

🔥 Three complete boss fights — Glacier Mage, Guardian, and Frost Giant with full phase transitions, hand-tuned for soulslike aggression
EQS-driven enemy positioning and decision-making
Custom native BTTasks, BTServices, and BTDecorators
Async enemy spawning pipeline

Architecture

Event-driven UI — attribute changes pushed from PostGameplayEffectExecute through a UI component via interfaces and TWeakObjectPtr, zero polling
Data-driven inventory system built as a standalone plugin
Interface-driven death and interaction pipelines

🔗 https://github.com/Santhoshlk/CombatLearning

🕯️ Ashes Beyond the Grave — Foundation Project

My first UE5 C++ project — third-person action combat foundations: light attack combos, weapon collision handling, custom ASC setup with input-tag-driven activation, and native Behavior Tree architecture. The project where the fundamentals were forged.

🔗 https://github.com/Santhoshlk/AshesBeyondTheGrave

🧠 CppAdvancedLearning

Systems C++ study repo — advanced memory semantics and concurrency, written and tested by hand rather than read.

🔗 https://github.com/Santhoshlk/CppAdvancedLearning

📖 kingC

C from the ground up via K.N. King, building toward a from-scratch software renderer.

🔗 https://github.com/Santhoshlk/kingC

⚡ Tech Stack

Engine: Unreal Engine 5 (C++ primary)

Gameplay Ability System — custom GEExecutions, AttributeSets, ASC architecture
Custom movement modes via UCharacterMovementComponent extension
Control Rig, Full Body IK, procedural animation
Enhanced Input + Gameplay Tags
Behavior Trees, EQS, Blackboards — native C++ AI
Animation Blueprints, Linked Anim Layers, Motion Warping
Niagara VFX, MetaSounds

Languages: C++ (primary) · C

Concurrency: std::thread / jthread, mutexes and lock types, condition variables, futures and promises

IDEs: JetBrains Rider (Unreal) · Visual Studio 2026 (C++) · CLion (C)

🎯 Current Focus
⚔️ Climbing & traversal systems — Vince Petrelli's advanced course, complete
🧵 C++ Concurrency — threading, synchronisation primitives, futures
🛠️ Udacity C++ Nanodegree — project track
📐 Math for game developers — Freya Holmér's series, applied in Unreal

🗺️ Up next: rendering arc — shaders, OpenGL, and a software renderer from scratch. Then Squad AI: an original squad-based tactical AI project.

📊 GitHub Stats

Show Image Show Image

📫 Connect

📧 lukksanthosh@gmail.com
