# Xcode-template-OpenGL

<b>该模板参考了 [huntto/Xcode-LearnOpenGL-Templates](https://github.com/huntto/Xcode-LearnOpenGL-Templates)，在此特别鸣谢</b>

## ·使用方法

1. 安装 GLEW, GLFW，下载并解压 GLAD

2. 打开 <b>Xcode -> Preferences… -> Locations -> Custom Paths</b> 进行如下配置

| Name | Display Name | Path |
| ---- | ------------ | ---- |
| GLAD_PATH | 随意 | GLAD路径 |
| GLFW_PATH | 随意 | GLFW路径 (在 /usr/local/Cellar/ 下) |
| GLEW_PATH | 随意 | GLEW路径 (在 /usr/local/Cellar/ 下) |

3. 在终端中输入 ```git clone https://github.com/Magic-Xin/Xcode-template-OpenGL.git ~/Library/Developer/Xcode/Templates/MacOS/OpenGLTemplate```

4. 打开 <b>Xcode -> Create a new Xcode project -> MacOS</b>，在下方寻找 <b>OpenGL Project</b> 即可使用
