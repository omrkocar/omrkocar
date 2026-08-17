## Omer Kocar

C# engineer in Gatineau, QC. Five years of production C# on shipped commercial
games: gameplay systems, developer tooling, and performance work. Lately I've
been building backend web services with ASP.NET Core and EF Core.

### Games

Software Developer at **Chasing Rats Games** since 2022, on the released title
*Worship*. Before that, C++ on *Baldur's Gate 3* at **Larian Studios**. I founded
**Emberfall Games** in 2025 and was its sole programmer on *Veil of Sight*, which
reached a public demo before the studio wound down in January 2026.

**[Commercial Projects](https://github.com/omrkocar/Commercial-Projects-Showcase)**:
the shipped titles, which are closed-source: *Baldur's Gate 3*, *Worship*,
*Veil of Sight*.

**[SazEngine](https://github.com/omrkocar/SazEngine)**: C++ game engine
written from scratch to work through engine architecture, rendering, memory
management, and a lightweight entity component system.

**[The Stroke of Midnight](https://github.com/omrkocar/TheStrokeOfMidnight)**:
Unreal Engine first-person horror game with AI encounters, interaction and
progression systems, and a custom save/load framework.

### Backend and tools

**[WarehouseAPI](https://github.com/omrkocar/WarehouseAPI)**: inventory and
order management REST API. ASP.NET Core (.NET 10), EF Core, layered behind the
repository pattern. Optimistic concurrency stops inventory oversell under
concurrent orders; xUnit unit and integration tests boot the app in-process via
`WebApplicationFactory`. Runs from one codebase on two clouds, with the EF Core
provider selected by configuration.
· [Render](https://warehouseapi-h38c.onrender.com/scalar/v1)
· [Azure](https://warehouseapi-omer.azurewebsites.net/scalar/v1)

**[WarehouseAPI-Frontend](https://github.com/omrkocar/WarehouseAPI-Frontend)**:
React 19 and TypeScript client for it. TanStack Query for server state,
protected routing, typed Axios client with centralized auth and error handling.
· [Live](https://warehouse-api-frontend.vercel.app)

**[imla](https://github.com/omrkocar/imla)**: push-to-talk dictation for
Windows. Whisper large-v3 runs on the local GPU through faster-whisper; hotkey,
clipboard and synthetic keystrokes go through Win32 via `ctypes`. No API key, no
account, no audio leaving the machine.

### Tech

C# · .NET / ASP.NET Core · Entity Framework Core · C++ · TypeScript / React ·
PostgreSQL · SQL Server · Azure · Docker · xUnit · Unity · Unreal

[LinkedIn](https://www.linkedin.com/in/omrkocar/)
