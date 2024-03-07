<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SocialGPT Features</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        .feature-list {
            list-style: none;
            padding: 0;
        }
        .feature-list li {
            margin-bottom: 10px;
        }
        .feature-list li::before {
            content: "✅";
            margin-right: 8px;
            color: green;
        }
        .feature-list li.incomplete::before {
            content: "❌";
            color: red;
        }
        .colab-button {
            background-color: #f9a825;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>GPT-YouTube-Short-Make</h1>
    <p>GPT-YouTube-Short-Make is an AI-powered tool that utilizes OpenAI's GPT-4 model to recreate videos based on YouTube short links. This project aims to generate engaging and motivational video content by leveraging artificial intelligence.</p>
    
    <h2>Features</h2>
    <ul class="feature-list">
        <li>Get the transcript for a video</li>
        <li>Generate similar scripts</li>
        <li>Pick the best one</li>
        <li>Generate a voice over for the video</li>
        <li>Download background videos (luxury cars, mansions, vacations, etc)</li>
        <li>Create 9:16 video (One vision 3-5 seconds, scene transition, caption, caption bounce, filter)</li>
        <li>(Optional) Use trending background music</li>
        <li>Use GPT-4 to generate video titles</li>
        <li>Guess the music using shazam or similar service and get the youtube link</li>
        <li>Generate a caption for video</li>
        <li>The generated video transcript is not sounds as "effective" as an original one</li>
        <li>Add watermark</li>
        <li>Add ability to post on youtube</li>
        <li class="incomplete">Resolve youtube 'No, it's not made for kids'</li>
        <li class="incomplete">Keep it under 1 minute</li>
        <li class="incomplete">Auto search for reference video</li>
        <li class="incomplete">Add ability to post on Instagram</li>
        <li class="incomplete">If reference youtube video is age restricted try to download the next one</li>
    </ul>

    <h2>Usage</h2>
    <p>To recreate the provided example, run the <a href="https://github.com/enterprisium/SocialGPT/blob/main/Youtube_Similar_Shorts_Genration.ipynb">main.ipynb</a> notebook. Make sure to set the required environment variables, such as OPENAI_API_KEY and PEXELS_API_KEY.</p>
    
    <a href="https://colab.research.google.com/github/enterprisium/SocialGPT/blob/main/Youtube_Similar_Shorts_Genration.ipynb" class="colab-button" target="_blank">Open in Google Colab</a>

    <h2>Sample Output</h2>
    <p>Check out the <a href="https://www.youtube.com/@MojoVibesDaily/shorts">sample YouTube channel</a> to view the output generated by this tool.</p>
</body>
</html>
