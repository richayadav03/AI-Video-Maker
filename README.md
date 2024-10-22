# AI-Video-Maker
This project aims at creating a tool that helps to convert web contents into summarized videos to simplify work. Given a URL it is able to download the content of the page, generate a brief summary of the text as well as add narration using text-to-speech functionality. It also creates visual images known as B-roll according to the content of the page as well as provide written text for subtitles or texts overlay. 

## Features
- **Web Page Parsing**: Automatically extracts and summarizes web page content.
- **Text-to-Speech**: Converts the summarized text into a voiceover using external services or libraries.
- **B-roll Image Generation**: Generates relevant images based on the page content.
- **Subtitles**: Adds subtitles or text overlays based on the summarized content.
- **Video Creation**: Uses FFmpeg to combine voiceover, images, and subtitles into a complete video file.

## Requirements
- Node.js
- FFmpeg (with `ffmpeg-static` and `fluent-ffmpeg`) - It is an open source multimedia tool that is used for capturing, decoding/encoding or streaming videos and audios, and other related tools with support for numerous formats.
- External text-to-speech and image generation services

## Dependencies
- **@gptscript-ai/gptscript**: For generating summaries or interacting with AI models.
- **ffmpeg-static** and **fluent-ffmpeg**: To manage and process media content.
- **express** and **cors**: For handling HTTP requests and cross-origin resource sharing.
- **dotenv**: For managing environment variables.
- **uniqid**: To generate unique identifiers for files or requests.
- **path** and **fs**: For file system and path handling.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/richayadav03/AI-Video-Maker.git
    cd AI-Video-Maker
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Ensure FFmpeg is installed and available on your system.

## Usage
1. Run the script by providing the URL of the webpage to convert:
    ```bash
    node generateVideo.js <webpage_url>
    ```

## License
[MIT License](LICENSE)



