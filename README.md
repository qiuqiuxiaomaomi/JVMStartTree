# JVMStartTree
JVM启动流程技术研究

![](https://i.imgur.com/S40PE2u.png)

<pre>
步骤：

      1：创建JVM装载环境和配置
      2：装载JVM.dll
      3: 初始化JVM.dll并挂接到JNIENV实例
      5：调用JNIEnv实例装载并处理class类。
</pre>