# conceptual artifact


{
  "project": "resto_kit",
  "artifact_type": "project_context",
  "date": "2026-06-01",
  "version": "0.1",
  "description": "A private, job-agnostic personal knowledge base and decision-support system for water damage restoration work, built to be loaded into an AI voice assistant for faster, more consistent field decisions.",
  "purpose": "Reduce mental load for the operator by externalizing decision logic, equipment calculations, procedures, and personal standards so the technician can focus on reading the building and making good calls on site.",
  "core_principles": [
    "Job-agnostic: No addresses, customer details, job numbers, or property-specific information stored.",
    "Personal standard first: core/ reflects how the operator wants the work done, not necessarily how any company does it.",
    "Middle path on standards: Rewrite everything in own words. Pull from general science where possible. Never copy IICRC tables or large sections directly.",
    "Operator-oriented: Plain language, practical, rough around the edges when appropriate. Designed for real field use, not corporate training manuals.",
    "Voice-first design: Built to be loaded into Grok voice mode for real-time assistance on active jobs."
  ],
  "folder_structure": {
    "core/": "Foundational principles and standards written in operator's own words",
    "procedures/": "Main job flows from call/intake through completion",
    "logic/": "Decision trees, rules, category × class interactions, material response logic",
    "equipment/": "Sizing calculations, setup patterns, practical field math",
    "voice/": "Assistant modes and speaking styles (Rookie, Tech, Deep, Smartass)",
    "personal/": "Generalized field observations, lessons learned, and refinements",
    "templates/": "Reusable checklists and quick reference formats"
  },
  "how_to_use": [
    "Load relevant sections into Grok voice at the start of the day or when needed on site.",
    "Talk naturally while working. Use for quick guidance, calculations, checklists, and decision support.",
    "Update with new observations or refinements as they come up on jobs.",
    "Use voice modes to match the situation (Tech mode for normal work, Rookie for training, Smartass when mentally done)."
  ],
  "rules": [
    "Keep everything job-agnostic. No addresses, customer details, or specific job information.",
    "Write in plain, operator language. Focus on what actually works in the field.",
    "This is a personal tool. It reflects how the operator wants the work done.",
    "Do not store company-specific 'dirty' practices or fraudulent methods in any folder.",
    "Company folder (if used) only contains legitimate, documented company preferences and procedures."
  ],
  "voice_modes": {
    "Rookie": "Simple explanations, step-by-step, assumes minimal experience",
    "Tech": "Default mode. Direct, rough around the edges, practical, no fluff",
    "Deep": "Full technical depth — psychrometry, vapor pressure, material science, calculations",
    "Smartass": "Unfiltered, sarcastic, experienced tech voice for when the operator is over it"
  },
  "important_design_decisions": [
    "Three conceptual layers exist even if not all folders are heavily used: core (personal standard), company (current employer's way), personal (operator's private observations).",
    "No per-job or per-day storage in the repo. Job history stays in Encircle or operator's head. Context is passed verbally when returning to a site.",
    "Focus is on decision support and reducing cognitive load, not on duplicating documentation tools.",
    "Future product potential acknowledged but current priority is personal daily use as an employee."
  ],
  "current_status": "Early definition phase. README skeleton complete. Folder structure defined. Voice modes conceptualized. First content (logic and equipment sections) pending.",
  "next_steps": [
    "Begin populating logic/ with Category × Class interaction and equipment sizing rules.",
    "Create voice/modes.md with example phrasing for each mode.",
    "Build minimal templates for quick field use."
  ]
}