### YouTube Channel Video Analysis using YouTube API    

This Python project is designed to access a user's YouTube channel and retrieve details of all the videos within the channel. The script creates a Pandas DataFrame containing information on each video, including the title, publish date, number of views, likes, and comments.

### Prerequisites   
* Python 3.x
* Google API key
* Channel ID

### Installation    
Clone the repository: *git clone https://github.com/username/YouTube-Video-Analysis.git*    
Install the required packages: *pip install pandas requests*

### Usage   
* Enter your Google API key and YouTube Channel ID in the keys.py file.
* Run the script youtube_api.py. The script will output a Pandas DataFrame containing details of all the videos within your channel.
* The DataFrame is sorted by view count in descending order to show the most viewed videos in the channel.

### Functionality   
The script uses the YouTube Data API v3 to retrieve data on a user's channel and videos. It makes a GET request to the API with the user's API key and channel ID to retrieve the necessary data. The data is then parsed to extract the required information and create a Pandas DataFrame.

The **'get_videos'** function retrieves the details of all videos in the channel, including the video ID, title, publish date, view count, likes, and comments. The **'Video ID'** column is dropped from the DataFrame, and the **'View Count'** column is converted to an integer to enable sorting by view count.

### Contributions   
Contributions to this project are welcome. To contribute, please create a pull request and include a description of the changes made.

### Acknowledgements    
This project was inspired by Moringa School

### Contact 
If you have any questions or comments about this project, please feel free to contact me at ekaledaniel84@gmail.com.