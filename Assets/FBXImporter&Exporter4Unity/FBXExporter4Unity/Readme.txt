----------------------------------------------------------------------------------------------

FBX Exporter 4 Unity �� Version 2015/08/07

Copyright (c) 2015, ACTINIA Software. All rights reserved.

Homepage: http://actinia-software.com

E-Mail: hoetan@actinia-software.com

Twitter: https://twitter.com/hoetan3

GitHub: https://github.com/hoetan

Developer: �ق�����(Hoetan)

----------------------------------------------------------------------------------------------
[Japanese Manual]

���Ή�OS

 Windows 10 (64bit)
 Windows 8/8.1 Update 1 (64bit)
 Windows 7 ServicePack 1 (64bit) [��Windows7�́AKinect2�͓����܂���B]


���Ή�3D�G���W��

 Unity Personal/Professional v5.1.2f1 (64bit)

���K�����̃o�[�W�����ȍ~�ŃV�[��(Scene)���J���ĉ������B������ȉ����ƃV�[���𐳏�ɊJ���܂���B


���Ή�Visual C++�����^�C��

 Visual Studio 2015 �� Visual C++ �ĔЕz�\�p�b�P�[�W (x64)�i���{��j: https://www.microsoft.com/ja-jp/download/details.aspx?id=48145

���uDllNotFoundException: Assets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Plugins/x86_64/FBXExporter4Unity.dll�v�̃G���[���ł��ꍇ�́A��L�̃����^�C���̃C���X�g�[�����K�{�ł��B


���Ή�Kinect1�h���C�o

 Kinect for Windows SDK v1.8 : http://www.microsoft.com/en-us/download/details.aspx?id=40278

��Kinect1�̃f�o�C�X���g�p�������ꍇ�́A��L�̃h���C�o���C���X�g�[�����Ăo�b���ċN�����Ă��������B


���Ή�Kinect2�h���C�o

 Kinect for Windows SDK 2.0 (1409): http://www.microsoft.com/en-us/download/confirmation.aspx?id=44561

��Kinect2�̃f�o�C�X���g�p�������ꍇ�́A��L�̃h���C�o���C���X�g�[�����Ăo�b���ċN�����Ă��������B


���g�p���C�u����(DLL)

 FBX SDK 2016.1 VS2015 (64bit): http://www.autodesk.com/products/fbx/overview

���uDllNotFoundException: Assets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Plugins/x86_64/FBXExporter4Unity.dll�v�̃G���[���ł��ꍇ�́A��L�̂r�c�j�ɂ���c�k�k�̃R�s�[���K�{�ł��B

�@�uC:\Program Files\Autodesk\FBX\FBX SDK\2016.1\lib\vs2015\x64\release\libfbxsdk.dll�v���AUnity�v���W�F�N�g�̃��[�g�i���j�փR�s�[���Ă��������B
�@(��Assets���ЂƂ�̊K�w�̃��[�g�̃v���W�F�N�g�t�H���_���փG�N�X�v���[���Łulibfbxsdk.dll�v���R�s�[����j


���g�p�v���O���~���O�c�[��(VisualC++)

 Visual Studio 2015 Professional


���g�pUnity�A�Z�b�g

 "Unity-chan!" model: https://www.assetstore.unity3d.com/jp/#!/content/18705

 Kinect Wrapper Package for Unity3D: http://wiki.etc.cmu.edu/unity3d/index.php/Microsoft_Kinect_-_Microsoft_SDK

 KinectForWindows UnityPro 2.0.1410: http://download.microsoft.com/download/F/8/1/F81BC66F-7AA8-4FE4-8317-26A0991162E9/KinectForWindows_UnityPro_2.0.1410.zip


���g�p���@

�@FBX Exporter���g�p�������ꍇ�́AUnity Editor��ŁA�uAssets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Scenes/FBXExporter4Unity.unity�v�̃V�[�����J���Ă�����s�i�Đ��j���Ă��������B
�@Kinect1���g�p�������ꍇ�́AUnity Editor��ŁA�uAssets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Scenes/UnityKinect1ToFBX.unity�v�̃V�[�����J���Ă�����s�i�Đ��j���Ă��������B
�@Kinect2���g�p�������ꍇ�́AUnity Editor��ŁA�uAssets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Scenes/UnityKinect2ToFBX.unity�v�̃V�[�����J���Ă�����s�i�Đ��j���Ă��������B
�@�V�K�V�[���̏ꍇ�́AHierarchy�́uMain Camera�v�ɁuAssets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Scripts/FBXExporter4Unity.cs�v�̃X�N���v�g���A�^�b�`���Ă�����s�i�Đ��j���Ă݂Ă��������B
�@���s�i�Đ��j����ƁA�v���W�F�N�g�̃��[�g�f�B���N�g�Ƀf�t�H���g�̃t�@�C�����uUnity.fbx�v��������������܂��B
�@FBX�t�@�C���́A3ds Max 2016 / Maya 2016 / Softimage 2015 / MotionBuilder 2016�ɑΉ����Ă��܂��B
�@Maya�p��Animator�̏o�͂�����ꍇ�́A�uApply Root Motion�v�̃`�F�b�N���O���Ă���o�͂���悤�ɂ��Ă��������B
�@�g�p���ꂽ�e�N�X�`���́A�uTextures�v�t�H���_�ɁAPNG�`���Ɏ����ϊ�����o�͂���܂��B
�@DCCTools��2016��艺�ʂ̃o�[�W�����ŁAFBX�`��(2016.1)��ǂݍ��ޏꍇ�́A�uFBX Converter 2013.3�v���g�p���āA�Â��o�[�W�����̂e�a�w�`���ɃR���o�[�g���Ă���ǂݍ���ŉ������B


�����C�Z���X

�@���̃\�t�g�E�F�A�ŏo�͂����e�a�w�t�@�C���́A���R�ɏ��p�E�񏤗p�Ŏg�p���邱�Ƃ������܂��B
�@�����̂o�b�i�p�\�R���j�ւ̃C���X�g�[���́A�䐔���̃��C�Z���X���K�v�ɂȂ�܂��̂ŁA���ӂ��Ă��������B


���̌��ł̎g�p����

�@�̌��łł́AFBX�t�@�C���́A����90�t���[��(����R�b�ԁj�ȏ�̃A�j���[�V�����͏o�͂���܂���B���i�łł͖������ł��B
�@FBX�t�@�C�����������ݎ��ɁA�A�Z�b�g�X�g�A�̃z�[���y�[�W�i��`�j�������ŊJ���܂��B���i�łł̓X�L�b�v����܂��B


�����i�ŏЉ�

�@�uAsset Store�v�ɂĐ��i�ł́uFBX Importer 4 Unity ���v�ƁuFBX Exporter 4 Unity ���v�ƁuFBX Importer & Exporter 4 Unity ���v��̔����ł��B

�@�EFBX Importer 4 Unity ��
�@�@http://u3d.as/iit

�@�EFBX Exporter 4 Unity ��
�@�@http://u3d.as/ghk

�@�EFBX Importer & Exporter 4 Unity ��
�@�@http://u3d.as/iiu


�����₢���킹

�@���P�āi�A�C�f�A�j��o�O�񍐂��A���[���ɂĎ󂯕t���Ă���܂��B
�@���łɁA���̃c�[���̎g�p�ړI���A���[���ŏڍׂ������Ă����Ə�����܂��B�i�����[�X�j

�@E-Mail: hoetan@actinia-software.com


----------------------------------------------------------------------------------------------
[English Manual]

��Compatible OS

Windows 10 (64bit)
Windows 8/8.1 Update 1 (64bit)
Windows 7 Service Pack 1 (64bit) [Windows7: Kinect2 is no support.]


��Compatible 3D Engine

Unity Personal/Professional v5.1.2f1 (64bit)

*Always open scenes using the version stated above or newer. Scenes will not properly open on older versions than the one stated above.


��Compatible Visual C++ Runtime

Visual Studio 2015 Visual C++ Redistributable Package (x64):
Japanese: https://www.microsoft.com/ja-jp/download/details.aspx?id=48145
English: https://www.microsoft.com/en-US/download/details.aspx?id=48145

*If the following error occurs:"DllNotFoundException: Assets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Plugins/x86_64/FBXExporter4Unity.dll"

Please download a runtime from one of the links above that best matches your language.


��Compatible Kinect1 Driver

Kinect for Windows SDK v1.8 : http://www.microsoft.com/en-us/download/details.aspx?id=40278

*If you want to use the Kinect1 device, install the above driver and restart your computer before use.


��Compatible Kinect2 Driver

Kinect for Windows SDK 2.0 (1409): http://www.microsoft.com/en-us/download/confirmation.aspx?id=44561

*If you want to use the Kinect1 device, install the above driver and restart your computer before use.


��Library Dependency(DLL)

FBX SDK 2016.1 VS2015 (64bit): http://www.autodesk.com/products/fbx/overview

*If the following error occurs:"DllNotFoundException: Assets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Plugins/x86_64/FBXExporter4Unity.dll"

Please copy-paste the DLL that is found in the above SDK.
Copy the DLL found from this path, "C:\Program Files\Autodesk\FBX\FBX SDK\2016.1\lib\vs2015\x64\release\libfbxsdk.dll", to the root (*) of the Unity project.
(*Copy-paste "libfbxsdk.dll" into the root project directory that is one hierarchy above the Assets directory.)


��Programming Tool Dependency (Visual C++)

Visual Studio 2013 Professional Update 5


��Used UnityAsset

"Unity-chan!" model: https://www.assetstore.unity3d.com/en/#!/content/18705

Kinect Wrapper Package for Unity3D: http://wiki.etc.cmu.edu/unity3d/index.php/Microsoft_Kinect_-_Microsoft_SDK

KinectForWindows UnityPro 2.0.1410: http://download.microsoft.com/download/F/8/1/F81BC66F-7AA8-4FE4-8317-26A0991162E9/KinectForWindows_UnityPro_2.0.1410.zip


��How to use

Using the FBX Exporter on Unity Editor: "Assets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Scenes/FBXExporter4Unity.unity" open this scene and play.

Using the Kinect1 to FBX on Unity Editor: "Assets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Scenes/UnityKinect1ToFBX.unity" open this scene and play.

Using the Kinect2 to FBX on Unity Editor: "Assets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Scenes/UnityKinect2ToFBX.unity" open this scene and play.

*If it is a new scene, attach the following script, �gAssets/FBXImporter&Exporter4Unity/FBXExporter4Unity/Scripts/FBXExporter4Unity.cs�h, to the �gMain Camera�h found in the Hierarchy.
Running(playing) the scene will automatically create a file with a default name �gUnity.fbx�h under the project's root directory.
This FBX file is compatible with: 3ds Max 2016, Maya 2016, Softimage 2015, MotionBuilder 2016.

When outputting Animation for Maya, please uncheck "Apply Root Motion".

Applied textures are automatically converted into PNG format and output to the �gTextures�h folder.

If the DCCTools being used is prior to the 2016 version; in order to be able to open the FBX format file (2016.1), please convert it to an older version of the FBX format using �gFBX Converter 2013.3�h.


��License

The FBX files exported through this software are free for personal and commercial use.
Please be aware that it is prohibited to use a single license to install this software on multiple computers. Each license purchased can only be applied to a single computer. Multiple computers will mean a need to purchase an equivalent amount of licenses.


��Limitations for the trial version

In the trial version, exported FBX files can only have animations up to 90 frames (about 3 seconds). There is no frame limitation for the product version.

Everytime a FBX file is saved, the asset store homepage will be automatically opened.
This will not occur for the product version.


��Now on sale

"FBX Importer 4 Unity ��" and "FBX Exporter 4 Unity ��" and "FBX Importer & Exporter 4 Unity ��" is now on sale in the "Asset Store".

FBX Importer 4 Unity ��
http://u3d.as/iit

FBX Exporter 4 Unity ��
http://u3d.as/ghk

FBX Importer & Exporter 4 Unity ��
http://u3d.as/iiu


��Contact Us

Mails about ideas for improving this software and bug reports are welcome.
Mails about how this software is being used are also very welcome.
 
E-Mail: hoetan@actinia-software.com