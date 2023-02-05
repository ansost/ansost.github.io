# ansost.github.io
A note to myself as to how this website works. 
This repository is only the `public` folder within my actual website folder.
The `public` folder in return, is the generated version of the website. Everytime you make changes, you have to generate the site again (in the future, this should probably be a workflow/script). 

Workflow:
1. Change files (not in the public folder). 
2. Run `hugo` in the website folder (outside of `public`), this generates a new `public` folder.
3. In the `public` folder, commit the changes. Your website is now updated. 
