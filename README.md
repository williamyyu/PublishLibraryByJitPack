# Publish an Android Library by JitPack
![](https://jitpack.io/v/ome450901/TestPublishLibrary.svg)
(https://jitpack.io/#ome450901/TestPublishLibrary)

## See more detail in my [Blog](https://medium.com/@ome450901/publish-an-android-library-by-jitpack-a0342684cbd0#.gcakfn5mw)

![image](https://cdn-images-1.medium.com/max/1600/1*7_n-b5as466ZCcpJkFn6eA.png)

>JitPack is a novel package repository for JVM and Android projects. It builds Git projects on demand and provides you with ready-to-use artifacts (jar, aar).

## Steps
1. Create an Android project and add a library module, here my library module name is mylibrary.
2. Add the android-maven plugin in your project/build.gradle
3. In your library/build.gradle add maven plugin and group setting
4. Upload this project to your github
5. Create a release tag
6. Open JitPack and lookup your repository
7. Now you can get your library from JitPack!

## Other Git Hosts
JitPack also works with other Git hosting providers. The only difference is the groupId of your artifacts:
- BitBucket: org.bitbucket.Username:Repo:Tag
- GitLab: com.gitlab.Username:Repo:Tag

## Private Repos
Currently seems only github and bitbucket are works.(2017/03/06)

## References
- http://www.jianshu.com/p/434911cd8732
- https://jitpack.io/docs/
