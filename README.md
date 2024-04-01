# 本地服务器更新脚本
# Qubic-Solutions local update script
# Linux( mobile )
# 作者: tiyo (Discord: tiyo)

# 需要搭建本地服务器，将rqiner-aarch64文件放置在服务器上
# Need to set up a local server and place the rqiner-aarch64 file on the server

# 移动端需要进入ubuntu后执行
# Mobile needs to enter ubuntu to execute

# 文件需要加可执行权限 chmod +x start
# The file needs to be executable chmod +x start

# 执行方式 ./start ， 自动获取本地服务器上的rqiner-aarch64文件并执行
# Execute ./start, automatically get the rqiner-aarch64 file on the local server and execute it

# 获取当前脚本的名称
# Get the name of the current script

# 脚本运行时按下Ctrl+C，关掉tail输出，但是rqiner-aarch64进程仍在后台运行
# Press Ctrl+C while the script is running to turn off the tail output, but the rqiner-aarch64 process is still running in the background

# 使用 ./start -kill 命令可以杀死rqiner-aarch64进程
# Use ./start -kill command to kill the rqiner-aarch64 process

# 移动端ubuntu没有系统服务功能，鉴于Qubic-Solutions作者将会在未来提供自动更新，所以此脚本暂时不提供定时功能
# Mobile ubuntu does not have system service function, in view of Qubic-Solutions author will provide automatic update in the future, so this script does not provide timing function temporarily
