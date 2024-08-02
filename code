def divisors_of_number(n):
  p = 1
  for i in range(1, int(n ** 0.5 + 1)):
    if n % i == 0:
      p = p*i* n/i
  return p

for n in range(2, 10037):
  if divisors_of_number(n) == n ** 6:
    print(n)
    break
