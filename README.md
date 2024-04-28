# SchedulerAI

## Overview
The SchedulerAI notebook provides a Python script that utilizes the Google Calendar API to manage events. With SchedulerAI, you can easily add, delete, shift, and check appointments in your Google Calendar, all from the convenience of the command line.

## Prerequisites
Before using SchedulerAI, you need to set up the Google Calendar API and obtain the necessary credentials. Here's how you can do it:

1. **Create a Google Cloud Project**:
   - Go to the [Google Cloud Console](https://console.cloud.google.com/).
   - Create a new project or select an existing one.

2. **Enable the Google Calendar API**:
   - In the Cloud Console, navigate to the "API & Services" > "Library" page.
   - Search for "Google Calendar API" and enable it for your project.

3. **Create OAuth 2.0 Credentials**:
   - In the Cloud Console, navigate to the "API & Services" > "Credentials" page.
   - Click on "Create Credentials" and select "OAuth client ID".
   - Choose "Desktop app" as the application type.
   - Save the generated credentials (JSON file) to your local machine.

## Setup
Once you have obtained the Google Calendar API credentials, follow these steps to set up SchedulerAI:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your_username/SchedulerAI.git
   cd SchedulerAI
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Place Credentials File**:
   - Move the credentials JSON file (obtained from the Google Cloud Console) to the `.credentials` directory within the repository.

## Usage
To use SchedulerAI, open the Jupyter Notebook file (`SchedulerAI.ipynb`) in Jupyter Notebook or JupyterLab. Follow the instructions provided within the notebook to manage your Google Calendar events.

## Replicating Google Calendar API
If you're interested in replicating the functionality of the Google Calendar API used in SchedulerAI, you can refer to the code provided in the notebook. It demonstrates how to authenticate users, interact with calendar events, and handle errors and exceptions.

## Support and Contributions
For any questions, issues, or feedback regarding SchedulerAI, please open an issue on the GitHub repository. Contributions are welcome via pull requests.


