CC     := gcc
CFLAGS := -g -O0
SRC    := showip.c
EXE    := showip
RM     := rm -fr
all :  $(EXE)
$(EXE) : $(SRC)
clean :
	$(RM) $(EXE) *~ *.dSYM/
run :
ifeq ($(URL),$(EMPTY))
	./$(EXE) http://beej.us
else
	./$(EXE) $(URL)
endif
