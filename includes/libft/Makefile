#******************************************************************************#
#                                                           LE - /             #
#                                                               /              #
#    Makefile                                         .::    .:/ .      .::    #
#                                                  +:+:+   +:    +:  +:+:+     #
#    By: bjuarez <marvin@le-101.fr>                 +:+   +:    +:    +:+      #
#                                                  #+#   #+    #+    #+#       #
#    Created: 2018/10/03 09:13:06 by bjuarez      #+#   ##    ##    #+#        #
#    Updated: 2018/10/23 13:52:01 by jominodi    ###    #+. /#+    ###.fr      #
#                                                          /                   #
#                                                         /                    #
#******************************************************************************#

NAME	= libft.a
FLAGS 	= -Wall -Werror -Wextra
CFLAGS	= $(FLAGS) -I. -c
SRC		= ft_atoi.c\
		  ft_bzero.c\
		  ft_isascii.c\
		  ft_isalnum.c\
		  ft_isalpha.c\
		  ft_isprint.c\
		  ft_isdigit.c\
		  ft_lstadd.c\
		  ft_lstdel.c\
		  ft_lstdelone.c\
		  ft_lstiter.c\
		  ft_memalloc.c\
		  ft_itoa.c\
		  ft_lstnew.c\
		  ft_memchr.c\
		  ft_memccpy.c\
		  ft_lstmap.c\
		  ft_memdel.c\
		  ft_memcpy.c\
		  ft_memset.c\
		  ft_memcmp.c\
		  ft_putchar.c\
		  ft_putchar_fd.c\
		  ft_putendl.c\
		  ft_memmove.c\
		  ft_putendl_fd.c\
		  ft_putstr.c\
		  ft_putnbr.c\
		  ft_putstr_fd.c\
		  ft_putnbr_fd.c\
		  ft_strcat.c\
		  ft_strclr.c\
		  ft_strcmp.c\
		  ft_strdel.c\
		  ft_strcpy.c\
		  ft_strchr.c\
		  ft_strequ.c\
		  ft_striter.c\
		  ft_strjoin.c\
		  ft_striteri.c\
		  ft_strdup.c\
		  ft_strlen.c\
		  ft_strncat.c\
		  ft_strlcat.c\
		  ft_strmap.c\
		  ft_strmapi.c\
		  ft_strnequ.c\
		  ft_strnew.c\
		  ft_strncpy.c\
		  ft_strncmp.c\
		  ft_strrchr.c\
		  ft_strstr.c\
		  ft_strnstr.c\
		  ft_tolower.c\
		  ft_strsub.c\
		  ft_strtrim.c\
		  ft_strsplit.c\
		  ft_toupper.c\
		  ft_swap.c\
		  ft_sqrt.c\
		  ft_power.c\
		  ft_strlwr.c\
		  ft_strupr.c\
		  ft_countword.c\

GCC		= gcc
OBJ		= $(SRC:.c=.o)

all: $(NAME)



$(NAME): $(OBJ)
	ar rc $(NAME) $(OBJ)
	ranlib $(NAME)

%.o: %.c
	$(CC) $(CFLAGS) $< -o $@

clean:
	rm -f $(OBJ)

fclean: clean
	rm -f $(NAME)

re: fclean all
