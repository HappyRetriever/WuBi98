# WuBi98
Debian下可用的五笔98输入法，SCIM码表。
首先下载这里的码表，然后解压并执行如下命令：
sudo scim-make-table wubi98-scim.txt -b -o /usr/share/scim/tables/wb98-scim.bin
重启后选择五笔98即可使用。
如果需要使用动态词频，可调整AUTO_ADJUST = FALSE为TRUE，如果需要2、3码无重码时直接上屏，请调整AUTO_COMMIT = FALSE为TRUE。
