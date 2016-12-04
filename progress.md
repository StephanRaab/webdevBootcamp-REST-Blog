#November 30th
###Restful App Index
+ Setup the blog app
+ Created the Blog model
+ Added INDEX route and template

###Basic Layout
+ Add header and footer partials
+ Include Semantic UI
+ Add simple nav

#December 1st
### NEW and CREATE routes
+ Add NEW route
+ Add NEW template
+ Add CREATE route
+ Add CREATE template

#December 3rd
### AngularJS meetup
### SHOW Route
### SHOWtime
+ Add show route
+ Add show template
+ Add links to show page
+ Style show template

### Edit/Update
+ Add EDIT route
+ Add Edit form
+ Add UPDATE route
+ Add update form
+ Add method override

### DESTROY
+ Add destroy route
+ Add edit and destroy links

#December 4th
### Restful Blog Final Updates
+ Sanitize Blog body
+ Style Index
+ Update REST Table

Name|Path|HTTP Verb|Purpose|Mongoose Method
:---|:---|:---|:---|:---|
Index|/blogs|GET|List all blogs|Blog.find()
New| /blogs/new|GET|Show new blog form|N/A
Create|/blogs|POST|Create new blog, then redirect somewhere|Blog.create()
Show| /blogs/:id|GET|Show info about one specific blog|Blog.findById()
Edit|/blogs/:id/edit|GET|Show edit form one blog|Blog.findById()
Update|/blogs/:id/edit|PUT|Update particular blog, then redirect somewhere|Blog.findByIdAndUpdate()
Destroy|/blogs/id|DELETE|Delete a particular blog, then redirect somewhere|Blog.findByIdAndRemove()

