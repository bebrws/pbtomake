###################################################
#
# Makefile for lsq
# Creator [PBTOMAKE]
# Created: [Mon Aug 22 16:24:03 2005]
#
###################################################

#
# Macros
#

CC = /usr/local/bin/g++-4.9
CC_OPTIONS = 
LNK_OPTIONS = \
		-framework IOKit\
		-framework CoreFoundation


#
# INCLUDE directories for lsq
#

INCLUDE = -I.\
		-I../../TGLib/NewTL1\
		-I../../interface\
		-I../../TTY\
		-I../../DDCMPLib\
		-I../../TGLib\
		-I../../L2\
		-I../../CORE\
		-I../../TGLib/MAC_SUPPORT\
		-I../../NET_MAC\
		-I../../DDCMPLib/OSX\
		-I../../XMODEM\
		-I../../32/include\
		-I../../32/src\
		-I../../Limolib\
		-I../../32/debug\
		-I../../32/src/PCIO\
		-I../../TTY/OSX


#
# Build lsq
#

lsq : \
		Tl12parse.o\
		lua_tl12parse.o\
		interface.o\
		console.o\
		tgttyio.o\
		lioi.o\
		ConvPDP.o\
		ddcmplib.o\
		luadsup.o\
		ieee_fake.o\
		tggpib.o\
		protocol.o\
		protocolsup.o\
		Tl1parse.o\
		ltgevent.o\
		ltgevent_internal.o\
		lkvplib.o\
		ltbxmlib.o\
		ddcmpmon.o\
		xmodem.o\
		xmgr.o\
		lua.o\
		CSerial.o\
		CSStream.o\
		CTCPNet.o\
		CTimer.o\
		CDDCMP.o\
		Cpsnet.o\
		TGParse.o\
		lapi.o\
		lauxlib.o\
		lbuffer.o\
		lbuiltin.o\
		ldo.o\
		lfunc.o\
		lgc.o\
		llex.o\
		lmem.o\
		lobject.o\
		lparser.o\
		lstate.o\
		lstring.o\
		ltable.o\
		ltm.o\
		lundump.o\
		lvm.o\
		lzio.o\
		ldblib.o\
		linit.o\
		liolib.o\
		lmathlib.o\
		lstrlib.o\
		llimolib.o\
		ltglib.o\
		ldebug.o\
		CSNet.o\
		tgnewio.o\
		ddcmptrans.o\
		ddcmpenv.o\
		qdxmlparse.o\
		tgkbhit.o
	$(CC) $(LNK_OPTIONS) \
		Tl12parse.o\
		lua_tl12parse.o\
		interface.o\
		console.o\
		tgttyio.o\
		lioi.o\
		ConvPDP.o\
		ddcmplib.o\
		luadsup.o\
		ieee_fake.o\
		tggpib.o\
		protocol.o\
		protocolsup.o\
		Tl1parse.o\
		ltgevent.o\
		ltgevent_internal.o\
		lkvplib.o\
		ltbxmlib.o\
		ddcmpmon.o\
		xmodem.o\
		xmgr.o\
		lua.o\
		CSerial.o\
		CSStream.o\
		CTCPNet.o\
		CTimer.o\
		CDDCMP.o\
		Cpsnet.o\
		TGParse.o\
		lapi.o\
		lauxlib.o\
		lbuffer.o\
		lbuiltin.o\
		ldo.o\
		lfunc.o\
		lgc.o\
		llex.o\
		lmem.o\
		lobject.o\
		lparser.o\
		lstate.o\
		lstring.o\
		ltable.o\
		ltm.o\
		lundump.o\
		lvm.o\
		lzio.o\
		ldblib.o\
		linit.o\
		liolib.o\
		lmathlib.o\
		lstrlib.o\
		llimolib.o\
		ltglib.o\
		ldebug.o\
		CSNet.o\
		tgnewio.o\
		ddcmptrans.o\
		ddcmpenv.o\
		qdxmlparse.o\
		tgkbhit.o\
		-o lsq

#
# Build the parts of lsq
#


# Item # 1 -- Tl12parse --
Tl12parse.o : ../../TGLib/NewTL1/Tl12parse.cpp
	$(CC) $(CC_OPTIONS) ../../TGLib/NewTL1/Tl12parse.cpp -c $(INCLUDE) -o Tl12parse.o


# Item # 2 -- lua_tl12parse --
lua_tl12parse.o : ../../TGLib/NewTL1/lua_tl12parse.cpp
	$(CC) $(CC_OPTIONS) ../../TGLib/NewTL1/lua_tl12parse.cpp -c $(INCLUDE) -o lua_tl12parse.o


# Item # 3 -- interface --
interface.o : ../../interface/interface.cpp
	$(CC) $(CC_OPTIONS) ../../interface/interface.cpp -c $(INCLUDE) -o interface.o


# Item # 4 -- console --
console.o : ../../TTY/console.cpp
	$(CC) $(CC_OPTIONS) ../../TTY/console.cpp -c $(INCLUDE) -o console.o


# Item # 5 -- tgttyio --
tgttyio.o : ../../TTY/tgttyio.cpp
	$(CC) $(CC_OPTIONS) ../../TTY/tgttyio.cpp -c $(INCLUDE) -o tgttyio.o


# Item # 6 -- lioi --
lioi.o : ../../32/src/PCIO/lioi.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/PCIO/lioi.cpp -c $(INCLUDE) -o lioi.o


# Item # 7 -- ConvPDP --
ConvPDP.o : ../../DDCMPLib/ConvPDP.cp
	$(CC) $(CC_OPTIONS) ../../DDCMPLib/ConvPDP.cp -c $(INCLUDE) -o ConvPDP.o


# Item # 8 -- ddcmplib --
ddcmplib.o : ../../DDCMPLib/ddcmplib.cpp
	$(CC) $(CC_OPTIONS) ../../DDCMPLib/ddcmplib.cpp -c $(INCLUDE) -o ddcmplib.o


# Item # 9 -- luadsup --
luadsup.o : ../../DDCMPLib/luadsup.cpp
	$(CC) $(CC_OPTIONS) ../../DDCMPLib/luadsup.cpp -c $(INCLUDE) -o luadsup.o


# Item # 10 -- ieee_fake --
ieee_fake.o : ../../TGLib/ieee_fake.cpp
	$(CC) $(CC_OPTIONS) ../../TGLib/ieee_fake.cpp -c $(INCLUDE) -o ieee_fake.o


# Item # 11 -- tggpib --
tggpib.o : ../../TGLib/tggpib.cpp
	$(CC) $(CC_OPTIONS) ../../TGLib/tggpib.cpp -c $(INCLUDE) -o tggpib.o


# Item # 12 -- protocol --
protocol.o : ../../L2/protocol.cpp
	$(CC) $(CC_OPTIONS) ../../L2/protocol.cpp -c $(INCLUDE) -o protocol.o


# Item # 13 -- protocolsup --
protocolsup.o : ../../L2/protocolsup.cpp
	$(CC) $(CC_OPTIONS) ../../L2/protocolsup.cpp -c $(INCLUDE) -o protocolsup.o


# Item # 14 -- Tl1parse --
Tl1parse.o : ../../CORE/Tl1parse.cpp
	$(CC) $(CC_OPTIONS) ../../CORE/Tl1parse.cpp -c $(INCLUDE) -o Tl1parse.o


# Item # 15 -- ltgevent --
ltgevent.o : ../../TGLib/ltgevent.cpp
	$(CC) $(CC_OPTIONS) ../../TGLib/ltgevent.cpp -c $(INCLUDE) -o ltgevent.o


# Item # 16 -- ltgevent_internal --
ltgevent_internal.o : ../../TGLib/MAC_SUPPORT/ltgevent_internal.cpp
	$(CC) $(CC_OPTIONS) ../../TGLib/MAC_SUPPORT/ltgevent_internal.cpp -c $(INCLUDE) -o ltgevent_internal.o


# Item # 17 -- lkvplib --
lkvplib.o : ../../32/src/lib/lkvplib.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lib/lkvplib.cpp -c $(INCLUDE) -o lkvplib.o


# Item # 18 -- ltbxmlib --
ltbxmlib.o : ../../TGLib/ltbxmlib.cpp
	$(CC) $(CC_OPTIONS) ../../TGLib/ltbxmlib.cpp -c $(INCLUDE) -o ltbxmlib.o


# Item # 19 -- ddcmpmon --
ddcmpmon.o : ../../DDCMPLib/OSX/ddcmpmon.cpp
	$(CC) $(CC_OPTIONS) ../../DDCMPLib/OSX/ddcmpmon.cpp -c $(INCLUDE) -o ddcmpmon.o


# Item # 20 -- xmodem --
xmodem.o : ../../XMODEM/xmodem.cp
	$(CC) $(CC_OPTIONS) ../../XMODEM/xmodem.cp -c $(INCLUDE) -o xmodem.o


# Item # 21 -- xmgr --
xmgr.o : ../../XMODEM/xmgr.cpp
	$(CC) $(CC_OPTIONS) ../../XMODEM/xmgr.cpp -c $(INCLUDE) -o xmgr.o


# Item # 22 -- lua --
lua.o : ../../32/src/lua/lua.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lua/lua.cpp -c $(INCLUDE) -o lua.o


# Item # 23 -- CSerial --
CSerial.o : ../../NET_MAC/CSerial.cpp
	$(CC) $(CC_OPTIONS) ../../NET_MAC/CSerial.cpp -c $(INCLUDE) -o CSerial.o


# Item # 24 -- CSStream --
CSStream.o : ../../NET_MAC/CSStream.cpp
	$(CC) $(CC_OPTIONS) ../../NET_MAC/CSStream.cpp -c $(INCLUDE) -o CSStream.o


# Item # 25 -- CTCPNet --
CTCPNet.o : ../../NET_MAC/CTCPNet.cpp
	$(CC) $(CC_OPTIONS) ../../NET_MAC/CTCPNet.cpp -c $(INCLUDE) -o CTCPNet.o


# Item # 26 -- CTimer --
CTimer.o : ../../NET_MAC/CTimer.cpp
	$(CC) $(CC_OPTIONS) ../../NET_MAC/CTimer.cpp -c $(INCLUDE) -o CTimer.o


# Item # 27 -- CDDCMP --
CDDCMP.o : ../../NET_MAC/CDDCMP.cpp
	$(CC) $(CC_OPTIONS) ../../NET_MAC/CDDCMP.cpp -c $(INCLUDE) -o CDDCMP.o


# Item # 28 -- Cpsnet --
Cpsnet.o : ../../NET_MAC/Cpsnet.cpp
	$(CC) $(CC_OPTIONS) ../../NET_MAC/Cpsnet.cpp -c $(INCLUDE) -o Cpsnet.o


# Item # 29 -- TGParse --
TGParse.o : ../../CORE/TGParse.cpp
	$(CC) $(CC_OPTIONS) ../../CORE/TGParse.cpp -c $(INCLUDE) -o TGParse.o


# Item # 30 -- lapi --
lapi.o : ../../32/src/lapi.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lapi.cpp -c $(INCLUDE) -o lapi.o


# Item # 31 -- lauxlib --
lauxlib.o : ../../32/src/lauxlib.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lauxlib.cpp -c $(INCLUDE) -o lauxlib.o


# Item # 32 -- lbuffer --
lbuffer.o : ../../32/src/lbuffer.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lbuffer.cpp -c $(INCLUDE) -o lbuffer.o


# Item # 33 -- lbuiltin --
lbuiltin.o : ../../32/src/lbuiltin.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lbuiltin.cpp -c $(INCLUDE) -o lbuiltin.o


# Item # 34 -- ldo --
ldo.o : ../../32/src/ldo.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/ldo.cpp -c $(INCLUDE) -o ldo.o


# Item # 35 -- lfunc --
lfunc.o : ../../32/src/lfunc.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lfunc.cpp -c $(INCLUDE) -o lfunc.o


# Item # 36 -- lgc --
lgc.o : ../../32/src/lgc.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lgc.cpp -c $(INCLUDE) -o lgc.o


# Item # 37 -- llex --
llex.o : ../../32/src/llex.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/llex.cpp -c $(INCLUDE) -o llex.o


# Item # 38 -- lmem --
lmem.o : ../../32/src/lmem.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lmem.cpp -c $(INCLUDE) -o lmem.o


# Item # 39 -- lobject --
lobject.o : ../../32/src/lobject.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lobject.cpp -c $(INCLUDE) -o lobject.o


# Item # 40 -- lparser --
lparser.o : ../../32/src/lparser.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lparser.cpp -c $(INCLUDE) -o lparser.o


# Item # 41 -- lstate --
lstate.o : ../../32/src/lstate.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lstate.cpp -c $(INCLUDE) -o lstate.o


# Item # 42 -- lstring --
lstring.o : ../../32/src/lstring.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lstring.cpp -c $(INCLUDE) -o lstring.o


# Item # 43 -- ltable --
ltable.o : ../../32/src/ltable.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/ltable.cpp -c $(INCLUDE) -o ltable.o


# Item # 44 -- ltm --
ltm.o : ../../32/src/ltm.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/ltm.cpp -c $(INCLUDE) -o ltm.o


# Item # 45 -- lundump --
lundump.o : ../../32/src/lundump.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lundump.cpp -c $(INCLUDE) -o lundump.o


# Item # 46 -- lvm --
lvm.o : ../../32/src/lvm.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lvm.cpp -c $(INCLUDE) -o lvm.o


# Item # 47 -- lzio --
lzio.o : ../../32/src/lzio.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lzio.cpp -c $(INCLUDE) -o lzio.o


# Item # 48 -- ldblib --
ldblib.o : ../../32/src/lib/ldblib.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lib/ldblib.cpp -c $(INCLUDE) -o ldblib.o


# Item # 49 -- linit --
linit.o : ../../32/src/lib/linit.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lib/linit.cpp -c $(INCLUDE) -o linit.o


# Item # 50 -- liolib --
liolib.o : ../../32/src/lib/liolib.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lib/liolib.cpp -c $(INCLUDE) -o liolib.o


# Item # 51 -- lmathlib --
lmathlib.o : ../../32/src/lib/lmathlib.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lib/lmathlib.cpp -c $(INCLUDE) -o lmathlib.o


# Item # 52 -- lstrlib --
lstrlib.o : ../../32/src/lib/lstrlib.cpp
	$(CC) $(CC_OPTIONS) ../../32/src/lib/lstrlib.cpp -c $(INCLUDE) -o lstrlib.o


# Item # 53 -- llimolib --
llimolib.o : ../../Limolib/llimolib.cpp
	$(CC) $(CC_OPTIONS) ../../Limolib/llimolib.cpp -c $(INCLUDE) -o llimolib.o


# Item # 54 -- ltglib --
ltglib.o : ../../TGLib/ltglib.cpp
	$(CC) $(CC_OPTIONS) ../../TGLib/ltglib.cpp -c $(INCLUDE) -o ltglib.o


# Item # 55 -- ldebug --
ldebug.o : ../../32/debug/ldebug.cpp
	$(CC) $(CC_OPTIONS) ../../32/debug/ldebug.cpp -c $(INCLUDE) -o ldebug.o


# Item # 56 -- CSNet --
CSNet.o : ../../NET_MAC/CSNet.cpp
	$(CC) $(CC_OPTIONS) ../../NET_MAC/CSNet.cpp -c $(INCLUDE) -o CSNet.o


# Item # 57 -- tgnewio --
tgnewio.o : ../../TGLib/tgnewio.cpp
	$(CC) $(CC_OPTIONS) ../../TGLib/tgnewio.cpp -c $(INCLUDE) -o tgnewio.o


# Item # 58 -- ddcmptrans --
ddcmptrans.o : ../../DDCMPLib/ddcmptrans.cpp
	$(CC) $(CC_OPTIONS) ../../DDCMPLib/ddcmptrans.cpp -c $(INCLUDE) -o ddcmptrans.o


# Item # 59 -- ddcmpenv --
ddcmpenv.o : ../../DDCMPLib/ddcmpenv.cpp
	$(CC) $(CC_OPTIONS) ../../DDCMPLib/ddcmpenv.cpp -c $(INCLUDE) -o ddcmpenv.o


# Item # 60 -- qdxmlparse --
qdxmlparse.o : ../../DDCMPLib/qdxmlparse.cpp
	$(CC) $(CC_OPTIONS) ../../DDCMPLib/qdxmlparse.cpp -c $(INCLUDE) -o qdxmlparse.o


# Item # 61 -- tgkbhit --
tgkbhit.o : ../../TTY/OSX/tgkbhit.cpp
	$(CC) $(CC_OPTIONS) ../../TTY/OSX/tgkbhit.cpp -c $(INCLUDE) -o tgkbhit.o


##### END RUN ####
