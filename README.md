<!DOCTYPE html>
# Testing
<html>
 <head>
   
  </head>  
   <h2>Just testing</h2>
  <p>Darewolves, dont back out now!</p>


  <p>You dumb fucking darewolves!</p>

  <p id="insult-two">You idiot!</p>
  <a href="#wp-anchor"> Sends to you the paragraph about webpage anchors</a>
  
   <!--
Lil bugger, shut up and stop stalling, idiot! Also, while <p+number> works, it is not needed, i believe.
-->
  <body>
  <main>
    <p>Darewolves is a certified idiot</p>
    <p>But as much as an idiot as you are, you aren't that stupid, are you?</p>
  
  <h2>Img Element</h2>
    
  <p>Img elements are self closing. This means that they do not need a < /img > at the end, as the image code/src is part of the first <>, starting from < img src=> </p>
    
   <p>The link slash source will be in " " and after the =. The alt element is like this too. For example, alt="insert" and comes after the sourse. The alt is like a caption, basicaly shows if the picture doesnt load. You can leave it empty if the image isnt important, as it's like a caption, the have the person know what the picture is of.</p>
  
  <img src="https://gamepress.gg/arknights/sites/arknights/files/2020-03/char_136_hsguma_nian%233.png" alt="Hoshiguma Patrolling Ronin skin">
  
  <p>Later, we will learn how to make the image smaller in css. Stick to HTML stuff for now, dare. However, once you learn cc, you can go ahead and make your own Ao3 site colors and stuff. </p>
  
  <h2>Anchor Element</h2>
  
  <p> An anchor element, 'a' is used to link to sites outside of this webpage. The destination is the href. This element is not self closing. However, the link is put in the first <a>. a href="link" Then between these, you put the text you want to show up. For example, 'Hoshiguma'. Clicking on it will lead to whatever page you set, for example, Hoshiguma's gamepress page.</p>
                  
  <a href="https://gamepress.gg/arknights/operator/hoshiguma/" rel="noopener noreferrer">Hoshiguma's Gamepress Page</a>
                  
  <p id="wp-anchor">On the other hand, this anchor element can also be used to skip/jump to different parts of the webpage. FreeCodeCamp says it's called an internal link. Anyway, you give the href an # attribute, basically, href="#blank" The blank is where you put the id of the element you want to jump to. "An id is an attribute that uniquely identifies an element." Just like real ids.You assign an id with id="blank". You put this, for example, after the <p . Making it a <p id="blank. I will set the "You idiot!" paragraph's id to insult-two. Also, footer is another element. It's, y'know, a footer. I will then stick another anchor to send you back.</p>
  
  <a href="#insult-two">Anchor to insult-two</a>
  
  <p> Another note on this anchor element. If you would like it to open in a new page, you can add 'target="_blank" ' in the first set of brackets. For example, this link to Matoimaru's page will open in new tab, I believe. Starting the attribute slash element with an # probably makes it an internal thing. Basically, on this webpage.</p>
  
  <a href="https://gamepress.gg/arknights/operator/matoimaru/" target="_blank" rel="noopener noreferrer"> Matoimaru's Gamepress page, in another tab.</a>
  
  <p> Yeah i know it doesnt work, ill fix it later. You can actually dump link elements into text elements. Like this <a href="#insult-two">anchor<a> This is, uh, anchor text? Anyway, for anchor elements with dead links. you set the href to #. href="#". You now have an anchor, placeholder, that doesnt work! Like this <a href="#">[one]</a> Let's go to another attribute. 'rel' is also put in the first bracket, after the target, I believe. rel stands for relationship! It sets the relationship between your page and the link. Setting it to 'noopener norefferer' stops tabnabbing, apparently. </p>
  <p>You wanna know how to turn a photo into a link? Look a bit further, after this sentence. First you dump your image(code and all) between an anchor element, between the 2 sets of brackets. Remember, sticking '#' for the href makes it a dead link! Remember to add an alt</p>
    
  <a href="https://gamepress.gg/arknights/operator/matoimaru/" target="_blank" rel="noopener noreferrer"><img src="https://gamepress.gg/arknights/sites/arknights/files/2020-03/char_136_hsguma_nian%233.png" alt="fuckers stole my cat"></a>
  
  <h2>Unordered Lists</h2>
    
  <p>It may not open in a new tab, but like, I don't know what the problem is, so let's ignore it for now. Did you know that you can create bullet lists in html? Now you definitely do! This is an unordered list. The element for is this 'ul', which, y'know, stands for unordered list. Now, start another line, and use the element 'li'. Each line/thing you list need a set of the 'li' tags. When your list is done, use '/ul'. Below is a list of things Darewolves are.</p>
  
  <ul> 
    <li>An idiot</li>
    <li>Stupid</li>
    <li>smolbrain</li>
    <li>deadbeat doctor</li>
  </ul>
  
  <h2>Ordered Lists</h2>
  
  <p>The element for unordered lists is 'ul', so for ordered lists it is 'ol'. This is the only difference. You still used the 'li' for the items. Below is an ordered list of the hardest enemies so far in global.</p>
    
  <ol>
    <li>Talulah</li>
    <li>Patriot</li>
    <li>Frostnova</li>
  </ol>
    
  <h2>Text Fields</h2>  

  <p> The 'input' element is aa way to get....input. Just like img elements, the input element is self closing. There are also input types. the input element is like, >input type="blank"<. In this case, the type is text.</p>
    
  <input type="text">
    
  <p> An input placeholder is what you see when nothing has been typed yet. I believe it's an attribute. You put it after the type. placeholder="blank". Yes, I know, the input element is 95% likely not working. Whatever!</p>
    
  <input type="text" placeholder="Life is a placeholder for hell.">
    
  <p>You actually need a place for the input to end up in. Probably why it's failing to show up. The form element exists to help. It is not self closing. Give the form element an 'action; attribute. action="where-you-want-the-stuff-to-go". You stick the input element between this form element. Too bad I don't have a server.</p>
    
  <form action="#">
    <input type="text" placeholder="help call 911">
  </form>
     
  
  <p>On the other hand, we need a submit button. How else are you gonna get that nice nice input? Anyway, create a button element...useing 'button'. It is not self closing. Anyway, within the first bracket, specify a type attribute. In this case, 'submit'. type="submit" Between the tags themselves, you type what you want to button to say.</p>
    
  <form action="#">
    <input type="text" placeholder="SOS">
    <button type="submit">[Confirm I'm an idiot.]</button>
  </form>
    
  <p>You know how annoying it is when a form requires you to fill something out or you can't move on? Yup, lets learn how to do that! It's very easy. Just add on the 'required' attribute to your input element. Dont ask whether it comes before or after the placeholder. Idk.</p>
    
  <form action="#">
    <input type="text" placeholder="Hell" required><!-- It comes after the placeholder I think -->
    <button type="submit">[help]</button>
  </form>
    
  <h2>Radio Buttons!</h2>
    
  <p>Radio buttons! The confusion of life! Nah, its basiclaly just giving multiple choice options. Don't worry. Radio buttons are a 'type' of input. radio buttions are also annoying help. Anyway. You stick this input element between label elements. Nope, not self closing. Give the a 'for=' attribute(for the label). What do you want the option to say? Thats what the 'for' is for(not really, it just makes life easier). Do not shut the label element yet. You still need to add the input element! Give the input element an id attribute,(same as the 'for'attribute). Then set the input type to radio. Then add in the 'name' attribute, and name it. You may close the input tag now. Before you close this label element, remember to actually give it a label. This is now one button! Repeat for more options. Then you can close the form element. The name attribute ensures that they are in the same radio group.
   
  <form action="#">
    <button type=submit>[Heck]</button>
    <label for="yes"><input id="yes" type="radio" name="yesno"></label>
    <label for="no"><input id="no" type="radio" name="yesno"></label>
  </form>
    
  <p>To be honest, I actually have no idea how it works. So don't like...actually use this info...</p>
    
  <h2>Checkboxes</h2>
    
  <p>So much input types! How do I remember them all. It's not like programming is a test. You can search thing's up. Anyway, checkboxes. Questions with 1+ answers? Here's your solution! Each checkbox(input) goes between a label element.It will automatically associate the input with the label element. If the inputs are all related, they should have the same name! To make life easier, the 'for' attribute in the label element should match the 'id' of the input element. This is basically the same as before. Change the type to 'checkbox'.
    
  <form action="#">
    <button type=submit>[Submit]</button>
    <label for="Patriot"><input id="Patriot" type="checkbox" name="akboss"></label>
    <label for="Frostnova"><input id="Frostnova" type="checkbox" name="akboss"></label>
    <label for="Talulah"><input id="Talulah" type="checkbox" name="akboss"></label
  </form>
  
  <p>Time for the value attribute. BY THE WAY THIS IS JUST ME TAKING NOTES FROM FREECODECAMP! I recommend you look at this lesson actually since, values. <a href="https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/use-the-value-attribute-with-radio-buttons-and-checkboxes">link.</a> Anyway, radio and checkbox input types submit the answers/value from the value attribute. Lets's just copy paste the text from freecodecamp here.</p>
      
  <p>"Here, you have two radio inputs. When the user submits the form with the indoor option selected, the form data will include the line: indoor-outdoor=indoor. This is from the name and value attributes of the "indoor" input."</p>
      
  <p>You stick this 'value' attribute in the input element, after the id.<br><!--br is the break lines option--> The value option identifies the option.</p>
      
  <form action="#">
    <button type=submit>[Submit]</button>
    <label for="patriot"><input id="patriot" value="patriot" type="checkbox" name="akboss">Patriot</label>
    <label for="frostnova"><input id="frostnova" value="frostnova" type="checkbox" name="akboss">Frostnova</label>
    <label for="talulah"><input id="talulah" value="talulah" type="checkbox" name="akboss">Talulah</label
  </form>

  <p>Okay, but like, what if you want to force an option onto someone? That is also possible! Remember the 'required' attribute. It will be used the same way. Instead of required thought, it's 'checked'. You stick it in the input element.
    
  <h2>Div Element</h2>

  <p>Want to make things neater? Yes. I do. This mess of words is killing my eyes. This is not a self closing element. 'div' and '/div'.</p>
      
  <h2>Doctype Time!</h2>  
  <p>At the top of the document, you need to specify the doctype! In this case, HTML and HTML5. You can use 'html' though. !DOCTYPE blank. The blank is the doctype, in this case, 'html. So !DOCTYPE html. However, this is not the end. You need to stick your entire chunk of html code between 'html' elements. Do it now.</p>
      
      
  <h2>Markup</h2>
  <p>Another level of organization here. The 'head' and 'body' element. There's also metadata elements and stuff. "Metadata elements, such as link, meta, title, and style, typically go inside the head element."</p>
    
<main>

  <h1>BASIC CSS</h1>

  <h2>Text Color</h2>
  <p>Finally, we are here. CSS. Time to turn my Ao3 text cyan. For this, you need the style attribute or smth. style="color: blue;" Like that. Stick it in the first tag of an element. And remember to end it with a ';' Oh and like, you need to set a color for 'blue' I believe.<br><br> That is one way to change text color. But you can do it another way, by setting up a style block/element. This is a quick way to change all of one element at once. the 'color: blank' is considered a style rule. You need curly brackets around the style rule. DO NOT FORGET THE SEMICOLON. Do this at the top of the code. UNFORTUNATELY I HAVE NO IDEA HOW TO MAKE THIS WORK. Okay apparently CSS isnt suppported for this file. Makes life easier, in a way.</p>
      
    <style>
      h2 {
        color: red;
      }
    </style>
<p>Fun, isn't it? Anyway, but what if, you don't want all the h2 elements to be red? And you want some others to be red too? You create your own class! Then instead of using the style attribute, you can use the class attribute with the class name. To create a class, you replace the block of code above, the part where you stick the element with a class name. It will start with a period, but when using it, you do not need the period.</p>
 
  <style>
   .frost {
    color: #ooFFFF
   }
  </style>
 
 <p>Just like that! To use it, refer to the example below.</p>
    
 <h2 class=.frost>HELP</h2>
 
 
  </body>  
</html>







