# Ciao, sono Paolo Marani 👋

### Software Engineering Student @ 42 Firenze | Backend, System Programming & AI

*"Il modo in cui lavorerai, rispecchierà la tua vita fuori"*

## 👨‍💻 Chi sono

Sono uno sviluppatore software in formazione presso **42 Firenze**, dove affronto quotidianamente sfide di programmazione a basso livello, algoritmica, architetture di sistema e intelligenza artificiale attraverso un approccio pratico e *peer-to-peer*.

Parallelamente al percorso in 42, frequento un **corso serale di Telecomunicazioni**: una scelta nata per unire lo sviluppo software a una comprensione solida delle reti, dei protocolli di comunicazione e delle infrastrutture hardware.

Mi piace costruire software solido dietro le quinte — dalla gestione della concorrenza in **C** alla persistenza dei dati con **C# / SQL Server** e allo sviluppo in **Python** — senza perdere di vista l'esperienza reale dell'utente davanti allo schermo.

* 🔭 **Attualmente al lavoro su:** `RAG against the machine` (sistemi RAG e LLM) e `NetPractice` (architetture di rete e routing TCP/IP) presso 42 Firenze.
* 📡 **Formazione parallela:** Studente al corso serale di **Informatica e Telecomunicazioni**.
* 🌍 **Lingue:** Italiano (Madrelingua), Inglese (B2), Francese (B1).
* 📫 **Contatti:** [marani.paolo99@gmail.com](mailto:marani.paolo99@gmail.com)

## 🛠️ Tech Stack & Cosa ho imparato alla 42

### Linguaggi & Database
* **Linguaggi:** `C` • `Python` • `C++` • `C#` • `SQL` • `Bash`
* **Database & ORM:** `SQL Server` • `Entity Framework Core`

### Competenze sviluppate nel percorso 42
* **System & Concurrent Programming (C / Unix):** Gestione manuale della memoria, chiamate di sistema Unix, creazione e gestione di processi, IPC (pipe e segnali), programmazione concorrente con POSIX Threads (`pthreads`), Mutex, variabili di condizione e algoritmi di scheduling (`FIFO`/`EDF`) per prevenire *deadlock* e *starvation*.
* **Algoritmica & Strutture Dati:** Progettazione e ottimizzazione di algoritmi su array, liste concatenate, stack e grafi; algoritmi di ordinamento vincolati (`push_swap`), generazione di labirinti e *pathfinding* concorrente multi-agente (`Fly-in`).
* **AI & Data Engineering (Python):** Architetture *Object-Oriented* e programmazione funzionale avanzata, gestione ambienti e dipendenze (`Poetry`/`pip`), validazione rigorosa dei dati con `Pydantic`, integrazione di Large Language Models, *Function Calling* con *Constrained Decoding* per garantire output JSON tipizzati (`Call Me Maybe`) e sistemi RAG (`RAG against the machine`).
* **Networking & System Administration:** Configurazione e messa in sicurezza di server Linux virtualizzati (partizionamento LVM, SSH hardening, firewall UFW, policy di sicurezza in `Born2beroot`) e progettazione di topologie di rete, subnetting e routing TCP/IP (`NetPractice`).

## 🚀 Progetto in Evidenza (Azienda Esterna)

### 🎮 GameVerse — *Terranova Challenge (con 42 Firenze)*

> **Stack:** `C#` • `Entity Framework Core` • `SQL Server` • `UI/UX Iteration`
>
> *(Repository privata — progetto realizzato per sfida aziendale)*

**Il mio ruolo e cosa mi ha insegnato questo progetto:**

* **Backend & Persistenza Dati:** Mi sono occupato principalmente della gestione dei preferiti e della loro persistenza su database relazionale utilizzando **SQL Server** ed **Entity Framework Core**.
* **Design & Revisione UI assistita dall'AI:** Sul lato interfaccia ho lavorato con il supporto dell'AI, concentrandomi sul testare il risultato direttamente nel browser e guidare le scelte di revisione in base al comportamento dell'utente:
  * *Risoluzione del taglio immagini:* Nella pagina di dettaglio del gioco la copertina verticale veniva tagliata male occupando tutta la larghezza. Ho scelto di sostituirla con gli screenshot di gioco orizzontali.
  * *Sincronizzazione del caricamento:* Ho fatto in modo che l'animazione di dissolvenza partisse solo quando l'immagine successiva era effettivamente pronta, evitando scatti o schermate vuote.
  * *Tempi contestuali:* Ho impostato tempistiche diverse per due situazioni d'uso distinte: nella **Home** la transizione al passaggio del mouse è rapida per chi vuole dare un'occhiata veloce al catalogo, mentre nella **Pagina di dettaglio** i tempi sono più distesi per permettere all'utente di osservare la scena.

## 💻 Progetti Principali @ 42 Firenze

### 🤖 AI, Python & Data Engineering

| Progetto | Descrizione | Competenze Chiave |
| ----- | ----- | ----- |
| **Call Me Maybe** *(Con Bonus)* | Sistema di *Function Calling* per Large Language Models che traduce prompt in linguaggio naturale in chiamate a funzioni strutturate e tipizzate, implementando *constrained decoding* per garantire output JSON validi con un modello da 0.5B parametri. | `Python`, `LLM`, `Constrained Decoding`, `JSON Schema` |
| **Fly-in** *(Con Bonus)* | Sistema di routing per droni autonomi su rete dinamica. Sviluppo di un algoritmo di *pathfinding* concorrente personalizzato che gestisce costi di movimento, zone soggette a restrizioni, colli di bottiglia e prevenzione dei *deadlock*. | `Python`, `Graph Algorithms`, `OOP`, `Optimization` |
| **RAG against the machine** *(In corso)* | Progettazione e sviluppo di un sistema di *Retrieval-Augmented Generation* per interrogare basi di conoscenza strutturate e non strutturate. | `Python`, `RAG`, `Databases`, `OOP` |
| **Python Piscine (Moduli 00–10)** | Percorso intensivo di 11 moduli: dall'OOP e polimorfismo alla gestione dei pacchetti (`Poetry`/`pip`), validazione dati complessa con `Pydantic` e programmazione funzionale avanzata (decoratori, *higher-order functions*). | `Python`, `Pydantic`, `Poetry`, `Design Patterns` |

### ⚙️ System Programming, Concorrenza & Algoritmi (C / Unix)

| Progetto | Descrizione | Competenze Chiave |
| ----- | ----- | ----- |
| **Codexion** | Simulazione concorrente in C in cui più thread competono per risorse condivise limitate. Implementazione di POSIX threads, mutex, variabili di condizione e algoritmi di scheduling (`FIFO`/`EDF`) per prevenire *deadlock* e *starvation*. | `C`, `POSIX Threads`, `Mutex`, `Scheduling` |
| **push_swap** | Algoritmo di ordinamento ad alta efficienza su due stack con un set limitato di istruzioni, ottimizzato per ridurre al minimo il numero di mosse. | `C`, `Sorting Algorithms`, `Data Structures` |
| **A-Maze-ing** | Generatore e visualizzatore grafico di labirinti conformi a vincoli strutturali specifici, sviluppato in team. | `C`, `Graphics`, `Algorithms`, `Teamwork` |
| **Born2beroot** *(Con Bonus)* | Configurazione di un server Linux virtualizzato con criteri rigorosi di sicurezza, partizionamento LVM, firewall, policy SSH e monitoraggio di sistema. | `Linux`, `SysAdmin`, `Virtualization`, `Security` |
| **Libft / ft_printf / get_next_line** | Ricodifica da zero delle funzioni fondamentali della libreria standard C, gestione di funzioni variadiche e lettura bufferizzata da file descriptor multipli. | `C`, `Memory Management`, `Unix I/O` |

---

# Hi there, I'm Paolo Marani 👋

### Software Engineering Student @ 42 Firenze | Backend, System Programming & AI

*"The way you work will reflect your life outside"*

## 👨‍💻 About Me

I am a Software Engineering student at **42 Firenze**, tackling low-level programming, algorithms, system architecture, and artificial intelligence daily through a hands-on, peer-to-peer methodology.

Alongside my curriculum at 42, I attend an **evening program in Telecommunications**: a path chosen to combine software development with a solid understanding of computer networks, communication protocols, and hardware infrastructure.

I enjoy building reliable software behind the scenes — from managing concurrency in **C** to data persistence with **C# / SQL Server** and development in **Python** — without losing sight of the actual user experience on screen.

* 🔭 **Currently working on:** `RAG against the machine` (RAG systems and LLMs) and `NetPractice` (network architectures and TCP/IP routing) at 42 Firenze.
* 📡 **Parallel Education:** Evening student in **Computer Science and Telecommunications**.
* 🌍 **Languages:** Italian (Native), English (B2), French (B1).
* 📫 **Contact:** [marani.paolo99@gmail.com](mailto:marani.paolo99@gmail.com)

## 🛠️ Tech Stack & What I Learned at 42

### Languages & Databases
* **Languages:** `C` • `Python` • `C++` • `C#` • `SQL` • `Bash`
* **Databases & ORM:** `SQL Server` • `Entity Framework Core`

### Core Skills Developed at 42
* **System & Concurrent Programming (C / Unix):** Manual memory management, Unix system calls, process creation and management, IPC (pipes and signals), and concurrent programming with POSIX Threads (`pthreads`), Mutexes, condition variables, and scheduling algorithms (`FIFO`/`EDF`) to prevent deadlocks and resource starvation.
* **Algorithms & Data Structures:** Designing and optimizing algorithms across arrays, linked lists, stacks, and graphs; constrained sorting algorithms (`push_swap`), procedural maze generation, and multi-agent concurrent pathfinding (`Fly-in`).
* **AI & Data Engineering (Python):** Object-Oriented architectures and advanced functional programming, environment and package management (`Poetry`/`pip`), strict data validation with `Pydantic`, Large Language Model integration, *Function Calling* with *Constrained Decoding* for guaranteed typed JSON outputs (`Call Me Maybe`), and RAG architectures (`RAG against the machine`).
* **Networking & System Administration:** Configuring and hardening virtualized Linux servers (LVM partitioning, SSH hardening, UFW firewall, and security policies in `Born2beroot`), as well as designing network topologies, subnetting, and TCP/IP routing (`NetPractice`).

## 🚀 Featured Project (External Company Challenge)

### 🎮 GameVerse — *Terranova Challenge (with 42 Firenze)*

> **Stack:** `C#` • `Entity Framework Core` • `SQL Server` • `UI/UX Iteration`
>
> *(Private repository — built for an external company challenge)*

**My role and what this project taught me:**

* **Backend & Data Persistence:** I was primarily responsible for the favorites system and its relational database persistence using **SQL Server** and **Entity Framework Core**.
* **AI-Assisted Design & UI Iteration:** On the frontend side, I worked with AI assistance, focusing on testing the interface directly in the browser and guiding design revisions based on user intent and behavior:
  * *Solving image cropping issues:* On the game detail page, vertical cover art was poorly cropped when stretched across the full width. I chose to replace it with horizontal gameplay screenshots.
  * *Loading synchronization:* I ensured that the crossfade animation only started once the next image was fully loaded, preventing visual glitches or blank frames.
  * *Context-aware timings:* I set different transition timings for two distinct user contexts: on the **Home page**, hover transitions are fast for users quickly scanning the catalog, whereas on the **Detail page**, transitions are slower to give users time to observe the scene.

## 💻 Main Projects @ 42 Firenze

### 🤖 AI, Python & Data Engineering

| Project | Description | Key Skills |
| ----- | ----- | ----- |
| **Call Me Maybe** *(With Bonus)* | Function calling system for Large Language Models that translates natural language prompts into structured, typed function calls, implementing constrained decoding to guarantee valid JSON output with a 0.5B parameter model. | `Python`, `LLM`, `Constrained Decoding`, `JSON Schema` |
| **Fly-in** *(With Bonus)* | Autonomous drone routing system across a dynamic network. Built a custom concurrent pathfinding algorithm handling movement costs, restricted zones, bottlenecks, and deadlock prevention. | `Python`, `Graph Algorithms`, `OOP`, `Optimization` |
| **RAG against the machine** *(In progress)* | Designing and building a *Retrieval-Augmented Generation* system to query structured and unstructured knowledge bases. | `Python`, `RAG`, `Databases`, `OOP` |
| **Python Piscine (Modules 00–10)** | Intensive 11-module track: from OOP and polymorphism to package management (`Poetry`/`pip`), complex data validation with `Pydantic`, and advanced functional programming (decorators, higher-order functions). | `Python`, `Pydantic`, `Poetry`, `Design Patterns` |

### ⚙️ System Programming, Concurrency & Algorithms (C / Unix)

| Project | Description | Key Skills |
| ----- | ----- | ----- |
| **Codexion** | Concurrent simulation in C where multiple threads compete for scarce shared resources. Implemented POSIX threads, mutexes, condition variables, and scheduling algorithms (`FIFO`/`EDF`) to prevent deadlocks and starvation. | `C`, `POSIX Threads`, `Mutex`, `Scheduling` |
| **push_swap** | High-efficiency sorting algorithm using two stacks and a limited instruction set, optimized to minimize the total number of operations. | `C`, `Sorting Algorithms`, `Data Structures` |
| **A-Maze-ing** | Procedural maze generator and graphical visualizer compliant with specific structural constraints, developed in a team. | `C`, `Graphics`, `Algorithms`, `Teamwork` |
| **Born2beroot** *(With Bonus)* | Configuration of a virtualized Linux server following strict security standards, LVM partitioning, firewall rules, SSH policies, and system monitoring. | `Linux`, `SysAdmin`, `Virtualization`, `Security` |
| **Libft / ft_printf / get_next_line** | Recoding core C standard library functions from scratch, variadic function handling, and buffered line reading across multiple file descriptors. | `C`, `Memory Management`, `Unix I/O` |
