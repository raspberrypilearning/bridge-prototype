## Step 10

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

my_image = "lizard.webp"

def setup():
    add_background(100, 170, 500, 500)

def draw():
    if is_drawing() :
        circle(mouse_x, mouse_y, {draw_circle_radius})
```

`draw()` is another function, it will contain code to control the paintbrush and add colours to your image.

It uses an `if` statement, to detect if the mouse button is pressed or not.

If the mouse button is pressed, a circle will be drawn at the `x` and `y` position of the mouse pointer.

You can choose a value for the size of the circle.

Click **Run code** and you can start painting over the image you chose.
