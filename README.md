TASK NUMBER-22
 Name:	Water level	
 Components:	Container (server), adder, remover.
 Description:	If water level is below chosen lower limit, adder components generate random positive amounts of water added. Generated amounts are accumulated in the server. Otherwise, adder components do nothing. If water level is above chosen upper limit, remove components generate random positive amounts of water removed. Generated amounts are removed from the server. Otherwise, remover components do nothing. Server changes lower and upper limits randomly every 8 secs. The difference between upper and lower limits must always be positive and bigger than zero. Adders are not allowed to add water above lower limit. Removers are not allowed to remove water below upper limit.
