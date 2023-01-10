GITROOT := $(shell git rev-parse --show-toplevel)
PATCHES := $(wildcard $(GITROOT)/patches/*.patch)
.PHONY: $(PATCHES)

apply: $(PATCHES)

$(PATCHES):
  git apply $@
