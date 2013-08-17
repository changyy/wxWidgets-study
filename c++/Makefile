CXX=clang++ -std=c++11 -stdlib=libc++
CXXFLAGS=`wx-config --cxxflags`
LDFLAGS=`wx-config --libs`

all:
	$(CXX) $(CXXFLAGS) $(LDFLAGS) main.cpp -o helloworld
clean:
	rm helloworld
