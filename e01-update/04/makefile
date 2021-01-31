# t 依赖 p，且有匹配 p 的规则, 且 p 不是伪目标
# 
#             有文件 p        没有文件 p
# p 执行      比较p和t        t 需要执行
# p 不执行    比较p和t        -（没有文件p，p一定会执行）


t: p
	touch t

p:
	@echo execute recipe of p

clean:
	rm -vf t p

.PHONY: clean


