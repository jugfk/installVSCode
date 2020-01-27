# installVSCode (Korean Version)
젯슨나노에서 사용할수있는 VSCode 입니다.

Visual Studio Code의 커뮤니티 빌드를 설치하기위한 셸 스크립트입니다.

https://code.headmelted.com/

The primary focus of code.headmelted.com is to provide open-source edition of Visual Studio Code for less common architectures.
The builds are automated builds of the open-source edition of Microsoft's Visual Studio Code. The releases are not provided by Microsoft, but rather are an independent community effort. These builds are not affiliated with Microsoft, nor are they associated with JetsonHacks.

To install Visual Studio Code on the Jetson:

```
$ ./installVSCode.sh
```

This will add the repository keys for the installer, and then install Visual Studio Code. To run Visual Studio Code after installation:

```
$ code-oss
```

<h3>Notes</h3>

<ul><li>Initial Release September, 2019</li>
<li>Tested on Jetson Nano</li>
<li>L4T 32.2.1 (JetPack 4.2.2)</li>
<li>Code-OSS Version: 1.32.0 (user setup)</li>
<li>Commit: aeaef41d51201e555735f5e8d2f38a9d0ddb9026</li>
<li>Date: 2019-02-20T06:32:49.577Z</li>
</ul>
