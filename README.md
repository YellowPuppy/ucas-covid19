

Github提供了一个secret功能，用于存储密钥等敏感信息，请按照以下步骤操作。

使用步骤:
- 点击右上角 `star` :)
- 克隆这个仓库到你名下
- fork的仓库默认禁用了`workflow`，需要手动打开：点击 `actions`选项卡，点击`I understand my workflows, go ahead and run them`。
- 在仓库设置里面, 设置 secrets 如下
  - `SEP_USER_NAME`: 你的 SEP 用户名(邮箱)
  - `SEP_PASSWD`: 你的 SEP 密码
  
- 测试actions是否可以正常工作：编辑本项目内任意文件，推荐修改`README.md`，比如添加一个空行，并提交以触发action运行，提交后的一分钟左右可以在action选项卡中看到运行记录


