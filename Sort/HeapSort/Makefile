.SUFFIXES : .cc .o

TOPDIR := $(shell pwd)

INC := -I$(TOPDIR)/include
CXX := g++
CXXFLAGS := -g $(INC)

OBJS := main.o
SRCS := main.cpp

TARGET := main

all: $(TARGET)

$(TARGET) : $(OBJS)
	$(CXX) -o $(TARGET) $(OBJS)

clean:
	rm -rf $(OBJS) $(TARGET) core

debug:
	@echo $(TOPDIR)
