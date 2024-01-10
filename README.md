# Dual-Tone-Multi-Frequency-DTMF-Signaling-Project
In this project, I performed web scraping through python BeautifulSoup library in Trendyol Website and made insights from them. 


## Background
Signaling plays a crucial role in communication systems, facilitating tasks such as dialing phone numbers and controlling automated equipment. In the mid-20th century, rotary phones were the norm, using pulse dialing for addressing. However, this method was slow and inefficient. The advent of push-button dialing with Dual-Tone Multi-Frequency (DTMF) signaling revolutionized telecommunications.

In DTMF signaling, each key press generates a signal comprising two constant frequencies. This project involves implementing signal processing methods in MATLAB to generate, transmit, receive, and decode audio DTMF signals.
<br/><br/>

### Deliverables
For both transmitter and receiver components, MATLAB codes and a graphical user interface (GUI) using the app designer are required.
#### Transmitter Panel
- Push-Button Keypad: Allows input of DTMF signals.
- Display Field: Shows pressed keys as text.
- Reset Button: Clears pressed keys.
- Input Fields: For signaling duration per key (Td ) and resting duration (Tr).
- Amplitude Adjustment Field: To adjust the amplitude of the time domain signal.
- Time Domain Signal Panel: Displays the DTMF-encoded sequence m(t;Td,Tr ).
- Spectrogram Display: Shows the spectrogram of the generated signal.
- Save and Play Buttons: For saving and playing the generated signal as audio.
<br/>

#### Receiver Panel
- Input Fields: For signaling duration per key (Td ) and resting duration (Tr).
- Start/Stop Listening Button: Initiates/stops listening via a microphone.
- Time Domain Signal Display: Plots the received time domain signal.
- Spectrogram Display: Shows the spectrogram of the received signal.
- Decoding Algorithm Switch: Allows selection between spectrogram-based method and another algorithm.
- Decoded Signal Display Field: Shows the decoded signal.

### Implementation
#### Transmitter Side
Generates arbitrary length DTMF-encoded signals, displays input sequence, time domain signal, and spectrogram. Allows parameter adjustments and audio playback or saving.
#### Receiver Side
Listens via a microphone, displays received audio signal, spectrogram, and decoded signal. Supports parameter adjustments for real-time displays.

### Further Reading
- DTMF: https://en.wikipedia.org/wiki/Dual-tone_multi-frequency_signaling
- Signalling: https://en.wikipedia.org/wiki/Signaling_(telecommunications)
- Filter Banks: https://en.wikipedia.org/wiki/Filter_bank
- Goertzel algorithm: https://en.wikipedia.org/wiki/Goertzel_algorithm
- MUSIC algorithm: https://en.wikipedia.org/wiki/MUSIC_(algorithm)
Useful MATLAB Links:
- Real Time Audio: https://www.mathworks.com/help/audio/gs/real-time-audio-in-matlab.html
- Audio I/O Buffering: https://www.mathworks.com/help/audio/gs/audio-io-buffering-latency-andthroughput.html
- DTMF Generator and Receiver: https://www.mathworks.com/help/dsp/ug/dtmf-generator-andreceiver.html
- Filter Banks: https://www.mathworks.com/help/dsp/ug/overview-of-filter-banks.html
- Goertzel algorithm: https://www.mathworks.com/help/signal/ref/goertzel.html
