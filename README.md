Add your api key and secret to src/Config.js. Create one if it doesn't exist. Here's an example

```
const appConfig = {
    username: "",
    password: ""
}

export  default  appConfig
```

Since the App run on the localhost:3000, we can make it accessible through ngrok. Whereas in production it is going to be customer's service IP/Domains. 
