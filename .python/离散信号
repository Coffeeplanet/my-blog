from tkinter import *

def hanshu1():
    import numpy as np
    import matplotlib.pyplot as plt

    x=np.linspace(0,5,20)
    x1=np.linspace(0,10,10)
    X=[2,1.5,1,0.5]
    y1=[]
    for i in range(32):
        y1.append(X[i%4])
    fig=plt.figure('周期信号')

    plt.stem(list(y1))
    plt.grid(True)
    plt.title('zhouqi')

    plt.show()

def hanshu2():
    import numpy as np
    import matplotlib.pyplot as plt

    x=np.linspace(0,5,20)
    x1=np.linspace(0,10,10)
    X=[2,1.5,1,0.5]
    y1=[]
    for i in range(32):
        y1.append(X[i%4])
    fig=plt.figure('正弦信号')

    y2=2*np.sin(0.5*np.pi*x+2)
    plt.title('zhengxian')
    plt.grid(True)
    plt.stem(x,y2)

    plt.show()

def hanshu3():
    import numpy as np
    import matplotlib.pyplot as plt

    fig=plt.figure('冲击信号')
    y3=[1,0,0,0,0,0,0,0,0]
    plt.stem(y3)
    plt.grid(True)
    plt.title('chongji')
     
    plt.show()

def hanshu4():
    import numpy as np
    import matplotlib.pyplot as plt

    fig=plt.figure('阶跃信号')
    y4=[0,0,0,1,1,1,1]
    plt.stem(y4)
    plt.grid(True)
    plt.title('jieyue')
    plt.show()


root = Tk(className='离散信号')
root.geometry('400x300')

Label = Label(root)
Label.pack()

Button1 = Button(root)
Button1['text'] = '周期信号'
Button1['command'] = hanshu1
Button1['bg'] = 'pink'
Button1.pack()

Button2 = Button(root)
Button2['text'] = '正弦信号'
Button2['command'] = hanshu2
Button2['bg'] = 'pink'
Button2.pack()

Button3 = Button(root)
Button3['text'] = '冲击信号'
Button3['command'] = hanshu3
Button3['bg'] = 'pink'
Button3.pack()

Button4 = Button(root)
Button4['text'] = '阶跃信号'
Button4['command'] = hanshu4
Button4['bg'] = 'pink'
Button4.pack()


root.mainloop()
