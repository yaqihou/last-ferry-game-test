# Credits and asset provenance

## Original work

Story, characters, dialogue, branching system, interface, arcade simulation, and procedural arcade geometry were created for this project in this session.

Simplified Chinese and Japanese story/interface translations were authored for this project on 2026-09-08. They preserve the original English script as the gameplay and speech source. No external translation API was used; independent native-speaker editorial review is pending.

Three original images were generated with OpenAI ImageGen on 2026-09-08:

- `public/art/diner.png`: rain-soaked ferry-terminal diner, neon mint/coral lighting, harbor beyond glass.
- `public/art/rooftop.png`: moonlit harbor deck, canned coffees, distant cargo ship with a giant inflatable duck.
- `public/art/characters.png`: adult cast portrait sheet, left to right: Mira (28), Jun (29), Captain Sable (35).

Each asset was generated once. The portrait sheet includes background lighting; the UI intentionally uses framed crops instead of treating it as a transparent sprite sheet. No third-party game artwork was copied.

## Typeface and interface

Pixelify Sans is by the Pixelify Sans Project Authors, obtained from Google Fonts and self-hosted. The SIL Open Font License is included at `public/fonts/OFL.txt`. See [the font's source directory](https://github.com/google/fonts/tree/main/ofl/pixelifysans).

UI icons use Lucide. The starter supplies Base UI/Shadcn primitives. Dependency licenses remain with their respective packages. Audio feedback is synthesized locally using Web Audio.

## Voice and music production

The ElevenLabs cast is Laura (Mira), Will (Jun), Lily (Captain Sable), River (Robin), George (narrator), and Alice (terminal). Casting uses the provider's public voice descriptions checked on 2026-09-08; no voice cloning was performed. `audio/cast.json` pins IDs/settings. All 196 passages were generated on 2026-09-08 using the user-authorized `ELEVANLABS_API_KEY`, consuming 13,967 reported credits. Adjacent JSON receipts record each clip's provenance and checksum. Generated performances have not received a listening review.

The user supplied five manually generated Suno MP3s on 2026-09-08: Terminal, A Very Legal Duck, Things Left Unsent, Somewhere Less Lonely, and Absolutely Licensed to Drive. The files retain their supplied names and map to the terminal, caper, dawn, ending and arcade cues in `public/audio/music.json`. All five passed full decoding; durations and file metadata appear in `docs/qa/music-results.json`. Original direction prompts remain in `docs/SUNO-PROMPTS.md`.
