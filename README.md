# sample.x-Template
<img width="781" alt="Screenshot 2023-01-24 at 12 48 20 PM" src="https://user-images.githubusercontent.com/28975372/214409011-5c55f7b4-ec2b-4724-8260-11f761c82a97.png">
<img width ='700' alt ='logo' =src'https://uploads-ssl.webflow.com/61579705e509c4f3e4ec5318/62541e9b4c15eab18595b215_logo%20ungu.png?'>


### Prerequisites 
1. Register an account at [Lyrid Web Application] (https://app.beta.lyrid.io/) 
2. Download our command line tool, [the lc] (https://docs.lyrid.io/initialization)
3. Clone the repo 'git clone https://github.com/sample_here'

### Run locally
Test your application by building and running it with the following command:
'''
go get 
go run ./main.go
'''

Your application will be served in http://localhost:8000

### Edit 
To change your file information:
Open .lyrid-definition.YML
Change these variables to your choice
1. name
2. module name

Open go.mod file
Replace the variable after module following this format:
[name].[modulename]

Open main.go file
Replace the entry variable thats inside the import function following this format:
entry 
    "[name].[modulename]/entry"

### Start Coding!
Users can edit route url, settings, and views with custom APIs. 

### Submit to Lyrid 
Use our command line tool to easily upload your application to the cloud.
'''
lc code submit
'''

### Contact Us
Have any questions? We are here to help!
Email us at support@lyrid.io  
