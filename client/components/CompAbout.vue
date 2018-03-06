<template>
    <li :class="this.inverted? 'timeline-inverted':''">

        <div class="timeline-image">
            <img class="rounded-circle img-fluid" :src="this.image" alt="">
        </div>
        <div class="timeline-panel">
            <div class="timeline-heading">
                <h4>{{this.age}}</h4>
                <h4 class="subheading">{{this.title}}</h4>
            </div>
            <div class="timeline-body">
                <p class="text-muted">{{this.description}}</p>
            </div>
        </div>
    </li>
        
    
</template>

<script>
export default {
  props: [
      'image',
      'age',
      'title',
      'description',
      'inverted'
  ]
}
</script>

