!pip install pytest
!pip install pytest

with open ("teste_calculadora.py", "w") as f:
  f.write ("""
import pytest

# Funções que serão testadas
def soma(a, b):
    return a + b

def subtração (a, b):
    return a - b

def multiplicação (a, b):
    return a * b 
             
def divisão (a, b):
  if b == 0:
    raise ValueError ("Não pode dividir por zero!")
  return a / b""")

