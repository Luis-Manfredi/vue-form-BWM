<script setup>
    defineProps({
        message: {
            type: String, 
            required: true
        }, 
    });
</script>


<template>

    <div class="form-container">
        
        <div class="content">
            <p><strong>Primero lo primero:</strong> {{ message }}</p>

            <form action="">
            <div class="row-form">
                <div class="form-field">
                <label for="firstName">Nombre</label>
                <input type="text" id="firstName" name="firstName" placeholder="Nombre">
                </div>
                <div class="form-field">
                <label for="lastName">Apellido</label>
                <input type="text" id="lastName" name="lastName" placeholder="Apellido">
                </div>
            </div>

            <div class="form-field">
                <label for="address">Dirección</label>
                <input type="text" id="address" name="address" style="width: 350px" placeholder="Dirección">
            </div>


            <div class="form-field">
                <label for="dropdownButton">Número de teléfono</label>
                <div class="row-form">
                <select name="dropdownButton" id="dropdown_btn">
                    <option value="0412">0412</option>
                    <option value="0414">0414</option>
                    <option value="0416">0416</option>
                    <option value="0424">0424</option>
                </select>
                <div style="width: 20px"></div>
                <label for="phone" style="display: none;">Teléfono</label>
                <input type="text" id="phone" name="phone" style="width: 260px" placeholder="1234567">
                </div>
            </div>


            <div class="form-field">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" style="width: 350px" placeholder="ejemplo@ejemplo.com">
            </div>

            <button type="submit" class="submit_btn" style="margin-top: 20px">Siguiente</button>
            </form>
        </div>    
    </div>

</template>

<style>

  .form-container {
    display: flex;
    flex-direction: column;
    position: relative;
    height: 100%;
    width: 600px;
    color: black;
    text-align: center;
  }

  .form-container p {
    margin: 0 auto;
  }

  form {
    margin: 20px auto;
    margin-bottom: auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 400px;
  }

  select {
    margin-top: 5px;
    padding: 0 10px;
    border: none;
    border-radius: 8px;
    background-color:  rgba(2, 171, 164, 0.20);
  }

  select:focus {
    outline-color: #02aba4;
  }

  .form-field {
    width: 170px;
    display: flex;
    align-items: flex-start;
    flex-direction: column;
    padding: 10px;
  }

  .row-form {
    display: flex;
    flex-direction: row;
    justify-content: start;
  }

  label {
    font-size: 14px;
  }

  input {
    padding: 0 10px;
    margin-top: 5px;
    height: 30px;
    border-width: 1px;
    border-color: rgba(0, 0, 0, 0.25);
    border-radius: 8px;
    border: none;
    background-color: rgba(2, 171, 164, 0.20);
  }

  input:focus{
    outline-color: #02aba4;
    border-width: 2px;
    border-radius: 8px;
  }

</style>