1. 用户管理
    查询
    增加
        数据检查
            1. 用户名不能重复

            成功
                => 数据添加
                => 跳转到列表页面
            失败
                仍然显示新建页面
                需要回显错误信息以及用户提交时填写的数据
    删除
    修改
       1. 点击编辑页面 传递id =>
            打开修改页面 并填写原值
        2. 提交
            数据检查
            成功
            失败

2. web页面（挑战）
    curl上传文件 请求web服务器

    页面下拉框显示所有可以查询的文件内容
    选择文件点击查询显示当前文件

    IP 访问次数(访问次数最多的TOP10)
    状态码 分布(每隔状态码出现次数)