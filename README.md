# Simplify-Syntax-Highlighting-with-highlight.js
Simplify Syntax Highlighting with highlight.js Bloger Html Web site
![image](https://github.com/coolsasindu/Simplify-Syntax-Highlighting-with-highlight.js/assets/45946252/17f85b5c-bb06-4fb0-a5c6-1f4a9f872a50)

![image](https://github.com/coolsasindu/Simplify-Syntax-Highlighting-with-highlight.js/assets/45946252/29ef379d-e114-4b85-a2de-5f2616d0fb04)


[Code.txt](https://github.com/coolsasindu/Simplify-Syntax-Highlighting-with-highlight.js/files/13777398/Code.txt) <link href='https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github-dark.css' rel='stylesheet'/>

 	<script src='https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js'/>
	<!-- and it's easy to individually load additional languages -->
	<script src='https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/languages/go.min.js'/>
    <script src='//cdnjs.cloudflare.com/ajax/libs/highlightjs-line-numbers.js/2.8.0/highlightjs-line-numbers.min.js'/>


<script>
  hljs.highlightAll();
  hljs.initLineNumbersOnLoad();

</script>  




https://cdn.jsdelivr.net/npm/highlight.js@11.9.0/styles/

#CSS Link (add End tag is /> for bloger)
```
<link href='https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/github-dark.css' rel='stylesheet'/>

```
![image](https://github.com/coolsasindu/Simplify-Syntax-Highlighting-with-highlight.js/assets/45946252/26a3c61a-842b-481b-9621-5e4a578b2be7)

#Add Java Script for Highlighting 
```
<script src='https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js'/>
	<!-- and it's easy to individually load additional languages -->
	<script src='https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/languages/go.min.js'/>
    <script src='//cdnjs.cloudflare.com/ajax/libs/highlightjs-line-numbers.js/2.8.0/highlightjs-line-numbers.min.js'/>


<script>
  hljs.highlightAll();
  hljs.initLineNumbersOnLoad();

</script>

```
![image](https://github.com/coolsasindu/Simplify-Syntax-Highlighting-with-highlight.js/assets/45946252/71604264-894d-47ad-b007-56b55695f782)

##write code Like this 
'''
<pre><code>
from typing import Union

from fastapi import FastAPI

app = FastAPI()


@app.get("/")
def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
def read_item(item_id: int, q: Union[str, None] = None):
    return {"item_id": item_id, "q": q}


</code></pre>

<pre><code>

import java.util.Scanner;

class abc{
  public static void main(String[] args) {

    // creates an object of Scanner
    Scanner input = new Scanner(System.in);

    System.out.print("Enter your name: ");

    // takes input from the keyboard
    String name = input.nextLine();

    // prints the name
    System.out.println("My name is " + name);

    // closes the scanner
    input.close();
  }
}

</code></pre>

<pre><code>

INSERT INTO `transaction` (`id`, `item_id`, `weight`, `nug`, `total_weight`, `transaction_type`, `comment`, `created`) VALUES
(8, 7, 50.2, 12, 602.4, 'buy', 'Added', '2014-09-19'),
(9, 11, 100, 5, 500, 'buy', 'Gold ring purchase', '2014-09-12'),
(10, 11, 100.25, 10, 1002.5, 'buy', 'Purchases', '2014-09-17'),
(11, 10, 25, 5, 125, 'buy', '', '2014-09-16'),
(12, 7, 50.2, 5, 251, 'sale', 'Sale', '2014-09-26');

</code></pre>
'''
![image](https://github.com/coolsasindu/Simplify-Syntax-Highlighting-with-highlight.js/assets/45946252/5637f2e0-c4a7-42e7-88af-79a9db77459e)

More Theams : https://cdn.jsdelivr.net/npm/highlight.js@11.9.0/styles/
