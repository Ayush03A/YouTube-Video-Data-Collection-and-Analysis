# 📺 YouTube Video Data Collection & Analysis

This Python-based project automates the retrieval of metadata from YouTube videos using the **YouTube Data API v3**. It collects and organizes data for the **top 500 videos** in a user-specified genre and stores the output in a structured CSV file for easy analysis.

---

## 🚀 Features

- 🎯 **Dynamic Genre Input**  
  Accepts a genre (e.g., `music`, `education`) and fetches relevant video data.

- 📊 **Comprehensive Metadata**  
  Collects:  
  - Video URL  
  - Title  
  - Description  
  - Channel Title  
  - Tags  
  - Views & Comments  
  - Captions Availability  
  - Publishing Details

- 📝 **Captions Handling**  
  Automatically downloads captions for videos where available.

- 📂 **CSV Output**  
  Saves everything into a structured `.csv` file (e.g., `music_videos.csv`).

---

## 🧰 Tools & Technologies

- 🐍 **Python 3.x**
- 📦 **Libraries**:  
  - `google-api-python-client` (YouTube API)  
  - `pandas` (Data handling)

- 🔑 **API**: YouTube Data API v3  
- ⚙️ **Tech**: Automation, Data Processing, File Handling

---

## 🖥️ How to Run the Project

### ✅ Prerequisites

1. Python 3.x installed
2. A [YouTube Data API Key](https://console.cloud.google.com/)
3. Install required libraries:

```bash
pip install google-api-python-client pandas
