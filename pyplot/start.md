Neste arquivo, irei fazer como um dicionário ou uma forma de pesquisa rápida.

# Instalação
Para instalar a biblioteca do Matplotlib podemos rodar o seguinte comando 

```
pip install matplotlib
```
ou

```
!pip install matplotlib
```
caso esteja utilizando jupyter notebook.

# Importar 

Por enquanto iremos utilizar somente o pyplot, logo 

```
import matplotlib.pyplot as plt
```

# Casos de uso 

## Gerar Gráficos
Podemos gerar gráficos a partir do seguinte comando:

```
plt.plot() # Gráfico de linhas
plt.pie() # Gráfico de Pizza (Setores)
plt.scatter() # Gráfico de Dispersão
plt.show() # Sinalizar ao Matplotlib a finalização dos ajustes
```
Para mais informações de outros gráficos podemos acessar o site do
[Sumário Pyplot](https://matplotlib.org/stable/api/pyplot_summary.html).

## Labels
Para gerar os labels podemos utilizar os seguintes comandos:
```
plt.xlabel()
plt.ylabel()
```
passando dentro uma string.

## Grid
Para mostrar ou não o grid podemos utilizar:

```
plt.grid()
```
passando um boolean.
