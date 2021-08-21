Mi proyecto sobre el control de temperatura de una cámara frigorífica se manejará con las siguientes instrucciones:
Habrá una temperatura configurada como Tconfig, un DeltaT y una temperatura TS que es la temperatura leída por un Sensor. Esa temperatura podrá variar una cantidad DeltaT tal que Tconfig-DeltaT<TS<Tconfig+DeltaT.
Cuando la temperatura TS<Tconfig-DeltaT, se habilitarán varias entradas de aire al exterior, considerando una temperatura ambiente en el aire. En caso de que la temperatura no se regule en un cierto tiempo U, sonará una alarma de aviso X1 para avisar por falta de calor.
Si la temperatura TS retoma un valor mayor a Tconfig-DeltaT, entonces las entradas de aire se cierran.
En caso de que la temperatura TS exceda a Tconfig+DeltaT, se habilitarán extractores de calor, un sistema de refrigeración aparte del que ya contiene la cámara frigorífica. Al igual que con las entradas de aire, si la temperatura no se regula en un cierto tiempo
U, se habilitará otra alarma X2 ![IMG_20210820_234744](https://user-images.githubusercontent.com/82184438/130308429-ec427fec-195a-45e2-9133-f8cf9e1c302f.jpg)
