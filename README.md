
# Hey, I'm TerminalDev 👋

I build software with AI rather than manually writing the code myself.

All of the code in my software projects is AI-generated. **OpenAI Codex is my primary coding tool and the tool I use for all of my projects.** I also use **Claude Code** and **Google Antigravity** when I choose to experiment with them or compare their performance.

I provide the ideas, requirements, direction, testing, feedback, and final decisions, while the coding tools generate, inspect, debug, correct, and modify the code.

## What I build

My main development interests include:

- **Supercell private servers**
- **Transformer-based models**
- Small models trained for narrow tasks
- Occasional larger language-model experiments
- AI-generated tools and software
- Windows-related experiments and projects

## Supercell private servers

I am well-versed in the Supercell private-server space and have worked on private servers for games including **Brawl Stars** and **Squad Busters**.

My private-server work can involve server logic, client compatibility, protocol implementation, matchmaking, battles, progression systems, databases, shops, rewards, clubs, leaderboards, events, and other game systems.

I am also considering building private servers for **Clash Royale** and **Clash of Clans**, since I have not worked on servers for those games before.

For compatible game clients, I search the web myself and usually find the required APK versions through **APKMirror**. I do not rely on AI coding agents for client searching because they can be overly cautious, inconsistent, or unreliable during that part of the process.

## Transformer-based model training

I train transformer-based models for both narrow tasks and broader language-model experiments.

Some of my models are intentionally small and designed to perform one specific task. These can include models that predict structured outputs or interact with basic tools, such as retrieving the current system date and time.

One of my larger projects was **HyperAI R1-325M**, a 325-million-parameter GPT-style reasoning model with tool calling and a 6K context window.

I do not exclusively focus on either narrow-task models or larger language models. I may train a small specialist model for one experiment and later decide to work on something much broader.

## Frontier AI model testing

I regularly stress test newly released frontier AI models through practical software-development work.

This testing is separate from training my own transformer-based models. The goal is to determine whether a new frontier model is capable, reliable, and efficient enough to become the default model for all of my software projects.

When a model meets those requirements, I switch to it as my default across everything I build. I continue using it until another frontier model proves better suited to my workflow.

My current default is **GPT-5.6 Sol with Medium reasoning**, used through **OpenAI Codex**. This is not a permanent preference and may change when a newer frontier model proves efficient enough.

My tests are not limited to simple benchmark-style questions. I evaluate models through practical tasks such as:

- Following detailed and highly specific instructions
- Building complete projects
- Working inside existing codebases
- Maintaining context across long sessions
- Inspecting and debugging their own implementations
- Analysing screenshots and visual problems
- Correcting failures without manual code edits from me
- Producing usable single-file HTML applications
- Handling unusual or complex project requirements

I sometimes create single-file HTML projects specifically to compare model behaviour and results. These tests make differences in implementation quality, visual design, instruction following, reasoning, and reliability easier to see.

If people are interested in the results, I may upload some of my single-file HTML model tests and comparisons to GitHub.

## How I develop

I do not consider myself a traditional manual programmer.

I build through **AI-assisted development and vibe coding**. I do not manually write or edit the code in my projects. All project code is generated and modified using AI coding tools.

That does not mean giving an AI one sentence and blindly accepting whatever it produces.

My workflow involves deciding what a project should do, explaining the intended behaviour, directing the implementation, running the project, and visually inspecting and testing how it behaves.

When I encounter a problem, unexpected behaviour, or something that does not match my requirements, I usually take a screenshot and provide it to the coding agent alongside a description of what happened and what I expected instead.

I then direct the agent to visually analyse the screenshot, inspect the relevant parts of the project, investigate the cause, and make the necessary corrections.

I do not manually inspect, debug, edit, or correct the code myself.

I understand how my projects work conceptually, including how their components and systems interact, what behaviour they are intended to produce, and how the overall project should function. I do not need to read or manually inspect the generated source code to understand or direct a project.

Codex is an agent rather than an IDE that I manually code inside. It reads the repository, inspects the implementation, runs checks, investigates problems, edits files, and corrects the code itself.

In many cases, Codex inspects its own work, runs tests or checks, identifies bugs, and makes corrections before presenting the result to me. Sometimes the final result works without me finding any bugs during my own visual testing.

My role is to control the direction of the project, understand it conceptually, evaluate the behaviour of the result, provide screenshots and feedback when necessary, and decide what should happen next.

## Languages and technologies

The languages and technologies used depend on the project and may include Python, C#, JavaScript, HTML, SQL, MongoDB, MariaDB, and other project-specific tools.

My preferred development stack is **Python with SQLite**, particularly for projects that need a straightforward local database.

These are technologies that appear in the projects I direct. I am not presenting myself as a specialist or analyst in every technical area involved, and I do not consider myself a networking analyst.

## Windows

Windows is the main platform for all of my projects, including my AI-generated software, private servers, model experiments, and other tools.

I also know a lot about Windows and experiment with Windows Setup, OOBE, Windows PE, Command Prompt, registry configuration, user setup, and the Windows deployment process.

My deployment experiments do not involve manually applying Windows images with DISM or manually creating and configuring the full partition structure.

Instead, I allow Windows Setup to complete the normal installation stage, then take control during the **Getting Ready** phase by crashing **WinDeploy**. From there, I manually work with the remaining setup state, user configuration, registry values, and other parts of the deployment process.

This Windows deployment work is separate from my normal coding workflow. I perform the deployment process manually, while all code in my software projects is generated and modified using AI.

Windows-related projects may appear on this account, and Windows will remain the main platform for almost everything I build. However, I do not intend to publish my personal Windows deployment process or dedicated deployment projects here.

## A note about AI and accessibility

Yes, my bio and parts of this README were written with help from ChatGPT.

I struggle with manually typing for long periods, so I usually communicate through dictation, voice recordings, or built-in speech-to-text tools.

Raw dictation can easily turn what I mean into a linguistic mess, especially when I am explaining something long or technical. I use ChatGPT to organise my dictated thoughts into readable writing while keeping the meaning accurate.

I use the same approach with coding tools. I often give instructions through dictation, audio-recording features, or speech-to-text instead of manually typing long prompts.

Using AI for writing does not mean the ideas came from the AI. I provide the information, read every paragraph, correct inaccuracies in the writing, reject descriptions that do not represent me, and decide what the final text should say.

I am not hiding the fact that all of my project code is AI-generated. This profile is openly about building software with AI.

I direct the projects, define the requirements, understand how their systems work conceptually, run and visually test the results, provide screenshots and descriptions of problems when I find them, and decide what changes should be made.

The AI coding tools visually analyse the screenshots, inspect the project, generate the code, debug problems, make corrections, and modify the implementation. I do not manually inspect or modify the source code myself.

If AI-generated writing or code bothers you, this probably is not the account for you. You are free not to follow me.

## Previous projects

This account is a fresh start for my newer projects.

My previous GitHub account, **Core Studio Dev AI**, contains older projects such as Crystal Browser, its mobile version, several Supercell private-server projects, and other experimental tools.

Many of those projects were developed on a laptop I no longer use for development. I still have the laptop, but I have no intention of continuing most of those projects.

Some of the older tools work but contain many bugs. A few were never originally intended to become public projects but were published anyway.

One example was a Windows deployment tool built with Claude Code. That old tool does not represent the manual Windows deployment process I use now, and similar deployment projects will not be published on this account.

The old account now serves mostly as an archive of an earlier development era.

## What to expect

Expect Supercell private-server projects—including Brawl Stars and Squad Busters servers, and potentially future Clash Royale and Clash of Clans servers—AI-generated tools and software, transformer-based model training, narrow-task model experiments, occasional larger language-model projects, frontier-model stress tests, single-file HTML comparisons, Windows-based projects, and whatever else I decide is interesting enough to build.

**Stay tuned for cool projects.**