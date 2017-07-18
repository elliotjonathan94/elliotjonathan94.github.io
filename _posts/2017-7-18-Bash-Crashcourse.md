The purpose of this second blog post is really simple, I'm just showing off a little bit of the work that I've done in this class.  
We began to use the program bash to create scripting documents that perform tasks and provide feedback to the user.  
The shebang (#!) was an important part of the scripting process, because it designates a file to be run by the bash program.  
After that, the computer pretty much executes all the commands that you put into it.  
Writing echo causes the computer to run whatever you tell it to as Standard Output back to the user, it's pretty useful for leaving notes to people operating software.  
I wrote up a small piece of work, similar to this, using markdown style and I committed it to my github repository.  
I then took this file and converted it to   
1..docx,  
2.pdf,  
3.odt, and  
4.html.  
The process was simple!  
I just followed the prompting from John's bash script and I entered corresponding commands.  
It looks pretty much like this: pandoc -o OriginalWork.html OriginalWork.md. That particular command converts from markdown to HTML.  
In the end, I converted my work, OriginalDocument1, from markdown into four other types of file! You can find them all [here.](https://github.com/elliotjonathan94/convert-documents)
The shell scripting that I used to create these documents is located in the same repository, it's under ELLIOTJONATHAN94-convert-docs.sh
