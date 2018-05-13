# Rules for the test code (use `make check` to execute)
TESTS = MoneyApp
check_PROGRAMS = $(TESTS)
MoneyApp_SOURCES = src/Money.h src/MoneyTest.h src/MoneyTest.cpp src/MoneyApp.cpp
MoneyApp_CXXFLAGS = $(CPPUNIT_CFLAGS)
MoneyApp_LDADD = $(CPPUNIT_LIBS) -ldl
