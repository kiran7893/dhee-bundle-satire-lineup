# @dhee_ai/bundle-satire-lineup

Satire **lineup reel** pipeline for [Dhee](https://github.com/dheeai/dhee-core).

Inject one script defining a cast of characters (visual design, setting, exact spoken line, emotion, SFX). The bundle:

1. Extracts the cast from the script
2. Generates locked actor + setting stills per character (Krea2)
3. Designs and clones a voice per character (OmniVoice)
4. Animates each frame as a lip-synced talking head (LTX Director)
5. Concatenates clips into a vertical reel

## Install

From the Dhee desktop **New Project** screen, search npm for `satire` and install `@dhee_ai/bundle-satire-lineup`.

## External runners

`dhee-runner-tts` (auto-installed by the desktop).

## License

MIT
