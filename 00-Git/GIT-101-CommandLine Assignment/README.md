# Git Basics Exercises
- Create a folder called learn_with_geekster.
- cd into the learn_with_geekster folder.
- Create a file called first.txt.
- Put your name in first.txt
- Display the file content in terminal

<hr>

# Git Exercises-2

1. Create the folder hierarchy shown below using command line. 
There is a parent directory called Geekster1, and inside of it are four more directories named HTML, CSS, Javascript, and React.
2. Create a  file ```index.html``` in ```\Geekster1\Html``` 
2. use the command line to move the file ```index.html``` from the ```\Geekster1\Html``` directory to the ```\Geekster1\React``` directory.

```
Geekster
│   
└─── Css
│
└─── Html
│   │____ index.html
│    
└─── Javascript
│   
└─── React
```

**Please test it out on your own first, then refer to the answers below. 👇🙂**

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 
```sh
    mkdir Geekster1
    cd Geekster
    mkdir Html
    mkdir CSS
    mkdir JavaScript
    mkdir React

    // create the file index.html in Html folder

    mv img.html ../React/
```
    
</p>


</details>

# Git Exercises-3

1. Create the folder hierarchy shown below using command line. Below is a breakdown of the folder structure. Geekster2, the parent directory, contains the directories React and Angular.
2. Create ```f1.txt``` file in TS folder as shown below.
3. Move ```f1.txt``` file to ```Geekster2/React/Component/``` using commandline


```
Geekster2
│
└─── React
│   │____ Component
|              | -----
│   
└─── Angular
        │____ Services
                  │____ TS
                          │____ f1.txt
```


**Please test it out on your own first, then refer to the answers below. 👇🙂**


<details><summary><b>Answer</b></summary>
<p>

##### Answer: 
```
    mkdir Geekster
    cd Geekster
    mkdir React
    mkdir Angular
    cd React
    mkdir Component
    cd ..
    cd Angular
    mkdir Services/TS
    cd Services/TS

    touch f1.txt
    // add yourname in f1.txt

    mv f1.txt ../../../React/Component/


``` 
</p>
</details>