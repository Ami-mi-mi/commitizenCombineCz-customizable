### 安装commitizen
- npm install -g commitizen

### 初始化cz-conventional-changelog
- commitizen init cz-conventional-changelog --save --save-exact

### git cz 代替 git commit
- git cz

### 安装cz-customizable
- npm install cz-customizable --save-dev

### package.json commitizen path修改
- "commitizen": {
-    "path": "node_modules/cz-customizable"
-  }

### 根目录下创建 .cz-config.js
- 通过module.exports = { }配置types, scopes,messges,skipQuestionsubjectLimit

### 详细配置
- https://juejin.cn/post/7094919796373848071
