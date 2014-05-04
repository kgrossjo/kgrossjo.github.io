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
	cp template.md contents/articles/$(NAME)/index.md; \
	echo "Now edit contents/articles/$(NAME)/index.md"

preview:
	wintersmith preview &
	sleep 5
	open 'http://localhost:4000/'

clean:
	if [ -d ../.git ]; then \
		rm -rf ../articles ../css ../page ../*.html ../feed.xml; \
	else \
		echo "ERROR: No such directory '../.git', are you in the right directory?" ; \
		exit 1; \
	fi
