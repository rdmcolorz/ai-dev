create a python script that takes 2 parameters: input.txt and background.jpeg, and creates output.ppt file

## files

## create_slides.py

This file contains the main logic for splitting text into chunks, creating a ppt file based
on the chunks and background

- `chunk_text`: A function that takes the txt content, use openai gpt-4 to chunk them into an array containing key value pairs where the content value is under 100 characters. EX: [{"title": "Story of my life", "content": "I am a man living in Iowa, planting corn everyday."}]
- `create_slides`: A function that takes the array of key value pairs from `chunk_text` and background.jpeg and use title as large text and content as small text for slides. Creates output.ppt.