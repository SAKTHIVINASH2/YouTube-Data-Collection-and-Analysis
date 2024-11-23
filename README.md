# YouTube-Data-Collection-and-Analysis
This project is designed to collect and analyze trending video data from YouTube using the YouTube Data API v3. The goal is to understand the key factors that contribute to a video becoming popular on YouTube.


## Overview
The YouTube Data API v3 provides access to detailed information about YouTube videos, channels, and playlists. By leveraging this API, we can extract data such as video titles, descriptions, statistics, and more. This project focuses on trending videos to identify patterns and trends.

## Prerequisites
1. A Google Cloud Console account.
2. The YouTube Data API v3 enabled for your project.
3. An API key generated in the Google Cloud Console.

---

## Features
* Fetches trending video data using YouTube Data API v3.
* Collects video metadata, statistics, and additional details.
* Analyzes engagement metrics to identify key trends.
* Provides a foundation for further data analysis and visualization.

---

## Setup Instructions
Step 1: Set Up Google Cloud Project
1. Log in to Google Cloud Console.
2. Create a new project by clicking the project drop-down and selecting New Project.
3. Enable YouTube Data API v3 under APIs & Services > Library.

Step 2: Generate API Key
1. Navigate to APIs & Services > Credentials.
2. Click + CREATE CREDENTIALS and select API Key.
3. Copy the generated key to use in the project scripts.

---

## How to Use
1. Clone the repository:
```
git clone https://github.com/your-username/YouTube-Data-Analysis.git  
cd YouTube-Data-Analysis
```
2. Install required Python libraries:
```
pip install -r requirements.txt
```
3. Replace YOUR_API_KEY in the script with your YouTube Data API key.
4. Run the script to fetch and save trending video data.

---

## Data Collected
The following fields will be extracted for analysis:
1. Video Metadata: Title, description, tags, and published date.
2. Statistics: View count, like count, comment count.
3. Additional Details: Duration, video quality (HD/SD), and caption availability.

---

## Goals of Analysis
* Identify trends in popular video categories.
* Analyze viewer engagement metrics.
* Determine optimal posting times for trending videos.

---

## Future Improvements
* Add visualization for trends and patterns.
* Expand data collection to include comments and sentiment analysis.
* Automate periodic data collection.

---

## Resources
* [Google Cloud Console](https://cloud.google.com/free?utm_source=PMAX&utm_medium=display&utm_campaign=FY24-H2-apac-gcp-DR-campaign-IN&utm_content=in-en&gad_source=1&gclid=CjwKCAiAl4a6BhBqEiwAqvrquvxZUGIm6eVFeUAYPzWtWD98tpQlaF02EYbwx7tL5c7y_ZtbiqYpVxoCp0cQAvD_BwE&gclsrc=aw.ds)
* [YouTube Data API v3 Documentation](https://developers.google.com/youtube/v3/getting-started)

---

## License
This project is licensed under the [MIT License](LICENSE)
