<div align="center">

## A C\+\+ Tutorial for Complete Beginners \# 1


</div>

### Description

I wrote this tutorial for those who wish to fully understand things from the beginning. If something is not explained clearly or is incoherent, please let me know and I will try to fix it ASAP!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jared Devall](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jared-devall.md)
**Level**          |Beginner
**User Rating**    |4.7 (802 globes from 170 users)
**Compatibility**  |C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+, UNIX C\+\+
**Category**       |[Documents](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/documents__3-27.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jared-devall-a-c-tutorial-for-complete-beginners-1__3-2040/archive/master.zip)





### Source Code

<FONT SIZE="2">
<BR><BR>
I will continue to write these (If you people actually enjoy them.) until I come across things I
do not yet fully understand.<BR><BR>
First things first. To start programming you will need to get you a Compiler. There are several
free as well as a few Commercial ones. Unless you have a few hundred dollars to buy the Commercial
Compilers I suggest you get you a free compiler.<BR><BR>
Here is a list of a few free compilers for Windows:
<ul>
<li> <A HREF="http://www.bloodshed.net">Bloodshed's Dev-C++</A>(IDE: uses MinGW or Cygwin)</li>
<li> <A HREF="http://www.cygwin.com">Cygwin: Windows GCC Port</A>(Command Line)</LI>
<li> <A HREF="http://www.borland.com/bcppbuilder/freecompiler/">Borland's</A>(I think it's Command
Line)</LI></UL>
Linux and Unix come with a C/C++ compiler(I think). Just make sure you installed it and read the
manuals!<BR><BR>
Okay. You'll need to download one of those compilers and read the manuals on them. I use Dev-C++.
If you have some questions using that specific compiler I might be able to help.<BR><BR>
Let's get on with the code Shall we?<BR><BR>
Windows users: Open up Notepad.<BR>
Dev-C++ : Just open it up and click on the new file icon. <BR>
*nix: Open up your favorite Text Editor. :)<BR>
<HR><br>
1: #include &lt;iostream.h&gt;<br>
2: <BR>
3: int main()<BR>
4: {<BR>
5: cout << "Hello World!" << endl;<BR>
6: return 0;<BR>
7: }<BR><br>
<HR>
Go ahead and copy that little piece of code. (Starting with #include and ending with the last
<B>}</B> ) You can paste it or just type it up in the text editor. Save it as hello.cpp . The .cpp extention lets the compiler know it's a C++ Source File. To compile in Dev-C++ click on
the compile icon or Execute->Compile. <BR>
<FONT SIZE="1">
Note: The Remove the numbers. They are there only to help analyze the code!<BR>
You will have to read the instructions on how to compile it in Compilers other than
Dev-C++.</FONT><FONT SIZE="2"><BR><BR>
<B>Congratulations! You are now a C++ Programmer!</B><BR><BR>
On Windows Machines the application will close very quickly if you run it. <B>THAT IS OKAY!</B> We
will learn how to fix that later.. The point is you got the program to compile! Now let's break
down the code.<BR><BR>
<i>#include &lt;iostream.h&gt; </i><BR><BR>
The first symbol is the <i>pound</i> symbol. It is a symbol to the <A
HREF="http://">preprocessor</a>. (Any words that are links will link to another tutorial with
definitions in it. For now it <B>DOES NOT EXIST</B>)<BR>
After that is the word <i>include</i>. Together #include tells the compiler to <b>include</b> a
file into your program. It is just as you had written it in there yourself!<BR>
Iostream.h is called a <A HREF="http://">header file</a> and is <i>included</i> our program. Why?
Iostream stands for <b>Input-Output-stream</b> and is needed for <A HREF="http://">cout</a>, which
prints things to the screen. <b>iostream.h</b> is surrounded by a &lt; and a &gt;. This tells the
compiler to search in the 'include' directory for the file. <b>iostream.h</b> can also be
surrounded by Quotations like so: "iostream.h" <BR>
This tells the compiler to look in the current directory for the file. iostream.h is obviously not
in your current directory so leave the greater than and less than sign there!<BR><BR>
Line 2 is just a blank line. It's just there as a part of <A
HREF="http://">whitespace</a>.<BR><BR>
Line 3 is the beginning of the Actual Program. On it is the <i>main()</i> <A
HREF="http://">function</a>. <b>Every</b> C++ program has a <i>main()</i> program. When your
program starts it automatically calls <i>main()</i>. According to ANSI Standard we must state
<i>main()</i> to be <A HREF="http://">int</A>. This will be discussed in another tutorial.<BR><BR>
Line 4 begins the body of the <i>main()</i> function. All functions begin with an <b>Opening
brace</b> ( <i>{</i> ) and a <b>closing brace</b> ( <i>}</i> ) just as <i>main()</i> does.
Everything inbetween is considered to be a part of the function.<BR><BR>
Line 5 is what the program is all about! The object <b>cout</b> is used to print a message to the
screen. This is how <b>cout</b> is used:<BR>
You write <b>cout</b> followed by the output redirection operator ( << ). The operator is created
by hitting shift-comma twice. Everything after the <b><</b> is printed to the screen. (Or atleast
tried to.) until it reaches a semi-colon. <b>;</b> <BR>
<b>endl</B> is way to make the string go to a new line. You also put a <B>\n</b> in the string
instead of using endl like this:<BR><BR>
cout << "Hello World\n";<BR><BR>
If you want a string of characters to be written to the screen you put your text between two
Quotations: <b>"</b>Hello world!<b>"</b> like so! You then put a semi-colon at the end signifying
the end of the statement. Semi-Colons are somewhat like an English period. It tells the compiler
that a statement is over. You'll learn where to put them and where not to put them as we get
further into the tutorials.<BR><BR>
Line 6 is a return statement. It returns <b>0</b> to close the program. It also ends in a
semi-colon. This will be discussed in more detail in a later tutorial!<BR><BR>
Line 7 is just a closing brace and the end of our program. The closing brace is required to
'close' the function!
That's the 'hello world' program fully explained. You can experiment with outputting text by
simply making a couple more <b>cout</b> statements. <BR><BR>
If anything is to complicated to understand or if I screwed up. >:) then be sure to let me know.
Please let me know if you would like anything more, want something explained in a little more
detail or whatever. I'll try my best to fix it!
- <B>JARED</b>

