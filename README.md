# Tp-1-ALGO-II-AirMiles
tp de algo II especificacion TAD AirMail

Cosas por hacer: 

- ~~obs PROMOS (NO CONTAR CUANTAS VAN,. IR RESTANDO AL TOPE)~~
-~~UNificar observadores para minimal historiales : Diccionario⟨U suario, struct<transacciones:HistorialT ransaccion,vuelos:historailVuelos>⟩~~
  -Ver si dejamos Historial como Renombre o si ponemos el struct en el observador



~~-acumularmilla
  cambiar el queruier ( promoion sin ope OR_l  ((esOro() ->'_l' cuentaMilla()  > tope promocion INT esBronce... ) )) 
  asegura (CAMBIAR TOPE (RESTAR, O AGREGAR)
          si promo tiene tope y llega a cero por millas ENTONCES eliminar promo~~

~~AGREGAR PRED ESorO....~~


~~-proc acumullarMillas() 
{
    requier
    asegura{                                                     
         esOro(storialesTransacciones, usuario) -> am.historialesTransacciones = setKey(AM0.historialesTransacciones,usuario,AM0.historialesTransacciones[usuario]++<('Acumular',CuentadeMilla(),'')>) INT
          esPlatino(storialesTransacciones, usuario) -> distancia*0*factorpromocion) INT
        esBronce(storialesTransacciones, usuario) -> distancia*1.5*factorpromocion) INT
}
}~~



~~-aux millasCategortai (distancia, factor, categoria) = distancia*
-pred esOro(historialesTransacciones, usuario) { millatotales(historialesTransacciones, usuario) <= 10000 
}~~

-ORDER PRED Y AXU

-Elimar igualesSalvoUsuarios (Controlar los proc que la usan. Pasarlos a usar igualesSalvoUsuariosIdaVuelta. Fijarse si se puede usar directamente setKEy() )

~~-Modificar RankingMillas~~ 

-Controlar que en sonParejaUsuario el observador 'comentario'  que es string no sea usado para compara con obs Usuario que es INT


~~-Modificar lops proc que usen millasDisponibles para que usen millasDisponibles(historialTransaccionesSinCanjeo())~~
~~-Agregar un aux que sea historialTransaccionesSinCanjeo que tome un historial de t rsnacciones, un usuario, y devuelve el historial sin las transaccaiones que son CAnjear~~
~~-aux millasDisponibles(hist : HistorialT ransaccion) : R =∑︁ |hist−1|i=0 fThenElse(esUso(hist[i]0), −1∗hist[i]1, hist[i]1)~~


cambiar aux eliminarPromocion(baseDeDatos : Diccionario⟨N ombreP romocion, seq⟨T ⟩ POR  Diccionario⟨N ombreP romocion,PromocionesActivas

En particualr eliminar aux eliminarPromocion Y dejar solo delKey


