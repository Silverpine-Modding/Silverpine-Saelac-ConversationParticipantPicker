# Conversation Participant Picker

Silverpine BepInEx mod that lets the player choose nearby visible NPCs when beginning a conversation, including multi-participant dialogue.

Created by **Saelac and ChatGPT**.

**Current version:** 1.1.1

The conversation-choice menu, participant picker, and selection review each have a **Cancel** button that closes the menu without starting a conversation. The picker shows three NPCs per page, leaving room for navigation, review, and cancellation without exceeding six buttons.

## Installation

Build the project and place `ConversationParticipantPicker.dll` under `BepInEx/plugins/`.

## Building

The project targets `netstandard2.1` and requires the local Silverpine managed assemblies referenced by the project file.
