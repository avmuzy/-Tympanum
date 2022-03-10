
# importing required module # importando modulos
import pygame
from tkinter import *

# defining functions # definindo funçces
def play():
    pygame.mixer.music.load('Thunder.mp3')
    pygame.mixer.music.play()


def pause():
    pygame.mixer.music.pause()


def unpause():
    pygame.mixer.music.unpause()

def stop():
    pygame.mixer.music.stop()






pygame.init()
sound_effect = pygame.mixer.Sound('Thunder.mp3')

root = Tk()
root.title('Tympanum') # giving a tile for the window # titulo da janela
root.geometry('360x400')

myframe = Frame(root)
myframe.pack()

mylabel = Label(myframe, text="Audiometry Self-Test") # description # descriçao
mylabel.pack()

# setting buttons # definindo botoes

button1 = Button(myframe, text="Play", command=play, width=15)
button1.pack(pady=5)
button2 = Button(myframe, text="Unpause", command=unpause, width=15)
button2.pack(pady=5)
button3 = Button(myframe, text="Pause", command=pause, width=15)
button3.pack(pady=5)
button4 = Button(myframe, text="Stop", command=stop, width=15)
button4.pack(pady=5)

# modify the window title # modificando a o titulo da janela

title=Label(root,text="Tympanum",bd=9,relief=GROOVE,font=("times new roman", 30, "bold"),bg="black",fg="blue")
title.pack(side=TOP,fill=X)

root.mainloop()
