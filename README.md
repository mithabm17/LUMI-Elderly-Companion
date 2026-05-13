# LUMI-Elderly-Companion
AI-Powered Elderly Care System with Sentiment Analysis, Real-Time Alerts, and Family Monitoring

## Overview
LUMI is a Raspberry Pi-based AI companion device designed to support elderly individuals who live alone or require constant monitoring.
The device continuously monitors:
- Voice interactions
- Facial expressions
- Body movements
- Daily activity patterns

Using multimodal sentiment analysis, LUMI detects emotional states such as:
- Calm
- Happy
- Tired
- Restless
- Distressed

When abnormal behavior or emergencies are detected, real-time alerts are sent to family members through Firebase.

---

# Problem Statement
Many elderly individuals live alone and may face:
- Delayed emergency support
- Loneliness
- Mental health issues
- Missed medications
- Fall incidents
- Lack of continuous family monitoring

Traditional healthcare monitoring systems often focus only on physical health and ignore emotional well-being.

---

# Solution
LUMI acts as an intelligent elderly companion that combines:
- AI sentiment detection
- Voice communication
- Emergency monitoring
- Family connectivity

The system provides proactive care instead of reactive emergency response.

---

# Core Features

## 1. Voice Monitoring
- Captures voice through microphone
- Supports:
  - Kannada
  - Hindi
  - English
- Converts speech to text
- Detects emotional sentiment

---

## 2. Facial Emotion Detection
Uses camera input to detect:
- Happiness
- Stress
- Fatigue
- Distress
- Calmness

---

## 3. Body Movement Monitoring
Tracks:
- Posture
- Motion speed
- Head movement
- Gesture patterns
- Fall detection indicators

---

## 4. Medicine Reminder System
Detects missed medications and alerts family members.
Example:
- Medicine not taken
- No response alert

---

## 5. SOS Emergency Button
Allows elderly users to manually request immediate help.

---

## 6. Family Dashboard
Family members can:
- View live status
- Track emotional state
- Receive alerts
- Check activity logs
- Contact elderly person instantly

---

# System Architecture
## Input Layer
- Microphone
- Raspberry Pi Camera
- PIR Motion Sensor
- SOS Push Button

---

## Processing Layer
- Speech-to-text conversion
- Translation
- Natural Language Processing
- Sentiment Engine
- Alert Engine
- Memory-based conversation logic

---

## Output Layer
- Speaker responses
- OLED display
- LED mood indicator

---

## Cloud Layer
Firebase Realtime Database:
- Mood logs
- Notifications
- Alert storage

---

## Family App Layer
- Real-time monitoring dashboard
- Emergency notifications
- Activity tracking

---

# Sentiment Analysis Pipeline
Camera Input → Pose Extraction → Facial Emotion Detection → Body Movement Analysis → Sentiment Fusion → Final Decision → Action Trigger

---

# Technology Stack

## Hardware
- Raspberry Pi 4 Model B (4GB)
- Raspberry Pi Camera v2
- USB Microphone Array
- 3W Speaker
- PIR Sensor
- Push Button

---

## AI/Software
- MediaPipe Pose
- DeepFace
- FER2013 Emotion Model
- Whisper STT
- IndicTrans2
- Llama 3.1 (Quantized Local Model)

---

## Backend
- Firebase Realtime Database
- Cloud Functions

---

# Performance

- Inference Time: <500ms per frame
- Always-on monitoring
- PIR sleep mode optimization
- WiFi + Ethernet support

---

# Use Cases

- Elderly individuals living alone
- Assisted living centers
- Hospitals
- Family caregiving support systems

---

# Future Enhancements

- Health wearable integration
- Voice personalization
- Doctor connectivity
- Predictive health analytics

---

# Prototype Documentation

Complete prototype documentation, UI flows, architecture diagrams, and technical specifications are available in:

LUMI_Prototype.pdf

---

# Demo

Demo video link:
https://youtu.be/RP4gSlLVhMk?si=x0A4ASaPnNVqwQRw

---

# Team
Team Name: HealSync

Members:
- Mitha B.M
- Navyashree R.K
- Dimpu.M.Gowda

---

# Impact

LUMI aims to create safer, emotionally supportive, and independent living experiences for elderly individuals through AI-powered care.
