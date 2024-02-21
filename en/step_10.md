## Step 11

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
        fill({fill_colour})
        circle(mouse_x, mouse_y, 20)
```

The colour you are drawing can changed by setting its `fill`. 

This uses the same RGB system as before, so you could add in three numbers between `0` and `255`. However the colour of the last button you clicked on is stored in a variable called `current_color`. Try adding `current_color` to the code, then *click **Run code**. You should now be able to select your colours to paint.
