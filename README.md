# Making-the-boxes-using-hastags
def box(n):
  if n == 1:
    return ['#']
  else:
    top = ['#' * n]
    middle = ['#' + ' ' *(n-2) + '#']*(n-2)
    bottom = ['#' * n]
    print(*top)
    print(*middle , sep = '\n')
    print(*bottom)
box(10)
