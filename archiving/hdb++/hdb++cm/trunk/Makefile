NAME_SRV = hdb++cm-srv

include ../../Make-hdb++.in

CXXFLAGS += -DRELEASE='"$HeadURL$ "' -I$(LIBHDB_INC)
LDFLAGS = -lhdb++ -l$(LIBHDBIMPL) -L$(LIBHDB_LIB) -L$(LIBHDBIMPL_LIB) $(DBIMPL_LIB)

include ../../Make-8.1.2.c.in
