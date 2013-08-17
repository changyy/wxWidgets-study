CXX=clang++ -std=c++11 -stdlib=libc++
CXXFLAGS=`wx-config --cxxflags`
LDFLAGS=`wx-config --libs`

helloworld:
	$(CXX) $(CXXFLAGS) $(LDFLAGS) main.cpp -o helloworld

run: helloworld
	./helloworld

clean:
	rm helloworld
