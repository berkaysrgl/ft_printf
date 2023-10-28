# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: bsarigul <bsarigul@student.42istanbul.c    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2023/03/07 00:25:31 by bsarigul          #+#    #+#              #
#    Updated: 2023/03/11 05:40:11 by bsarigul         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

SRCS	= ft_printf.c \
			ft_printf_utils.c

NAME	= libftprintf.a

OBJS	= $(SRCS:.c=.o)

FLAGS	= -Wall -Wextra -Werror

$(NAME):
		gcc $(FLAGS)   -c $(SRCS)
		ar rc $(NAME) $(OBJS)

all: $(NAME)

clean:
		rm -rf $(OBJS)

fclean: clean
		rm -rf $(NAME)

re: fclean all

.PHONY: all clean fclean re