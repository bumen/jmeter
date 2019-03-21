## idea中安装jmeter

1. ren eclipse.project .project
  + 将eclipse.project 重命名为.project
2. ren eclipse.classpath .classpath
  + 将eclipse.classpath 重命名为 .classpath

3. 作为module，导入eclipse项目
4. 打开右边ant build
  + 加入jmeter/build.xml
5. 双击download_jars
  + 会下载所依赖的jar包
6. 打开jmeter module配置
  
7. 将protocal设置为srouce dir

8. 配置依赖jar

9. 执行 ant install

10. 打开NewDriver.java