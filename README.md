## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Fri Sep 13 06:46:04 UTC 2024
- Auto Sign-in run successful on Sat Sep 14 00:42:53 UTC 2024
- Auto Sign-in run successful on Sun Sep 15 00:49:58 UTC 2024
- Auto Sign-in run successful on Mon Sep 16 00:46:55 UTC 2024
- Auto Sign-in run successful on Tue Sep 17 00:36:34 UTC 2024
- Auto Sign-in run successful on Wed Sep 18 00:43:25 UTC 2024
- Auto Sign-in run successful on Thu Sep 19 00:44:07 UTC 2024
- Auto Sign-in run successful on Fri Sep 20 00:44:01 UTC 2024
- Auto Sign-in run successful on Sat Sep 21 00:43:29 UTC 2024
- Auto Sign-in run successful on Sun Sep 22 00:50:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 23 00:46:06 UTC 2024
- Auto Sign-in run successful on Tue Sep 24 00:45:36 UTC 2024
- Auto Sign-in run successful on Wed Sep 25 00:46:27 UTC 2024
- Auto Sign-in run successful on Thu Sep 26 00:45:11 UTC 2024
- Auto Sign-in run successful on Fri Sep 27 00:45:37 UTC 2024
- Auto Sign-in run successful on Sat Sep 28 00:45:00 UTC 2024
- Auto Sign-in run successful on Sun Sep 29 00:51:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 30 00:48:00 UTC 2024
- Auto Sign-in run successful on Tue Oct  1 00:51:42 UTC 2024
- Auto Sign-in run successful on Wed Oct  2 00:45:32 UTC 2024
- Auto Sign-in run successful on Thu Oct  3 00:45:38 UTC 2024
- Auto Sign-in run successful on Fri Oct  4 00:45:47 UTC 2024
- Auto Sign-in run successful on Sat Oct  5 00:44:59 UTC 2024
- Auto Sign-in run successful on Sun Oct  6 00:50:47 UTC 2024
- Auto Sign-in run successful on Mon Oct  7 00:48:17 UTC 2024
- Auto Sign-in run successful on Tue Oct  8 00:45:24 UTC 2024
- Auto Sign-in run successful on Wed Oct  9 00:45:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 10 00:45:23 UTC 2024
- Auto Sign-in run successful on Fri Oct 11 00:45:27 UTC 2024
- Auto Sign-in run successful on Fri Oct 11 15:19:02 UTC 2024
- Auto Sign-in run successful on Fri Oct 11 15:19:26 UTC 2024
- Auto Sign-in run successful on Sat Oct 12 02:40:32 UTC 2024
- Auto Sign-in run successful on Sun Oct 13 02:59:47 UTC 2024
- Auto Sign-in run successful on Mon Oct 14 03:00:10 UTC 2024
- Auto Sign-in run successful on Tue Oct 15 02:57:05 UTC 2024
- Auto Sign-in run successful on Wed Oct 16 02:58:18 UTC 2024
- Auto Sign-in run successful on Thu Oct 17 02:55:18 UTC 2024
- Auto Sign-in run successful on Fri Oct 18 02:57:01 UTC 2024
- Auto Sign-in run successful on Sat Oct 19 02:52:13 UTC 2024
- Auto Sign-in run successful on Sun Oct 20 03:02:44 UTC 2024
- Auto Sign-in run successful on Mon Oct 21 03:00:48 UTC 2024
- Auto Sign-in run successful on Tue Oct 22 02:56:44 UTC 2024
- Auto Sign-in run successful on Wed Oct 23 02:55:00 UTC 2024
- Auto Sign-in run successful on Thu Oct 24 02:54:40 UTC 2024
- Auto Sign-in run successful on Fri Oct 25 02:58:20 UTC 2024
- Auto Sign-in run successful on Sat Oct 26 02:41:27 UTC 2024
- Auto Sign-in run successful on Sun Oct 27 03:01:31 UTC 2024
- Auto Sign-in run successful on Mon Oct 28 03:02:07 UTC 2024
- Auto Sign-in run successful on Tue Oct 29 02:58:09 UTC 2024
- Auto Sign-in run successful on Wed Oct 30 02:57:01 UTC 2024
- Auto Sign-in run successful on Thu Oct 31 02:58:29 UTC 2024
- Auto Sign-in run successful on Fri Nov  1 03:07:16 UTC 2024
- Auto Sign-in run successful on Sat Nov  2 02:51:52 UTC 2024
- Auto Sign-in run successful on Sun Nov  3 03:01:59 UTC 2024
- Auto Sign-in run successful on Mon Nov  4 03:01:18 UTC 2024
- Auto Sign-in run successful on Tue Nov  5 02:42:49 UTC 2024
- Auto Sign-in run successful on Wed Nov  6 02:41:14 UTC 2024
- Auto Sign-in run successful on Thu Nov  7 02:43:41 UTC 2024
- Auto Sign-in run successful on Fri Nov  8 02:52:25 UTC 2024
- Auto Sign-in run successful on Sat Nov  9 02:36:55 UTC 2024
- Auto Sign-in run successful on Sun Nov 10 02:55:52 UTC 2024
- Auto Sign-in run successful on Mon Nov 11 02:54:12 UTC 2024
- Auto Sign-in run successful on Tue Nov 12 01:23:21 UTC 2024
- Auto Sign-in run successful on Wed Nov 13 01:25:07 UTC 2024
- Auto Sign-in run successful on Thu Nov 14 01:25:13 UTC 2024
- Auto Sign-in run successful on Fri Nov 15 01:37:49 UTC 2024
- Auto Sign-in run successful on Sat Nov 16 01:35:36 UTC 2024
- Auto Sign-in run successful on Sun Nov 17 01:41:36 UTC 2024
- Auto Sign-in run successful on Mon Nov 18 01:42:20 UTC 2024
- Auto Sign-in run successful on Tue Nov 19 01:37:59 UTC 2024
- Auto Sign-in run successful on Wed Nov 20 01:37:04 UTC 2024
- Auto Sign-in run successful on Thu Nov 21 01:36:43 UTC 2024
- Auto Sign-in run successful on Fri Nov 22 01:37:49 UTC 2024
- Auto Sign-in run successful on Sat Nov 23 01:26:55 UTC 2024
- Auto Sign-in run successful on Sun Nov 24 01:43:05 UTC 2024
- Auto Sign-in run successful on Mon Nov 25 01:39:29 UTC 2024
- Auto Sign-in run successful on Tue Nov 26 01:38:25 UTC 2024
- Auto Sign-in run successful on Wed Nov 27 01:39:49 UTC 2024
- Auto Sign-in run successful on Thu Nov 28 01:39:25 UTC 2024
- Auto Sign-in run successful on Fri Nov 29 01:39:17 UTC 2024
- Auto Sign-in run successful on Sat Nov 30 01:36:47 UTC 2024
- Auto Sign-in run successful on Sun Dec  1 01:53:15 UTC 2024
- Auto Sign-in run successful on Mon Dec  2 01:42:49 UTC 2024
- Auto Sign-in run successful on Tue Dec  3 01:41:19 UTC 2024
- Auto Sign-in run successful on Wed Dec  4 01:41:50 UTC 2024
- Auto Sign-in run successful on Thu Dec  5 01:41:25 UTC 2024
- Auto Sign-in run successful on Fri Dec  6 01:40:26 UTC 2024
- Auto Sign-in run successful on Sat Dec  7 01:39:27 UTC 2024
- Auto Sign-in run successful on Sun Dec  8 01:47:15 UTC 2024
- Auto Sign-in run successful on Mon Dec  9 01:44:27 UTC 2024
- Auto Sign-in run successful on Tue Dec 10 01:42:48 UTC 2024
- Auto Sign-in run successful on Wed Dec 11 01:41:37 UTC 2024
- Auto Sign-in run successful on Thu Dec 12 01:41:11 UTC 2024
- Auto Sign-in run successful on Fri Dec 13 01:42:20 UTC 2024
- Auto Sign-in run successful on Sat Dec 14 01:37:55 UTC 2024
- Auto Sign-in run successful on Sun Dec 15 01:47:07 UTC 2024
- Auto Sign-in run successful on Mon Dec 16 01:44:29 UTC 2024
- Auto Sign-in run successful on Tue Dec 17 01:40:55 UTC 2024
