sample_ubuntu1204_java
======================

This sample helps you create a shippable.yml file for your Java project on Shippable. Please refer to our [language specific documentation on Java](http://docs.shippable.com/languages/#java) for more details.

### Build Image

The sample uses a Java specific build image that's available for public use:
 [shippableimages/ubuntu1204_java](https://registry.hub.docker.com/u/shippableimages/ubuntu1204_java)  ([Dockerfile](https://github.com/shippableImages/ubuntu1204_java/blob/master/Dockerfile)).

To set your build image in Shippable:
- Login to [Shippable](https://www.shippable.com) 
- Navigate to your project page by clicking on the project link
- Click on **Settings** and choose the following option:

`Pull Image from : shippableimages/ubuntu1204_java`

For more details on project settings, you can refer our docs on  [Build and Project Settings](http://docs.shippable.com/project_settings).
