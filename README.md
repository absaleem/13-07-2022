# 13-07-2022
Array and Objects tasks

1) for the given json iterate all for loops

a) for loop:
var arr=[{name:"dennis",age:27,gender:"Male"},{name:"sweety",age:24,gender:"Female"},];
for(var i=0;i<arr.length;i++){
console.log(arr[i].name+" "+arr[i].age+" "+arr[i].gender);
}

b) for in loop:
var arr1=[{name:"dennis",age:27,gender:"Male"},{name:"sweety",age:24,gender:"Female"},];
for(var i in arr1){
console.log(i,arr1[i]);
}


2) Create your own resume data in JSON format
var arr=[{name:"Abdul Saleem",age:"34",gender:"Male",email:"saleem.mcstn@gmail.com",education:"MCA (2010 –2012), Bsc-CS (2005-2008)",tools:"HTML,CSS,JAVASCRIPT,JSON,ARRAY",expereince:"Professional experience in Web application development, architecture, optimization, design, maintenance, testing, and support.
•	Lead teams in the design of new applications.
•	Extensive knowledge and on-hands experience in information architecture, project management.
•	Proven background in large-scale enterprise application implementations. Well Communication with analytical, interpersonal skills and working in a team-oriented environment. Rapidly adapts to new technologies, standards and ideas.
"}];
for(var i=0;i<arr.length;i++){
console.log("Name: "+arr[i].name+", Age: "+arr[i].age+", Gender: "+arr[i].gender+", Email: "+arr[i].email+", Education: "+arr[i].education+", Tools used: "+arr[i].tools+", Experience:"+arr[i].expereince);
}


3) Read the difference between window,screen and document in javascript

Window is the main JavaScript object root, aka the global object in a browser, and it can also be treated as the root of the document object model. You can access it as window.

window.screen or just screen is a small information object about physical screen dimensions.

window.document or just document is the main object of the potentially visible (or better yet: rendered) document object model/DOM.


