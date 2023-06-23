# duid_template
duid template


## Install  
```  
cargo install cargo-duid-app  
```  
  
## Create project  
```  
cargo duid-app init --name <PROJECT_NAME>  
```  
  
## Develop your project  
```  
cd <PROJECT_NAME>  
cargo duid-app dev  
```  

## Run develop server 
Open another terminal      
```  
cargo duid-app serve // default --host="0.0.0.0" --port=3000  
cargo duid-app serve --host <HOST>  --port <PORT>  
```  

## Build your project    
```  
cargo duid-app build  
``` 

## Run production server  
```  
cargo duid-app deploy // default --host="0.0.0.0" --port=3000  
cargo duid-app deploy --host <HOST>  --port <PORT>  
``` 