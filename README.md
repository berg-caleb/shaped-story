# shaped-story
## GOAL: Take a black and white silouette and a story, fill the image's shape with text 
First though: Python script - input .png, and text

### GPT
Asked GPT for a starting point to find some tools I should learn to help me do this
#### It suggested the libraries:
* PIL (Pillow) – To process the black-and-white image.*
* NumPy – To convert the image into a grid for text placement.
* OpenCV – To analyze image contours and place text accordingly.
* Matplotlib – To visualize the final output.
* Textwrap – To handle line breaks and fit the text properly.
#### And following the rough outline below
Convert the black-and-white image into a NumPy array.
Identify the black (or white) pixels where text should be placed.
Fill those pixels with the input text while maintaining the shape.
Output the final image.

This feels a little overengineered though. So I asked it about other options and it suggested looking for tools in photoshop or gimp that would allow me to restrict text's margin's based on a mask layer
### Gimp
