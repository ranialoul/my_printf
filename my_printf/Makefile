##
## Makefile for makefile in /home/menett_a/rendu/my_printf
## 
## Made by Nicolas Menettrier
## Login   <menett_a@epitech.net>
## 
## Started on  Sun Nov  8 16:39:36 2015 Nicolas Menettrier
## Last update Fri Feb  5 17:38:02 2016 menett_a
##

SRC	= my_printf.c			\
	  hexa.c			\
	  octal.c			\
	  my_put_unsigned_nb.c		\
	  hexa_capitalize.c		\
	  binary.c			\
	  my_putchar.c			\
	  my_put_nbr.c			\
	  my_putstr.c			\
	  pourcent.c			\
	  hexa_add.c			\
	  put_octal.c

NAME	= lib/libmy.a

OBJ	= $(SRC:.c=.o)

RM	= rm -rf

all:	$(NAME)

$(NAME):$(OBJ)
	@ar rc $(NAME) $(OBJ)
	@ranlib $(NAME)

clean:
	$(RM) $(OBJ)

fclean: clean
	$(RM) $(NAME)

re:	fclean all

.PHONY: all clean fclean re
