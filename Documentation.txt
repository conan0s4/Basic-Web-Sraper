# Dark Web & Surface Web Scraper

Author: Alexander M. Sapo  
Course: BSIT 1st Year – 2nd Semester Finals Project  
Subject: Human-Computer Interaction  
Goal: Learn offensive programming and efficient open-source intelligence (OSINT)

---

## Project Description
This is a Python-based web scraper capable of accessing and extracting data from both the surface web and the dark web using Tor. It's designed for OSINT purposes and demonstrates the basics of web scraping, anonymity, and data collection.

---

## What is Web Scraping?
Web scraping is an automated method of gathering data from websites.

---

## Features
- Supports both surface and `.onion` sites (dark web)
- Tor integration via SOCKS5 proxy (`localhost:9050`)
- Extracts:
  - Usernames (e.g., @username)
  - Standard links (href)
  - `.onion` links
- Simple interface and terminal-based interaction
- Educational banner and ASCII art

---

## Scraping Process
1. Identify the target website
2. Enter its URL
3. Send an HTTP request (via Tor or direct)
4. Parse the HTML content using BeautifulSoup
5. Extract specific data (usernames, links, onion links)
6. Display results in the terminal

Note: Crawler not implemented yet – Currently scrapes only the first page. You can manually re-run with new links.

---

## Requirements
- Python 3.x
- Tor (running locally)
- ProxyChains (optional)
- Python packages:
  - requests
  - bs4 (BeautifulSoup)
  - re (standard)

Install required packages using: pip install requests beautifulsoup4
