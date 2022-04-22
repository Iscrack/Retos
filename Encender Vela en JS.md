var vela;

vela = prompt("¿Está la vela encendida?");

if(vela == "Si" || vela == "Sí"|| 
   vela == "si" || vela == "sí"||
   vela == "sI" || vela == "sÍ"|| vela == "SI"){

alert("Vela encendida");
}

else if (vela == "NO" || vela == "no"
        ||vela == "No" || vela == "nO")
 {

alert("Encender vela");
 }

else alert("Comando inválido, vuelva a intentar");
