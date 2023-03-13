# ChatWRD
Creepy chatbot trained on Lovecraft stories.  
The WRD in ChatWRD stands for WORD, but in the context of a Lovecraftian chatbot could also be read as ChatWEIRD,  
as Lovecraftian horror is technically in the weird genre of fiction.  

The code, when run, generates a tkinter window with a user imput box where you can type a prompt.  
There is a drop down menu below that with a selection of numbers between 1 and 300.  
The number you choose will be the number of words in the sentence ChatWRD generates as a reply.  
When you hit the "Submit" button, the code runs and generates a reply.  
Keep in mind that this will take several minutes.
The tkinter window will freeze and say (Not Responding) in the window title.  
Don't worry; it doesn't mean anything is going wrong.  
I'm not sure why it does this or how to fix it, but as soon as the reply is generated it goes back to normal.  
The chatbot's reply to your prompt then types itself across the bottom of the screen.  

I wrote the music using Vital Synth and Cakewalk DAW and edited it with Audacity audio editor.  
When the .py file is run, it generates a tkinter window with looping music and  
randomly selects a window image from an image bank of 31 images (19 lovecraftian landscapes and 12 lovecraftian seascapes).  
I generated the images using Stable Diffusion.  
The chatbot uses a .txt file made up of several stories by H. P. Lovecraft.  
I originally planned to use the complete works of H. P. Lovecraft, but due to the processing limitations of my computer,  
it would take a very long time to generate output based on that file, so instead,  
my .txt file the chatbot trains on is a couple of his stories that I randomly chose.    

It would be pretty easy to change the txt. file that this chatbot trains on.   
You could clone the code and rewrite it so that it generates output based on any txt. file you want.  
You could similarly change the images and the music or any other settings if you so desired.  
Feel free to clone this code and change it to be the chatbot you so desire.
I'd be interestood to see what people create with that.

Limitations:  
The chatbot takes several minutes to generate content.  
The chatbot may not necessarily generate intelligable output.  
The chatbot is not moderated in any way so I don't take any responsibility for the content it generates.
