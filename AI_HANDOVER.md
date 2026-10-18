# K2 Studio OS — Multi-AI Architecture & Handover Protocol

## 1. Project Overview
A custom web-based 3D Product Design Studio, Freeform 3D Sandbox, Multi-Platform Order Queue, and Creality K2 Plus (350x350x350mm + CFS) Print Scheduler built for a Bristol-based maker/founder.
- **Mobile & Desktop Ready:** Must remain responsive so the founder can monitor orders, profits, and print queues from an iPhone, and design/slice from a PC.
- **Current Architecture:** Single-file (`index.html`) zero-build Three.js / WebGL application for instant browser execution and GitHub Pages / Vercel live deployment, alongside modular backend automation scripts (`/scripts`).

## 2. Mandatory Multi-AI Handover Protocol (READ FIRST)
Every AI assistant (Gemini, Claude, ChatGPT) working on this repository MUST follow this 3-step loop on every turn:
1. **READ:** Before writing any code, read `AI_HANDOVER.md` and `CHANGELOG.json` to understand the latest state, active modules, and what the previous AI modified.
2. **EXECUTE BY SPECIALTY:**
   - **Gemini:** 3D Three.js parametric geometry, CSG/STL binary export math, 350mm build-plate visualizer, and UK unit-economics/grant calculators.
   - **Claude:** UI/UX state management, modular architecture refactoring, Freeform 3D Sandbox gizmos/tools, and Supabase/MCP connector wiring.
   - **ChatGPT:** Python/Apps Script email order parsers (Etsy, eBay, Vinted Pro), local Creality K2 Plus Moonraker (`:4408`) API bridges, and shift scheduling logic.
3. **UPDATE & LOG:** At the end of every code turn, provide an updated block for `AI_HANDOVER.md` (Section 4: Current State & Next Tasks) and a new JSON entry for `CHANGELOG.json`.

## 3. Core 10 Base Product Templates
1. Sculptural Vase-Mode Table Lamp (up to 340mm tall, fits 59mm LED Lamp Kit 001 puck)
2. UK Recessed Electrical Socket Spacers (1-Gang 86x86mm & 2-Gang 146x86mm, PETG)
3. Under-Desk Power Brick & Laptop Dock Cage (Parametric L/W/H + screw/VHB tabs)
4. One-Piece 8x8 Gridfinity Master Baseplate (336x336mm on 42mm grid)
5. 2-Colour Personalised Gamer Headset & Controller Tower (CFS multi-colour embossed plate)
6. Curved Pet & Family Photo Lithophane Nightlight (59mm LED puck mount)
7. Snap-On Monitor Arm & Standing Desk Cable Spine Clips (Parametric pole diameter)
8. Tactile "Click" Game Cartridge Vault Sphere (Fits 6x6x5mm switch + 6x3mm magnets)
9. Invisible Floating Wall Cradle (Routers, remotes, display masks + Command Strip slots)
10. Ergonomic One-Handed Jar Opener & Arthritic Key Turner Set (UnLtd £8k Grant Catalyst SKU)

## 4. Current System State & Active Roadmap
- **Latest Version:** `v1.0.0` (Initial Lamp Shade, 59mm Base & Gridfinity CAD Studio)
- **Last Updated By:** Gemini (2026-10-18)
- **Files in Repo:**
  - `AI_HANDOVER.md` (Multi-AI coordination protocol)
  - `CHANGELOG.json` (Audit trail of AI commits)
  - `index.html` (Main 3D CAD & Print Studio web application)
- **Next Priority Tasks (V2 Upgrade):**
  - [ ] Expand left sidebar to house all 10 Base Product Templates with beginner-friendly `?` tooltips.
  - [ ] Add Multi-Item 350x350mm Bed Batcher (1 to 16 copies arranged automatically on the virtual K2 Plus plate).
  - [ ] Build Independent 3D Sandbox Mode (spawn/move/scale primitives + assign CFS colours 1-4).
  - [ ] Add Order Queue & Work/Sleep Print Scheduler (Overnight 23:00-07:30, Office 08:15-17:45, Evening 18:00-22:45).
  - [ ] Add In-App AI Handover & Revenue/SWEF Grant Tracker tab.
