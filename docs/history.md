# 历史版本
1.0.20
   - 新增前后端资源关联，前端上传qupload，后端下载qdownload

1.0.19

   - upload功能重命名为publish

   - 追加上传下载静态资源（从swfit）的功能：upload／download

1.0.18

   - 追加upload功能，可以本地直接上传一个私有包到中央缓存

   - 私有包可以使用alwasySync（相当于snapshot）功能，每次安装都会去中央缓存上最新代码

   - 优化了安装单个模块的流程

1.0.17

   - fix

1.0.16

   - 安装时使用指定npm路径，参数-n或者--npm

1.0.15

   - 增加快捷指令ncs

1.0.14

   - 添加安装前置的对npm-shrinkwrap.json和package.json一致性的校验

1.0.13

   - 添加本地开发与对yarn.lock的支持

1.0.12

   - 修复拷贝隐藏文件的问题

1.0.11

   - 修复强依赖平台的包的过滤
