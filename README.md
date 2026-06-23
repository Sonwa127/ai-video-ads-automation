# AI Facebook Video Ads Automation

A fully automated video production pipeline that takes a text brief or landing page URL and outputs a complete 30-second vertical video ad with AI voiceover, B-roll footage, styled captions, and cloud delivery -- no manual editing required.

## What it does

- Generates a 5 to 8 scene ad storyboard from any text brief or landing page
- Creates a natural-sounding AI voiceover using ElevenLabs
- Sources cinematic royalty-free B-roll footage matched to each scene via Pexels
- Auto-generates and syncs captions using Whisper
- Renders the complete video with styled caption overlay via Shotstack
- Delivers the final MP4 automatically to Google Drive

## How it works

1. GPT generates a storyboard following Hook, Problem, Solution, Benefit, Call-to-Action structure
2. ElevenLabs generates a voiceover from the script
3. Pexels API matches each scene keyword to royalty-free B-roll footage
4. Whisper transcribes the voiceover and generates SRT captions with precise timing
5. Shotstack compiles all assets into a rendered video with styled caption overlay
6. Final MP4 is automatically uploaded to Google Drive for delivery

## Stack

- **n8n** - workflow automation
- **OpenAI GPT** - script and storyboard generation
- **ElevenLabs** - AI voiceover
- **Pexels API** - stock B-roll footage
- **Shotstack** - video rendering and caption overlay
- **Whisper** - caption generation
- **Google Drive** - cloud delivery

## Usage

Import `Video_Ads_Creation.json` into your n8n instance. Configure your OpenAI, ElevenLabs, Pexels, Shotstack, and Google Drive credentials before running.

## Demo

Watch it in action: https://www.loom.com/share/c953e5306ba043379e2fa2540c33cf22

## License

Creative Commons Attribution 4.0 International (CC BY 4.0)

Built by [Ann Chisom Sokwueaku](https://www.linkedin.com/in/ann-chisom-s-172027244)
