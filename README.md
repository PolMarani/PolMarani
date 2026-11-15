<div align="center">

# Ciao, sono Paolo Marani 👋
### Software Engineering Student @ 42 Firenze | Backend, System Programming & AI

*"Il modo in cui lavorerai, rispecchierà la tua vita fuori"*

[![Email](https://img.shields.io/badge/Email-marani.paolo99%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:marani.paolo99@gmail.com)
[![Location](https://img.shields.io/badge/Firenze,_Italia-4285F4?style=for-the-badge&logo=google-maps&logoColor=white)](#)
[![42 School](https://img.shields.io/badge/42_Firenze-Level_4.10-000000?style=for-the-badge&logo=42&logoColor=white)](#)

</div>

---

## 👨‍💻 Chi sono

Sono uno sviluppatore software in formazione presso **42 Firenze**, dove affronto quotidianamente sfide di programmazione a basso livello, algoritmica, architetture di sistema e intelligenza artificiale attraverso un approccio pratico e *peer-to-peer*.

Parallelamente al percorso in 42, frequento un **corso serale di Telecomunicazioni**: una scelta nata per unire lo sviluppo software a una comprensione solida delle reti, dei protocolli di comunicazione e delle infrastrutture hardware. 

Mi piace costruire software solido dietro le quinte — dalla gestione della concorrenza in **C** alla persistenza dei dati con **C# / SQL Server** e allo sviluppo in **Python** — senza perdere di vista l'esperienza reale dell'utente davanti allo schermo.

- 🔭 **Attualmente al lavoro su:** `RAG against the machine` (sistemi RAG e LLM) e `NetPractice` (architetture di rete e routing TCP/IP) presso 42 Firenze.
- 📡 **Formazione parallela:** Studente al corso serale di **Informatica e Telecomunicazioni**.
- 🌍 **Lingue:** Italiano (Madrelingua), Inglese (B2), Francese (B1).

---

## 🛠️ Tech Stack & Competenze

### Linguaggi & Database
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL Server](https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

### Framework, Librerie & Strumenti
![.NET / EF Core](https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![Poetry](https://img.shields.io/badge/Poetry-60A5FA?style=flat-square&logo=poetry&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_/_Unix-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

- **System & Concurrent Programming:** POSIX Threads (`pthreads`), Mutex, semafori, scheduling (`FIFO`/`EDF`), gestione della memoria e chiamate di sistema Unix.
- **AI & Data Engineering:** Integrazione LLM, *Function Calling* con *Constrained Decoding* (JSON garantito), architetture RAG, validazione dati con Pydantic.
- **Networking & SysAdmin:** Configurazione reti e subnetting, routing, virtualizzazione e hardening di sistemi Linux.

---

## 🚀 Progetto in Evidenza (Azienda Esterna)

### 🎮 GameVerse — *Terranova Challenge (con 42 Firenze)*
> **Stack:** `C#` • `Entity Framework Core` • `SQL Server` • `UI/UX Iteration`  
> *(Repository privata — progetto realizzato per sfida aziendale)*

<!-- Sostituisci il percorso qui sotto con il link o il file della tua GIF -->
<div align="center">
  <img src="./assets/gameverse-home.gif" alt="GameVerse Home Preview" width="750" />
  <br>
  <em>⬆️ Anteprima della Home di GameVerse (inserisci qui la GIF della tua applicazione)</em>
</div>

**Il mio ruolo e cosa mi ha insegnato questo progetto:**
- **Backend & Persistenza Dati:** Mi sono occupato principalmente della gestione dei preferiti e della loro persistenza su database relazionale utilizzando **SQL Server** ed **Entity Framework Core**.
- **Design & Revisione UI assistita dall'AI:** Sul lato interfaccia ho lavorato con il supporto dell'AI, concentrandomi sul testare il risultato direttamente nel browser e guidare le scelte di revisione in base al comportamento dell'utente:
  - *Risoluzione del taglio immagini:* Nella pagina di dettaglio del gioco la copertina verticale veniva tagliata male occupando tutta la larghezza. Ho scelto di sostituirla con gli screenshot di gioco orizzontali.
  - *Sincronizzazione del caricamento:* Ho fatto in modo che l'animazione di dissolvenza partisse solo quando l'immagine successiva era effettivamente pronta, evitando scatti o schermate vuote.
  - *Tempi contestuali:* Ho impostato tempistiche diverse per due situazioni d'uso distinte: nella **Home** la transizione al passaggio del mouse è rapida per chi vuole dare un'occhiata veloce al catalogo, mentre nella **Pagina di dettaglio** i tempi sono più distesi per permettere all'utente di osservare la scena.

---

## 💻 Progetti Principali @ 42 Firenze

### 🤖 AI, Python & Data Engineering
| Progetto | Descrizione | Competenze Chiave |
| :--- | :--- | :--- |
| **Call Me Maybe** *(Con Bonus)* | Sistema di *Function Calling* per Large Language Models che traduce prompt in linguaggio naturale in chiamate a funzioni strutturate e tipizzate, implementando *constrained decoding* per garantire output JSON validi con un modello da 0.5B parametri. | `Python`, `LLM`, `Constrained Decoding`, `JSON Schema` |
| **Fly-in** *(Con Bonus)* | Sistema di routing per droni autonomi su rete dinamica. Sviluppo di un algoritmo di *pathfinding* concorrente personalizzato che gestisce costi di movimento, zone soggette a restrizioni, colli di bottiglia e prevenzione dei *deadlock*. | `Python`, `Graph Algorithms`, `OOP`, `Optimization` |
| **RAG against the machine** *(In corso)* | Progettazione e sviluppo di un sistema di *Retrieval-Augmented Generation* per interrogare basi di conoscenza strutturate e non strutturate. | `Python`, `RAG`, `Databases`, `OOP` |
| **Python Piscine (Moduli 00–10)** | Percorso intensivo di 11 moduli: dall'OOP e polimorfismo alla gestione dei pacchetti (`Poetry`/`pip`), validazione dati complessa con `Pydantic` e programmazione funzionale avanzata (decoratori, *higher-order functions*). | `Python`, `Pydantic`, `Poetry`, `Design Patterns` |

### ⚙️ System Programming, Concorrenza & Algoritmi (C / Unix)
| Progetto | Descrizione | Competenze Chiave |
| :--- | :--- | :--- |
| **Codexion** | Simulazione concorrente in C in cui più thread competono per risorse condivise limitate. Implementazione di POSIX threads, mutex, variabili di condizione e algoritmi di scheduling (`FIFO`/`EDF`) per prevenire *deadlock* e *starvation*. | `C`, `POSIX Threads`, `Mutex`, `Scheduling` |
| **push_swap** | Algoritmo di ordinamento ad alta efficienza su due stack con un set limitato di istruzioni, ottimizzato per ridurre al minimo il numero di mosse. | `C`, `Sorting Algorithms`, `Data Structures` |
| **A-Maze-ing** | Generatore e visualizzatore grafico di labirinti conformi a vincoli strutturali specifici, sviluppato in team. | `C`, `Graphics`, `Algorithms`, `Teamwork` |
| **Born2beroot** *(Con Bonus)* | Configurazione di un server Linux virtualizzato con criteri rigorosi di sicurezza, partizionamento LVM, firewall, policy SSH e monitoraggio di sistema. | `Linux`, `SysAdmin`, `Virtualization`, `Security` |
| **Libft / ft_printf / get_next_line** | Ricodifica da zero delle funzioni fondamentali della libreria standard C, gestione di funzioni variadiche e lettura bufferizzata da file descriptor multipli. | `C`, `Memory Management`, `Unix I/O` |

---

<details>
<summary>🇬🇧 <b>Read in English (Click to expand)</b></summary>

<br>

# Hi there, I'm Paolo Marani 👋
### Software Engineering Student @ 42 Firenze | Backend, System Programming & AI

*"The way you work will reflect your life outside"*

## 👨‍💻 About Me
I am a Software Engineering student at **42 Firenze**, tackling low-level programming, algorithms, system architecture, and AI engineering through a hands-on, peer-to-peer methodology. 

Alongside my curriculum at 42, I am attending an **evening program in Telecommunications**, bridging software engineering with a strong foundation in computer networks, communication protocols, and infrastructure.

### 🎮 Featured Project: GameVerse (Terranova Challenge)
> **Tech Stack:** `C#` • `Entity Framework Core` • `SQL Server` • `AI-Assisted UI/UX`

Team project built for the **Terranova Challenge** (external company project with 42 Firenze).
- **Database & Backend:** I was responsible for the favorites feature and its persistence layer using **SQL Server** and **Entity Framework Core**.
- **UI/UX Iteration:** I helped refine the game discovery experience through AI-assisted UI iteration and in-browser testing. For example, because vertical box art was poorly cropped when stretched across the game detail page, I switched the layout to use horizontal gameplay screenshots and ensured fade transitions only triggered once the next image was fully preloaded. I also implemented context-aware transition timings: faster previews on home page hover for quick browsing, and slower transitions on the detail page where users take time to observe the scene.

### 💻 Key 42 Projects
- **Call Me Maybe (Bonus):** Function calling in LLMs using constrained decoding to guarantee valid JSON output on a 0.5B parameter model.
- **Fly-in (Bonus):** Autonomous multi-drone routing system in Python with custom concurrent graph pathfinding and deadlock prevention.
- **Codexion:** Concurrent programming in C using POSIX threads, mutexes, condition variables, and FIFO/EDF scheduling algorithms.
- **Born2beroot (Bonus) & NetPractice:** Linux system administration, virtualization, security hardening, and TCP/IP network routing.

</details>

---

<div align="center">
  <b>📫 Contattami:</b> <a href="mailto:marani.paolo99@gmail.com">marani.paolo99@gmail.com</a>
</div>
