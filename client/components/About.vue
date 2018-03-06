<template>
    
    <section id="about">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center">
                    <h2 class="section-heading text-uppercase">About</h2>
                    <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-12">
                    <ul class="timeline">
                        <CompAbout />
                        <CompAbout inverted="true" />
                        <CompAbout />
                        <CompAbout inverted="true" />
                        <CompAbout />
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import CompAbout from 'components/CompAbout'

export default {
    components: {
        CompAbout
    }
  
}
</script>


