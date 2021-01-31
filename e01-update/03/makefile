# t 依赖 p，且有匹配 p 的规则, 且 p 是伪目标
# 无条件执行 p，接着执行 t

t: p
	touch t
p:
	@echo execute recipe of p

.PHONY: p clean

clean:
	rm -vf t p
