NAME	=	libftprintf.a

SRCS	=	ft_printf.c ft_printf_ut.c

OBJS = $(SRCS:.c=.o)


CC	=	gcc
RM	=	rm -f
FLAGS	= -Wall -Wextra -Werror

all: $(NAME)

$(NAME): 
		$(CC) $(FLAGS) -c $(SRCS) 
		ar rc $(NAME) $(OBJS)

clean:
		$(RM) $(OBJS) 

fclean: clean
		$(RM) $(NAME)

re: fclean all

.PHONY: all clean fclean re