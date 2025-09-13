# Ayn-Path: AI-Driven Smart Indoor Navigation System with AR for the Visually Impaired

<img width="746" height="776" alt="AynPath_Prototype" src="https://github.com/user-attachments/assets/515efdb7-f636-4576-95d9-a29a3edc2573" />

## Overview

Navigating inside large buildings is often difficult for people with disabilities, especially those who are blind or have low vision. Most navigation tools today are designed for outdoor use and depend on GPS, which is unreliable indoors because of weak satellite signals. This makes it challenging to move through complex spaces such as campuses, shopping malls, or office buildings. Existing assistive apps usually focus on one specific feature, like detecting objects, reading text aloud, or guiding someone across a street. To get the full navigation experience, users often have to switch between several different apps, which can be inconvenient and overwhelming.

**Ayn-Path** is my Final Year Project (FYP), developed to bring these needs together in a single application. By combining artificial intelligence and augmented reality, the system offers accurate indoor localization, detects obstacles commonly found in buildings, and provides real-time guidance. Directions are delivered through clear audio cues, gentle haptic feedback, and AR-based visual arrows. For this project, the implementation is focused on **Block A, Level 1 of KICT IIUM**, serving as the test environment for indoor navigation. The goal of Ayn-Path is to give blind and visually impaired people more independence and confidence when moving through indoor environments, making navigation safer, smoother, and easier.

## Repositories

* [aynpath-datasets](https://github.com/Ayn-Path/aynpath-datasets) - Training and testing datasets for obstacle detection and indoor feature recognition. Includes annotated images, extracted ORB features, with the code for extracting them.

* [aynpath-app](https://github.com/Ayn-Path/aynpath-app) - Flutter-based AR navigation app. Contains the full user interface and functional modules, integrating localization, obstacle detection, audio guidance, haptic feedback, and AR visual arrows.

* [aynpath-server](https://github.com/Ayn-Path/aynpath-server) - Backend service for indoor localization and navigation. Provides APIs for VPS matching of the user’s current location using ORB features and image-based positioning.

* [aynpath-object-detection](https://github.com/Ayn-Path/aynpath-object-detection) - Object detection module powered by MobileNetV1 (TensorFlow Lite). Includes a pretrained model based on the COCO dataset, optimized for detecting common indoor obstacles.

## Tools Used
* Flutter
* Unity
* Python

## Video Demonstration
