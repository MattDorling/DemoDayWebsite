# DemoDayWebsite

- The entire source for the website is within the html folder, this makes it easier to transfer it to the group website html folder on afs.
- Can just ssh into DICE, `git clone` or `git pull` it from home directory, then `cp -r html /afs/inf.ed.ac.uk/group/teaching/sdp/sdp20`
- Go to https://group20.sdp.inf.ed.ac.uk/ to see it.
- Read through https://group20.sdp.inf.ed.ac.uk/index-demo.html to see what you can do with the template. Make it look nice.
- The icons come from FontAwesome, browse them here https://fontawesome.com/v4.7.0/cheatsheet/ (I think our template uses an older version so not all work)

# To add your section:
- `git clone https://github.com/RoboGardenerTeam/DemoDayWebsite.git`
- `git checkout -b "feature-branch-name"` to create and checkout a new branch
- edit the file `index.html` to add your section
- `git add .`
- `git commit -m "description of commit"`
- `git push -u origin feature-branch-name`
