Proteus Examples
================

[![Join the chat at https://gitter.im/mlickeivipa/proteus-examples](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/mlickeivipa/proteus-examples?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


Example App
-----------

The example app (*/proteus-examples/example-app*) is a gradle project with dependencies on proteus framework that you can download [here](https://github.com/VentureTech/proteus-examples/releases/). The project is preconfigured for use with Intellij IDEA version 13+. Standard settings are provided for Intellij IDEA and Eclipse in the config folder.

<strong>Use</strong>
* Download and unpack the project.
* Open the project in your IDE of choice. 
* Rename the project to match your needs - both project name and directory name unless the directory will become the root of the git repo.
* Update gradle.properties (especially app_group and app_vesion). You'll want to copy the read access properties for the artifact repo to your /home/$USER/.gradle/gradle.properties* file.
* Decide on a good package name for your project and update the files so that they don't use com.example.
* Modify com.example.app.config.ExampleAppProjectConfig to suit your project.  Don't leave it named "ExampleAppProjectConfig".
* Add -Dspring.config=com.example.app.config.ExampleAppProjectConfig to all of your launch configurations (update for actual class name)
* If using Intellij IDEA then import the standard settings (File->Import Settings) from */proteus-examples/example-app/config/idea/settings.jar*. Make sure the __i2rd__ Code Style scheme is selected in the IDEA settings dialog.
* Create a git repo where you host your code such as github and push the project up.
* Code!


For documentation on the Proteus Framework, head over to http://docs.proteusframework.com
