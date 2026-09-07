# Tp-1-ALGO-II-AirMiles
tp de algo II especificacion TAD AirMail

* \begin{proc}{elQueTieneMasMillas}
{
\In am:AirMiles
}{
\Tipo{Usuario}
}
    \requiere{|am.historial|>0}
    %no se si esta bie npedir no vacio o si deberia tener que aceptar el vacio y devolver nada
    \aseguraLargo{
        res \in am.historiales \land \\
        ~~\forall k \in \Z)(k \in am.historiales[k].transacciones\ \implicaLuego \ millasTotales(am.historiales[k].transacciones)\\ \leq millasTotales(am.historiales[res].transacciones))~~
        \forall k \in \Z)(k \in am.historiales \implicaLuego \ millasTotales(am.historiales[k].transacciones)\\ \leq millasTotales(am.historiales[res].transacciones))
        }
\end{proc}
