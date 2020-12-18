# voice-assistant
voice assistant














import tkinter
window = tkinter.Tk()
window.title("PyVA")
label = tkinter.Label(window, text ="I am PyVA! Command me").pack()
top_frame = tkinter.Frame(window).pack()
bottom_frame = tkinter.Frame(window).pack(side = "bottom")
btn1 = tkinter.Button(top_frame, text = "Command!", fg = "red").pack()
window.mainloop()
