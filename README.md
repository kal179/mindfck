# mindfck - A Brainfck Interpreter
<b> Project no longer in active development and will be available as a Public Archive only. (28/11/2025)</b>

A simple Brainfck interpreter implemented in two different ways.  <br/>

<strong>Implementation</strong>  <br/>
(1) Direct Interpreter  <i>(/master/first-hand-interpretation)</i>   <br/>
(2) Bytecode Interpreter  <i>(dev in progress)</i>
<br/>
<br/>
<strong>(1) Direct Interpretation  </strong>   <br/>
Implementation of brainfck in direct interpretation method, In which scripts are executed  
with their native language, and not converted to any intermediate representation!  <br/>
For e.g. Lisp, Scheme, etc! <br/>
<br/>
<strong>(2) Bytecode Interpretation   </strong><br/>
Implementation of brainfck in which scripts are converted    
to an intermediate language-representation and then executed   
by dedicated VM(Virtual Machine)!     
<br/>
<i>I'm implementating interpreter   
in two distinct ways, for learning purposes!    
And also b'cuz Brainfck is easy to implement!     </i>
<br/>
<br/>
<strong>Usage:</strong> <br/>
<pre>
    ~$ python first-hand-interpretation/mindfck.py source.bf
    ~$ python middle-man-interpretation/mindfck.py source.bf
    
</pre>

I'd Love to hear edits, suggestions, and your contribution. <br/>
