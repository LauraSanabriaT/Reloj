j = 0

def setup() :
    size(300, 600)

def draw() :
    global j
    background(175)


    ellipse(width/ 2, j, 50, 50)
    fill(255, 134, 239)
    if j > height :
        j = 0
    else:
        j = map(minute(), 0, 60, 0, height)
        
        
        
        
    ellipse(width/ 2, j, 50, 50)
    fill(226, 134, 255)
    if j > height :
        j = 0
    else:
        j = map(second(), 0, 59, 0, height)
        
        
        

    ellipse(width/ 2, j, 50, 50)
    fill(114, 224, 250)
    if j > height :
        j = 0
    else:
        j = map(hour(), 0, 24, 0, height)
