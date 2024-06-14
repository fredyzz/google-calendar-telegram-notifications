# Google Calendar Telegram Notifications

This project provides an application that sends notifications to Telegram when events are added or modified in Google Calendar. It's ideal for staying up-to-date with changes in a shared calendar.

## Getting Started

To run this application, you will need to have Node.js installed on your machine. Make sure your Node.js version supports the necessary features such as handling `.env` files.

### Prerequisites

Before running the application, you need to set up an `.env` file at the root of the project that contains all necessary environment variables, such as the credentials for the Google Calendar API and the Telegram bot token.

### Installation

Clone the repository to your local machine using:

```bash
git clone https://your-repository-here.git
cd google-calendar-telegram-notifications
npm install
```

### Running the application

```bash
node --env-file=.env --watch index.js
```
