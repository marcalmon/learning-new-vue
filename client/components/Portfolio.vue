<template>
    <section class="bg-light" id="portfolio">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Portfolio</h2>
            <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
          </div>
        </div>
        <div class="row">
            <ImgPort image="/img/portfolio/01-thumbnail.jpg" title="Threads" description="Illustration" />
            <ImgPort image="/img/portfolio/02-thumbnail.jpg" title="Explore" description="Graphic Design" />
            <ImgPort image="/img/portfolio/03-thumbnail.jpg" title="Finish" description="Identify" />
        </div>
        <div class="row">
            <ImgPort image="/img/portfolio/04-thumbnail.jpg" title="Lines" description="Branding" />
            <ImgPort image="/img/portfolio/05-thumbnail.jpg" title="Southwest" description="Website Design" />
            <ImgPort image="/img/portfolio/06-thumbnail.jpg" title="Window" description="Photography" />
        </div>
      </div>
    </section>
</template>

<script>
import ImgPort from 'components/ImgPort'

export default {
  components: {
      ImgPort
  }
}
</script>

