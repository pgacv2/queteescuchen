---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Nuestra Asamblea Legislativa tiene [49 representantes](http://www.tucamarapr.org/dnncamara/ComposiciondelaCamara/Biografia.aspx) y [30 senadores](https://senado.pr.gov/Pages/Senadores.aspx). ¿Cuántos de ellos realmente representan *tus* intereses? ¿Cuándo fue la última vez que les dejaste saber lo que *tú* quieres?
============


**{{ site.title }}** te permite enviarle cartas (¡físicas, no email!) a tus legisladores para que sepan lo que *tú*,
como constituyente, quieres que ellos hagan.

<form method="post" action="https://formspree.io/queteescuchen@queteescuchen.pedroacevedo.pr">
    <input type="text" name="name" required="required" autofocus="autofocus" maxlength="50" style="width:40%" placeholder="Tu nombre completo"><br />
    <input type="email" name="email" maxlength="50" style="width:40%" placeholder="Tu correo electrónico (opcional)"><br />
    <input type="text" name="address_1" required="required" maxlength="100" style="width:40%" placeholder="Línea #1 de tu dirección física"><br />
    <input type="text" name="address_2" maxlength="100" style="width:40%" placeholder="Línea #2 de tu dirección física (opcional)"><br />
    <select name="city" required="required">
        <option value="Adjuntas">Adjuntas</option>
        <option value="Aguada">Aguada</option>
        <option value="Aguadilla">Aguadilla</option>
        <option value="Aguas Buenas">Aguas Buenas</option>
        <option value="Aibonito">Aibonito</option>
        <option value="Añasco">Añasco</option>
        <option value="Arecibo">Arecibo</option>
        <option value="Arroyo">Arroyo</option>
        <option value="Barceloneta">Barceloneta</option>
        <option value="Barranquitas">Barranquitas</option>
        <option value="Bayamón">Bayamón</option>
        <option value="Cabo Rojo">Cabo Rojo</option>
        <option value="Caguas">Caguas</option>
        <option value="Camuy">Camuy</option>
        <option value="Canóvanas">Canóvanas</option>
        <option value="Carolina">Carolina</option>
        <option value="Cataño">Cataño</option>
        <option value="Cayey">Cayey</option>
        <option value="Ceiba">Ceiba</option>
        <option value="Ciales">Ciales</option>
        <option value="Cidra">Cidra</option>
        <option value="Coamo">Coamo</option>
        <option value="Comerio">Comerio</option>
        <option value="Corozal">Corozal</option>
        <option value="Culebra">Culebra</option>
        <option value="Dorado">Dorado</option>
        <option value="Fajardo">Fajardo</option>
        <option value="Florida">Florida</option>
        <option value="Guánica">Guánica</option>
        <option value="Guayama">Guayama</option>
        <option value="Guayanilla">Guayanilla</option>
        <option value="Guaynabo">Guaynabo</option>
        <option value="Gurabo">Gurabo</option>
        <option value="Hatillo">Hatillo</option>
        <option value="Hormigueros">Hormigueros</option>
        <option value="Humacao">Humacao</option>
        <option value="Isabela">Isabela</option>
        <option value="Jayuya">Jayuya</option>
        <option value="Juana Díaz">Juana Díaz</option>
        <option value="Juncos">Juncos</option>
        <option value="Lajas">Lajas</option>
        <option value="Lares">Lares</option>
        <option value="Las Marías">Las Marías</option>
        <option value="Las Piedras">Las Piedras</option>
        <option value="Loíza">Loíza</option>
        <option value="Luquillo">Luquillo</option>
        <option value="Manatí">Manatí</option>
        <option value="Maricao">Maricao</option>
        <option value="Maunabo">Maunabo</option>
        <option value="Mayagüez">Mayagüez</option>
        <option value="Moca">Moca</option>
        <option value="Morovis">Morovis</option>
        <option value="Naguabo">Naguabo</option>
        <option value="Naranjito">Naranjito</option>
        <option value="Orocovis">Orocovis</option>
        <option value="Patillas">Patillas</option>
        <option value="Peñuelas">Peñuelas</option>
        <option value="Ponce">Ponce</option>
        <option value="Quebradillas">Quebradillas</option>
        <option value="Rincón">Rincón</option>
        <option value="Río Grande">Río Grande</option>
        <option value="Sabana Grande">Sabana Grande</option>
        <option value="Salinas">Salinas</option>
        <option value="San Germán">San Germán</option>
        <option value="San Juan">San Juan</option>
        <option value="San Lorenzo">San Lorenzo</option>
        <option value="San Sebastián">San Sebastián</option>
        <option value="Santa Isabel">Santa Isabel</option>
        <option value="Toa Alta">Toa Alta</option>
        <option value="Toa Baja">Toa Baja</option>
        <option value="Trujillo Alto">Trujillo Alto</option>
        <option value="Utuado">Utuado</option>
        <option value="Vega Alta">Vega Alta</option>
        <option value="Vega Baja">Vega Baja</option>
        <option value="Vieques">Vieques</option>
        <option value="Villalba">Villalba</option>
        <option value="Yabucoa">Yabucoa</option>
        <option value="Yauco">Yauco</option>
    </select>
    <input type="text" name="zip" required="required" maxlength="10000" placeholder="Tu código zip"><br />
    <textarea name="message" required="required" rows="15" cols="80" placeholder='Tu mensaje. Enviaremos hasta dos páginas de texto (aproximadamente 1,000 palabras) por carta, así que puedes escribir todo lo que quieras.

Puedes omitir la introducción ("Estimado(a) representante...") y la despedida ("Atentamente, yo"). Nosotros se lo añadiremos automáticamente a la carta.'></textarea><br />
    Deseo enviarle esta carta a:<br />
    <input type="checkbox" name="send_dist_rep">Mi representante de distrito ({{ site.letter_cost }})<br />
    <input type="checkbox" name="send_dist_sen">Mi senador(a) de distrito ({{ site.letter_cost }})
    <p style="margin-top:1em">Envía tu pago por ATH Móvil al {{ site.ath_movil }}.</p>
    <button type="submit">Enviar</button>
</form>
