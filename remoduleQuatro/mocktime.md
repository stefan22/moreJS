# mocktime

- Assuming four questions, one question per page.

    + data should be separate from code, so a data json file-array, that i can 
      iterate through
    + first question arrives at page load
    + Questions type:    
        * true/false question               //the first two questions                  
        * multiple choice Questions         //should work the same way
        * fill in question

    +   methods/properties:
            //properties (constructor)
            - type              //type of question
            - actual question   //makes sense
            - id                //to load/validate not sure
            - correct           //correct response using an if statement ?
            - feedback          //may need to display some feedback to the user
            - result            //keeping score perhaps

            //methods (prototype)
            - loadquestions     //load questions from json
            - checkAnswer       //it changes for multiple choice and fill-in question
            - display questions //once loaded json display it
            - hide question     //im moving between questions so need to hide them too
            - show feedback     //also need to show/hide feedback
            - hide feedback 




 - Navigation left/right arrows to go from question to question/page to page   

    + right/bad answers to load an image depending on whether answered correct
      or not/ or some feedback
    + multiple choice, true/false type of questions


- two partials, two json files
  data asynchonous
    + maincontent partial
    + footer partial
    + questions data
    + inner html data (why not)


- modular pattern:  

    + 2 globals => one under mainApp and another under a Utilities module

    + 5 modules - self-exec fns, public and private methods and funs  

        - mainApp => mainContent (questions/answers)

        - utilities => will load main content and footer

             + dom, gen, string, page, and main util
             + sub-modules, call everything from main util


- images/css - minimum

<br/>

<kbd>working screenshot</kbd>
<br/>


![](images/remod4.png)


<br/>













