# CalculoDescuentoPython
def calcular_descuento(monto_total, porcentaje_descuento=10):
    """
    Calcula el descuento en base al monto total y el porcentaje de descuento.
    :param monto_total: Total de la compra
    :param porcentaje_descuento: Porcentaje de descuento a aplicar (10% por defecto)
    :return: Monto del descuento
    """
    descuento = (monto_total * porcentaje_descuento) / 100
    return descuento

# Ejemplo de llamadas a la función
total_compra1 = 200

descuento1 = calcular_descuento(total_compra1)
print(f"Total de compra: ${total_compra1}")
print(f"Descuento aplicado: ${descuento1}")
print(f"Monto final a pagar: ${total_compra1 - descuento1}\n")

total_compra2 = 300
porcentaje_descuento2 = 15

descuento2 = calcular_descuento(total_compra2, porcentaje_descuento2)
print(f"Total de compra: ${total_compra2}")
print(f"Descuento aplicado: ${descuento2}")
print(f"Monto final a pagar: ${total_compra2 - descuento2}")
