# fac-13.github.io

fac-13 blog

## PROPOSAL

* NOTE - If any fac-13rs or mentors / organisers disagree with the proposal then I will remove the repo asap! Just thought the quickest way to get discussion going might be to get a README.md up and running.

### WHAT

* Set up a fac-13 blog to sit on github pages running as either an 'org' site (as it is set up presently) or as a 'project' site (if people prefer...)
* Use Jekyll static site generator to publish collaboratively: collaborators add markdown files to the `_posts` folder and commit-master to publish
* The blog is easily accessible at the url 'fac-13.github.io' (or slightly different if a 'project' page set-up)
* Create a nice theme if we feel like it...

### WHY

We have talked a lot at recent Friday SGCs about how best to store and share our learning. The research repo is an excellent resource (with loads of excellent contributions mainly from Tamara and Matthew) but:

1.  while adding important discoveries etc. to the repository issues is useful, code snippets, situation walkthrougs, reports on problems and solutions etc. are **not** issues
2.  while adding issues on a repo from the comand-line is not impossible, it requires fiddling and weird installs etc.
3.  because the research repo is just another repo:

* we tend not to put things in it which are to be found in other repos - what is the point of reproducing information already somewhere in github
* it is more or less as indistinguishable as all the other repos - it is found by navigating from some start point like a starred repository etc.

But the reason for having a resource like this is to make really useful information both as accessible and as easy to create and publish as possible. Having a distinct site/url offering a different interface from the usual github thing, and making adding new items to the list as easy as adding a new markdown file to the `_posts`folder and committing to master (maybe after a pull request...) might be a better way to do this.

Dotted around the FAC coursebook there are loads of walkthroughs of tasks that we have to perform relentlessly but which are hard to remember (because there are lots of stages or options, or because we have so many different things to set up overall for each project) - these are a pain to find and many of them could also be improved. It would be excellent to have them all in a centralised resource so that when we are in the middle of seting up a project and need to reassign a postgres user to a differnt DB, for example, we can just find the snippets we need immediately. And when we learn a good way to go about setting up Heroku, AWS or Azure etc. (as we might do in the course of the upcoming projects), we need a go to place to submit a walkthrough. It would also be brilliant ot have a place for us to build resources specific to the roles we are to be implementing in the coming weeks; good stuff for the Dev Ops or UX tema-members to know about etc.

Through a careful use of `tags`and `categories`etc. it should be pretty easy to create a rich but accessible resource that we all can benefit from and might provied a lot of useful material for when we are thinking about developing content for fac-14.

I am not an expert on Jekyll but I think it should be pretty simple for us all to be able to collaboratively publish 'posts' and to build site utilities (like filter posts by tag or show all the categories etc.) using the templating language which is very similar to handlebars.

I think I have gone on enough now - I look forward to hearing your thoughts: as I say, if the response is negative then I will take the repo down, and obvs we should discuss doing this in different ways if people want to do that as well...

Hxx
