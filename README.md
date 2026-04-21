# WhatsApp AI Chatbot

A live AI-powered WhatsApp chatbot built with n8n and Google Gemini.
Replies to incoming messages as Maya, VisionGroup's AI sales assistant,
and logs all conversations to Google Sheets automatically.

## What it does
- Receives WhatsApp messages via Twilio webhook
- Sends message to Gemini AI for intelligent response
- Replies instantly to the user on WhatsApp
- Logs full conversation history to Google Sheets

## Workflow
Twilio webhook → n8n → Gemini AI → Twilio reply → Google Sheets

## Tech stack
- n8n (workflow automation)
- Twilio (WhatsApp API)
- Google Gemini API (AI responses)
- Google Sheets (conversation logging) 

## How to import
1. Download workflow.json
2. Open n8n → Import from file
3. Add your Twilio and Gemini credentials
4. Set Twilio webhook URL to your n8n webhook URL
5. Activate workflow

## Use case
Demonstrates end-to-end WhatsApp AI chatbot automation —
applicable to customer engagement and AI sales deployments.
Google Sheet Link for Conversation Logs - [Conversation Logs](https://docs.google.com/spreadsheets/d/1PA8LO9HWCCf9npbSHdfp8Df88JS3oih4rm8yWXS7OeU/edit?usp=sharing)

---
Built by Mohamad Ashraf bin Oothman Sah
QA Automation Engineer → AI Workflow Automation