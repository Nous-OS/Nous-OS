# JOURNAL_SPEC.md — Nous-OS Journal Specification

---

## Purpose

The journaling module is the therapeutic core of Nous-OS.  
It allows users to structure their inner experiences into clearly defined, encrypted, and printable categories.

---

## Core Principles

- Fully offline & locally encrypted data
- Structured categories for self-reflection
- LaTeX-based export for high-quality printable reports
- Optional AI-assisted reflections (offline-only)

---

## Journal Categories

1️⃣ Dreams  
- Free-form dream logs  
- Optional guided prompts:
  - Key symbols
  - Emotional tone
  - Recurring themes

2️⃣ Thoughts  
- Daily thoughts, cognitive patterns, worries, or rumination  
- Optional AI summary support

3️⃣ Emotions  
- Emotional logs with optional intensity scales  
- Context tagging (situation, trigger, response)  
- Optional use of Plutchik's wheel or custom emotion trees

4️⃣ Body Observations  
- Somatic experiences, physical tensions, energy levels, sleep quality

5️⃣ AI Reflections  
- Auto-generated AI notes (optional)
- Pattern suggestions
- Reflection prompts
- No diagnostics, no recommendations

---

## Data Structure

- Each journal entry is stored as a structured file (YAML or JSON + Markdown body)
- Separate directories for each category
- Encrypted via system-wide encryption (LUKS or fscrypt)
- Timestamped & versioned

---

## Example Entry (YAML Header + Markdown Body)

```yaml
entry_id: 2025-06-12-001
category: dreams
date: 2025-06-12
title: "The endless stairs"
emotional_tone: anxious
key_symbols:
  - stairs
  - fog
  - unknown
