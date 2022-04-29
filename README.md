## Why

工作之后时间精力有限，所以必须要明确学习目的，搞清楚为什么要花时间来学习三维开发相关知识。

首先，可以快速看一下 three.js 上的各种 demo，了解在 web 上可以做出多么惊艳的效果，而且如此轻松的所见即所得的进行调试（我相信这也是我们选择做前端的一个重要原因），提升学习兴趣：[https://threejs.org/examples](https://threejs.org/examples/#webgl_animation_cloth)

另外，我们做业务用的 Tiny 虽然是 2D 互动引擎，但是底层其实跑的还是 WebGL，所以了解相关知识，可以看懂底层源码，从而理解框架设计意图，写出更好的代码，解决更难的问题：<http://tinyjs.alibaba.net/>

## 快速入门

在这个阶段，需要以最快的速度使用最基础的 WebGL API 绘制一个最简单的图形，建立一个整体认识。

首先，吐血推荐 MDN 的教程，非常简单明了，一步一步跟着去做即可： <https://developer.mozilla.org/zh-CN/docs/Web/API/WebGL_API/Tutorial/Getting_started_with_WebGL>

如果想学习更多例子，可以看这个网站，非常生动，讲了很多基础概念：<https://webglfundamentals.org/webgl/lessons/zh_cn/>

尤其是这个演示，使用单步调试的方式展示了每个 API 调用之后 GPU 的状态，方便理解 WebGL 的状态机本质：<https://webglfundamentals.org/webgl/lessons/resources/webgl-state-diagram.html>

## 补充图形学基础

首推闫令琪老师的视频课程：<https://www.bilibili.com/video/BV1X7411F744?from=search&seid=4046304325389272905&spm_id_from=333.337.0.0>

快速上手的话，重点看第一部分（前 9 节课），非常清晰地讲解了光栅化和传统光照模型。

几何和动画部分有时间的话，也可以学习一下，形成初步印象。

光线追踪部分是闫老师的研究领域，讲的非常精彩，如果未来想在渲染方面深入的话，可以结合 Games 202 继续学习，但是对入门来说就不是太必要了~

## 看工作相关源码

在这一步就没有那么多教程和文档了，需要自己用心去看代码，结合业务进行研究。

如果是为了快速解决工作中的问题，看 Pixi.js 的源码，推荐看最新的 6.x，架构很漂亮，代码很清晰：<https://pixijs.io/>

理解基本原理之后，工作中遇到问题就看 Tiny 源码了：<http://code.alipay.com/tiny/tiny>

如果想实现各种 3D 效果，看 Three.js 的 demo 和源码

到这一步，可以说已经能够完全满足日常业务开发，遇到问题也能深入到源码找到答案了。

## Next

入门之后，还有更广阔的世界等着你~

计算机图形学是一个非常广阔的领域，有非常多的文档和教程，这里再推荐一个 ：<https://learnopengl-cn.github.io/>，很多概念讲的很好，跟 webglfundamentals 互相补充，美中不足的是用 C++ 实现~

学习技术美术相关知识，了解工业界的生产流程，我目前在看这个：<https://space.bilibili.com/7398208/video>

然后就 follow your heart，学 Unity，Blender，Houdini。。。实现各种效果，解决各种问题，准备花一万小时吧少年~
