include $(SYSTEMC)/examples/build-unix/Makefile.config

SYSTEMC_HOME = $(SYSTEMC)
TARGET_ARCH = linux64
FLAGS_STRICT += -Wno-variadic-macros

PROJECT := simple_fifo
SRCS := $(wildcard *.cpp)
OBJS := $(SRCS:.cpp=.o)

include $(SYSTEMC)/examples/build-unix/Makefile.rules