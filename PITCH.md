# Atlantis — PITCH

One-liner

Atlantis — The AI Planet: een modulair, uitbreidbaar AI-ecosysteem dat toolboxrooms en AI-modules levert voor realtime immersive experiences (Viverse + lokale Unreal builds).

Probleem

Organisaties en creators missen een out-of-the-box, modulaire infrastructuur om meerdere AI-agents en interactieve 3D-toepassingen snel te deployen en demonstreren.

Oplossing

- Modulaire toolboxrooms: kleine, herbruikbare scenes/components die je kunt spawn-en in Unreal of uploaden naar Viverse.
- Lokale en cloud-ready pipelines: self-hosted runners (Threatrippers) voor snelle cooks/builds en GitHub Actions orchestration.
- API-contracten per module zodat integratie tussen systemen eenvoudig en betrouwbaar is.

Demo (3–5 min)

1. Startscene in Viverse of local Unreal (1 min)
2. Spawn een toolboxroom en laad 2–3 AI‑agents (1–2 min)
3. Laat agents samenwerken en reageer op input (1 min)
4. Snel switch naar backup video als fallback (optioneel)

Technologie & infra

- Engine: Unreal Engine (exact versie tracken in docs)
- Assets: Git LFS (of Perforce voor grote art pipelines)
- CI: GitHub Actions + self-hosted runners (labels: threatripper, heavy-build)
- Deployment: Viverse upload / local staging servers

Team & rollen (voorstel)

- Project lead / demo host: @naam
- Engine devs: 2–4 (Unreal scenes & integration)
- AI devs: 3–6 (agents & orchestration)
- Infra / ops: 1–2 (runners, NAS, network)
- Art & UX: 1–3 (toolboxroom assets)

Roadmap & timeline (hoog niveau)

- Week 0–1: Stabiliseer toolboxrooms, maak staging build
- Week 1–2: Integratie in Viverse + smoke tests
- Week 2: Rehearsal + demo polish + fallback video

Ask (voor live demo)

- 2 extra Threadrippers (self‑hosted runners) of equivalente build capaciteit
- Netwerk met lage latency en snelle NVMe storage
- 1–2 mensen on-call tijdens demo

Contact & follow-up

Voor vragen of toewijzingen voeg issues toe of tag teamleden in PRs/Issues.
