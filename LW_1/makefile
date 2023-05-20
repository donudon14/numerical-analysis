CC=g++
CFLAGS=-std=c++14 -Werror -pedantic -Wall -Wextra -O3
LDFLAGS=
LIBS=-lm
SOURCES=LW_1_1.cpp LW_1_2.cpp LW_1_3.cpp LW_1_4.cpp LW_1_5.cpp
EXECUTABLE=$(SOURCES:%.cpp=%)

all: $(EXECUTABLE)

$(EXECUTABLE): %: %.cpp
	$(CC) $(CFLAGS) $< -o $@

clean:
	rm -frd $(EXECUTABLE)


