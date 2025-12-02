# Spelling Bee Practice

A web-based spelling practice application designed to help students prepare for spelling bee competitions through interactive audio-based learning and comprehensive performance analytics.

## Overview

This application provides an immersive spelling bee practice environment that leverages pre-recorded audio to simulate authentic competition conditions. Students can practice with curated word lists, receive immediate feedback on their attempts, and track their progress over time through persistent session analytics.

Key capabilities include:
- Audio-based word pronunciation using pre-recorded audio files
- Real-time performance metrics and accuracy tracking
- Configurable practice modes (random or sequential word selection)
- Comprehensive session history with LocalStorage persistence
- Post-session review of incorrect spellings for targeted improvement

The application features a distraction-minimized interface with a blurred background, allowing students to maintain focus during practice sessions.

## Features

### Core Functionality
- **Audio Pronunciation**: Plays pre-recorded audio for words and definitions
- **Real-time Progress Tracking**: Live display of total words, correct answers, wrong answers, and accuracy percentage
- **Session History**: Detailed statistics saved in browser LocalStorage with persistent data across sessions

### Practice Modes
- **Random Mode**: Words appear in randomized order for varied practice
- **Sequential Mode**: Words appear in list order with optional starting position configuration

### User Experience
- **Responsive Design**: Blurred background with centered practice interface for distraction-free learning
- **Wrong Word Review**: End-of-session summary displaying all missed words for targeted review

## Getting Started

### How to Use

1. Choose your preferred practice mode:
   - **Random**: Words presented in random order
   - **Sequential**: Words presented in order (optionally specify starting word number)
2. Click "Start Practice" to begin your session
3. Listen to each word pronunciation and type your spelling
4. Press Enter to submit your answer
5. Review incorrect spellings at the end of your session

## File Structure

- `index.html` - Main application
- `background.jpg` - Background image
- `wordlists/` - CSV word lists by year (e.g., wordlist-2025.csv)
- `tts/` - Audio files for words and definitions
