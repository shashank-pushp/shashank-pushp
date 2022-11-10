import turtle


def draw_A(pen):

 pen.setposition(30, -110)
 pen.pendown()
 pen.begin_fill()
 pen.color('red')
 pen.pensize(10)
 pen.pencolor('white')
 pen.forward(23)
 pen.backward(123)
 pen.left(60)
 pen.backward(220)
 pen.right(60)
 pen.backward(100)
 pen.right(117)
 pen.backward(710)
 pen.right(63)
 pen.backward(110)
 pen.right(90)
 pen.backward(510)
 pen.right(90)
 pen.backward(100)
 pen.right(90)
 pen.backward(70)
 pen.end_fill()
 pen.penup()

def draw_triangle(pen):

 pen.pensize(10)
 pen.setposition(53, -40)
 pen.pendown()
 pen.begin_fill()
 pen.color('black')
 pen.pencolor('white')
 pen.right(90)
 pen.forward(100)
 pen.right(115)
 pen.forward(250)

 pen.right(157)
 pen.forward(227)
 pen.end_fill()

def draw_arrow(pen):

 pen.backward(80)
 pen.left(42)
 pen.forward(147)
 pen.right(83)
 pen.forward(140)

if __name__ == '__main__':
 win = turtle.Screen()
 win.bgcolor('black')

 avengers = turtle.Turtle()
 avengers.speed(10)
 avengers.pensize(10)
 avengers.penup()


draw_A(avengers)
draw_triangle(avengers)
draw_arrow(avengers)

avengers.hideturtle()
turtle.done()


