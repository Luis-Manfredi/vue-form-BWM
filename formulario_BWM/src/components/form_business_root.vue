<script setup>
    import partOne from "./form_business_one.vue";
    import partTwo from "./form_business_two.vue";
    import partThree from "./form_business_three.vue";
    defineProps({
        title: {
            type: String,
            required: true,
        }
    });
</script>


<template>

    <div class="form-container">
        <!-- <div style="height: 120px"></div> -->

        <div class="content">
            <h3 style="margin-bottom: 20px">{{ title }}</h3>

           <partOne />
            
            <!-- <partTwo /> -->

            <!-- <partThree /> -->

        </div>
    </div>

</template>

<style>
    
    .form_field {
        width: auto;
    }
  
    .title {
        display: flex;
        justify-content: center;
    }
    
</style>