[![](https://jitpack.io/v/CarGuo/GSYIjkJava.svg)](https://jitpack.io/#CarGuo/GSYIjkJava)

### 用于迁移 ijkplayer-java

```
implementation "com.github.CarGuo:GSYIjkJava:1.0.0"
```

### 更多请见 https://github.com/CarGuo/GSYVideoPlayer



1、先执行 ./gradlew publishToMavenLocal
2、在本地 .m2 > repository 找到  io\github\carguo\gsyijkjava\1.0.0 目录下的包
3、给每个包都执行   gpg -ab  生成 asc
4、给每个包都支持 md5sum 和 sha1sum 生成 md5 和 sha1
6、从 io 目录开始压缩文件上传

https://medium.com/@alidoran/publishing-in-the-maven-central-by-central-portal-method-in-sonatype-for-an-android-project-e22baeec2701