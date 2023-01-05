# Nice_Noise
---

## Nice noise: background noise enhancement with generated musical content

## Noise definitions
- Noise as Irregular Vibrations 
- Noise as Redundant Information 
- Noise as Undesirable and Annoying

## Use-case
LEGO Kladno
- Packing LEGO for distribution
- Employees are working in a noisy environment without a hearing protection
- Noise level < 80 dB (Czech legislation for mandatory hearing protection)
- The company placed speakers playing a commercial radio station

## Noise to music translation
![image](https://user-images.githubusercontent.com/44833796/210792325-7d1b5559-3a4e-4cc5-8345-9b858a94ef9c.png)

## Inspirations
### Noise music
- Luigi Russolo: The Art of Noises 1913 - Futurist manifesto
- Noise as a part of the music

### Metastaseis
- Iannis Xenakis
  - Using diagrams and physical principles to describe what instruments have to play
  - Development of the confined system where indeterministic music is happening
 
## Project roadmap
✅ Factory fields recording\
🟩 Sound analysis system\
🟩 Sound generation system\
🟩 Offline study -> sound evaluation\
🟩 Live online systemin the LEGO factory\

## Field recordings
- Twelve different microphone placements
- Posts of the workers
- Strong rhythmic content
- Some machines create distinguishable pitch (e. g. motor ~315 Hz)\
![image](https://user-images.githubusercontent.com/44833796/210793509-7f5a0733-81f2-41e8-8c21-5c127964a617.png)

## Sound analysis
### Harmonic content - frequency domain
- Detecting the loudest fundamental frequency
- Detecting overtones series
- Testing Faust language and Essentia.js framework for FFT\
![image](https://user-images.githubusercontent.com/44833796/210793744-f968b07b-9c51-4f88-909e-82f629318253.png)
### Rhytmic content - time domain
- Combination of filters and noise gate
- Leaving the strongest beat
- Detecting BPM\
![image](https://user-images.githubusercontent.com/44833796/210794001-287cbb20-f571-4213-a4c8-c011399a5cda.png)

## Music Generation
- Using harmonic series
  - Emphasise existing fundamental frequency
  - Use subharmonic frequency 
- Call-and-response - from calculated BPM
- Place underlining rhythm

## Performance Evaluation
- Use a music information retrieval (MIR) system to compare it with ambient music
- Using genetic algorithms to improve metrics
- 80 dB threshold ‼️
- Users evaluation using Amazon Mechanical Turk

## Conclusion & Future work
- Proposal of the system for noise sonification to reduce noise annoyance
- Factory application in LEGO Kladno factory

- Possible application in public places - e. g., subway station escalators












