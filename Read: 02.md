# reading-notes 
------
## Seeing Your Remotes
--------
### The git remote command displays the short names of all listed remote handles, such as "origin."

### With git remote -v, you can see all of the remote URLs along with their short names.
 $cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

remote3 https://github.com/remote3/example (fetch)

remote3 https://github.com/remote3/example (push)

---------
## Adding Remotes
#### create a new remote Git repository with a short name
$ git remote add js https://github.com/janesmith/project1

$ git remote -v

origin https://github.com/johndoe/project1 (fetch)

origin https://github.com/johndoe/project1 (push)

js     https://github.com/janesmith/project1 (fetch)

-----------
![remotes]( https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRaN-qIb0NFE6B9r4FkcCL0M1ZpQPVhyCvqZayZPNcqiLHwYfvmbA1niY5a5aU1jmSMGY&usqp=CAU )



