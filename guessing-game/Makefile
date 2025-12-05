.PHONY: help
help:
	@echo '                                                                          '
	@echo 'Makefile                                                                  '
	@echo '                                                                          '
	@echo 'Usage:                                                                    '
	@echo '   make help                           show help                          '
	@echo '                                                                          '
	@echo '   make build                          build                              '
	@echo '   make run                            run                                '
	@echo '   make check                          check                              ' 
	@echo '                                                                          '
	@echo '                                                                          '

.PHONY: build
build:
	cargo build
	cargo build --release
.PHONY: run
run:
	cargo run

.PHONY: check
check:
	cargo check
