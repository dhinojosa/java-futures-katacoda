Enter the following into your editor

<pre class="file" data-filename="src/MyApp.java" data-target="replace">
package com.xyzcorp;

class MyApp {
   public static void main(String[] args) {
     System.out.println("Hello!");
   }
}
</pre>


Clear the screen

`clear`{{execute}}

We will then compile


`javac -d target src/MyApp.java`{{execute}}

Then we will run

`java -cp target com.xyzcorp.MyApp`{{execute}}


