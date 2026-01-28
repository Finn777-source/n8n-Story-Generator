Story Generator Workflow (n8n)

Automated Story Generator with TTS and Telegram Notifications

Description

This n8n workflow automatically generates short, emotional stories using OpenAI. Each story is analyzed to detect the narrator’s gender and then converted into speech (TTS) before being sent directly to Telegram.

Key Features:

Story Creation: Generates unique short stories in a Reddit-style narrative.

Gender Detection: Determines if the narrator is male or female to choose a matching TTS voice.

Text-to-Speech (TTS): Converts stories into audio (mp3) using ElevenLabs or OpenAI TTS.

Telegram Integration: Sends both title notifications and audio files directly to Telegram.

Automated Scheduling: Can generate multiple stories per day (e.g., 12 daily).

How it Works:

Schedule Trigger: Starts the workflow at set times.

Generate Story (OpenAI): Creates the story text.

Detect Gender: Classifies the narrator.

Prepare Text: Prepares the story for TTS conversion.

Convert to Audio: Generates the mp3 audio file.

Send Title Notification: Sends a brief Telegram message with the story title.

Send Audio: Sends the completed story to Telegram.

Notes:

Credentials (OpenAI, Telegram, ElevenLabs) are not included in the workflow.

Users must insert their own credentials to run it.

Screenshots of the workflow can be added to illustrate its structure.
