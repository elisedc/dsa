target = hw2_4
CFLAGS = -O3 -Wall
CPPFLAGS = -O3 -std=c++11 -Wall

all: $(target)

%: %.c
	gcc $(CFLAGS) $< -o $@

%: %.cpp
	g++ $(CPPFLAGS) $< -o $@

hw2_4: hw2_4.cpp DataStruct.cpp DataStruct.h
	g++ $(CPPFLAGS) hw2_4.cpp DataStruct.cpp -o $@

clean:
	rm -rf $(target)

run:
	./hw2_4
