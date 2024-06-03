# Cryptocurrency Monitoring and Alert System

## Overview
This project is a comprehensive Cryptocurrency Monitoring and Alert System developed as a Year 13 NEA (Non-Exam Assessment) for A-level Computer Science. The system allows users to monitor the price of Dogecoin in real-time, view historical price data, and receive alerts when Elon Musk tweets about cryptocurrency. The project was developed using Python, leveraging various APIs and libraries to create an interactive and user-friendly application.

## Table of Contents
- [Background](#background)
- [Problem Identification](#problem-identification)
- [Current System Description](#current-system-description)
- [Prospective Users](#prospective-users)
- [User Needs](#user-needs)
- [Chosen Solution](#chosen-solution)
- [Design](#design)
- [Implementation](#implementation)
- [Testing](#testing)
- [Evaluation](#evaluation)
- [Appendix](#appendix)

## Background
Cryptocurrency is a digital currency without physical intrinsic value, created as a decentralized online currency. Bitcoin was the first cryptocurrency, leading to the creation of others like Dogecoin. Cryptocurrency prices are highly volatile and influenced by public figures like Elon Musk. An app to monitor and analyze these fluctuations can be beneficial for investors.

## Problem Identification
Cryptocurrency prices, particularly Dogecoin, fluctuate significantly based on tweets by influencers like Elon Musk. A tool to monitor cryptocurrency prices and provide alerts when relevant tweets are made would help investors make informed decisions.

## Current System Description
Current solutions like "Elon Stocks" offer similar functionalities but have limitations such as being paid services, lack of real-time stock price display, and dependence on mobile networks. 

## Prospective Users
- **Stock Market Brokers and Investors**: To decide when to buy/sell cryptocurrency.
- **Stock Market Analysts and Researchers**: To study the impact of tweets on cryptocurrency prices.
- **Specific User - Robert Carter**: An investor in Dogecoin influenced by Elon Musk's tweets.

## User Needs
1. Display real-time Dogecoin price graphs.
2. Show historical cryptocurrency price trends.
3. Display and alert users of Elon Musk's tweets.
4. Store data in an SQL database for analysis.
5. Simple, clear, and user-friendly interface.
6. Live feed of tweets about cryptocurrency.
7. Email alerts for tweets by Elon Musk regarding cryptocurrency.

## Chosen Solution
Python was selected due to its extensive libraries and ease of handling APIs and complex OOP concepts. Tkinter was used for GUI, Matplotlib for graphing, Tweepy for Twitter API, and Yahoo Finance for stock market data.

## Design
The program is structured with various modules for different functionalities:
- **Graphing Algorithm**: Uses Matplotlib to display historical and live prices.
- **Twitter Feed Algorithm**: Uses Twitter API to fetch and display relevant tweets.
- **Elon Musk Tweet Algorithm**: Fetches Elon Musk's tweets and sends email alerts.
- **Email Algorithm**: Uses SendGrid API for sending email alerts.
- **GUI**: Built with Tkinter, includes multiple interactive windows.

## Implementation
### Key Modules and Algorithms
- **Graphing Algorithm**: Downloads data from Yahoo Finance and plots it using Matplotlib.
- **Twitter Feed Algorithm**: Connects to Twitter API and updates the feed.
- **Elon Musk Tweet Algorithm**: Checks for new tweets and sends alerts.
- **Email Algorithm**: Connects to SendGrid API to send emails.
- **GUI Algorithm**: Manages the user interface and dynamically creates new windows.

## Testing
Extensive testing was conducted to ensure the system meets the user needs. Tests included checking real-time data updates, historical price graph generation, tweet fetching, and email alert functionality. Detailed test cases and their results are documented in the project report.

## Evaluation
### Achievements
- Implemented core features: real-time and historical price graphs, tweet feed, and alerts.
- Successfully used APIs and libraries to achieve desired functionalities.
- User feedback indicated satisfaction with the application's performance and features.

### Areas for Improvement
- Implementing animated graphs on the home screen.
- Allowing users to enter their email credentials and choose email servers.
- Formatting tweets graphically in the style of standard tweets.

## Appendix
### Sources
- Stack Overflow
- RapidAPI
- Tweepy Documentation
- Real Python
- MySQL Documentation
- DataCamp
- Linux Tutorials
- Python Tkinter Documentation



Download the project code and documentation for further details and to contribute to its development.

**[Download the Project](#)** | **[Report Issues](#)** | **[Contribute](#)**
