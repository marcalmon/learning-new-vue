<template>
    <div class="col-md-4 col-sm-6 portfolio-item">
        <a class="portfolio-link" data-toggle="modal" href="#portfolioModal1">
        <div class="portfolio-hover">
            <div class="portfolio-hover-content">
                <i class="fa fa-plus fa-3x"></i>
            </div>
        </div>
            <img class="img-fluid" :src="this.image" alt="">
        </a>
        <div class="portfolio-caption">
            <h4>{{this.title}}</h4>
            <p class="text-muted">{{this.description}}</p>
        </div>
    </div>
    
</template>

<script>
export default {
  props: [
      'image',
      'title',
      'description'
  ]
}
</script>

