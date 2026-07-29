# 🛡️ Guía Operativa Integral del Sistema Quirón

Esta guía está destinada para la correcta clasificación, carga de hechos delictivos y estandarización de criterios operativos DENTRO DE QUIRON.

<div style="background-color: #f1f8ff; border-left: 5px solid #0366d6; padding: 12px 16px; margin: 15px 0; border-radius: 4px;">
  <b>⚠️ Aviso operativo:</b> Verificar siempre la concordancia entre la franja horaria, la jurisdicción y la hora real del hecho antes de confirmar la carga en el sistema.
</div>

---

## 📑 SECCIÓN 1: Guía Completa de Ítems para la Carga

<details>
<summary><b>📖 Ver Guía de Campos del Sistema Quirón (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;">
    <th align="left" width="25%">Campo</th>
    <th align="left" width="75%">Criterio e Instrucciones de Carga</th>
  </tr>
  <tr><td><b>Partido</b></td><td>Seleccionar el partido donde fue cometido el hecho (desplegable).</td></tr>
  <tr><td><b>Localidad</b></td><td>Seleccionar la localidad donde fue cometido el hecho (desplegable).</td></tr>
  <tr><td><b>Jurisdicción</b></td><td>Seleccionar la dependencia policial a la que le corresponde el lugar del hecho (dependencia interviniente).</td></tr>
  <tr><td><b>Lugar del hecho</b></td><td>Dirección exacta donde se cometió el hecho.</td></tr>
  <tr><td><b>Coordenadas</b></td><td>Se cargan de manera automática; de lo contrario, utilizar Google Maps para buscar y copiar las coordenadas exactas.</td></tr>
  <tr><td><b>Fecha del hecho</b></td><td>Colocar la fecha en que fue cometido el hecho (o fecha de denuncia si se desconoce con precisión).</td></tr>
  <tr><td><b>Hora del hecho</b></td><td>Horario en el que ocurrió el hecho. Si no consta en el acta, colocar excepcionalmente el horario de carga en el SID. <br><b>Franjas horarias de análisis:</b> 00:00 a 06:00 hs, 06:00 a 12:00 hs, 12:00 a 18:00 hs, y 18:00 a 24:00 hs.</td></tr>
  <tr><td><b>Tipo de lugar</b></td><td>Locación física del ilícito (finca, vía pública, comercio, establecimiento educativo, etc.) mediante desplegable.</td></tr>
  <tr><td><b>Carátula</b></td><td>Calificación legal del hecho (desplegable). <i>Tildar la casilla correspondiente en caso de ser en grado de tentativa.</i></td></tr>
  <tr><td><b>Modalidad</b></td><td>Colocar según el instructivo técnico correspondiente a cada delito analizado.</td></tr>
  <tr><td><b>Imputados</b></td><td>Registrar Femenino/Masculino. Si son varios o de distintos géneros, consignar ambos. El número exacto y desglose se detalla en Observaciones.</td></tr>
  <tr><td><b>Víctimas</b></td><td>Registrar Femenino/Masculino y consignar ambos si corresponde. Detallar cantidad y menores en Observaciones.</td></tr>
  <tr><td><b>Menores</b></td><td>Registrar Femenino/Masculino. Detallar desglose de cantidad y género en Observaciones si es necesario.</td></tr>
  <tr><td><b>Lesionados</b></td><td>Registrar Sí o No. En Observaciones se especifica el tipo de lesión (golpes, arma de fuego, arma blanca). Exclusivamente hechos dolosos.</td></tr>
  <tr><td><b>Armas</b></td><td>Tipificar el elemento utilizado: Fuego, Blanca o Impropia.</td></tr>
  <tr><td><b>Observaciones</b></td><td>Campo abierto para volcar todo dato relevante, número exacto de víctimas/imputados discriminados por género, hallazgos de rodados, etc.</td></tr>
</table>
</details>

---

## 🔍 SECCIÓN 2: Guía Operativa de Carátulas y Modalidades

Haga clic sobre cada carátula para desplegar sus modalidades o utilice el buscador inteligente en tiempo real:

<div style="margin: 20px 0;">
  <input type="text" id="buscadorGuia" onkeyup="filtrarGuia()" placeholder="🔍 Escriba para buscar carátula, modalidad o criterio..." style="width: 100%; padding: 12px; font-size: 16px; border: 2px solid #ccc; border-radius: 6px; box-sizing: border-box;">
</div>

<div id="contenedorGuia">

<details open>
<summary><b>ROBO (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;">
    <th align="left">Modalidad</th>
    <th align="left">Descripción y Criterios Operativos</th>
  </tr>
  <tr><td><b>Arrebatador</b></td><td>Arrebato en la calle con violencia física o empujones.</td></tr>
  <tr><td><b>Asalto / Simple</b></td><td>Robo ejecutado mediante intimidación o amenazas generales.</td></tr>
  <tr><td><b>Asalto en Comercio</b></td><td>Ingreso delictivo intimidando a comerciantes o empleados.</td></tr>
  <tr><td><b>Asalto en Finca</b></td><td>Ingreso violento a vivienda con moradores o por escalamiento.</td></tr>
  <tr><td><b>Asalto en Vía Pública</b></td><td>Ataque directo a transeúntes mediante amenazas o armas.</td></tr>
  <tr><td><b>Bicicleta</b></td><td>Sustracción de bicicletas mediante amenaza o fuerza.</td></tr>
  <tr><td><b>Choferes</b></td><td>Asaltos a conductores de transporte público, remises, taxis o choferes de APP (DIDI - UBER ETC).</td></tr>
  <tr><td><b>Entradera</b></td><td>Ingreso violento aprovechando apertura de puertas o portones.</td></tr>
  <tr><td><b>Escruche</b></td><td>Robo en finca o local sin moradores forzando aberturas.</td></tr>
  <tr><td><b>Mechera</b></td><td>Sustracción en comercios con amenazas o violencia al ser descubiertos.</td></tr>
  <tr><td><b>Motochorro</b></td><td>Delincuentes en moto que interceptan a la víctima para robar.</td></tr>
  <tr><td><b>Oportunista</b></td><td>Robo perpetrado al surgir una situación imprevista de vulnerabilidad.</td></tr>
  <tr><td><b>Pertenencia</b></td><td>Sustracción de efectos personales del interior de Vehículos, viviendas u oficinas. Con violencia sobre el ingreso.</td></tr>
  <tr><td><b>Piraña</b></td><td>Ataque en grupo numeroso que rodea y abruma a la víctima.</td></tr>
  <tr><td><b>Polichorro</b></td><td>Hecho delictivo cometido por individuos vestidos de ropa Simil Policia.</td></tr>
  <tr><td><b>Punga</b></td><td>Robo mediante destreza pero con intimidación o forcejeo.</td></tr>
  <tr><td><b>Repartidor</b></td><td>Asalto dirigido específicamente a trabajadores de delivery o distribución de mercaderías en la vía pública.</td></tr>
  <tr><td><b>Roba Cable</b></td><td>Sustracción de cables mediante corte o herramientas.</td></tr>
  <tr><td><b>Roba Ruedas</b></td><td>Sustracción de ruedas mediante uso de herramientas.</td></tr>
  <tr><td><b>Roba Patentes</b></td><td>Sustracción Chapa patente mediante uso de herramientas.</td></tr>
  <tr><td><b>Rompe Vidrios</b></td><td>Delincuente que rompe la ventanilla de un automóvil detenido en semáforos o estacionado para sustraer elementos del interior en segundos.</td></tr>
  <tr><td><b>Salidera Bancaria</b></td><td>Asalto planificado tras marcar a la víctima retirando dinero, de entidad bancaria o financiera.</td></tr>
  <tr><td><b>Viuda Negra</b></td><td>Robo bajo suministro de sustancias con amenazas o violencia.</td></tr>
</table>
</details>

<details>
<summary><b>HURTO (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;">
    <th align="left">Modalidad</th>
    <th align="left">Descripción y Criterios Operativos</th>
  </tr>
  <tr><td><b>Arrebatador</b></td><td>Sustracción rápida al paso sin agresión física severa.</td></tr>
  <tr><td><b>Bicicleta</b></td><td>Sustracción de bicicletas en la vía pública sin seguridad.</td></tr>
  <tr><td><b>Hurto</b></td><td>Sustracción simple aprovechando un descuido o puerta abierta.</td></tr>
  <tr><td><b>Mechera</b></td><td>Sustracción en comercios ocultando mercadería sin violencia.</td></tr>
  <tr><td><b>Oportunista</b></td><td>Apoderamiento de un bien momentáneamente desatendido.</td></tr>
  <tr><td><b>Pertenencia</b></td><td>Sustracción de efectos personales del interior de Vehículos, viviendas u oficinas. Sin violencia sobre el ingreso.</td></tr>
  <tr><td><b>Punga</b></td><td>Sustracción por destreza y descuido en aglomeraciones.</td></tr>
  <tr><td><b>Roba Ruedas / Patentes</b></td><td>Sustracción de componentes específicos de vehículos estacionados.</td></tr>
  <tr><td><b>Viuda Negra</b></td><td>Sustracción con suministro de sustancias inhibidoras, sin violencia.</td></tr>
</table>
</details>

<details>
<summary><b>ABUSO SEXUAL (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;">
    <th align="left">Modalidad</th>
    <th align="left">Descripción y Criterios Operativos</th>
  </tr>
  <tr><td><b>Con Acceso Carnal</b></td><td>Acceso por vía vaginal, anal o bucal con fuerza o intimidación.</td></tr>
  <tr><td><b>Estupro</b></td><td>Delito contra la integridad sexual bajo circunstancias específicas de edad.</td></tr>
  <tr><td><b>Grooming</b></td><td>Contacto digital de un adulto con un menor con fines sexuales.</td></tr>
  <tr><td><b>Simple</b></td><td>Atentados contra el pudor o tocamientos sin acceso carnal.</td></tr>
</table>
</details>

<details>
<summary><b>ESTAFA (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;">
    <th align="left">Modalidad</th>
    <th align="left">Descripción y Criterios Operativos</th>
  </tr>
  <tr><td><b>Cuento del Tio</b></td><td>Engaño telefónico o presencial simulando familiares o banco.</td></tr>
  <tr><td><b>Informática</b></td><td>Fraudes por vulneración de sistemas, phishing o cuentas.</td></tr>
  <tr><td><b>MarketPlace</b></td><td>Fraudes en compras por redes sociales y falsas transferencias.</td></tr>
  <tr><td><b>Otros</b></td><td>Demás engaños defraudatorios que no encuadran en las categorías anteriores.</td></tr>
  <tr><td><b>WhatsApp</b></td><td>Secuestro de cuentas de mensajería para pedir dinero.</td></tr>
</table>
</details>

<details>
<summary><b>ESTUPEFACIENTES (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;">
    <th align="left">Modalidad</th>
    <th align="left">Descripción y Criterios Operativos</th>
  </tr>
  <tr><td><b>Comercialización</b></td><td>Venta, fraccionamiento o distribución de sustancias prohibidas.</td></tr>
  <tr><td><b>Consumo</b></td><td>Tenencia en escasa cantidad para uso personal.</td></tr>
  <tr><td><b>Siembra</b></td><td>Cultivo de plantas aptas para producción de drogas.</td></tr>
  <tr><td><b>Tenencia</b></td><td>Posesión de drogas sin justificación de consumo ni venta probada.</td></tr>
</table>
</details>

<details>
<summary><b>HOMICIDIO (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;">
    <th align="left">Modalidad</th>
    <th align="left">Descripción y Criterios Operativos</th>
  </tr>
  <tr><td><b>En ocasión de Robo</b></td><td>Muerte producida con motivo u ocasión de un robo.</td></tr>
  <tr><td><b>Indeterminado</b></td><td>Hecho con causa de muerte bajo investigación preliminar.</td></tr>
  <tr><td><b>Intrafamiliar</b></td><td>Homicidio en el seno familiar o de pareja.</td></tr>
  <tr><td><b>Reyerta</b></td><td>Muerte en pelea tumultuaria sin autor individualizado.</td></tr>
  <tr><td><b>Simple</b></td><td>Homicidio doloso tradicional sin agravantes específicas.</td></tr>
</table>
</details>

<details>
<summary><b>ENCUBRIMIENTO (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;">
    <th align="left">Modalidad</th>
    <th align="left">Descripción y Criterios Operativos</th>
  </tr>
  <tr><td><b>Domicilio Particular</b></td><td>Ocultamiento de efectos procedentes de ilícitos en fincas.</td></tr>
  <tr><td><b>Otro</b></td><td>Otras formas de receptación sospechosa.</td></tr>
  <tr><td><b>Taller</b></td><td>Ocultamiento en talleres mecánicos o de desguace.</td></tr>
  <tr><td><b>Vía Pública</b></td><td>Circulación o tenencia de elementos de dudosa procedencia en la calle.</td></tr>
</table>
</details>

<details>
<summary><b>SUSTRACCIÓN AUTOMOTOR Y MOTOVEHÍCULOS (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;">
    <th align="left">Modalidad</th>
    <th align="left">Descripción y Criterios Operativos</th>
  </tr>
  <tr><td><b>Asalto</b></td><td>Sustracción de vehículo mediante intimidación y violencia directa.</td></tr>
  <tr><td><b>Levantamiento</b></td><td>Sustracción del vehículo estacionado en la vía pública sin moradores ni testigos directos, usualmente mediante el uso de llaves amaestradas, puenteo de cables o remolque.</td></tr>
  <tr><td><b>Motochorro</b></td><td>Sustracción donde los malvivientes se movilizan en motovehículo.</td></tr>
</table>
</details>

<details>
<summary><b>RESTO DE CARÁTULAS Y SIN MODALIDAD (Hacer clic para desplegar)</b></summary>
<br>
<table width="100%" border="1" cellpadding="8" style="border-collapse: collapse;">
  <tr style="background-color: #f6f8fa;">
    <th align="left">Carátula</th>
    <th align="left">Modalidad</th>
    <th align="left">Descripción y Criterios Operativos</th>
  </tr>
  <tr><td><b>Abigeato</b></td><td>Abigeato</td><td>Sustracción de ganado en general.</td></tr>
  <tr><td><b>Abigeato</b></td><td>Faena</td><td>Sustracción de ganado y faena clandestina en el lugar.</td></tr>
  <tr><td><b>Abuso de Arma</b></td><td>Abuso de Arma</td><td>Disparos de arma de fuego contra personas o bienes sin heridos.</td></tr>
  <tr><td><b>Acopio de Arma de Fuego</b></td><td>Sin Modalidad</td><td>Tenencia ilegal de múltiples armas, piezas o municiones.</td></tr>
  <tr><td><b>Adulteración de Arma</b></td><td>Sin Modalidad</td><td>Modificación ilegítima de numeración de armas de fuego.</td></tr>
  <tr><td><b>Asociación ilícita</b></td><td>Sin Modalidad</td><td>Organización de tres o más personas para cometer delitos.</td></tr>
  <tr><td><b>Hallazgo</b></td><td>Hallazgo</td><td>Aparición fortuita de elementos varios.</td></tr>
  <tr><td><b>Hallazgo</b></td><td>Automotor / Moto</td><td>Aparición fortuita de rodados con pedido de secuestro.</td></tr>
  <tr><td><b>Ley 24.192</b></td><td>Ley 24.192</td><td>Violencia en espectáculos deportivos.</td></tr>
  <tr><td><b>Ley 25.761</b></td><td>Autopartes</td><td>Infracciones en desarmaderos y comercio de autopartes.</td></tr>
  <tr><td><b>Lesiones</b></td><td>Sin Modalidad</td><td>Afecciones a la integridad física, con o sin empleo de armas u objetos (leves, graves, gravísimas).</td></tr>
  <tr><td><b>Ley 12.569</b></td><td>Ley 12.569</td><td>Violencia familiar y de género en el ámbito doméstico.</td></tr>
  <tr><td><b>Piratería</b></td><td>Piratas del Asfalto</td><td>Asaltos organizados a camiones de carga en rutas de mercadería de alto valor.</td></tr>
  <tr><td><b>Piratería</b></td><td>Urbanos</td><td>Asaltos organizados a vehículos de reparto urbano de mercadería de alto valor.</td></tr>
  <tr><td><b>Portación de Arma</b></td><td>Arma de Guerra / Uso Civil</td><td>Portación ilegítima de armas listas para su uso en la vía pública.</td></tr>
  <tr><td><b>Privación Ilegal</b></td><td>Sin Modalidad</td><td>Retención o encierro de una persona contra su voluntad.</td></tr>
  <tr><td><b>Suicidio</b></td><td>Civil / Policial</td><td>Determinación de autoeliminación (civil o fuerza policial).</td></tr>
  <tr><td><b>Tenencia de Arma</b></td><td>Tenencia de Arma</td><td>Posesión de armas sin la debida habilitación legal.</td></tr>
  <tr><td><b>Usurpación</b></td><td>Sin Modalidad</td><td>Ocupación ilegal de inmuebles o terrenos.</td></tr>
</table>
</details>

</div>

<script>
function filtrarGuia() {
  let input = document.getElementById('buscadorGuia');
  let filtro = input.value.toLowerCase();
  let detalles = document.getElementsByTagName('details');

  for (let i = 0; i < detalles.length; i++) {
    let detalle = detalles[i];
    if (i === 0) continue; // Omitimos el primer details que corresponde a la guía de campos superior

    let filas = detalle.getElementsByTagName('tr');
    let encontroEnDetalle = false;

    if (filtro === "") {
      detalle.open = (i === 1); // Deja abierto solo el primero de carátulas (Robo) por comodidad
      detalle.style.display = "";
      for (let j = 1; j < filas.length; j++) {
        filas[j].style.display = "";
      }
      continue;
    }

    for (let j = 1; j < filas.length; j++) {
      let fila = filas[j];
      let textoFila = fila.textContent.toLowerCase();

      if (textoFila.indexOf(filtro) > -1) {
        fila.style.display = "";
        encontroEnDetalle = true;
      } else {
        fila.style.display = "none";
      }
    }

    if (encontroEnDetalle) {
      detalle.open = true;
      detalle.style.display = "";
    } else {
      detalle.style.display = "none";
    }
  }
}
</script>
