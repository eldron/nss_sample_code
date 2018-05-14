NSS_INCLUDE_PATH=/home/work/Documents/dist/public/nss
NSPR_INCLUDE_PATH=/home/work/Documents/dist/Debug/include/nspr
NSPR_LIBRARY_PATH=/home/work/Documents/dist/Debug/lib
LINK_FLAGS=-lfreebl3 -lnssckbi -lplc4 -lsqlite3 -lfreeblpriv3 -lnssdbm3 -lplds4 -lssl3 -lnspr4 -lnsssysinit -lsmime3 -lnss3 -lnssutil3 -lsoftokn3

all:sample1 sample2 sample3 sample4 sample5 sample6
	echo 'hello'

sample1:
	g++ sample1.cpp -fpermissive -I$(NSS_INCLUDE_PATH) -I$(NSPR_INCLUDE_PATH) -L$(NSPR_LIBRARY_PATH) $(LINK_FLAGS) -o sample1

sample2:
	echo $(LINK_FLAGS)
	g++ sample2.cpp -fpermissive -I$(NSS_INCLUDE_PATH) -I$(NSPR_INCLUDE_PATH) -L$(NSPR_LIBRARY_PATH) $(LINK_FLAGS) -o sample2

sample3:
	g++ sample3.cpp -fpermissive -I$(NSS_INCLUDE_PATH) -I$(NSPR_INCLUDE_PATH) -L$(NSPR_LIBRARY_PATH) $(LINK_FLAGS) -o sample3

sample4:
	g++ sample4.cpp -fpermissive -I$(NSS_INCLUDE_PATH) -I$(NSPR_INCLUDE_PATH) -L$(NSPR_LIBRARY_PATH) $(LINK_FLAGS) -o sample4
		
sample5:
	g++ sample5.cpp -fpermissive -I$(NSS_INCLUDE_PATH) -I$(NSPR_INCLUDE_PATH) -L$(NSPR_LIBRARY_PATH) $(LINK_FLAGS) -o sample5

sample6:
	g++ sample6.cpp -fpermissive -I$(NSS_INCLUDE_PATH) -I$(NSPR_INCLUDE_PATH) -L$(NSPR_LIBRARY_PATH) $(LINK_FLAGS) -o sample6

