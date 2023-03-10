# logo interpreter notes 
## lessons
[Lesson 1](https://github.com/tayeKole/tayeKole.github.io/edit/main/README.md#lesson-1)

[Lesson 2](https://github.com/tayeKole/tayeKole.github.io/edit/main/README.md#lesson-2)

[Lesson 3](https://github.com/tayeKole/tayeKole.github.io/edit/main/README.md#lesson-3)

[Lesson 4](https://github.com/tayeKole/tayeKole.github.io/edit/main/README.md#lesson-4)

[Lesson 5](https://github.com/tayeKole/tayeKole.github.io/edit/main/README.md#lesson-5)

## lesson 1
 learned repeat loops and how to make a square

<pre><code>repeat 4[fd 100 rt 90]
</code></pre>
![image](https://user-images.githubusercontent.com/122093059/224299785-f6655998-3e83-4783-b2f1-e6cd3cc57e99.png)


 ## lesson 2
learned how to make more complex shapes and how to find the degrees of a shape, using code in logo interpreter.
  ### pentagon
<pre><code>repeat 5[fd 100 rt 360/5]
</code></pre>
![image](https://user-images.githubusercontent.com/122093059/224300964-be927216-b068-4722-a6d4-b509eefbdb7c.png)


### A dodecagon
<pre><code>repeat 12[fd 100 rt 360/12]
</code></pre>
![image](https://user-images.githubusercontent.com/122093059/224301150-b32572dd-f444-4ec0-8407-60fb1f57c3fa.png)


 ## lesson 3
 We where challenged to build a house using log the furthest i got was to building the floor and the building itself.
 ### Code for the house
 if you use this i suggest ctrl + scroll out until it fits your screen
<pre><code>;sets up house base
cs pu bk 400 rt 90 pd fd 1000000 setx 200 lt 90 ;ht 

;building the main house and roof
repeat 4[fd 400 lt 90] fd 400 lt 30
repeat 2[fd 400 lt 120] seth 180 fd 100 rt 90

;sets up the entire side houses
repeat 2[fd 300 lt 90] fd 700 lt 90
repeat 3[fd 300 rt 90] rt 90 fd 300  rt 90
repeat 2[lt 120 fd 300] rt 60 pu fd 400 pd rt 180
repeat 2[lt 120 fd 300] pu setxy -150 -100 seth 90 pd

;builds the windows main house
repeat 4[fd 100 rt 90] repeat 2[repeat 4[fd 50 rt 90]fd 50] rt 90 fd 100 rt 90 repeat 2[repeat 4[fd 50 rt 90]fd 50] 
pu setxy 150 -100 seth 90 pd lt 180
repeat 4[fd 100 lt 90] repeat 2[repeat 4[fd 50 lt 90]fd 50] lt 90 fd 100 lt 90 repeat 2[repeat 4[fd 50 lt 90]fd 50]
pu setxy -50 -400 pd rt 270

;sets up door
repeat 2[fd 150 rt 90 fd 100 rt 90] pu setxy -250 -200 pd lt 90

;builds windows on both side houses
repeat 4[fd 50 lt 90] repeat 2[repeat 4[fd 25 lt 90]fd 25] lt 90 fd 50 lt 90 repeat 2[repeat 4[fd 25 lt 90]fd 25]
pu setxy -250 -200 bk 200 pd
repeat 4[fd 50 rt 90] repeat 2[repeat 4[fd 25 rt 90]fd 25] rt 90 fd 50 rt 90 repeat 2[repeat 4[fd 25 rt 90]fd 25]
pu setxy 250 -200  rt 180 pd
repeat 4[fd 50 rt 90] repeat 2[repeat 4[fd 25 rt 90]fd 25] rt 90 fd 50 rt 90 repeat 2[repeat 4[fd 25 rt 90]fd 25]
pu setxy 250 -200 bk 200 pd
repeat 4[fd 50 lt 90] repeat 2[repeat 4[fd 25 lt 90]fd 25] lt 90 fd 50 lt 90 repeat 2[repeat 4[fd 25 lt 90]fd 25]

show {Taye Colesky nine e}
</code></pre>
![image](https://user-images.githubusercontent.com/122093059/224301475-c02c86c9-c883-46dd-ab35-12b465de9001.png)


## lesson 4
### In this lesson we learnt how to comment thing out like you would see in the above lesson
<pre><code>;this comments this message by using a semicolon anything after the semicolon on that line
</code></pre>
![image](https://user-images.githubusercontent.com/122093059/224301624-0dbda88b-ef26-4918-9b37-428c2ed4ea42.png)

I learnt this is best to locate your errors in you project

## lesson 5
### In this lesson we learnt about the **filled** command that fills everything that uis in its brackect
<pre><code>filled[repeat 4[fd 100 rt 90]]
</code></pre>
![image](https://user-images.githubusercontent.com/122093059/224302132-e3bb5a6e-8e8c-4ff4-a7d0-940483b12c00.png)
This fills the square
