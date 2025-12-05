.PHONY: help
help:
	@echo '                                                                          '
	@echo 'Makefile                                                                  '
	@echo '                                                                          '
	@echo 'Usage:                                                                    '
	@echo '   make help                           show help                          '
	@echo '                                                                          '
	@echo '   make build                          build                              '
	@echo '   make run                            run                              '
	@echo '                                                                          '
	@echo '                                                                          '

.PHONY: build
build:
	rustc main.rs
	gcc main.c


.PHONY: run
run: build
	./main
	./a.out