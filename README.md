# Arduino Cyclone LED Game

This Arduino project is a Cyclone LED game where players navigate a single LED around obstacles using a push button. The game progresses through levels of increasing difficulty, with green LEDs flashing upon success and red LEDs flashing upon failure.

**Features:**
- Implemented using Arduino UNO, NANO, or Pro Mini.
- Uses FastLED library for controlling LED strips.
- Suitable for WS2812B LED strips.
- Push button connected to pin D4 for user input.
- Levels increase in difficulty as the game progresses.
- LED colors indicate game status: green for success and red for failure.
- Random obstacles challenge players' skills.

**Instructions:**
1. Connect the LED strip to the designated pin (DATA_PIN).
2. Connect the push button to pin D4.
3. Upload the code to your Arduino board.
4. Play the game by navigating the LED around obstacles using the push button.
5. Successfully complete levels to progress through the game.

**Requirements:**
- Arduino board (UNO, NANO, or Pro Mini)
- WS2812B LED strip
- Push button
- FastLED library

**Compatibility:**
This code is compatible with Arduino UNO, NANO, and Pro Mini boards. For ATtiny85, pin numbers need to be adjusted.
