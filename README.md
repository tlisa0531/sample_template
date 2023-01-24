## SAMPLE TEMPLATE
![hi](/logo.png)

## Prerequisites 
1. Register an account at [Lyrid Web Application](https://app.beta.lyrid.io/) 
2. Download our command line tool, [the lc](https://docs.lyrid.io/initialization)
3. Clone the repo 'git clone https://github.com/sample_here'

### Run locally
Test your application by building and running it with the following command:
```
go get 
go run ./main.go
```
Your application will be served in http://localhost:8000

### Edit 
To change your file information:
Open ```.lyrid-definition.YML``` file
Change ```name``` and ```module name``` to your choice

Open ```go.mod``` file
Replace the variable after module following this format:
```[name].[modulename]```

Open ```main.go``` file
Replace the entry variable thats inside the import function following this format:
```
entry 
    "[name].[modulename]/entry"
```

### Start Coding!
Users can edit route url, settings, and views with custom APIs. 

## Submit to Lyrid 
Use our command line tool to easily upload your application to the cloud.
```
lc code submit
```

## Contact Us
Have any questions? We are here to help!
Email us at support@lyrid.io  

### Find us on social medias
- [Discord](https://discord.com/invite/xtCCtc9WAX)
- [LinkedIn](https://www.linkedin.com/company/lyrid/?viewAsMember=true)
- [Twitter](https://twitter.com/LyridInc)
- [Facebook](https://www.facebook.com/lyridinc)

