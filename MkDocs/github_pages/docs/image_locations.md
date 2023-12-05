# Objectives
Image locations and references to the images has to change:

* Image location of lab images
* Edit build_all_mkdocs.sh 
¨


## 1. Image location of lab images

Previously it was needed to use absolute links to images which also had to include the name of the lab, e.g.:

    Select your branch in the dropdown box:
    ![Select branch](/img/contribute/add_select_branch.png)

this needs to be changed to a relative link, as github pages add a first level in the URL being the name of the Github repository.
Because of that the images needs to be located under the lab, e.g.:

    Select your branch in the dropdown box:
    ![Select branch](../img/add_select_branch.png)


This also means that the image files must be in the labs `img` folder without an additional folder that needs to have the same name as the lab.
Meaning this structure
![Image Location Before](../img/image_locations_01.png)

has to change to this structure
![Image Location After](../img/image_locations_02.png)

## 2. Edit build_all_mkdocs.sh

Once the image locations have changed (in the folder structure and in the links in the md files) then we need to change the build script from:
![Build script before](../img/image_locations_03.png)

by removing the last to lines per lab, hence do not copy images to a central (but unavailable for github pages) location:
![Build script after](../img/image_locations_04.png)

