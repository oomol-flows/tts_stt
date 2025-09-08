# TTS & STT - Text-to-Speech and Speech-to-Text

A powerful collection of audio processing blocks that convert between text and speech, making it easy to create voice-enabled applications without any programming knowledge.

## Overview

This project provides two essential building blocks for working with audio and text:

- **Text-to-Audio Block**: Converts written text into natural-sounding speech
- **Speech-to-Text Block**: Converts spoken audio into written text

These blocks can be used individually or combined together to create powerful voice processing workflows in the OOMOL platform.

## 🔧 Available Blocks

### 📢 Text-to-Audio Block

**What it does**: Takes any text you write and converts it into a spoken audio file.

**Perfect for**:
- Creating voiceovers for videos
- Generating audio announcements
- Making content accessible to visually impaired users
- Creating audio versions of written content

**How to use**:
1. **Input your text**: Type or paste the text you want to convert to speech
2. **Choose a voice**: Select from available voice options:
   - **Anna**: Female voice with clear pronunciation
   - **Alex**: Male voice with natural tone  
   - **Bella**: Female voice with expressive delivery
3. **Set output location**: Choose where to save the generated audio file
4. **Optional**: Give your audio file a custom name

**Output**: An audio file (.wav or .mp3) containing your text spoken aloud

### 🎤 Speech-to-Text Block

**What it does**: Takes an audio file with spoken words and converts it into written text.

**Perfect for**:
- Transcribing meetings and interviews
- Converting voice notes to text
- Making audio content searchable
- Creating subtitles for videos
- Accessibility applications

**How to use**:
1. **Select your audio file**: Choose an audio file containing speech
2. **Run the conversion**: The block will automatically process the audio
3. **Get your text**: Receive the transcribed text output

**Output**: Written text containing everything that was spoken in the audio

## 🚀 Getting Started

### For Non-Technical Users

1. **Open OOMOL Platform**: Access your OOMOL workspace
2. **Add Blocks**: Drag and drop the blocks you need into your workflow
3. **Connect Inputs**: 
   - For Text-to-Audio: Connect your text source or type directly
   - For Speech-to-Text: Connect your audio file source
4. **Configure Settings**: Choose voice options, file locations, etc.
5. **Run Your Workflow**: Click run and let the blocks process your content

### Common Use Cases

#### Creating Audio Content
```
Text Input → Text-to-Audio Block → Audio File Output
```
Perfect for creating podcasts, audiobooks, or voice announcements.

#### Transcribing Audio
```
Audio File → Speech-to-Text Block → Text Output
```
Great for converting recorded meetings, interviews, or lectures into text.

#### Complete Audio Processing Pipeline
```
Audio File → Speech-to-Text Block → [Edit Text] → Text-to-Audio Block → New Audio File
```
Useful for cleaning up audio recordings, translating content, or changing the speaker.

## 📁 File Requirements

### For Text-to-Audio Block:
- **Input**: Plain text (any length)
- **Output**: Audio files in common formats (WAV, MP3)
- **Storage**: Files are saved to your specified directory

### For Speech-to-Text Block:
- **Input**: Audio files (WAV, MP3, M4A, etc.)
- **Output**: Plain text
- **Quality**: Works best with clear audio and minimal background noise

## 💡 Tips for Best Results

### Text-to-Audio Tips:
- Use punctuation to add natural pauses
- Spell out numbers and abbreviations for clarity
- Keep sentences at reasonable length for natural flow
- Test different voices to find the best fit for your content

### Speech-to-Text Tips:
- Use high-quality audio recordings when possible
- Minimize background noise
- Speak clearly and at a moderate pace
- Consider the audio format - WAV files often work best

## 🔗 Integration

These blocks work seamlessly with other OOMOL platform components:
- **File Management Blocks**: For organizing input and output files
- **Text Processing Blocks**: For editing and formatting text
- **Media Blocks**: For further audio/video processing
- **AI Blocks**: For content analysis and enhancement

## 📋 Technical Information

- **Version**: 0.0.6
- **Language Support**: English (expandable to other languages)
- **File Formats**: Common audio and text formats supported
- **Performance**: Optimized for real-time processing
- **Dependencies**: All required components are automatically installed

## 🆘 Need Help?

- Check that your input files are in supported formats
- Ensure you have sufficient storage space for output files
- For audio quality issues, try using higher-quality source files
- Make sure file paths are accessible and have proper permissions

## 📄 License & Repository

Repository: [https://github.com/oomol-flows/tts_stt](https://github.com/oomol-flows/tts_stt)

---

Ready to start converting between text and speech? Add these blocks to your OOMOL workflow and begin creating powerful voice-enabled applications today!
