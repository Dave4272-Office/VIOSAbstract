# Modules

1. Voice Recognition (STT)
2. Feature Extractor (FE)
3. Command Interpreter (CmdInt)
4. Command Executor (CmdExec)
5. Speech Generator (SpGen)
6. Voice Synthesis (TTS)

## Control Flow
##### MIC -> STT -> FE -> CmdInt -> CmdExec -> FE -> SpGen -> TTS -> SPK

### MIC
It will record speech with 1 second of noise / silence between each individual quanta.

### STT
Convert speech to Text.

### FE
Extracts key points from texts from input and output.

### CmdInt
Interprets the features from input and converts to commands.

### CmdExec
Executes the command interpreted.

### SpGen
Generates Speech text from the features extracted from the output.

### TTS
Converts text to speech.

### SPK
Outputs the sound.

