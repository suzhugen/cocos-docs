# Publish

After editing resources in Cocos Studio, you need to publish them if you want to use them in Cocos 2d-x. In Cocos Studio, project files are stored in *.xml* format. After publishing, some unnecessary data will be removed from the project file. 
and at the same time*.xml* file is transferred into FlatBuffers and JSON, which are faster and memory efficient. 

To publish resources, do the following: 

1 Open HelloCcocos, click the publish button“![image](res/image0001.png) ”, and the resources are published. 

2 Click "publish and package![image](res/image0002.png)”, the following dialog box will pop up. 

![image](res/image0003.png)

3 Publish resources: perform the publish command. 

- Publish to Cocos Code IDE Project: first publish resources, then open project with Code IDE. For C++ project, this option cannot be selected. 

- Publish to Visual Studio Project: only for Windows, first publish resources, then open project with Visual Studio. 

- Publish to Xcode Project: only for Mac, first publish resources, and then open project with Xcode. 

4 Click **Setting**, you can see the following dialog box for project settings.  

![image](res/image0004.png)
 
5 Publish

- Resource and Project File: copy resources to publish directory; publish csd adn csi for Cocos 2d-x.  

    ***Note** The transfer speed will be lower if you publish a number of resources. It is recommended to select "Project File Only".* 

- Project File Only: only publish csd and csi for Cocos 2d-x. 

- Publish Directory: users can customize publish directory. Cocos Studio supports absolute and relative path. 

- Data Format

    - csb File: FlatBuffers is employed to read binary files, feature in high efficiency, small size, significant security. Support Cocos2d-x C++ and Lua Binding. 

    - JSON File: Lightweight data transfer format, good readability, native support for JavaScript. Support Cocos2d-JS.

    - Custom export: more information [Customizing Exported Data Formats](../../chapter3/Extend/CustomExport/en.md). 





