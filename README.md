# Hololens-Point-Cloud-Stream
Using Holo-Lights ISAR SDK to stream from Unity directly to my HoloLens 2 device

Built off of Repo by Dr. Takashi Yoshinaga: https://github.com/TakashiYoshinaga/Azure-Kinect-Sample-for-Unity.git

His Repo contains general instructions for setup.

As for ISAR Streaming make sure you are using Mixed Reality Toolkit version 2. Version I used was 2.8.2.

MRTK2 Documentation: https://learn.microsoft.com/en-us/windows/mixed-reality/mrtk-unity/mrtk2/?view=mrtkunity-2022-05

AS for ISAR setup instruction, follow this instruction: https://support.holo-light.com/portal/en/kb/articles/isar-sdk-2400-quickstart-guide-for-hololens-2

Clone this Repo: https://github.com/Holo-Light-GmbH/ISAR-SDK-Trial

Unity Version I developed this with is 2020.3.36f1 LTS. 
Note: 2021 or above version is still not fully supported for ISAR streaming

Build Platform should be set to Windows, Mac or Linux. 

For people who have Hololens device you can download ISAR Client app from Microsoft Store. You will need that installed to enter your Computer IP to the ISAR client app which will then stream the app yo have running in Unity Editor directly to the Hololens.

ISAR works for Both Point cloud and Texture mesh unity scenes

Youtube Demo: https://www.youtube.com/watch?v=MygckMAV3RA
