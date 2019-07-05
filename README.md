# AngularJs_ApiServices_Utils

# Step 1:
	Install node js by downloading the installable from Install NodeJS

# Step 2: 
	Install angular cli using the following command.It wll get us the latest version of angular cli.
	$ npm install -g @angular/cli
	
# Step 3: 
	Next we will create a new angular project using the angular cli as follows-
     $  ng new employee-management	

# Step 4: 
	To get the angular cli project started use the following command. We must go inside the employee-management folder and then use it.
    $ ng serve

# Step 5: 
	Go to localhost:4200 
     http://localhost:4200	
	
	
# Step 6: 
    Open Project in visual studio ide for angularjs download
	Shortcuts :
		Ctrl +P --->Search for File
		Ctrl+F4 -->Close single file
		Ctrl+K W -->Close all files in workspace/window
		Shift + Alt + F  ==>Code Format 


#Step 7: 
	Create employee component,We will be creating Employee Component which will fetch data from spring boot and display it. Lets begin with the employee component Open a command prompt and use the following command-
 ``` $ ng generate component employee 
  For this angular will have created the following 4 files-
		employee.component.ts
		employee.component.spec.ts
		employee.component.html
		employee.component.css
```
# Step 8: 
	Next in the app-routing.module.ts we will be defining the url for accessing this component-  add in app-rounting.module.ts below code for UI action
		  import { EmployeeComponent } from './employee/employee.component';
			const routes: Routes = [
			  { path:'', component: EmployeeComponent},
			];
# Step 9: Create HttpClient Service
	Next we will be creating a HTTPClient Service. This service will be having the httpClient and will be responsible for calling http GET request to the backend spring boot application.
	In Angular a service is written for any cross cutting concerns and may be used by more than one components
  	
  	$ ng generate service service/httpClient 
  The following service files are created-
		http-client.service.ts
		http-client.service.spec.ts

```

Templates means ===>> (Module + Component)
employee.component.html(View)
employee.component.ts(Module)

(Module+Component)   ---->
                                    ---> (Module[SERVICES])------>Servers
(Module+Component)   ---->

```

URL : https://www.javainuse.com/spring/ang7-hello

# Routers are responsible for the navigation. Thus, based on the URL, it will decide which view component will be presented to the user.

First download nodejs latest version

npm install -g angulr/cli

ng serve (ng means angular & serve ==> service or server,Invoking angular engine )

app.component.html

Angular Version 2==>
MVC Pattern
M--Model
V---> View
C-Components

V-->View ==>html (static)
        ===>app.component.html
		
		View need model
		
app.components.ts (type script)
  @Component({
  
  })		
  
 View and component is called as Templates

@Componets==> Componets 

import {Componet} from '@angular/core' 
  @Component({
  selector:'app-root',
  templaeUrl:'./app.compoent'
  })

app.componets.ts (Templates Info )

app.module.ts :

Goble Templates :

app.compnent.css
app.compnent.html
app.compnent.ts (Components)
app.componet.cs(componets)
CSS :SCSS 


CSS Frame work is called SCSS 

View means ==> app.compoment.html & app.componet.css)

Jasimne Karma :(Anuglar Testing Framework)
app.component.spec.ts
jasimne -->Engine 
Karmma --> TEsting Enviornemnt




app.module.ts(module Configuration file)

app.module.ts(Configuration)
@NgModule({
declartions:[
AppComponent
],
imports:[

]
})

=================================


Routing Module :====>>
export class AppRoutingModule

Anuglar Application is Single Page application
DOM ==> HTML & One page to another page convert
DOM totally reload the entire page

const routes:Routes=[];


model 

service: service also ts file 
create one folder 
src-->app--> CreateOneFolder 

Template ==VIew +Comppontes

Module ==>Components Realated Structed 
Routing ==>Navigation 
app.module.ts ==> Configuration
































		 
	
	
