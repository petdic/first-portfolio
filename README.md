# first-portfolio

## Create project

```
vue create "name"
```

## Add bootstrap

```
npm i bootstrap-vue

at app entry points add:

import BootstrapVue from 'bootstrap-vue'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
Vue.use(BootstrapVue);
```

## Add serverless file

```
copy serverless files across:

bin
resources
serverless.yml

and configure .gitignore
```

## Configure serverless files

```
change project name
configure dns and ssl
change delete and deploy information in bin
```

## Deploy serverless

```
sls deploy -s dev
or
sls deploy -s prod
```

## Check certificate manager

```
resend certificate
accept certificate in email
this can take as long as 30 mins
```

## Compile vue application

```
npm run build
```

## Upload to dist file to S3 bucket

```
bash ./bin/deploy_static_files.sh
```

## Project build complete

```
Vue application should be available on the web
```

```

```

## Vue application

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Run your tests

```
npm run test
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
