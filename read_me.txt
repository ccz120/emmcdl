1）在~/.bash_aliases中自定义命令 -- emm53（可定义为任意名称）：

alias emm53='sudo emmcdl -f prog_emmc_firehose_8953_ddr.mbn -x rawprogram_unsparse.xml && sudo emmcdl -f prog_emmc_firehose_8953_ddr.mbn -x patch0.xml  && sudo emmcdl -f prog_emmc_firehose_8953_ddr.mbn -r'

2）终端 进入下载镜像的copy目录下，及bin_for_dl目录下：
在中断下运行 emm53


