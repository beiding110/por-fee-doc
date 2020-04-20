## 方法论（持续集成）

### 选用技术

[GitLab-ci](https://docs.gitlab.com/ee/ci/README.html)

### 说明

代码进行提交后，会自动激活到 `分支对应` 的服务，进行预先设定好的功能（单元测试、编译、部署等）；

保证 `生产环境` 与 `对应分支` 内代码一致；降低人工成本；自动完成基础单元测试；

具体代码可参考 [ci-test](http://124.239.148.174:8800/yzh-front-test/ci-test) ;

![ci-flow](../_media/deploy/ci-flow.png)

![ci-console](../_media/deploy/ci-console.png)

![ci-tag](../_media/deploy/ci-tag.png)
