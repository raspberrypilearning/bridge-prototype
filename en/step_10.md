## Step 10

```python
circle_radius = ##

pos_1 = (0, 0) 
col_1 = (255, 255, 0)

pos_2 = (#, #, #)
col_2 = (#, #, #)

pos_3 = ()
pos_3 = ()

# HERE WOULD BE THE OTHER VARIABLE THEY HAVE SET

my_image = "cat.jpg"

def draw():
    add_background(200, 50, 400, 400)
    if mouse_down():
        circle(mouse_x, mouse_y, 0) ##They can choose a value for the size of the circle.
    
```

The function `draw()` now uses an `if` statement, to detect if the mouse button is pressed or not. If it is, then it will draw a circle at the `mouse_x` and `mouse_y` position. Yoy can choose a value for the size of the circle it will draw.