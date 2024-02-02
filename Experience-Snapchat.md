# Snapchat 工作经历

有关公司的介绍请参考：

- Snapchat [官网](https://www.snapchat.com/)
- Android App: [Google Play](https://play.google.com/store/apps/details?id=com.snapchat.android&hl=en_US&pli=1)
- Snap [Github Organization](https://github.com/Snapchat)

## Job Description

*2017/7 - 2024/2 (6 years and 7 months)*

- Department: Camera
- Position: Software Engineer
- Major area: Android Development - Camera

## Projects

**相机功能的开发、集成、优化和测试：**

- 参与Camera服务层重构的设计和实现，以提高相机启动和拍摄性能，并增强稳定性。重构后的框架更易适配不同的相机API，包括Camera1、Camera2、CameraX以及主流手机厂商的多个Camera SDK，具备开源能力。
- 负责与手机厂商深度合作的相机功能集成，基于Camera2 Extension、手机厂商SDK以及最新Android API，负责集成超级夜景模式，超广角模式，HDR，视频防抖等，丰富用户拍摄体验。
- 提出并实现了前后双摄像头同时打开的模式，完成了调研、demo并参与功能的开发与维护。主导相机帧处理和分发模块的重构，为多帧输入输出提供支持。
- 负责开发并推出人像背景虚化模式，通过使用JDK、内部Segmentation模块和OpenGL ES，实现了相机预览和拍摄的虚化模式，提升用户拍摄效果。

**图像处理与优化：**

- 提升相机拍摄质量，通过将拍摄方法从截图模式过渡到API拍摄模式、调整拍摄参数，实现相片后处理模块等。计算并上报拍摄的相片的评分，统计相片异常情况，从而不断优化拍摄体验。
- 负责图片的编解码，通过修改图片格式和使用libjpeg-turbo达到更高的压缩率，并且基于不同的网络环境配置不同的编码参数，平衡质量和性能，提升用户体验。

**Snapchat应用开发与优化：**

- 参与Snapchat主界面新功能的开发和现有功能的UI更新，包括相机页面上的手机相册功能、多张拍摄模式、倒计时、水平线、手势处理、按钮调整等，为用户提供了更丰富便捷的拍摄体验。
- 在整个Snapchat app重写期间，参与相机相关模块的更新，利用RxJava和Dagger框架提升了代码质量，加快了编译速度，并对应用的性能进行了优化，提高了用户的整体使用体验。
- 为各个手机厂商提供关于预装数据的统计的技术支持。

---

**Camera Integration, Optimization, and Testing**

- Designed and implemented the refactoring of the Camera service layer to enhance camera startup and creation performance and stability. The new framework is now more adaptable to various camera APIs, including Camera1, Camera2, CameraX, and multiple Camera SDKs from OEMs.
- Collaborated closely with OEMs to integrate advanced camera features such as Super Night Mode, Ultra Wide Angle Mode, HDR, etc., enriching the user’s shooting experience.
- Proposed and implemented the simultaneous front and rear Dual Camera Mode, as well as the refactoring of the camera frame processing and dispatcher module, providing support for multiple frame inputs and outputs.
- Responsible for the Portrait Mode, utilizing JDK, internal Segmentation module, and OpenGL ES to enhance the user’s capturing effect.

**Image Processing and Optimization**

- Enhanced photo quality by transitioning from screenshot to take picture API, adjusting parameters, and implementing post-processing modules to improve photo quality.
- Responsible for image encoding and decoding, achieving higher compression rates by modifying image formats and using libjpeg-turbo, and balancing quality and performance across different network environments to enhance user experience.

**Snapchat Application Development**

- Participated in the development of Snapchat new features and UI updates, including Mini Caousel, Batch Capture, etc., providing users with a richer and more convenient shooting experience.
- Optimized camera-related modules throughout the entire Snapchat app rewrite period using RxJava and Dagger frameworks, accelerating compilation speed, and improving user experience.
- Provided technical support for pre-installed on various smartphone manufacturers.
