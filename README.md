3.2良好的commit
·commitizen是一个格式化commit message的工具
·validate-commit-msg用于检查项目的Commit message 是否符合格式
·conventional-changelog-ci可以贝it metadas生成变更日志

·日志提交友好的类型选择提示使用commitize工具
·不符合要求格式的日志拒绝提交的保障机制
·需要使用validate-commit-msg 工具
·统一changelog文档信息生成
·使用conventional-changelog-ci工具

npm i commitizen validate-commit-msg conventional-changelog-cli -D
commitizen init cz-conventional-changelog --save --save-exact

npm i husky validate-commit-msg --save-dev
