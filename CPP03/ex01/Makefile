NAME = ScavTrap

CC = c++
CFLAGS = -Wall -Wextra -Werror -std=c++98

SRC = main.cpp ClapTrap.cpp ScavTrap.cpp
HEADER = ClapTrap.hpp ScavTrap.hpp

all: $(NAME)

$(NAME):	$(SRC) $(HEADER)
	@$(CC) $(CFLAGS) $(SRC) -o $(NAME)

clean:
	@rm -f $(NAME)

fclean:
	@rm -f $(NAME)

re: fclean all

.PHONY: all re clean fclean