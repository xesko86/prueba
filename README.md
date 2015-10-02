#!/usr/bin/env python
# -*- coding: utf-8 -*- 
# import pdb
numeros=[1,3,67,67,4,5,7,7,9,8,8,15,20,20]

# resultado=[]

#  indice=0

# for elemento in numeros:
#     posicion= numeros.index(elemento)
#     if posicion !=len(numeros) -1:
#         if elemento == numeros[posicion +1 ]:
#             numeros.remove(elemento)
            
# print numeros 

resultado =[]

for indice,elemento in enumerate(numeros):
    if indice != len(numeros) -1:
        if elemento != numeros[indice +1]:
            resultado.append(elemento)
            
resultado.append(numeros[-1])
print resultado
