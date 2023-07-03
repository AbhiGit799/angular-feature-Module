# angular-feature-Module

Hi, <br/>

This is a simple Angular POC created by Abhishek Choubey. <br/>

In this POC I tried to demonstrate Feature Module concepts in Angular. <br/>

Here,<br/>
I used following types of loading:-<br/>
✓ Eager loading is loading modules before application starts. <br/>
✓ Lazy loading is loading modules on demand. <br/>
✓ Preloading is loading modules in background just after application starts. <br/>

<br/> <br/>
<b>Key Points:- </b>  <br/>

--skip-tests by this attribute in terminal, we can skip creation of test file.  <br/>

Command for creating module = ng g m modulename  <br/>

Command for adding routing file in Module => ng g m modulename --routing   <br/>

Command to add module automatically inside app.module.ts file  <br/>
ng g m modulename --routing --flat --module=app  <br/>


<b>Example for Creating Module in Angular</b>

ng g m company --routing --module=app   <br/>

now we are creating root component of company module.  <br/>
means component without folder.  <br/>

ng g c company/company  --flat <------- for creating root component of company module  <br/>

now creating normal component inside company module  <br/>

ng g c comapny/company-list <------- command  <br/>

<b> I also demonstrated the concept of Canload Guard and CanActivate Guard </b>  <br/>


 <br/> <br/>

 
Software Used <br/>
node --version = v14.20.0 <br/>
npm --version = 6.14.17 <br/>
ng version <br/>
Angular CLI: 14.0.0 <br/>
