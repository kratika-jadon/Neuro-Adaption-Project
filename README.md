# Neuro-Adaption-Project

Project Overview: The Neuro-Adaptation Therapy System (NATS) is an AI-powered mental health and cognitive monitoring tool that uses EEG brainwave data to assess a patient’s emotional and cognitive states in real time. It delivers personalized neurofeedback therapy based on this analysis and tracks progress over time.

Core Objectives:

Analyze real-time or simulated EEG data.

Detect mental states: Stressed, Focused, Fatigued, or Neutral.

Deliver adaptive feedback (light, sound, vibration) for therapy.

Track patient sessions and maintain profiles.

Visualize emotional state patterns using graphs and pie charts.

Core Functionalities:

Patient EEG Data Analysis:
Loads unique EEG data per patient.

Evaluates cognitive states using alpha, beta, and theta brainwave ratios.

Cognitive State Detection:
Classifies mental state as:

Stressed

Focused

Fatigued

Neutral

Neurofeedback Response Generation:
Suggests appropriate therapeutic responses based on the detected mental state.

Visual Reporting:
Displays:

Line Graph showing state transitions over time.

Pie Chart summarizing session-wise state distribution.

Patient Profile Management:
Maintains longitudinal mental health history in a JSON file (patients.json).

Appends new session data per patient with timestamps and results.

Session Summarization:
Outputs session duration, cycle-wise results, and total state counts.

CSV Export:
Stores each session’s data in an individual CSV file (therapy_output_{patient_id}.csv).

Interactive History Viewer:
Allows users to retrieve and view a patient’s past sessions and states.

Tech Stack Used:

Python

CSV & JSON (for EEG data and patient profiles)

Matplotlib (for graphs & charts)

Simulated EEG data (can be replaced by real EEG input)

Command-line interface
