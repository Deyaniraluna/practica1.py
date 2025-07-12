 Deyanira_luna practica1.py
# Coordenadas de los puntos
x1, y1 = 5, 12
x2, y2 = 3, 4

# Calcular diferencia
dx = x2 - x1
dy = y2 - y1

# Distancia Euclidiana (con raíz cuadrada manual usando **0.5)
dist_euclidiana = ((dx)*2 + (dy)*2) ** 0.5

# Distancia Manhattan (solo valor absoluto con abs)
dist_manhattan = abs(dx) + abs(dy)

# Imprimir resultados
print("Distancia Euclidiana:", dist_euclidiana)
print("Distancia Manhattan:", dist_manhattan)
