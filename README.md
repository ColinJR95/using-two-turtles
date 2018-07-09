# using-two-turtles
#project today consisted of learning to draw using two turtles. 

import turtle

window = turtle.Screen()
jr = turtle.Turtle()
jr.color('red')

def draw_square(x):
    for i in range (1,5):
        x.forward(100)
        x.right(90)

def circle_j(y):
    y.circle(100)

def draw_art ():

    draw_square(jr)
    circle_j(jr)

draw_art()
