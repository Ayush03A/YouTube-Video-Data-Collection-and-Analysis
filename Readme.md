**\# YouTube Video Data Collection and Analysis**    
**\#\# Project Overview**    
This Python-based project automates the retrieval of metadata from YouTube videos using the YouTube Data API. It collects and organizes data for the top 500 videos in a user-specified genre, including detailed metrics like captions, view counts, and publishing details. The output is saved in a structured CSV file for analysis.    
\#\# Features    
\- **\*\*Dynamic Input\*\***: Accepts a genre as input and dynamically retrieves data for the specified category.    
\- **\*\*Comprehensive Data\*\***: Collects details such as video URL, title, description, channel, tags, views, comments, captions, and more.    
\- **\*\*Caption Handling\*\***: Downloads captions for videos with captions enabled.    
\- **\*\*Structured Output\*\***: Saves the extracted data into a CSV file for easy analysis and reporting.    
\#\# Skills & Tools Used    
\- **\*\*Programming Language\*\***: Python    
\- **\*\*Libraries\*\***:    
  \- \`google-api-python-client\` (YouTube Data API)    
  \- \`pandas\` (Data manipulation and CSV handling)    
\- **\*\*APIs\*\***: YouTube Data API v3    
\- **\*\*Technologies\*\***: Dynamic data processing, automation, and file handling.    
\#\# How to Run the Project    
\#\#\# Prerequisites    
1\. Python 3.x installed on your system.    
2\. A YouTube Data API Key (Get it from \[Google Cloud Console\](https://console.cloud.google.com/)).    
3\. Install the required Python libraries:    
   \`\`\`bash  
   pip install google-api-python-client pandas

**Steps to Execute**

	1\.	Clone this repository to your local system:  
git clone https://github.com/your-username/your-repo-name.git  
cd your-repo-name

	2\.	Replace YOUR\_YOUTUBE\_API\_KEY in the script with your actual API key.

	3\.	Run the script:  
python script\_name.py

	4\.	Enter the desired genre when prompted (e.g., “music”, “education”).

	5\.	The script generates a CSV file (e.g., music\_videos.csv) containing the metadata for    500 videos in the specified genre.

**Sample Output**  
The script creates a CSV file with the following columns:

	•	Video URL

	•	Title

	•	Description

	•	Channel Title

	•	Keyword Tags

	•	YouTube Video Category

	•	Video Published At

	•	Video Duration

	•	View Count

	•	Comment Count

	•	Captions Available

	•	Caption Text

	•	Location of Recording

Example Row:  
**Video URL**	**Title**	**Description**	**Channel Title**	**View Count**	**Captions Available**  
[YouTube Link](https://youtu.be/xyz123)	Example Video	This is a description.	Channel Name	1,000,000	True  
**Project Structure**  
├── script\_name.py         \# Main Python script  
├── README.md              \# Project documentation  
├── requirements.txt       \# Required libraries  
├── sample\_output.csv      \# Example output CSV  
**Future Enhancements**

	•	Add functionality to analyze the data for trends and insights.

	•	Extend the script to support other video platforms.

	•	Visualize data using tools like Power BI or Tableau.  
**License**  
This project is licensed under the MIT License.  
**Contact**  
If you have questions or feedback, feel free to reach out:

	•	**Author**: Ayush Anand

	•	**Email**: 0310ayushanand@gmail.com

	•	**GitHub**: [Ayush03A](https://github.com/Ayush03A)

