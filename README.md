# PHDOM 
The library is usually used to easily add html codes to php in a couple of lines of code! See a comparison with regular php code where html tags are used and look at examples of the PhDOM library! Noticeable right?


# Plain php:
` <?php $name = 'Kamron'; echo '<h1>'.$name.'</h1>'; ?>`
## PhDOM example:
 `<?php $name='Kamron'; echo h1($name);   ?>` <br>Conclusion:  `<h1>Kamron</h1>`
 
 ## Examples:
 `echo h2('Hello World!')` -> Hello World
 `loop(5,'Hello World!',['br'=>true]);` -> <br>Hello World <br>Hello World <br>Hello World <br>Hello World <br>Hello World
 
 `echo font('cursive','<h4>Hello World!</h4>');` -> <br>`<h4 style="font-family:cursive">Hello World!</h4>`
 
 `echo h4('Hello!',['id'=>'test']);` -> `<h4 id="test">Hello</h4>`
 
 `echo h4('Hello!',['class'=>'test']);` -> `<h4 class="test">Hello</h4>`
 
 # Functions:
 <b>loop(),  
  br(), 
  h(1,2,3,4,5,6)(), 
  p(), alert(), console(), serif(), serif2(), aharoni(), lower(), up(), upper(), mono(), create(), consolewarn(), consoleinfo(), consoleerror(), dump(), pr(), chars(), div(), pre(), times(), dates(), a(), and others...</b>
