# Future Cherry Noted Client

## Client 需求

- 快捷键操作
  - 快速保存(CTRL + C)
  - 快捷搜索栏打开(CTRL + F)
- 文章模糊搜索功能(支持对于文章的快速搜索和定位)
- 文件管理(支持一个文件列表管理已经打开的.md文件)
- 注册表功能
  - 鼠标右键注册(注册右键快捷方式使用Cherry Noted 打开*.md)
  - 打开方式(注册以*.md结尾的markdown文件打开方式为Cherry Noted)
  - logo替换(注册以*.md结尾的markdown文件logo更改Cherry logo)
- 支持用户配置图床
  - 支持配置上传文件选项(文件以本地预览 还是 上传到服务器回调预览)
- 支持发布到其他平台(获取登录秘钥和发布文章地址)
  - 知乎
  - 简书
  - 腾讯云社区
- 加密功能
  - 配置加密选项(使用双向的加密算法保证文件只能用客户端读取)
- 定制化客户端主题(改变客户端本身的主题样式)

  ---

## 因适配Client 可能导致的 Cherry Markdown 的优化

- 对于文件的优化
  - `draw` 是否保存历史编辑记录(以保持通用*.md标准)
