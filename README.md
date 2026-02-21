# the-geometric-architect
def draw_square( size, char ):
for i in range (size):
     print( char * size)
     
shape = input(" Enter shape( square/ triangle): ")
size =  int(input("Enter size: "))
char = input ("Enter symbol: ")

if shape == "square":
    draw_square( size, char)
