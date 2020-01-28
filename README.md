# 基于ijkplayer 0.8.8编译default版本
----------  


基于blibli开源的ijkplayer源码（[传送门](https://github.com/Bilibili/ijkplayer)）进行编译，使用的是module-default.sh配置编译，支持较全的编解码格式！具体描述可查看源码的README.md文件  
**gradle依赖**
```gradle
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```
```gradle
implementation 'com.github.LongAgoLong.ijkplayer:ijkplayer-java:1.0.0'
implementation 'com.github.LongAgoLong.ijkplayer:ijkplayer-exo:1.0.0'

implementation 'com.github.LongAgoLong.ijkplayer:ijkplayer-armv7a:1.0.0'
implementation 'com.github.LongAgoLong.ijkplayer:ijkplayer-x86_64:1.0.0'
implementation 'com.github.LongAgoLong.ijkplayer:ijkplayer-x86:1.0.0'
implementation 'com.github.LongAgoLong.ijkplayer:ijkplayer-arm64:1.0.0'
implementation 'com.github.LongAgoLong.ijkplayer:ijkplayer-armv5:1.0.0'
```
**maven依赖**
```gralde
<repositories>
	<repository>
		<id>jitpack.io</id>
		<url>https://jitpack.io</url>
	</repository>
</repositories>
```
```gradle
<dependency>
	<groupId>com.github.LongAgoLong</groupId>
	<artifactId>ijkplayer</artifactId>
	<version>$JitPack-Version$</version>
</dependency>
```
