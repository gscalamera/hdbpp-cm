NAME_SRV = hdb++cm-srv

include ../Make-hdb++.in

CXXFLAGS = -DRELEASE='"N$Name:  $ "' -I$(LIBHDB_INC) -D_USE_FERMI_DB_RW
LDFLAGS = -lhdb++ -l$(LIBHDBIMPL) -l$(SQLIMPL) -L$(LIBHDB_LIB) -L$(LIBHDBIMPL_LIB) -L$(SQLIMPL_LIB)

include ../Make-8.1.2.c.in
