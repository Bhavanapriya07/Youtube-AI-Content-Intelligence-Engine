# AI Content Intelligence Engine

This project analyzes YouTube content automatically using AI and generates insights through Google Sheets.

## Project Overview

The system fetches YouTube video data from selected channels and uses AI to analyze titles, descriptions, and trends. The results are stored in Google Sheets.

## Architecture

YouTube API → Google Apps Script → AI Analysis (OpenRouter) → Google Sheets Dashboard → Gmail Report

## Tools Used

Google Apps Script  
YouTube Data API  
OpenRouter AI API  
Google Sheets  
Gmail Automation

## Automation

The system runs automatically using an hourly trigger in Google Apps Script.

Every hour it:
- Fetches new YouTube video data
- Sends the content to AI for analysis
- Updates the Google Sheet
- Sends an email report

## Dashboard

The dashboard shows insights about:
- Video topics
- Content strategy
- Trends

## Future Improvements

- Multi-platform analysis (Instagram, TikTok, Twitter, Podcasts)
- Virality prediction using ML
- Real-time trend detection
- Web dashboard instead of Google Sheets
