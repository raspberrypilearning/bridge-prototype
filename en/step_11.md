## Step 12

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
    if is_drawing() {operator_not_in_circle}:
        fill(current_color)
        circle(mouse_x, mouse_y, 20)
```

At the moment you can colour over the top of your buttons. You can stop this using the `not_in_circle()` function.
If the mouse is down **and** the pointer is not in a circle, then the painting can begin. Complete your `if` statement to make your painting app.
