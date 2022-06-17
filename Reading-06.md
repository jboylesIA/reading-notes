<html>
   <head>
      <title>Reading-06</title>
   </head>
   <body>
      <header>
         <h1>Dynamic web pages with JavaScript</h1>
         <nav>
            <ul>
               <li><a href="/">https://developer.mozilla.org/en-US/docs/Web/JavaScript</a></li>
               <li><a href="/">https://code-maven.com/input-output-in-plain-javascript<a></li>
            </ul>
         </nav>
      </header>
      <main>
         <section>
            <p> Java Intro - JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. Read more about JavaScript. </p>
         </section>
         <p> Sample Code of Input & Outputs
         First name: <input id="first_name">
Last name: <input id="last_name">
<button id="say">Say hi!</button>
 
<hr>
<div id="result"></div>
 
<script>
function say_hi() {
    var fname = document.getElementById('first_name').value;
    var lname = document.getElementById('last_name').value;
 
    var html = 'Hello <b>' + fname + '</b> ' + lname;
 
    document.getElementById('result').innerHTML = html;
}
 
document.getElementById('say').addEventListener('click', say_hi);
         </p>
         </section>
      </main>
      <footer>
      </footer>
   </body>
</html>