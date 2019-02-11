# serverless-p1
serverless AWS prototype

1. create a repo for this static site in github. https://github.com/plastiq/serverless-p1.git
2. navigate to your $REPO directory and clone the repo above.
3. jump in to your project directory and run npm install -g serverless
4. run sls create --template  hello-world
    a. this generates the handler.js & serverless.yml file.
5. run npm init then the following commands to download the dependencies.
    a. npm i --save express
    b. npm i --save body-parser
    c. npm i --save  hbs
    d. npm i --save serverless-http
6.