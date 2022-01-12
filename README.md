# SSR一键搭建
下载ssr.sh，执行
```
chmod 777 ssr.sh
sudo sh ssr.sh
```
接下来根据提示操作即可。

- 查看ssr运行状态/配置
`sh ssr.sh info`

- 更改密码、端口、混淆参数的最简单方法：重新运行一次安装脚本；

- SSR管理命令：
启动:`systemctl start shadowsocksR`
停止:`systemctl stop shadowsocksR`
重启:`systemctl restart shadowsocksR`

- 卸载SSR
`sh ssr.sh uninstall`