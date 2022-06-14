
<script></script>

<template>

    <form action="">
        <div class="form-field">
            <label for="workHour">Horario de atención al cliente</label>
            <input type="text" id="workHour" name="workHour" style="width: 350px" placeholder="Horario de atención al público">
        </div>

        <div class="form-field">
            <label for="payments">Métodos de pago (Si aplica)</label>
            <input type="text" id="payments" name="payments" style="width: 350px" placeholder="Métodos de pago">
        </div>

        <div class="form-field">
            <label for="media">Sitio web o canales activos</label>
            <input type="text" id="media" name="media" style="width: 350px" placeholder="Sitio web o canales activos">
        </div>

        <div class="form-field">
            <label for="eventsList">Listado de eventos</label>
            <input type="text" id="eventsList" name="eventsList" style="width: 350px" placeholder="¿Cúal es el target habitual?">
        </div>

        <div class="form-field">
            <label for="support">Canales de atención online</label>
            <input type="text" id="support" name="support" style="width: 350px" placeholder="Canales de atención online">
        </div>

        <div class="form-field">
            <label for="menuList">Menú o lista de precios</label>
            <input type="file" id="menuList" name="menuList" placeholder="">
        </div>

        <div class="form-field">
            <label for="radio">Posicionamiento digital de tu marca</label>
            <div class="row-form">
                <div class="column-form">
                    <label for="radio_btn">1</label>
                    <input type="radio" id="radio" name="radio_btn">
                </div>
                <div class="column-form">
                    <label for="radio_btn">2</label>
                    <input type="radio" id="radio" name="radio_btn">
                </div>
                <div class="column-form">
                    <label for="radio_btn">3</label>
                    <input type="radio" id="radio" name="radio_btn">
                </div>
                <div class="column-form">
                    <label for="radio_btn">4</label>
                    <input type="radio" id="radio" name="radio_btn">
                </div>
                <div class="column-form">
                    <label for="radio_btn">5</label>
                    <input type="radio" id="radio" name="radio_btn">
                </div>
                <div class="column-form">
                    <label for="radio_btn">6</label>
                    <input type="radio" id="radio" name="radio_btn">
                </div>
                <div class="column-form">
                    <label for="radio_btn">7</label>
                    <input type="radio" id="radio" name="radio_btn">
                </div>
                <div class="column-form">
                    <label for="radio_btn">8</label>
                    <input type="radio" id="radio" name="radio_btn">
                </div>
                <div class="column-form">
                    <label for="radio_btn">9</label>
                    <input type="radio" id="radio" name="radio_btn">
                </div>
                <div class="column-form">
                    <label for="radio_btn">10</label>
                    <input type="radio" id="radio" name="radio_btn">
                </div>
            </div>
        </div>


        <button type="submit" class="submit_btn" style="margin-top: 20px; margin-bottom: 20px">Siguiente</button>
    </form>

</template>

<style>

    #partners {
        padding: 0;
        border-radius: 1px;
        height: auto;
    }

    input[type="radio"] {

        height: 25px;
        width: 25px;
    }

    .form-container {
        justify-content: center;
    }

    .form-field {
        width: auto;
    }

    .column-form {
        margin-top: 10px;
        display: flex;
        flex-direction: column;
    }

</style>