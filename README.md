<h1 align="center">Studento backend</h1>
<p align="center">Created with Serverless and AWS Lambda functions</p>

<h2 align="center">WIP</h2>

## Getting started

### 1. Clone the repository

```sh
git clone https://github.com/raulrusu88/studento-be-sls.git
```

<h2 align="center">I've separated each service into their own infrastructure</h2>

### 2. Go into each folder and install their respective dependecies

```
npm install
```

### 3. After you've installed their dependecies, you can follow their README instructions or just follow the guide here.

```
cd service-folder
```

- Now we need to deploy

```
sls deploy --verbose
```

- If we've made changes to a function, then we do not need to deploy the whole service, we can easily deploy only the changes from the function

```
sls deploy -f <functionName> --verbose
```

- To check the logs for a particular scheduled function

```
sls logs -f <processFunction>
```
