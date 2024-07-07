# YouTube Data Collection and Analysis using Youtube Data API v3

## Overview

This project focuses on gathering and analyzing data from YouTube to identify factors that contribute to a video's success on the platform. The goal is to understand what makes a video trend on YouTube by collecting data on trending videos and analyzing various metrics.

## Data Collection

To collect data from YouTube, you need to set up an API. Follow these steps to obtain your API key and start collecting data:

### Steps to Set Up YouTube Data API v3

1. **Go to [Google Cloud Console](https://console.developers.google.com/)**.

2. **Create a New Project**:
   - Click on the project drop-down at the top.
   - Select “New Project”.
   - Enter a project name and click “Create”.

3. **Enable YouTube Data API v3**:
   - In the Google Cloud Console, navigate to **“APIs & Services” > “Library”**.
   - Search for **“YouTube Data API v3”** and click on it.
   - Click **“Enable”**.

4. **Generate API Key**:
   - Go to **“APIs & Services” > “Credentials”**.
   - Click **“+ CREATE CREDENTIALS”** and select **“API key”**.
   - Copy the generated API key.

With your API key, you can start collecting data on trending YouTube videos.

### Analysis
![download](https://github.com/sathvik995/Youtube-Data-Collection-and-analysis-using-Youtube-Data-API/assets/88426655/27f103a9-5c26-4786-870d-cd653829fa37)
- The scatter plot reveals a slight negative correlation between video length and view count, suggesting that shorter videos generally attract more views. Videos in the 5-10 minute range show the highest average view counts, likes, and comments.

![download](https://github.com/sathvik995/Youtube-Data-Collection-and-analysis-using-Youtube-Data-API/assets/88426655/8f0570a5-8882-4e36-bf64-9d595bf63be6)
![download](https://github.com/sathvik995/Youtube-Data-Collection-and-analysis-using-Youtube-Data-API/assets/88426655/27eb9744-3ce1-4a81-beed-94dee7f70c84)
- The distribution indicates that most videos are published between 14:00 and 20:00 hours (2 PM – 8 PM), suggesting this might be an optimal time for video uploads. There is a very weak negative relationship between the hour of publication and view count, implying that the time of day has minimal impact on engagement metrics



### Conclusion

Based on the data collected and analyzed, here are the conclusions about what makes a video trend on YouTube:

- **Encourage viewers to like and comment** on videos to improve engagement metrics.
- **Create shorter or mid-length videos (under 10 minutes)** for better engagement, especially in categories like Music and Entertainment.
- **Schedule your video uploads during peak times (2 PM – 8 PM)** to maximize initial views and boost engagement.
