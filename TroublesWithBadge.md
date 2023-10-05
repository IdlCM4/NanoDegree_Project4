In the task, you are asked to add a status badge on README file to check the status of the project.

This [guide](https://circleci.com/docs/status-badges/) is provided to you, however, after followinf the steps the badge is not working, at least for me.  
There are 3 ways of creating a Badge:  
1. Badbe for the entire project:  

    ![Example 1](badge\example1.PNG)

    Following this example, my badge would be like this:  

    <pre>[![cci-lra36](https://circleci.com/gh/cci-lra36/NanoDegree_Project4.svg?style=svg)](https://circleci.com/gh/cci-lra36/NanoDegree_Project4)</pre>
    and this is the result:  
    [![cci-lra36](https://circleci.com/gh/cci-lra36/NanoDegree_Project4.svg?style=svg)](https://circleci.com/gh/cci-lra36/NanoDegree_Project4)

    As you can see, it doesn't work.


2. Badge for specific branch:

    ![Example 2](badge\example2.PNG)

      Following this example, my badge would be like this:  

      <pre>[![cci-lra36](https://circleci.com/gh/cci-lra36/NanoDegree_Project4/tree/main.svg?style=svg)](https://app.circleci.com/pipelines/circleci/XqgHvWAk6M7wq1Co6bdyYt/JJE1boYb9qGGfpDwctAdcm?branch=main)</pre>
      and this is the result:  
      [![cci-lra36](https://circleci.com/gh/cci-lra36/NanoDegree_Project4/tree/main.svg?style=svg)](https://app.circleci.com/pipelines/circleci/XqgHvWAk6M7wq1Co6bdyYt/JJE1boYb9qGGfpDwctAdcm?branch=main)

      As you can see, it doesn't show the "passed" badget .




[![CircleCI](https://dl.circleci.com/status-badge/img/circleci/XqgHvWAk6M7wq1Co6bdyYt/JJE1boYb9qGGfpDwctAdcm/tree/main.svg?style=svg&circle-token=0376ab30bcc409dbf72dc8233e938bf92e7002e3)](https://app.circleci.com/pipelines/circleci/XqgHvWAk6M7wq1Co6bdyYt/JJE1boYb9qGGfpDwctAdcm?branch=main)