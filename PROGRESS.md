# Progress tracker

Tick a box when a task is done and commit. Latest update at the top of the log.

## Phase 0 · Title, proposal and design documents ✅
- [x] FYP title approved by supervisor
- [x] FYP 1 proposal form submitted
- [x] PRD (Keil version) — `docs/VaultTest_PRD.pdf`
- [x] System architecture diagram — `docs/diagrams/architecture.png`
- [x] Run Test flow diagram — `docs/diagrams/run_test_flow.png`
- [x] Supervision logbook: meetings 1 to 3 (15/10, 23/10, 04/11/2026)
- [x] Board and debugger received (MCBSTM32F400 + ULINK2)

## Phase 1 · Literature review → Chapter 2
- [ ] Collect 25 to 40 papers (2021 to 2026) into a reference manager
- [ ] Firmware and embedded testing, hardware-in-the-loop
- [ ] Requirements-based testing, black box / white box / grey box
- [ ] LLMs for test generation (single agent vs multi-agent)
- [ ] RAG for code, local LLMs, sovereign AI
- [ ] LLM-based failure diagnosis / fault localisation
- [ ] Comparison table of existing tools and the research gap
- [ ] Chapter 2 draft sent to supervisor

## Phase 2 · Toolchain and board bring-up
- [ ] Install Keil MDK and ULINK2 driver on Windows
- [ ] Flash the Blinky example to the MCBSTM32F400
- [ ] Read joystick, LCD and UART sections of the board manual; write the pin map
- [ ] Build and flash from the command line (UV4 -b / -f) so it can be automated
- [ ] Serial output from the board seen on the laptop (USB-RS232)
- [ ] Run Qwen2.5-Coder locally on the AMD laptop (llama.cpp Vulkan or Ollama)
- [ ] Ask supervisor about access to a UTM lab GPU PC

## Phase 3 · System and rig design → Chapter 3
- [x] Architecture and flow diagrams
- [ ] Rig wiring diagram (Pi 5 ↔ board pins, voltage levels checked)
- [ ] Requirement and test case formats (YAML)
- [ ] Agent design: inputs, outputs and prompts for each agent
- [ ] Evaluation plan: seeded faults, metrics, baselines
- [ ] Chapter 3 draft sent to supervisor

## Phase 4 · First end-to-end test (proof of concept)
- [ ] Firmware for REQ-JOY-01 (joystick LEFT shows "LEFT" on LCD)
- [ ] Pi script presses joystick LEFT and reads the serial log
- [ ] Hand-written test passes on the real board
- [ ] LLM generates the same test from the requirement
- [ ] Seed one bug (LEFT/RIGHT swapped) and see the test fail
- [ ] Demo video recorded

## Phase 5 · FYP 1 submission
- [ ] Chapter 1 Introduction
- [ ] FYP 1 report compiled (Chapters 1 to 3 + PoC results)
- [ ] Presentation slides
- [ ] Logbook up to date

## FYP 2 (next semester)
- [ ] Camera, relay and ADC added to the rig
- [ ] Repair and triage agents
- [ ] LangGraph orchestration and audit log
- [ ] Dashboard and traceability report
- [ ] Seeded-bug experiments and baseline comparison
- [ ] Final report and demonstration
- [ ] Infineon PSoC adapter (if time allows)

---

## Log
- **24/11/2026** — Repository created. Design documents uploaded. Implementation not started.
