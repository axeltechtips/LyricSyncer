

# LyricSyncer 🎵  
**Effortlessly add lyrics to your music library!**  

LyricSyncer is a Python-powered tool with a user-friendly GUI that fetches song lyrics from Genius and embeds them directly into your `.mp3` files. Perfect for keeping your music collection complete and enriched with synced lyrics.  

## Features:
- Automatically fetch and embed lyrics using the Genius API.
- Easy-to-use GUI for folder selection and progress monitoring.
- Supports `.mp3`, `.m4a`, `.flac`, and `.wav` files with proper metadata (title and artist).
- Real-time logs and error handling for missing metadata or lyrics.

## Requirements:
- Python 3.x
- Genius API key
- `mutagen` and `lyricsgenius` libraries

## How to Use:
1. Clone the repository:
   ```
   git clone https://github.com/axeltechtips/LyricSyncer.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Create a Genius API key:
   - Go to the [Genius API client page](https://genius.com/api-clients/new).
   - Use **LyricSyncer** as the name for your API client.
   - Use our GitHub repo link or any link as the App Website
   - Copy the **Client Access Token** (API key) provided after creating your API client.
4. Run the script and select your music folder via the GUI:
   ```
   python lyric_syncer.py
   ```
5. Sit back as LyricSyncer enriches your songs with lyrics!

## Setup Guide:
1. Install Python 3.x from [python.org](https://www.python.org/downloads/).
2. Install the required dependencies by running:
   ```
   pip install mutagen lyricsgenius
   ```
3. Make sure you have your Genius API key ready before using the tool.

## Contributing:
Feel free to contribute by opening issues or pull requests in the GitHub repository.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
