CC = cc
CFLAGS = -Wall -Werror -Wextra
NAME = libft.a
SRCS = ./srcs/ft_putchar.c ./srcs/ft_swap.c ./srcs/ft_putstr.c ./srcs/ft_strlen ./srcs/ft_strcmp
OBJS = $(SRC:.c=.o)
HEADER = ./includes/ft/h
all : $(NAME)

(NAME) : $(OBJS)
	$(CC) $(CFLAGS) -I $(INC) $^ -o $

clean :
	rm -f $(OBJS)

fclean : clean
	rm -f $(NAME)

re : fclean all

.PHONY : all clean fclean re
