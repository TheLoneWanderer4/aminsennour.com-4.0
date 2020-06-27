# aminsennour.com 4.0

### Steps

- $mvn clean install 
    - This will generate the static site from the react, and copy 
    it into the folder for spring to serve
    - No clue how this will work with react router 
- Github actions time 
    - Next step is to create an action that runs this whenever 
    a merge to master is initiated, and then deploys the resulting jar file
    to AWS