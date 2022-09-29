name_list = []

def shakersort(lista):
  indice=0
  ultimo=len(lista)
  swapped=True
  while swapped==True:
      swapped=False
      while indice < len(lista)-1:
        if lista[indice]>lista[indice+1]:
          swapped=True
          lista[indice],lista[indice+1]=lista[indice+1],lista[indice]
        indice = indice + 1
      while indice >=1:
        if lista[indice]<lista[indice-1]:
          swapped=True
          lista[indice],lista[indice-1]=lista[indice-1],lista[indice]
        indice = indice - 1
      indice = 0
      ultimo = ultimo-1
  return lista

while True:
  escolha = input("Digite um nome(-1 para sair):")
  if escolha == "-1":
    print(name_list)
    break
  name_list.append(escolha)
  name_list = shakersort(name_list)
  print(name_list)
