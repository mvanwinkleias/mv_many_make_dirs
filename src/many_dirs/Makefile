# Run this with:
# make --keep-going --always-make --jobs j3 dirs/*

.PHONY: %
dirs/%:
	+cd $@ && $(MAKE)
