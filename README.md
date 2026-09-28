# AI Real-Estate Lead Qualification & Notification Automation

An AI-powered automation system that captures real-estate enquiries, qualifies them using Google Gemini, prioritizes leads, and notifies agents automatically.

## Overview

Real-estate businesses can receive many property enquiries, making it difficult for agents to identify which leads need immediate attention.

This project automates the initial lead qualification process and organizes enquiries based on their level of priority.

## Workflow

**Lead Form → Google Sheets → Google Gemini → Lead Classification → Agent Notification → Lead Tracking**

### How it works

1. A prospective customer submits a property enquiry.
2. The lead is automatically added to Google Sheets.
3. Google Gemini analyzes the enquiry.
4. The lead receives a score from 0–100.
5. Gemini classifies the lead as:

   * HOT: 80–100
   * WARM: 50–79
   * COLD: 0–49
6. Gemini generates a short reason for the classification.
7. HOT and WARM leads trigger an email notification.
8. Lead and notification status are tracked in Google Sheets.

## Tech Stack

* Tally – Lead capture
* Google Gemini – AI lead qualification 
* Make – Workflow automation
* Google Sheets – Lead database and tracking
* Gmail – Agent notifications

## Key Features

* Automated lead capture
* AI-powered lead scoring
* HOT / WARM / COLD classification
* AI-generated qualification reasoning
* Automated email notifications
* Lead status tracking
* Notification tracking
* Reduced manual lead sorting

## Example

A lead submitting:

* Intent: Buy
* Property Type: 3 BHK
* Location: Baner
* Budget: ₹1.2 Cr
* Timeline: Immediately
* Requirements: Looking for a ready-to-move-in property and interested in scheduling a site visit.

can be analyzed by Gemini and classified based on the information provided.

## Project Demo

[Add demo video link here]

## Screenshots

Screenshots of the workflow and automation will be added here.




## Future Improvements

* Automated agent assignment
* Round-robin lead distribution
* WhatsApp notifications
* CRM integration
* Automated follow-up reminders
* Multiple lead-source integrations
* Analytics and reporting dashboard

## Note

This project is an MVP demonstrating an AI-powered lead qualification and notification workflow. Demo data is used for portfolio purposes.

