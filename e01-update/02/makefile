#依赖文件 p，且没有匹配 p 的规则
# 若不存在文件p，则报错；
# 若存在p，则当p比t新的时候执行t，否则不执行t。

t: p
	touch t

.clean:
	rm -vf t

.PHONY: clean
