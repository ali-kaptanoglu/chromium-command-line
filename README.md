# chromium-command-line
chromium-command-line

>>--user-data-dir="Data" 

>>--user-data-dir="..\Data" 

>>--disk-cache-dir="Cache"

--no-first-run //不显示首次运行向导
--force-local-ntp //强制本地NTP
--disable-logging //禁用记录日志
--disable-breakpad //禁用崩溃报告
--no-report-upload //不发送匿名数据
--*-*-url="0.0.0.0" //强制指向无效地址
--bwsi //开启访客模式 (无扩展无登录同步)
--enable-ftp //允许ftp (88版本后不支持)
--disable-notifications //禁用网页通知
--make-default-browser //设置默认浏览器
--enable-leak-detection //加载网页检测泄露
--disable-component-update //禁止组件更新
--disable-background-networking //禁用后台联网检查更新

# 追加参数优化启动Chrome快捷方式示例：
chrome.exe --user-data-dir=Data --disk-cache-dir=Cache --no-first-run --enable-ftp --enable-gpu-rasterization --enable-leak-detection --disable-component-update --disable-crash-reporter --disable-breakpad --disable-background-networking --disable-logging --disable-notifications --no-report-upload --print-to-pdf-no-header --save-page-as-mhtml --site-per-process --crash-server-url="0.0.0.0" --force-update-remote-url="0.0.0.0" --google-url="0.0.0.0" --trace-upload-url="0.0.0.0"
