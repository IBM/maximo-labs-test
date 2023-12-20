# Deploy to Github Pages

This part of the contribution is performed by the repository administrators.</br>
Contact him to accept your Pull Request and then perform the build and deploy.

Build the site locally:

    cd ~/Git-Repos/maximo-labs
    ./build_all_mkdocs.sh
 
Once the build is complete, verify the changes works as expected</br>
- then press `Ctrl-C` to get back to the prompt.</br>
The site directory contains the complete MKdocs build. </br>
This has to be pushed to the `gh-pages` branch with the following command:
 
    ghp-import -po site

---
