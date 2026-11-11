<!-- ============ HEADER ============ -->


<p align="center">
  <a href="https://github.com/akutsner">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=2C9BD6&center=true&vCenter=true&width=620&lines=Senior+CS+major+%40+Ithaca+College;Building+fast%2C+dependable+software;Computer+vision+%C2%B7+ML+%C2%B7+systems;Open+to+new-grad+%26+internship+roles" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/alec-kutsner-64001a397"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <img src="https://img.shields.io/badge/Graduating-May_2027-2c5364?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Graduating May 2027"/>
  <img src="https://img.shields.io/badge/Location-Ithaca,_NY-203a43?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Ithaca, NY"/>
  <img src="https://komarev.com/ghpvc/?username=akutsner&style=for-the-badge&color=0f2027&label=Profile+views" alt="Profile views"/>
</p>

---

## About me

```python
class Alec:
    def __init__(self):
        self.school    = "Ithaca College"
        self.major     = "Computer Science"
        self.graduates = "May 2027"
        self.location  = "Ithaca, NY"
        self.focus     = ["Systems Engineering", "Software Engineering"]
        self.into      = ["real-time input", "data pipelines", "clean, testable design"]
        self.seeking   = "New-grad / entry-level & internship roles"

    def philosophy(self):
        return "Understand how the pieces fit together, then make them fast and dependable."
```

- Building projects at the intersection of **computer vision, machine learning and interactive software**
- Drawn to systems work: I like knowing what's happening *under* the abstraction
- I care about **testable, class-based design**: most of my projects ship with tests and a UML or architecture diagram
- Comfortable on team projects: NeuroPedal was a collaboration where I owned the full ML pipeline

---

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Quinnsmitth/NeuroPedal">NeuroPedal</a></h3>
      <p><b>Deep learning for guitar effects.</b> Listens to a guitar recording and predicts the pedal's <b>drive</b> and <b>tone</b> settings that produced it.</p>
      <ul>
        <li>Audio → mel spectrogram → single-channel <b>ResNet34</b> regression</li>
        <li>Smooth L1 loss, Adam with LR scheduling</li>
        <li>PyQt5 GUI for running predictions</li>
        <li><i>My role:</i> preprocessing, model adaptation, training & inference</li>
      </ul>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/librosa-4B8BBE?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/PyQt5-41CD52?style=flat-square&logo=qt&logoColor=white"/>
      <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/akutsner/HandTrackingWordle">HandTrackingWordle</a></h3>
      <p><b>Wordle you play in the air.</b> A webcam tracks your hand in real time; your index finger becomes the cursor on an on-screen keyboard.</p>
      <ul>
        <li>Tracks <b>21 hand landmarks</b> per frame with MediaPipe</li>
        <li>Gesture rules: point to type, make a fist to clear</li>
        <li>Frame-based debouncing for reliable key presses</li>
        <li>Built in steps: shape demo → virtual keyboard → full game</li>
      </ul>
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
      <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/akutsner/PokemonGame">PokemonGame</a></h3>
      <p><b>Flask web app and Pygame battle game</b> powered by live PokéAPI data.</p>
      <ul>
        <li>REST calls to PokéAPI for stats, types, species and items</li>
        <li>Object-oriented core: <code>Pokemon</code>, <code>PokemonTeam</code>, <code>Fight</code>, <code>Game</code></li>
        <li>Designed with a UML diagram first</li>
        <li><code>unittest</code> suites with JSON fixtures that stand in for API calls</li>
      </ul>
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
      <img src="https://img.shields.io/badge/Pygame-3B7A2A?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=postman&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/akutsner/TurtleMaze">TurtleMaze</a></h3>
      <p><b>Maze generator and solver</b> drawn live with turtle graphics.</p>
      <ul>
        <li>Modified <b>depth-first search</b> with backtracking</li>
        <li>Makes "perfect" mazes: exactly one path between any two cells</li>
        <li>Solve mode draws the route from start to finish</li>
        <li>"Strange" mode for chaotic, winding corridors</li>
      </ul>
      <img src="https://img.shields.io/badge/Algorithms-DFS-8A2BE2?style=flat-square"/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
    </td>
  </tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br>

| Project | Description |
|---|---|
| [RomanNumeral](https://github.com/akutsner/RomanNumeral) | Two-way Roman numeral ↔ integer converter. Checks subtractive pairs and rejects malformed input, with a test script. |

</details>

---

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,c,js,ts,react,mysql&perline=7" alt="Languages"/>
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=pytorch,opencv,flask,qt&perline=7" alt="Frameworks"/>
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=git,github,linux,vscode,pycharm&perline=7" alt="Tools"/>
</p>

| Category | Skills |
|---|---|
| **Languages** | Python · Java · C · JavaScript · SQL · React Native · JSON |
| **ML / Vision** | PyTorch · torchvision · librosa · MediaPipe · OpenCV · NumPy |
| **App / Game** | Flask · Pygame · PyQt5 · PIL |
| **Practices** | Unit testing · OOP design · UML (draw.io) · REST APIs · Git workflows |
| **Tools** | Git · GitHub · Linux · Jupyter · VS Code · PyCharm · QGIS |

---



## Currently learning

| Topic | Why |
|---|---|
| **Computer networking** | How packets actually get from A to B, and what breaks along the way |
| **Relational databases & SQL** | Schema design, indexing and query performance |
| **TypeScript** | Type-safe front-end and tooling work |
| **LLMs** | How they work under the hood and how to build reliable tools on top of them |

---

## What I'm looking for

I'm looking for **new-grad, entry-level or internship roles** in **systems or software engineering**, especially teams that build performance-sensitive, dependable software. I'm happy to dig into unfamiliar codebases, debug the hard stuff and write the tests that keep it fixed.

---

## Let's connect

<p align="center">
  <a href="https://www.linkedin.com/in/alec-kutsner-64001a397"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/akutsner"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" alt="footer"/>
</p>
