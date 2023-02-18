# Group 06
## Land Cover Change

## Description : 
    > The goal of the project is to visualize the Spatio-temporal changes of landsurface for two years. Currently, we have found the landsurface change for Münster, Germany for the year 2013 and 2022. We created an interactive web application using the Streamlit and Folium libraries. The application takes input paths for two directories, each containing seven raster image files representing different spectral bands of satellite imagery for two years. The user can select which vegetation index to calculate and visualize and can also adjust a threshold value for creating a binary mask. The NDVI (Normalized Difference Vegetation Index), NDWI (Normalized Difference Water Index), NDBI (Normalized Difference Built-up Index), and SAVI (Soil Adjusted Vegetation Index) are calculated using the specified spectral bands. The calculated vegetation index is then used to create a color-coded raster image, and the image is displayed on an interactive map using the Folium library. The color-coded image is also overlaid with a binary mask, which can be adjusted by the user using the threshold slider.

## Add your files

- [ ] [Create](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://zivgitlab.uni-muenster.de/cvmls/itsp22/group-06.git
git branch -M main
git push -uf origin main
```

## Integrate with your tools

- [ ] [Set up project integrations](https://zivgitlab.uni-muenster.de/cvmls/itsp22/group-06/-/settings/integrations)

## Installation
pip install folium

# Editing this README

When you're ready to make this README your own, just edit this file and use the handy template below (or feel free to structure it however you want - this is just a starting point!). Thank you to [makeareadme.com](https://www.makeareadme.com/) for this template.

## Suggestions for a good README
Every project is different, so consider which of these sections apply to yours. The sections used in the template are suggestions for most open source projects. Also keep in mind that while a README can be too long and detailed, too long is better than too short. If you think your README is too long, consider utilizing another form of documentation rather than cutting out information.

## Authors
-[Ram Kumar](ramkumar.m@uni-muenster.de)
-[Mohamed Shamsudeen](shamsudeen.m@uni-muenster.de)

## Project status
If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
