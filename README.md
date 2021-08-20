# pookalam


## Code

    Outer Circles
    c1 = circle(r=150, fill="DarkOrange", stroke="none")
    c2 = circle(r=140, fill="#00FF00", stroke="none") 
    c3 = circle(r=125, fill="yellow", stroke="none") 
    c4 = circle(r=110, fill="red", stroke="none") 
    show(c1,c2,c3,c4)
    #Repeating Ellipses
    shape1 = ellipse(fill="Gold") | repeat(10, rotate(30))
    shape2 = ellipse(fill="DarkGreen") | repeat(10, rotate(60))
    show(shape1,shape2)
    s1= rectangle(h=200, w=200, fill='#FF99CC') | (repeat(30, rotate(20))) | scale(0.6)
    show(s1)
    #Purple Flowers
    petals = ellipse(w=6,h=10,x=0,y=10, fill="purple")
    flower = petals|repeat(9,rotate(30))
    flgd= flower|translate(x=20,y=20)|repeat(12,rotate(30))
    e1 = flgd|translate(x=30,y=30)|repeat(10,rotate(60))
    show(e1)
    #Yellow Flowers
    petal = ellipse(w=6,h=10,fill="#FF4500")|translate(x=0,y=5)
    flower = petal|repeat(12,rotate(30))
    e1 = flower|translate(x=100,y=0)|repeat(12,rotate(30)) 
    show(e1)
    #Orange Flowers
    petal = ellipse(w=6,h=10,fill="yellow")|translate(x=0,y=5)
    flower = petal|repeat(12,rotate(30))
    r = flower|translate(x=100,y=0)|repeat(12,rotate(60)) 
    show(r)
    c1 = circle(r=50, fill="orange", stroke="none") 
    show(c1)
    petals = ellipse(w=6,h=8,x=0,y=10, fill="pink")
    flower = petals|repeat(10,rotate(30))
    flgd= flower|translate(x=10,y=10)|repeat(11,rotate(30))
    show(flgd)
   
## image
    
![image](https://github.com/milandeepak/pookalam/blob/main/x-7ebcf439df-8685550f4e02a4e71bceaee57db32e71-m_vr5.png)
