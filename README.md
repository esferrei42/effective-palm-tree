# effective-palm-tree

int ft_strlen(char *str)
{
  int i;
  
  i = 0;
  while (str)
  {
    i++;
  }
  return (i);
}

void  ft_putstr(char *str)
{
  write(1, str, ft_strlen(str));
}

int main()
{
  ft_putstr("Hello world!");
  return (0);
}
