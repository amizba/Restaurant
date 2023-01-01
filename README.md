# Restaurant
# 
# Aprende Java desde cero (https://empezandojava.blogspot.com)
#
# @author Amparo Izquierdo Bañez
# @mail amizba@gmail.com

# Aplicación de restaurante para colocar a los clientes en sus mesas. En una mesa se pueden sentar de 0 (mesa vacía) a 6 comensales (mesa llena). 
# Cuando llega un cliente se le pregunta cuántos son. De momento el programa no está preparado para colocar a grupos mayores a 6, por tanto, si un 
# cliente dice por ejemplo que son un grupo de 8, el programa dará el mensaje “Lo siento, no admitimos grupos de 8, haga grupos de 6 personas como 
# máximo e intente de nuevo”. Para el grupo que llega, se busca siempre la primera mesa libre (con 0 personas). Si no quedan mesas libres, se busca 
# donde haya un hueco para todo el grupo, por ejemplo si el grupo es de dos personas, se podrá colocar donde haya una o dos personas. Inicialmente, 
# las mesas se cargan con valores aleatorios entre 0 y 6. Cada vez que se sientan nuevos clientes se debe mostrar el estado de las mesas. Los grupos 
# no se pueden romper aunque haya huecos sueltos suficientes. 
