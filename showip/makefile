CC     := gcc
CFLAGS := -g -O0
SRC    := showip.c
EXE    := showip
RM     := rm -fr
all :  $(EXE)
$(EXE) : $(SRC)
clean :
	$(RM) $(EXE) *~ *.dSYM/
run : all
ifeq ($(URL),$(EMPTY))
	@echo
	@echo 'URL needed ... e.g.: make run URL=beej.us'
	@echo
else
	@./$(EXE) $(URL)
endif