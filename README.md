# DependencyStory
Plugin to extract data about project dependencies + Tool to visualize this data


1. Clone/download this repo
2. Run npm install to install dependencies
3. Init the dependencyStory Plugin
    - Add the following line in the buildscript of your project which dependencies you like to visualize
      apply from: "PATH/DependencyStoryPlugin.gradle"
    - Define the path to the assets folder of the dependency story app in the plugin-gradlescript
      in dependencyStoryPlugin.gradle in line 82: def path = "PATH/DependencyStory/src/assets"
4. Run the plugin on your project
   gradlew -q extractData 
5. Run ng serve to run the app locally
    Go to https://localhost:4200 in your browser
