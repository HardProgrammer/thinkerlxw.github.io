# thinkerlxw.github.io
个人网站评论系统

# 添加以下插件
### 1. hexo-generator-searchdb 用于搜索
cnpm install hexo-generator-searchdb --save

### 2. hexo-generate-feed 用于生成RSS订阅
cnpm install hexo-generator-feed --save

### 3. 字数统计
cnpm i --save hexo-wordcount

### 4. 相关插件(可选)
hexo-generator-index-pin-top 用于文章置顶

hexo-blog-encrypt 用于文章加密

hexo-tag-aplayer 用于播放音乐

hexo-tag-dplayer 用于播放视频

hexo-helper-live2d 二次元看板娘

# 步骤
### 创建新页面
$ hexo new "My New Post"

### 生成
$ hexo generate

### 执行
$ hexo server
执行成功后输入 localhost:4000 就可以打开网站

### 上传
$ hexo deploy

