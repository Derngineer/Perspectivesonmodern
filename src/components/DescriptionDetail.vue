<template>
    <div >
             <div class="card border-0" style="max-width: 540px;">
                    <div class="row g-0">
                        <div class="col-md-4">
                        <img src="/smartmockups_lpjq7oyb.jpg" class="img-fluid rounded-circle" alt="book-related">
                        </div>
                        <div class="col-md-8">
                        <div class="card-body">
                            <h3 class="card-title">{{ title }}</h3>
                            <p class="card-text text-wrap">{{ description }}</p>
                            <p class="card-text"><small class="text-body-secondary">{{ conclusion }}</small></p>
                             
                        </div>
                        </div>
                    </div>
                </div>


    </div>
</template>

<script>
    export default {

        name:'DescriptionDetail',
        props: {
            title:{
                type: String,
            },
            description: {
                type: String
            },
            conclusion: {
                type: String,
            }
        }
        
    }
</script>

<style  scoped>
.img-fluid {
    border-radius: 50%;
    width: 150px;
    height: 150px;
  }

  .card {
    /* background: linear-gradient(to bottom, white, #f0f9ff); */
    background: transparent;
    /* box-shadow: 0 4px 8px rgba(0, 0, 0, 0.4); */
    font-family: Poiret one;
    font-size: 24px;
  }

  @media (max-width: 767px) {
  .card {
    font-size: 20px; /* Adjust font size for even smaller screens */
  }
}

</style>