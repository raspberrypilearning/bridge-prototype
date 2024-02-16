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

my_image = "cat.png"

def draw():
    add_background(200, 50, 400, 400)
    if mouse_down():
        circle(mouse_x, mouse_y, 0) ##They can choose a value for the size of the circle.
    
```

`draw()` is another function, it will contain code to control the paintbrush and add colours to your image.

It uses an `if` statement, to detect if the mouse button is pressed or not.

If the mouse button is pressed, a circle will be drawn at the `x` and `y` position of the mouse pointer.

You can choose a value for the size of the circle.

Click **Run code** and you can start painting over the image you chose.