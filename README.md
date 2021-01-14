# 젯슨나노에서 VSCode 설치 및 사용하기 (Korean Version)
***

* 젯슨나노 2/4gb 에서 공식적으로 사용할수있는 VSCode 입니다.
 이 빌드는 공식적으로 Microsoft Visual Studio Code의 오픈 소스 버전의 자동화 된 빌드입니다. 

* Jetson Nano에 Visual Studio Code를 설치하려면:

```
$ cd
$ wget https://github.com/toolboc/vscode/releases/download/1.32.3/code-oss_1.32.3-arm64.deb
$ sudo dpkg -i code-oss_1.32.3-arm64.deb
```

*  Visual Studio Code가 설치됩니다. 설치 후 Visual Studio Code를 실행하려면:

```
$ code-oss
```

<h3></h3>
<li>젯슨나노 2, 4 gb에서 테스트했음</li>
<li>L4T 32.2.1 (JetPack 4.2.2)</li>
<li>Code-OSS 버전 : 1.32.3 (사용자 설정)</li>
</ul>

## 출처:

* https://github.com/toolboc/vscode/releases
* https://github.com/toolboc/vscode
