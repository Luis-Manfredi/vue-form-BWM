
<template>

    <form action="">
        <div class="form-field">
            <label for="businessName">Nombre de la marca</label>
            <input type="text" id="businessName" name="businessName" style="width: 350px" placeholder="Nombre de la marca">
        </div>

        <div class="form-field">
            <label for="rif">RIF (Si aplica)</label>
            <input type="text" id="rif" name="rif" style="width: 350px" placeholder="V00000000">
        </div>

        <div class="form-field">
            <label for="description">Breve descripción del servicio</label>
            <input type="text" id="description" name="description" style="width: 350px" placeholder="De lo micro a lo macro">
        </div>

        <div class="form-field">
            <label for="date">Fecha de fundación / Aniversario</label>
            <input type="date" id="date" name="date" style="width: 350px" placeholder="">
        </div>

        <div class="form-field">
            <label for="nameMeaning">Significado del nombre</label>
            <input type="text" id="nameMeaning" name="nameMeaning" style="width: 350px" placeholder="Significado del nombre">
        </div>

        <div class="form-field">
            <label for="threeWords">¿Cómo describirías tu marca en tres palabras?</label>
            <input type="text" id="threeWords" name="threeWords" style="width: 350px" placeholder="Describa su marca con tres palabras">
        </div>

        <div class="form-field">
            <label for="services">Servicio mas vendido</label>
            <input type="text" id="services" name="services" style="width: 350px" placeholder="Servicio mas vendido">
        </div>

        <button type="submit" class="submit_btn" style="margin-top: 20px">Siguiente</button>
    </form>

</template>

<style>

</style>