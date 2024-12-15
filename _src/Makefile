dirs = \
"1-be_careful_using_chars" \
"2-whats_const_for" \
"3-a_tale_of_two_unions" \
"4_be_careful_using_unsigned"

default:
	@for i in $(dirs); do \
		echo "Building in $$i"; \
		make -C "$$i"; \
	done

install:
	@for i in $(dirs); do \
		echo "Installing in $$i"; \
		make -C "$$i" install; \
	done

clean:
	@for i in $(dirs); do \
		echo "Cleaning in $$i"; \
		make -C "$$i" clean; \
	done

