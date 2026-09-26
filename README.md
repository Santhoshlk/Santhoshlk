<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:3b0a0a,100:8b0000&height=210&section=header&text=Santhosh%20Lukka&fontSize=58&fontColor=f5f5f5&fontAlignY=36&desc=UE5%20C%2B%2B%20Engineer%20%E2%9F%A1%20Real-Time%20Rendering&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/Santhoshlk">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=C0392B&center=true&vCenter=true&width=620&lines=%E2%9A%94%EF%B8%8F+GAS+combat+%26+soulslike+boss+fights;%F0%9F%94%A6+OpenGL+renderer+built+from+the+ground+up;%F0%9F%A7%97+Custom+climbing+on+the+Character+Movement+Component;%F0%9F%A9%B8+550%2B+commits.+Every+line+typed+by+hand." alt="typing banner"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenGL_4.5-5586A4?style=for-the-badge&logo=opengl&logoColor=white"/>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black"/>
  <img src="https://img.shields.io/badge/GLSL-8B0000?style=for-the-badge"/>
</p>

---

## 💀 About Me

```cpp
struct SanthoshLukka
{
    const char* Role     = "3rd-year CSE @ MANIT Bhopal";
    const char* Path     = "Self-directed: UE5 production C++  +  real-time rendering";
    const char* Style    = "Architecture-first. Data-driven. Event-driven. Ownership-conscious.";
    const char* NotThis  = "Surface-level Blueprint scripting";
    int         Commits  = 550; // and climbing
};
```

> 🔱 **The goal:** an Unreal developer who understands the GPU all the way down.
>
> 🎯 **Long-term:** AAA studio (Rockstar / Ubisoft / Larian) ➜ **DigiPen MSCS** ➜ international studio ➜ **my own 3D game studio**

---

## ⚔️ Flagship — CombatLearning

<p>
  <a href="https://github.com/Santhoshlk/CombatLearning"><img src="https://img.shields.io/badge/REPO-CombatLearning-8B0000?style=flat-square&logo=github"/></a>
  <img src="https://img.shields.io/badge/commits-300%2B-C0392B?style=flat-square"/>
  <img src="https://img.shields.io/badge/GAS-Action_RPG-0E1128?style=flat-square&logo=unrealengine"/>
</p>

A full **Gameplay Ability System** action-RPG combat framework in UE5 C++. Every system built by hand.

<table>
<tr>
<td width="50%" valign="top">

### 🗡️ Combat & Abilities
- Damage pipeline — `GameplayEffectSpecHandle` + curve-based scaling
- Directional hit-react system
- Cooldowns wired into the UI
- Hero specials with data-driven ability info *(icons, tags, input)*
- Block / counter / parry + target lock-on
- Posture & rage — rage invincibility via `ActivationBlockedTags`
- Motion warping woven into combat
- Socket-driven hit VFX via `GameplayCueNotify_Static` + Niagara params

</td>
<td width="50%" valign="top">

### 🧗 Traversal & Locomotion
- Custom climbing movement mode on `UCharacterMovementComponent`
  - surface-normal snapping
  - cross-product wall-space axes
  - dot-product exit detection
- Direction-agnostic hop — one generic probe for all four directions, motion-warped to traced impact points
- Procedural hand/foot IK in Control Rig — per-effector hit gating, no stale targets

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔥 Enemy AI & Bosses
- **Three full boss fights** — ❄️ Glacier Mage · 🛡️ Guardian · 🧊 Frost Giant, with phase transitions tuned for soulslike aggression
- EQS-driven positioning and decisions
- Native C++ `BTTask` / `BTService` / `BTDecorator`
- Async enemy spawning pipeline

</td>
<td width="50%" valign="top">

### 🏛️ Architecture
- Event-driven UI — attributes pushed from `PostGameplayEffectExecute` through interfaces + `TWeakObjectPtr`, **zero polling**
- Data-driven inventory built as a standalone plugin
- Interface-driven death & interaction pipelines

</td>
</tr>
</table>

---

## 🗂️ Projects at a Glance

| | Project | Built with | What it is | Status |
|:-:|:--|:--|:--|:-:|
| ⚔️ | [**CombatLearning**](https://github.com/Santhoshlk/CombatLearning) | `UE5` `C++` `GAS` | Soulslike action-RPG combat framework — three boss fights with phase transitions, parry & posture, custom climbing on the CMC, EQS + native BT enemy AI, zero-polling event-driven UI | ![](https://img.shields.io/badge/-Shipped-2ea44f?style=flat-square) |
| 🔦 | **Umbra** <!-- add repo link --> | `C++` `OpenGL 4.5` `GLSL` | My OpenGL renderer — tagged single-file shader parser, compile + link error reporting, DSA indexed drawing, its own abstraction layer, ImGui tooling. Lighting & shadow maps underway | ![](https://img.shields.io/badge/-Active-e9a21f?style=flat-square) |
| 🧠 | [**CppAdvancedLearning**](https://github.com/Santhoshlk/CppAdvancedLearning) | `C++20` | Systems C++ — memory semantics, threads, locks, condition variables, futures & promises, every example written and tested by hand | ![](https://img.shields.io/badge/-Complete-2f5bea?style=flat-square) |
| 📖 | [**kingC**](https://github.com/Santhoshlk/kingC) | `C` | C from the ground up via K.N. King — pointers, strings, structs, preprocessor — the groundwork for a software rasterizer | ![](https://img.shields.io/badge/-Ongoing-e9a21f?style=flat-square) |

---

## ⚡ Tech Stack

<table>
<tr><td><b>🎮 Engine</b></td><td>

`GAS` — custom GE Executions, AttributeSets, ASC architecture  
`CMC` — custom movement modes  
`Control Rig` · `Full Body IK` · `Motion Warping` · `Linked Anim Layers`  
`Enhanced Input` · `Gameplay Tags` · `CommonUI`  
`Behavior Trees` · `EQS` · `Blackboards` — native C++ AI  
`Niagara` · `MetaSounds`

</td></tr>
<tr><td><b>🔦 Graphics</b></td><td>

`OpenGL 4.5` · `GLSL` · `GLFW` · `GLEW` · `GLM` · `ImGui`

</td></tr>
<tr><td><b>🧵 Systems</b></td><td>

`std::thread` / `jthread` · mutexes & lock types · condition variables · futures & promises

</td></tr>
<tr><td><b>🛠️ Tools</b></td><td>

<img src="https://img.shields.io/badge/Rider-000000?style=flat-square&logo=rider&logoColor=white"/>
<img src="https://img.shields.io/badge/Visual_Studio_2026-5C2D91?style=flat-square"/>
<img src="https://img.shields.io/badge/CLion-000000?style=flat-square&logo=clion&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>

</td></tr>
</table>

---

## 🎯 Current Focus

| | Track | Now |
|:-:|:--|:--|
| 🔦 | **Rendering** | Umbra — Cherno's OpenGL series + Ben Cook + LearnOpenGL: batch rendering, every lighting type, omnidirectional shadow maps |
| 🖼️ | **Unreal UI** | CommonUI — Vince Petrelli's Advanced Frontend UI: widget stacks, a GameInstance UI subsystem, options tabs, input routing |

✅ **Recently wrapped:** Vince Petrelli's climbing & traversal course · C++ concurrency block

## 🗺️ Up Next

```
🧊 Voxel terrain renderer ──► 🕹️ Pikuma 2D game engine (ECS + Lua)
                           └─► 🔺 3D software renderer in C
                                        │
                                        ▼
            ⚙️ Hazel engine ──► 🧠 Squad AI ──► 🌐 Multiplayer GAS
```

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Santhoshlk&show_icons=true&theme=radical&hide_border=true&count_private=true"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Santhoshlk&layout=compact&theme=radical&hide_border=true"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Santhoshlk&theme=radical&hide_border=true"/>
</p>

---

## 📫 Connect

<p align="center">
  <a href="mailto:lukksanthosh@gmail.com"><img src="https://img.shields.io/badge/Email-lukksanthosh@gmail.com-8B0000?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8b0000,50:3b0a0a,100:0d0d0d&height=110&section=footer" width="100%"/>
</p>
