# Class Activity

**Week 6**

### Create a Script That:
1. Reads laser ping sensor data in centimeters and assigns it to a variable (e.g., `distance`); please note the sensor is connected to pin 15.
![Laser Ping](../../images/book/learning-modules/lab5_pic1.png)

2. Prints distance in centimeters in the terminal with its unit (e.g., `distance: 10 cm`).
3. Makes decisions based on the distance:

| No. | Conditions                | Do                                                                 |
|-----|---------------------------|-------------------------------------------------------------------|
| 1   | If `distance ≥ 50 cm`     | Nothing (speaker is OFF)                                          |
|     |                           | & Print(`“distance > 50”`) in terminal                            |
| 2   | If `30 ≤ distance < 50 cm`| Play a sound (e.g., `techloop.wav`) with volume 7                 |
|     |                           | & Print(`“30 ≤ distance < 50”`) in terminal                       |
| 3   | If `distance < 30 cm`     | Play a sound (e.g., `techloop.wav`) with volume 10                |
|     |                           | & Print(`“distance < 30”`) in terminal                            |

### Additional Instructions:
- Download `techloop.wav` from Canvas, or you can download a sound from this library: [Sound Library](https://learn.parallax.com/support/reference/sound-library)
- Paste the music files (`.wav`) onto the SD card of the activity board.

### Sample Code to Play Music
![Sample Code](../../images/book/learning-modules/lab5_pic2.png)
- Resource: [Play Music](https://learn.parallax.com/support/reference/sound-library)
