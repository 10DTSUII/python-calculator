## Python Calculator

# About my Project

## Members of the Development
Ahmed Abdi

## The Design
 Color-My color choice was derived from **Website**:[**www.w3schools.com**](https://www.w3schools.com/colors/colors_picker.asp)
 
 My conclusion of the color blue was derived from the fact that the  color enhances creativity and produces a calm, relaxing environment. Which is the ideal condition, as the purpose of a calculator is to carry out mathematical operations.(Red was another ideal color as it increases alertness, creativity and the color palette can be energizing  as well as increases attention for detail- However, blue is preferential. For instance, if a child is attempting to comprehend mathematical concepts such as addition and subtraction, a distracting, disruptive mindset and agitated mindset will be detrimental to the child's learning. However, the color blue migates such a mind set and brings the feeling of tranquility and serenity.  Furthermore, another reason why I derived the color blue, as opposed to other colors such is what affects the color placed upon the viewer. The color green is also placed around the operations and decimals because the color green and its relationship to nature causes us to pause , take a deep breath and relax ; all of which are ideal for a learning environment.




## Why some colors but not others?

Other possible colors that i could have picked:

Brown- The right mix of browns can reduce fatigue and promote a sense of relaxation and security; However, this can be very nuanced.

Yellow- Stimulates your eyes rather than your mental state which is the basis upon which you learn mathematical concepts effectively.

Purple & Pink were not chosen for the simple reason that the colors would be too distracting which is detrimental for a child's learning.


## Buttons
The buttons were colored white because it was a clam, neutral color that creates positive feelings and helps learners engage. 
The color black was used to create a contrast between the color of the buttons and the number key on it.
 
 
 
## Layout
 Miro - The planning of my layout is in this **Website**:[**Miro.com**](https://miro.com/app/board/uXjVPSxXFYc=/)
 

 
![image](https://user-images.githubusercontent.com/103612434/196822058-1355983e-0165-4d9a-ae00-b6e26177b8fc.png)


 ## Grid
 The numbers are listed 0-9, in order from top to bottom. This is because kids generally read from top to bottom. Therefore, the numbers were listed accordingly.
 The computer grid begins at 0. This means that as opposed to the conventoional method of 1 being the first number 0 is the computers first number. Therfore, the gird begins at 0,0. 
 
 For instance:
 The number 1 is row=0 column =0
 The number 2 is row=0 column =1
 The number 3 is row=0 column =2
 The number 4 is row=1 column =0
 The number 5 is row=1 column =1
 The number 6 is row=1 column =2
 The number 7 is row=2 column =0
 The number 8 is row=2 column =1
 The number 9 is row=2 column =2
 The number 0 is row=3 column =0
 
 I have excluded the clear button as this has been packed and not in the grid.....
 

### The window main loop is where all the hardware, code functions and demands resides.
"window.mainloop()"

## Design of the Graphic user interface
window = Tk() ### Window variable is set as the tkinter.
window.title("Python Calculator") ###  The title of the tkinter  defined by the window.title variable.
window.geometry("500x500")  ### The geometric measurements of the tkinter geometry is 500 pixels by 500 pixels.
window.configure(bg="blue") ### the window variable determines the background color of the tkinter calculator which is justifed above.


## The display area
(Where the inputs appear when a number or operator appears once clicked.)

" label= Label(window, textvariable=equation_label, font=("console",20), bg="white", width=24, height=1 )
label.pack()"
 As the code states the console is "packed", fills the entire frame of the label. The font is console and is 20 pixels.
 The reason as to why 20 pixles was chosen was that the size was ideal for a child. Not to big otherwise it would be distracting. To small and it would be hard to read. The width of the display are is 24 pixels. Followed by the height which is 1. The label is located in the window (Tkinter variable) ant the textvariable has been assigned as the equation label which is the text/input that appears on the display area after clicking on a function.






