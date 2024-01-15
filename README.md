# 从零开始学习的github action生活

## todo

- [ ] 学习github action工作原理
- [ ] 学习YAML语法以及各个字段配置项
- [ ] 把云服务器上的cron定时任务放到github action
- [ ] 部署一个频道发送


## github action lifecircle

1. **Triggier by Event**
   - pr or issue or push
   - schedule cron定时
   - 
2. Define workflow by users' **yaml**
   - on 指定trigger
   - jobs
   - runs-on 指定 虚拟机
   - steps
3. Run Job
4. Execute steps
   job分为很多个step
5. actions
   - action 是 GitHub Actions 平台的自定义应用程序，用于执行复杂但经常重复的任务。使用操作来帮助减少在工作流文件中编写的重复代码量
6. host runners
7. error handle
8. log
9. notification