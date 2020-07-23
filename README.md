# MAYORIA_ABSOLUTA

def mayoria_absoluta(lista):
	dicc={lista.count(i):i for i in lista}
	mayor_frecuencia=max(dicc.keys())
	if mayor_frecuencia>=len(lista)/2:
		print(dicc.get(mayor_frecuencia))
	else:
		print("None")
	 

mayoria_absoluta(['A', 'A', 'B'])
print("---")
mayoria_absoluta(['A', 'A', 'A', 'B', 'C', 'A'])
print("---")
mayoria_absoluta(['A', 'B', 'B', 'A', 'C', 'C'])
