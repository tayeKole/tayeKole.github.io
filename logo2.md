# leesons 7-12 
## lessons

## Lesson 7: show and Label
### Show and Label
In lesson 7 we learnt about how to use **show** and **labels** and how to make a sentence
<pre><code>make "name (readword[what is your name])
show :name </pre></code>
![image](https://user-images.githubusercontent.com/122093059/224308263-b8045db3-880f-430d-bde4-30a826e56c5a.png)
(The input)
![image](https://user-images.githubusercontent.com/122093059/224311340-ead884af-bfb7-484a-9b41-e6c12a0ae96a.png)
(The output)

**Show** is not as good as label although it does do the same things. The reason being is that a **show** is permanent and the only way to get rid of it is by refreshing the page and it can only go to the top left of the working area.
### Label
<pre><code>make "name (readword[what is your name])
cs rt 90 label :name</pre></code>
![image](https://user-images.githubusercontent.com/122093059/224310113-adde5a8d-8c85-483b-91d1-445ee92a33f0.png)
(The Input)
![image](https://user-images.githubusercontent.com/122093059/224310555-0b1f7eef-af63-4cf7-8469-779258301ab7.png)
(The Output)
Along with it being able to be put anywhere you can customize the font and size.

## lesson 8
### challenge
In this lesson we where challenged to great a star like shape and then make the outer triangles flash random colours.
<pre><code>CS
ht
repeat 1000000000000000 [
  pu home pd setpencolor random 15
filled "red [repeat 4 [fd 100 rt 90]] pu fd 100 pd
filled random 75 [repeat 3 [lt 120 fd 100]] pu rt 90 fd 100 pd 
filled random 50 [repeat 3 [lt 120 fd 100]] pu rt 90 fd 100 pd
filled random 25 [repeat 3 [lt 120 fd 100]] pu rt 90 fd 100 pd
filled random 100 [repeat 3 [lt 120 fd 100]] pu rt 90 fd 100 pd
 wait 2
]</pre></code>
![image](https://user-images.githubusercontent.com/122093059/224339394-45850e0f-c3cc-4f01-9418-1b90cd7d8856.png)
