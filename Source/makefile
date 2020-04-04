###################################################
#
# Makefile for pbtomake
# Creator [PBTOMAKE]
# Created: [Fri Jun 10 11:19:39 2005]
#
###################################################

#
# Macros
#

CC = /usr/bin/cc
CC_OPTIONS = 

#
# INCLUDE directories for pbtomake
#

INCLUDE = 


#
# Build pbtomake
#

pbtomake : \
		CMaker.o\
		cutil.o\
		main.o\
		CpbxLexFile.o\
		CBufFile.o\
		CSymbol.o\
		CLexFile.o\
		CTokFile.o

	$(CC) $(LNK_OPTIONS) \
		CMaker.o\
		cutil.o\
		main.o\
		CpbxLexFile.o\
		CBufFile.o\
		CSymbol.o\
		CLexFile.o\
		CTokFile.o\
		-o pbtomake

#
# Build the parts of pbtomake
#


# Item # 1 -- CMaker --
CMaker.o : CMaker.cp
	$(CC) $(CC_OPTIONS) CMaker.cp -c $(INCLUDE) -o CMaker.o


# Item # 2 -- cutil --
cutil.o : cutil.cp
	$(CC) $(CC_OPTIONS) cutil.cp -c $(INCLUDE) -o cutil.o


# Item # 3 -- main --
main.o : main.cp
	$(CC) $(CC_OPTIONS) main.cp -c $(INCLUDE) -o main.o


# Item # 4 -- CpbxLexFile --
CpbxLexFile.o : CpbxLexFile.cp
	$(CC) $(CC_OPTIONS) CpbxLexFile.cp -c $(INCLUDE) -o CpbxLexFile.o


# Item # 5 -- CBufFile --
CBufFile.o : CBufFile.cp
	$(CC) $(CC_OPTIONS) CBufFile.cp -c $(INCLUDE) -o CBufFile.o


# Item # 6 -- CSymbol --
CSymbol.o : CSymbol.cp
	$(CC) $(CC_OPTIONS) CSymbol.cp -c $(INCLUDE) -o CSymbol.o


# Item # 7 -- CLexFile --
CLexFile.o : CLexFile.cp
	$(CC) $(CC_OPTIONS) CLexFile.cp -c $(INCLUDE) -o CLexFile.o


# Item # 8 -- CTokFile --
CTokFile.o : CTokFile.cp
	$(CC) $(CC_OPTIONS) CTokFile.cp -c $(INCLUDE) -o CTokFile.o


##### END RUN ####
