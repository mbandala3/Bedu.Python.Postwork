#Ejercicio Postwork1

#Nombre de la tarjeta
print("Ingrese nombre de la tarjeta")
nombre_tarjeta= input()


#Tasa de interés
print("Tasa de interés anual (en decimal)")
interes_anual= input()
interes_anual1 = float(interes_anual)
# Intereses
interes_mensual = interes_anual1/12
print("Interés mensual:", interes_mensual)

#Deuda
print("Monto deuda")
monto_deuda= input()
monto_deuda1 = float(monto_deuda)

#Pago
print("Pago a realizar: ")
pago= input()
pago1= float(pago)
if pago>monto_deuda:
    print("El pago es mayor a deuda, intente un monto menor")
    #Aquí me faltó un bucle para regresar el monto deuda pero no supe cómo hacerlo.

# Nuevos Cargos
deuda_recalculada = (1+interes_mensual) * (monto_deuda1 - pago1)
deuda_recalculada1= float(deuda_recalculada)
print("Nueva deuda es: $", deuda_recalculada1)
var2="deuda_recalculada1"

# Mensaje final (usando .format)
print("El monto actual de tu tarjeta {tarjeta} es de ${debt}".format(tarjeta=nombre_tarjeta, debt=deuda_recalculada1))
