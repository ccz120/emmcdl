#### emmcdl 的用法

1）把目录下的 emmcdl 拷贝到 /usr/bin/目录下，并且修改权限为 777 ，例如chmod 777 /usr/bin/emmcdl


2）在~/.bash_aliases中自定义命令 -- emm53（可定义为任意名称）：

alias emm53='sudo emmcdl -f prog_emmc_firehose_8953_ddr.mbn -x rawprogram_unsparse.xml && sudo emmcdl -f prog_emmc_firehose_8953_ddr.mbn -x patch0.xml  && sudo emmcdl -f prog_emmc_firehose_8953_ddr.mbn -r'

3）终端进入高通大版本编译完成的镜像目录下，即 bin_for_dl 目录下：
在终端下运行 emm53


