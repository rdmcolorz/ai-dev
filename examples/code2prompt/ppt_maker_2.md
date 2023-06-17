create a python script that takes 2 parameters: input.txt and background.jpeg, and creates output.ppt file

## files

## create_slides.py

This file contains the main logic for splitting text into chunks, creating a ppt file based
on the chunks and background

`create_presentation()`: This function creates a new PowerPoint presentation.
- It initializes a presentation object using the python-pptx library.
- You can set the slide layout, title, author, etc.
`add_slide()`: This function adds a new slide to the presentation.
- You can specify the slide layout, such as a title slide, content slide, etc.
- You can set the title and content of the slide.
`add_text_box()`: This function adds a text box to a slide and sets its content.
- You can specify the position, size, and formatting of the text box.
- You can also set the font, font size, color, etc.
`add_image()`: This function adds an image to a slide.
- You can specify the image file path and its position on the slide.
- You can also set the size, scale, and other properties of the image.
`save_presentation()`: This function saves the presentation to a file.
- You can specify the file name and path where the presentation should be saved.
`convert_text_to_slides()`: This is the main function that converts the input text into slides.
- It can take the input text as a parameter.
- This function can split the text into separate slides or sections.
- It can utilize the above functions to create slides, add content, and save the presentation.
