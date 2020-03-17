# Game Development
Das Thema 'Game Development beim [PIT-Hackathon 2019](https://github.com/PIT-Hackathon/2019-Infos) umfasst die erste Phase der Spieleentwicklung, von der Erstellung eines Konzepts bis zum lauffähigen Prototypen. Dabei werdet ihr diverse Rolle wie Game Designer, Game Developer, Visual Artist, Audio Engineer uvm. einnehmen und zusammen im Team euer Spiel entwickeln. Dabei bieten wir verschiedene Einstiegsmöglichkeiten in das Thema an.

Schaut euch vor mal dieses Video an:
- [Biggest Game Desing Mistakes](https://www.youtube.com/watch?v=5x4Q_SOLN28)

---

## Vorbereitung auf den Hackathon

### Generell
Je nach eueren Fähigkeiten könnt ihr euch, wenn ihr Lust habt (und das sollte ihr), schon auf den Hackathon vorbereiten. Dazu haben wir für jeden interessante Kurse und Videos zusammen gestellt und erweiteren diese Liste ständig bis zu beginn des Hackathons

Ihr solltet euch auf jeden Fall diese Grundlagen angesehen haben:
- [Unity Interface](https://youtu.be/D7v2pjke5sc)
- [Unity Scripting](https://learn.unity.com/project/beginner-gameplay-scripting?courseId=5d532306edbc2a1334dd9aa8)
- [Unity Prefabs](https://youtu.be/H1OkG3a1w-o)
- [Unity In Depths](https://learn.unity.com/course/teaching-game-design-and-development)

### Unity
Entwicklung mit der Unity3d-GameEngine (einer der führenden Entwicklungsumgebungen für kommerzielle Computerspiele). Hier laden wir euch ein mit echter Industrie-Standard-Software euer Ideen umzusetzen. Eingesetzt wird hier die Scriptsprache C#. Diese Sprache findet auch großen Einsatz, bei der Entwicklung von Unternehmmensapplikationen und nicht wenige der am Hackathon beteiligten Unternehmen setzen auf diese Sprache bei der Entwicklung ihrer Software.
Je nach Erfahrungslevel gibt es hier auch sehr interessante Möglichkeiten, sich auf den Hackathon vorzubereiten:
* Coursera Game Design Spezialisation [https://www.coursera.org/learn/game-development]
* Pluralsight Unity [https://www.pluralsight.com/paths/unity-game-development-core-skills]
* Unity Learn [https://unity3d.com/de/learn]
* Coursera Preparation for Unity Expert Gameplay Programmer Exam [https://blogs.unity3d.com/2018/05/28/now-available-worldwide-unity-certified-programmer/]

### Von uns bereitgestellte Komponenten
Wir stellen ein paar Komponenten bereit, die euch das Leben leichter machen können.
* [einfaches EventSystem für Unity](https://gist.github.com/BernhardRubow/35d8ef9b6cc553ad547adec05210eead)

---
## Vorbereiten des Rechners für die Teilnahme am Hackathon (im Bereich GameDevelopment)

### Notwendige Useraccounts anlegen
* Vor Beginn des Hackathons einen Unity Account anlegen. [Unity3d](https://unity3d.com/de)
* Vor Beginn des Hackathons einen GitHub Account anlegen. [GitHub](https://github.com/)
* Ver Beginn des Hackathons einen Trello Account anlegen. [Trello](https://trello.com)

### Installation von Software
* Unity LTS-Version 2018.4.3.f1 installieren: [Download](https://download.unity3d.com/download_unity/8a9509a5aff9/UnityDownloadAssistant-2018.4.3f1.exe)
* Git installieren: [[Download]](https://git-scm.com/)
* Visual Studio Code installieren: [[Download]](https://code.visualstudio.com/)
* In Visual Studio Code folgende Plugins installieren
  * [C#] von Microsoft
  * [Debugger for Unity] von Unity Technologies
  * [Unity Tools] von Tobiah Zarlez
  
---

## Themengebiete
Als Themengebiete auf die sich die Mentoren besonders vorbereiten wurden für diesen Hackathon die Bereiche :
#### Begleitung bei Einstieg in die Spieleentwicklung (ohne Programmierkenntnisse)
*Für Anfänger*
* Heranführung an die Spieleprogrammieung mit Hilfe eines Tutorials
* fertiges Spiel, welches sich nachher noch durch durch features erweitern läßt

#### Begleitung bei Einstieg in Unity (mit Programmierkenntnissen)
*Mit ersten Programmierkenntnisssen*
* Prüfung der Spielidee auf Durchführbarkeit 
* Unterstützung bei Ausarbeitung des GDD
* erste Software-Design-Patterns (SOLID, Publish&Subscribe)
* Tools (git)

#### Begleitung bei Einstieg in Unity unter Verwendung von Software Design Patterns 
*Fortgeschrittene*
* Prüfung der Spielidee auf Durchführbarkeit 
* Unterstützung bei Ausarbeitung des GDD
* Unterstüzung bei autretenden Problemsitiation
* Fortgeschrittene Tools unter Unity (z.B Profiler)
* fortgeschrittene Software-Design-Patterns (z.b Dependency Injection)
* Software-Testing
* Tools (z.B. Unity-Collaborate, Trello, Hack&Plan)

---

## SourceCode-Repositories

### Unity
* [Level 100 - Pathfinding with NavMesh](https://github.com/BernhardRubow/example_unity_0002_nav_mesh)
* [Level 100 - Basic techniques in Unity](https://github.com/BernhardRubow/example_unity_0005_tutorials)
* [Level 300 - Regeln nach Command-Pattern](https://github.com/BernhardRubow/019_boardgame_rules_tdd)
* [Level 300 - Zong Mobile Game](https://github.com/BernhardRubow/games-013_zong)
* [Tool - ScriptTemplateFile](https://gist.github.com/BernhardRubow/e088a4e43fc36245bca067b1fc48a86e)

---

## Womit entwickeln wir nachher?
Im Rahmen des Hackathons verwenden wir folgende Tools für die Entwicklung. Diese könnt ihr vorab auf eueren Geräten installieren oder wir machen das zu Beginn des Hackathons.

### 1. Git - Source Code Verwaltung 
Wir wollen hier entwickeln, also machen wir es von Anfang an richtig. Da ist eine Versionsverwaltung ein Muss und keine Option. Damit könnt ihr jederzeit Nachvollziehen, wer was geändert hat und im idealen Fall können Änderungen ohne Probleme zusammengefasst werden. Wenn es dann doch mal einen Konflikt gibt, dann wird GIT euch den entsprechenden Bereich markieren und ihr könnte bequem (abhängig vom Editor) entscheiden welche Änderung übernommen werden soll. 
* Download: [https://git-scm.com](https://git-scm.com)
* Anleitung: [tryGit - learn git in 15 minutes](https://try.github.io/levels/1/challenges/1)
* MOOC: [Wie man Git und GitHub nutzt](https://de.udacity.com/course/how-to-use-git-and-github--ud775)
* Anleitung: [Unity für Git konfigurieren](https://thoughtbot.com/blog/how-to-git-with-unity)

### 2. Code Editor 
Ihr benötigt einen Text Editor um den Source Code schreiben zu können. Am besten einen mit Syntax Highlight, Code Vervollständigung und Validierung. Unser Vorschlag: Visual Studio Code 
* Download: [https://code.visualstudio.com]

### 3. Unity3d
* Download: [https://unity3d.com/de/unity/qa/lts-releases] Unity LTS 2018.4.3f1

### 4. Trello
Um im Team zusammenarbeiten zu können und immer überblick über das Projekt zu haben, setzen wir ein sehr einfaches aber extrem mächtiges Werkzeug ein. Trello ist ein sog. Kanban-Board mit dem man auf unkomplizierte Weise ein Projekt steuern kann. Diese Tool ist kostenlos.

---

## In welchen Rollen werden wir an dem Spiel arbeiten?
Ihr werdet eine oder mehrere der folgenden Rollen bei der Entwicklung einnehmen.

### Game Designer
Der Game Designer einwickelt eine Vision des Spiels. Er beschreibt was der Spieler in dem Spiel unternehmen kann, welche Charaktere er treffen wird und welche Entscheidungen er treffen kann. Alle Optionen und sämtliche Interaktionen werden durch den Game Designer definiert.

### Game Developer
Als Game Developer setzt ihr die Ideen des Game Designer technisch um. Dafür werden diverse Kompontenten wie Physik, Grafik Engine, AI uvm. entwickelt oder integriert.

### Visual Artist
Der Visual Artist erstellt alle visuallen Element, wie 3D Modelle, Texturen, Materialien und Effekte, für das Spiel.

### Post Processing Artist
Der Post Processing Artist kümmert sich um alle Effect, die nicht direkt im Spiel implementiert werden, sondern er nachdem der aktuelle Frame berechnet worden ist (Post Processing) auf das fertige FrameBild berechnet werden, wie z.B. Color Grading, Motion Blur und viele andere Effekte.

### Audio Engineer
Der Audio Engineer ist vergleichbar mit dem Visual Artist, nur das dieser statt Grafiken Geräusche erstellt. Dazu gehören neben Effekten auch die Hintergrund Musik, der Sound Track und vertonte Dialoge.

### Animator
Der Animator erweckt die 3D Modelle des Visual Artist zum Leben.

### Level Designer
Der Level Designer kombiniert die visuellen und akustischen Komponenten und erstellt damit ein Level für das Spiel. 

### Producer
Der Producer steuert und überwacht den Erstellungsprozess des Spiels (auch Finanziell).

### QA Tester
Die QA bestätigt die Qualität des Spiels und zeigt Mängel (Bugs) auf.

---


## Tutorials & Anleitungen

- Tutorials Spieleentwicklung:
    - [unity3d.college (Dragons)](https://www.youtube.com/playlist?list=PLB5_EOMkLx_WCGalAUeKXA1I-qQqYY_Sk)
    - [Unity Basics (Grundlagen)](https://learn.unity.com/course/unity-basics?language=en)
- Massiv Open Online Courses (MOOC) zu Gamedesign und Gamedevelopment
    - [edX : 5 teiliger Kurs zu Gamedesign & -development](https://www.edx.org/xseries/video-game-design)
    - [studyToLearn: Kurs zu Konzepten im Gamedesign](https://www.open2study.com/courses/concepts-in-game-development)
    - [coursera: Game Design and Development Specialization](https://www.coursera.org/specializations/game-development)
    - [coursera: Game Design Art and Concepts Specialization](https://www.coursera.org/specializations/game-design)
    - [und natürlich: ExtraCredits](https://www.youtube.com/user/ExtraCreditz)
    - [Unity Certified Programmer Exam Preparation](https://www.coursera.org/specializations/unity-certified-programmer)
- Tools
    - [Jesse Schell: A book of lense (Android App)](https://play.google.com/store/apps/details?id=com.schellgames.deckoflenses&hl=de)
    - [MDA Framework: A Formal Approach to Game Design and Game Research](http://www.cs.northwestern.edu/~hunicke/MDA.pdf)
- Game Design Documet (Vorlage)
    - [High Concept Document Template](https://www.dropbox.com/s/cit5rsx8f5d5o6b/HighConceptTemplate.pdf?dl=0)
    - [One Page Game Design Document Template](https://www.dropbox.com/s/xfmzl2d64teinre/OnePageGameDesignDocument.pdf?dl=0)
    - [Game Story Bible Template](https://www.dropbox.com/s/hapw4l0bev115r5/GameStoryBibleTemplate.pdf?dl=0)
- Software
    - [Autodesk 3ds Max (Educational)](http://www.autodesk.com/education/free-software/3ds-max)
    - [Autodesk Maya (Educational)](https://www.autodesk.com/education/free-software/maya)
- Texturen
    - [CG Textures](http://www.cgtextures.com/)
    - [Texture King](http://www.textureking.com)
    - [Stock Textures](http://stocktextures.com/)
- Farbgestaltung
    - [Adobe Color](https://color.adobe.com/de/create/color-wheel/)
    - [Color Lovers](http://www.colourlovers.com/)
- Audio Assets
    - [Übersicht über Seiten mit freier Musik für Spiele](https://v-play.net/game-resources/free-music-for-games)
    - [Übersicht über Seiten mit freien SoundFX für Spiele](https://v-play.net/game-resources/16-sites-featuring-free-game-sounds#_noiseforfun.com/)
    - [ZapSplat Free Effects and Music](https://www.zapsplat.com)
    - [Flashkit](http://www.flashkit.com/soundfx/)
    - [Indie Game Music](http://indiegamemusic.com/)
    - [Jamendo](http://www.jamendo.com/)
    - [Free Sound Effects](http://www.freesoundeffects.com/)
    - [Free Sound Project](https://freesound.org/)
- Models
    - [TurboSquid](http://www.turbosquid.com/Search/?KEYWORD=Free)
    - [Archive 3d](http://www.archive3d.net)
    - [3d Xtras](http://www.3dxtras.com/index.asp)
    - [Artist-3d](http://www.artist-3d.com/)
    - [Exchange 3d](http://www.exchange3d.com/FreeModels/cat_35.html)
- Coding Challanges
    - [CodeWars](https://www.codewars.com/)
    - [Codeacademy](https://www.codecademy.com/)
    - [Zoombowi](https://zoombowi.com/)
    - [exercism.io](http://exercism.io/)
    - [freeCodeCamp](https://www.freecodecamp.com/)
    - [TreeHouse](https://teamtreehouse.com/)
    - [Hackr.io](https://hackr.io/)
    - [W3Schools](http://www.w3schools.com/)
    - [CodinGame](https://www.codingame.com/)
    - [The Odin Project](http://www.theodinproject.com/)
    - [Codeeasy](http://codeasy.net/)
    - [LiveEdu.tv](https://www.liveedu.tv/)
- interessante kostenfreie assets aus dem Assetstore
    - [Prototyping](https://assetstore.unity.com/packages/tools/level-design/yume-free-77387)

## Cheat Sheets (Merkblätter über die wichtigsten Befehle und Funktionen eine Software)

- [Unity3d-CheatCheat](https://www.raywenderlich.com/227-unity-cheat-sheet-and-quick-reference-2018)
- [MarkDown-CheatCheat](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Git-CheatCheat](https://www.git-tower.com/blog/git-cheat-sheet/)
- [MS Code-CheatCheat](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)

