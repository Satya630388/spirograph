import random
import turtle as t
t.colormode(255)

tim=t.Turtle()

def random_colour():
    r= random.randint(0,255)
    g = random.randint(0, 255)
    b = random.randint(0, 255)
    colour=(r,g,b)
    return colour
## to draw a spirograph

tim.speed('fastest')

def spirograph(gap_size):
    for i in range(int(360/gap_size)):
        tim.color(random_colour())
        tim.circle(100)
        tim.setheading(tim.heading()+gap_size)

spirograph(5)

screen=t.Screen()
screen.exitonclick()
