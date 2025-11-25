
# 📘 SnapSummary – Spring Boot Backend + Chrome Extension 

A lightweight AI-powered web summarizer & notes tool

## 🚀 Overview

SnapSummary is a productivity-focused tool that allows users to:
- Select text on any webpage
- Summarize it instantly using Gemini AI
- Save notes directly to Chrome Local Storage
- View, manage, and update notes from the extension popup

It combines a Spring Boot backend with a Chrome Extension, creating a seamless real-time summarization and note-taking experience right inside the browser.

## Run Locally

Clone the project

```bash
  git clone https://github.com/Amresh6101/SnapSummary.git
```

Go to the project directory

```bash
  cd SnapSummary
```
Add API key as ENV var
```bash
  gemini.api.key=${GEMINI_API_KEY}
   
```   
Start the server on 8080

```bash
mvn spring-boot:run
```
Extension setup
```bash
 go to this url 'chrome://extensions/'
 enable developer mode
 load manifest.json using load unpacked
```

## Screenshots

### Image-1
<img width="953" height="538" alt="Screenshot 2025-11-26 000320" src="https://github.com/user-attachments/assets/e44f518a-c83e-4ed7-bf97-9bf51da0a9f8" />

### Image-2
<img width="952" height="523" alt="Screenshot 2025-11-26 000338" src="https://github.com/user-attachments/assets/519667ea-f0f2-45ed-9fc8-1938b2aaef6e" />


## Author

- [@Amresh Ranjan](https://github.com/Amresh6101)





