baidu_pcs_cli
=============

百度个人云存储API命令行工具

    使用方法: baidu_pcs 命令 [选项]
    
    命令列表:
    
    info      查看云盘信息
    
    ls        列出远程文件或目录
              选项:
                -l 显示详细信息
                -r 递归子目录
    
    upload   [选项] [本地路径] [远程路径] 上传文件或目录
              选项:
                覆盖策略
                默认:略过已存在同名远程文件
                -o 覆盖远程同名文件
                -n 如果存在同名文件，创建以日期结尾的新文件
    
                -l 跟随软链
    
    download [选项] [远程路径] [本地路径] 下载文件或目录
              选项:
                -o 覆盖本地同名文件
                -n 如果存在同名文件，创建以日期结尾的新文件
    cp       [选项] [远程路径] [目的远程路径] 复制远程文件或目录
    mv       [选项] [远程路径] [目的远程路径] 移动远程文件或目录
    rm       [选项] [远程路径] 删除远程文件或目录
