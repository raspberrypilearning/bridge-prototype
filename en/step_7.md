## Step 8

```python
circle_radius = 40

pos_1 = (400, 150)
col_1 = (0, 255, 0)

pos_2 = (500, 150)
col_2 = (255, 0, 0)

pos_3 = (300, 150)
col_3 = (0, 0, 255)

pos_4 = (400, 50)
col_4 = (255, 0, 255)

my_image = "dog.webp"

def setup():
    add_background({background_x}, {background_y}, {background_width}, {background_height})
```
You have been provided with an image to paint over, but you need to decide its size and position.

A function called `setup()` contains a function call to `add_back_ground()`. This is used to set the background image. The first two numbers set the position of the image, and the second two numbers set the size of the image.

Experiment with the position and size of the image, so that it looks correct on your screen.


