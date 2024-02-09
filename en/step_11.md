## Step 11

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
        fill()
        circle(mouse_x, mouse_y, 0) ##They can choose a value for the size of the circle.
    
```

The colour of the drawn circle can changed by setting its `fill`. Try these options for fill, to see what they do.

```python
fill(255, 255, 255)
```
```python
fill(0, 0, 0)
```
```python
fill(255, 0, 255)
```
```python
fillcurrent_color)
```