all:
	wintersmith build

status:
	cd ..; git status

# Add a new page
new:
	@if [ "x$(NAME)" = "x" ]; then \
		echo "Error: missing NAME."; \
		echo "Usage: make new NAME=foo"; \
		exit 1; \
	fi; \
	mkdir contents/articles/$(NAME); \
	cp template.md contents/articles/$(NAME); \
	echo "Now edit contents/articles/$(NAME)/index.md"
