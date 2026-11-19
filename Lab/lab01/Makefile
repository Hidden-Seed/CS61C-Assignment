CC       = gcc
CFLAGS   = -g -Wall -Wextra
WORK_DIR = $(shell pwd)

BINS = eccentric hello int_hello segfault_ex no_segfault_ex test_ll_cycle

$(BINS): %: %.c
	$(CC) $(CFLAGS) -o $@ $^

.PHONY: clean
clean:
	rm -f $(BINS)
