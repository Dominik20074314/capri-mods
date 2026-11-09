# Capri Stream

![Capri Stream banner](preview.png)

Capri Stream is a Windows code mod for Capri Desktop. It mirrors Capri’s avatar, visible speech bubble, and application audio in a transparent OBS Browser Source on the same PC.

## Installation

1. Download [capri-stream.capri-code](capri-stream.capri-code).
2. Open **Mainframe → Mods → Import mod** and select the file.
3. Approve the code mod when prompted.

## OBS setup

1. In Capri’s Mainframe, click **Stream Mode: Off** to turn it on.
2. In OBS, add a **Browser Source** with URL **http://127.0.0.1:8766/**, width **720**, and height **720**.
3. Enable **Control audio via OBS**. Optionally set the custom frame rate to **60 FPS**.
4. If audio is blocked, open **Interact** and click **Enable Capri audio**. If OBS loaded the page while Stream Mode was off, turn it on and refresh the source.

Use Capri’s regular voice and text controls to interact with her. **Stream Mode: Off** stops the local server. The mirrored speech bubble can show text from your conversation, and application audio can include Capri’s sound effects.

## Memory in Stream Mode

While Stream Mode is on, direct inputs intercepted by the mod use an isolated model request without Capri's saved memories or private conversation history. Turning Stream Mode off restores the normal input path. Built-in autonomous features, other mods and provider-side memory are outside this control.

## Credits

- Made by Dominik20074
- Version 1.6.2
