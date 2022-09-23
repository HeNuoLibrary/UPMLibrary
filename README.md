## 插件库 简介

这是一个Unity Package Manager 的插件库文件

1. **添加插件** 
创建一个插件分支git checkout -b upm

2. **添加Package.json**

{
  "name": "com.henuo.upm",
  "version": "1.0.0",
  "displayName": "upm",
  "description": "upm 插件",
  "repository": {
      "type": "git",
      "url": "https://github.com/HeNuoScott/UPMLibrary.git"
  },
  "unity": "2021.3",
  "documentationUrl": "https://github.com/qiankanglai/LoopScrollRect/blob/master/README.md",
  "licensesUrl": "https://github.com/qiankanglai/LoopScrollRect/blob/master/LICENSE.md",
  "dependencies": {
    "com.unity.ugui": "1.0.0"
  },
  "keywords": [
    "UGUI"
  ],
  "author": {
    "name": "Kanglai Qian",
    "email": "qiankanglai@gmail.com",
    "url": "https://qiankanglai.me"
  },
  "samples": [
    {
      "displayName": "Demo",
      "description": "Contains several Loop Scroll demo",
      "path": "Samples~/Demo"
    }
  ]
}

3. **添加标签** 
git tag 1.0.0 upm
git push origin upm --tags

4. **使用** 
unity dependencies 添加 "com.henuo.upm": "https://github.com/HeNuoScott/UPMLibrary.git#1.0.0"

