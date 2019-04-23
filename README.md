# Udacity Carnival
Starter project for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Course: Introduction to Virtual Reality
- Project: Udacity Carnival

# About
This project was built by Gabriel A. León Paredes. The goal of this project is to modify the original Udacity Carnival VR project to interact with the Unity game framework. This project has been built using 2017.4.21f1 Unity version (oculus recommended version). I have used this Unity version because I am developing apps for Oculus Rift hardware. 

Also, to meet with the specifications of the Udacity Carnival Project, I have (1) personalized the Scoreboard title with "Gabriel A. Leon Paredes Scores". I have changed the font size to 1.7 in order to fit into the text input box. Also, I have (2) customized the Coin Toss Game so that the coin could be toss. To accomplish this specification I have changed the Min and Max toss power of the Carnival Coin Toss component. I have changed to 10 (min) and 13 (max) values. These values have been obtained from the secret code "CTMin10Max13". Then, I have (3) customized the wheel of fortune game to display different values of the wedges. I have used 75, 100, 150, 200 values for smaller to larger wedges correspondingly. Additionally, I have (4) customize the Plinko game in order to start falling the ball in different positions. I have used an oscillation distance value of 0.7. This value has been obtained when successfully toss a coin in the Toss Coin game. The value presented is "OssDist0.7". Finally, I have (5) changed the position of the Teddy Bear in order to land near to the wheel of fortune game and not under the player.

### Versions Used
- [Unity LTS Release 2017.4.21f1](https://unity3d.com/unity/qa/lts-releases?version=2017.4)
- [GVR SDK for Unity v1.170.0](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.170.0)
- [TextMesh Pro](https://assetstore.unity.com/packages/essentials/beta-projects/textmesh-pro-84126) v1.2.2


### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated lesson.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.


### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is not included.
- The `Max Reticle Distance` value for the `GvrReticlePointer` used in the scene is set to `20` instead of the default `10`.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.170.0, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.
