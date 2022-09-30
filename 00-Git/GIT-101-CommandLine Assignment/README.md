# Git Basics Exercises
- Create a folder called learn_with_geekster.
- cd into the learn_with_geekster folder.
- Create a file called first.txt.
- Display the file content in terminal.
- Configure your name and your email

<hr>

# Git Exercises-2

1. The folder hierarchy is shown below. There is a parent directory called Geekster, and inside of it are four more directories named HTML, CSS, Javascript, and React.
You must use the command line to move the file img.html from the HTML directory to the react directory.

```
Geekster
│   
└─── Css
│
└─── Html
│   │____ img.html
│    
└─── Javascript
│   
└─── React
```

**Please test it out on your own first, then refer to the answers below. 👇🙂**

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 

    mv img.html ../React/

    
</p>
</details>



2. Below is a breakdown of the folder structure. Geekster, the parent directory, contains the directories React and Angular.
F1.txt should be placed in the component folder.
```
Geekster
│
└─── React
│   │____ Component
|              │____ img.html
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

   mv f1.txt ../../../React/Component/


    
</p>
</details>