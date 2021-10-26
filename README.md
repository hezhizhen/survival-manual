# 疑难杂症

1. 通过 terminal 打开 MacVim 后，terminal 会显示 `2021-10-26 16:34:29.860 MacVim[71204:6730155] TSM AdjustCapsLockLEDForKeyTransitionHandling - _ISSetPhysicalKeyboardCapsLockLED Inhibit` 信息
	1. 版本信息
		1. macOS: 11.6
		2. iTerm2: 3.4.10
		3. MacVim: 8.2.2681 (171)
	2. 解决方法
		1. 在系统设置的输入法中取消「通过 Capslock 切换输入法」的勾选
	3. 参考内容
		1. [How do I solve AdjustCapsLockLEDForKeyTransitionHandling?](https://stackoverflow.com/questions/67613071/how-do-i-solve-adjustcapslockledforkeytransitionhandling)
