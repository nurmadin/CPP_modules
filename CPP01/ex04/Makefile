NAME = SedIsForLosers

CC = c++
CFLAGS = -Wall -Wextra -Werror -std=c++98

SRC = main.cpp

all: $(NAME)

$(NAME):
	@$(CC) $(CFLAGS) $(SRC) -o $(NAME)

clean:
	@rm -f $(NAME) *.replace

fclean:
	@rm -f $(NAME) *.replace

re: fclean all

.PHONY: all re clean fclean