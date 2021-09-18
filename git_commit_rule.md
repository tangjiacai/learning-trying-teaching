# git代码提交规范

### Commit message格式  

```
<type>(<scope>: subject)
//注意冒号后面有空格
//如 feat(miniprogram): 增加小程序模板相关功能
```

**scope选填**表示commmit的作用范围，如数据层、视图层、也可以是目录名称  

**subject必填**用于对commit进行简短的描述  

**type必填**表示提交的类型，值有以下几种：

- feat - 新功能feature
- fix - 修复bug
- docs - 文档注释
- style - 代码格式（不影响代码运行的变动）
- refactor - 重构、优化（既不增加新功能，也不修复bug）
- perf - 性能优化
- test - 增加测试
- chore - 构建过程或辅助工具的变动
- revert - 回退
- build - 打包