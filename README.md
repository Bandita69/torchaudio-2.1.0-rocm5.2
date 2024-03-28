# torchaudio-2.1.0-rocm5.2 

It works with the https://repo.radeon.com/rocm/manylinux/.private-9bd8754a636553e1d1ce3e107bf18c00/20231018/

Built with python 3.9.5 on Ubuntu 22.10 for XTTS v2 to work with my RX5700XT

Extra: when i used it with xtts, i noticed the first generation is very slow. But it speeds up eventualy.

Im not the only one with the issue, apperently its a the same with Stable Diffusion. 

from https://www.bilibili.com/read/cv19172736/ 
" 
WebUI内首次生成图片需要等待一分钟到几分钟（主要取决于CPU性能），同时命令行会有类似这样的提示。

    MIOpen(HIP): Warning [SQLiteBase] Missing system database file: gfx1030_40.kdb Performance may degrade. Please follow instructions to install: https://github.com/ROCmSoftwarePlatform/MIOpen#installing-miopen-kernels-package

只是偶尔运行的话没必要花时间根据链接内步骤解决，那样花费的时间比等待时间还长。

此后运行每张图只需要数秒钟（主要取决于GPU性能）。"

----

"
The first generation of images within WebUI requires a wait of one minute to several minutes (mainly depending on CPU performance) while the command line is prompted with a message similar to this one.

    MIOpen(HIP): Warning [SQLiteBase] Missing system database file: gfx1030_40.kdb Performance may degrade. Please follow instructions to install. https://github.com/ROCmSoftwarePlatform/MIOpen#installing-miopen-kernels-package

There is no need to take the time to follow the steps in the link if you only run it occasionally, it will take longer than the wait.

After that it takes only a few seconds to run each graph (depending on GPU performance).

Translated with DeepL.com (free version)"
