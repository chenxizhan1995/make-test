# 用 t，p，d 构造最后一种场景：
# 3. 有文件 p，p 需要执行 -> t是否需要执行，看 p 和 t 的新旧关系。
t: p
	touch t
p: d
	@echo execute recipe in p

clean: 
	rm -vf p t

.PHONY: clean
