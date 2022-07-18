### Running the project:

1. To Execute network infrastructure stack Usage:
```shell
./create.sh myFirstStack network.yml network-parameters.json
```


2. execute services infrastructure stack Usage: 

```shell
./create.sh mySecStack servers.yml server-parameters.json
 ```
 
 3. To Update network infrastructure stack Usage:
 
```shell
./update.sh myFirstStack network.yml network-parameters.json
```
4. To Update services infrastructure stack Usage:

```shell
./update.sh mySecStack servers.yml server-parameters.json
```

5. To Delete Stack Usage:

```shell
aws cloudformation delete-stack --stack-name  mySecStack
aws cloudformation delete-stack --stack-name  myFirstStack
```