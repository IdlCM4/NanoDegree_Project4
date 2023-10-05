In the task, you are asked to add a status badge on README file to check the status of the project.

This [guide](https://circleci.com/docs/status-badges/) is provided to you, however, after followinf the steps the badge is not working, at least for me.  
There are 3 ways of creating a Badge:  
1. Badbe for the entire project:  

    ![Example 1](badge/example1.PNG)

    Following this example, my badge would be like this:  

    <pre>[![cci-lra36](https://circleci.com/gh/cci-lra36/NanoDegree_Project4.svg?style=svg)](https://circleci.com/gh/cci-lra36/NanoDegree_Project4)</pre>
    and this is the result:  
    [![cci-lra36](https://circleci.com/gh/cci-lra36/NanoDegree_Project4.svg?style=svg)](https://circleci.com/gh/cci-lra36/NanoDegree_Project4)

    As you can see, it doesn't work.


2. Badge for specific branch:

    ![Example 2](badge/example2.PNG)

      Following this example, my badge would be like this:  

      <pre>[![cci-lra36](https://circleci.com/gh/cci-lra36/NanoDegree_Project4/tree/main.svg?style=svg)](https://app.circleci.com/pipelines/circleci/XqgHvWAk6M7wq1Co6bdyYt/JJE1boYb9qGGfpDwctAdcm?branch=main)</pre>
      and this is the result:  
      [![cci-lra36](https://circleci.com/gh/cci-lra36/NanoDegree_Project4/tree/main.svg?style=svg)](https://app.circleci.com/pipelines/circleci/XqgHvWAk6M7wq1Co6bdyYt/JJE1boYb9qGGfpDwctAdcm?branch=main)

      As you can see, it doesn't show the "passed" badget and the url doesn't work either.


3. Badge for private repositories:  
    This shouldn't be the case, as my gitHub repo is public as you can see on the next image, but let me try as well.  
    ![GitHub repo](badge/github.PNG)

    ![Example 3](badge/example3.PNG)

      Following this example, my badge would be like this:  

      <pre>[![cci-lra36](https://circleci.com/gh/cci-lra36/NanoDegree_Project4.svg?style=svg&circle-token=2366ba47edb3a692ba4326bd23590de9ac7d0470)](https://circleci.com/gh/cci-lra36/NanoDegree_Project4)</pre>  
      and this is the result:  
      [![cci-lra36](https://circleci.com/gh/cci-lra36/NanoDegree_Project4.svg?style=svg&circle-token=2366ba47edb3a692ba4326bd23590de9ac7d0470)](https://circleci.com/gh/cci-lra36/NanoDegree_Project4)

      Doesn't work either.

4. There is another way to generate and include a badge. You have to go to the project -> click on "Project settings" and on the left menu go to Status Bades.

    ![CircleCI Repo](badge/ProjectStatusBadge.PNG)

    By clicking on "Add API Token" you generate a token and automatically the Markdown is shown to you. This is the code generated:

    <pre>[![CircleCI](https://dl.circleci.com/status-badge/img/circleci/XqgHvWAk6M7wq1Co6bdyYt/JJE1boYb9qGGfpDwctAdcm/tree/main.svg?style=svg&circle-token=9b51aa57c002a8472401ecd977e746c3f543f531)](https://dl.circleci.com/status-badge/redirect/circleci/XqgHvWAk6M7wq1Co6bdyYt/JJE1boYb9qGGfpDwctAdcm/tree/main)</pre> 

    And this is the result:

    [![CircleCI](https://dl.circleci.com/status-badge/img/circleci/XqgHvWAk6M7wq1Co6bdyYt/JJE1boYb9qGGfpDwctAdcm/tree/main.svg?style=svg&circle-token=9b51aa57c002a8472401ecd977e746c3f543f531)](https://dl.circleci.com/status-badge/redirect/circleci/XqgHvWAk6M7wq1Co6bdyYt/JJE1boYb9qGGfpDwctAdcm/tree/main)

    As you can see, now the badge displays properly but the link shows a page not found:
    ![Error](badge/NotFound.PNG)


This is my proyect page on CircleCI where you can see the passed builds, the name of the project, the branch, my organization, etc.   
![CircleCI Repo](badge/Status.PNG) 

I don't know why the links are not working, even the ones that's generating circleCi itself (option 4). Please, if you have any idea of what the problem is or what am I doing wrong let me know.

Kind regards.
