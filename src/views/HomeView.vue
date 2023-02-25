<template>

 <div class="bg-dark text-center text-light p-5 text-sm-start" >
  <div class="container">
      <div class="text-center text-light p-5 text-sm-start">
        <div class="container">
          <div class="d-sm-flex align-items-center justify-content-between">
            <div>
              <h1><span class="text-warning">Sheba Online </span> <span class="text-success">Art Gallery</span></h1>
          <p class="lead my-4">
              Welcome to Art Gallery, a digital art gallery showcasing works from various artists. Explore our
              website for an eclectic selection of artwork, featuring original pieces from emerging and
              established creators. Find inspiration in the beauty of the creative pieces and enjoy an
              immersive experience!
            </p>
            <router-link class="btn btn-primary btn-lg" to="/signup">Join Our Community</router-link>
          </div>
          <img
              :src="require('../assets/img/big-bang.png')"
              class="img-fluid w-40 d-none d-sm-block"
              style="width:900px;height:500px;"
                alt="Hot Air Balloons"
              />
        </div>
        </div>
      </div>
      </div>
  </div>

  
  <section id="artist" class="p-5 bg-light">
    <div class="container">
      <h2 class="text-center text-black">Popular Artists</h2>
      <p class="lead text-center text-black mb-5">
        Artists in our Website , all are creative and exprienced
      </p>
      <div class="row g-4">
        <div class="col-md-6 col-lg-3">
          <div class="card bg-light">
            <div class="card-body text-center">
              <img :src="require('../assets/img/bini.jpg')"  
              style="width:180px;height:180px;overflow:hidden;border-radius:50%;" class="rounded-circle mb-3" alt="" />
              <h3 class="card-title mb-3">Beneyam Legese</h3>
              <p class="card-text">
                I am an experienced painter with a passion for bringing life to walls, doors and furniture. 
                I love creating vibrant landscapes and abstract designs that bring a sense of joy and 
                colorful expression to any room or outdoor space.With my expertise, 
                I can help you make remarkable transformations with any interior wallpainting project.
              </p>
              <a href="#"><i class="bi bi-twitter text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-facebook text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-linkedin text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-instagram text-dark mx-1"></i></a>
            </div>
          </div>
        </div>

        <div class="col-md-6 col-lg-3">
          <div class="card bg-light">
            <div class="card-body text-center">
              <img :src="require('../assets/img/bekam.jpg')"  style="width:180px;height:180px;overflow:hidden;border-radius:50%;" class="rounded-circle mb-3" alt="" />
              <h3 class="card-title mb-3">Bereket Getachew</h3>
              <p class="card-text">
                I am a painter who values creating artwork that resonates with people's emotions and imaginations.
                Creating beautiful works of art gives me joy, and I enjoy exploring new techniques and materials to
                craft unique creations. My favorite style is realism, but I have also experimented in abstract and
                surrealism. Art making is my passion, my life's purpose, and I feel grateful to be able to share it with
                the world.
              </p>
              <a href="#"><i class="bi bi-twitter text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-facebook text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-linkedin text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-instagram text-dark mx-1"></i></a>
            </div>
          </div>
        </div>

        <div class="col-md-6 col-lg-3">
          <div class="card bg-light">
            <div class="card-body text-center">
              <img :src="require('../assets/img/mekdem.jpg')"  style="width:180px;height:180px;overflow:hidden;border-radius:50%;" class="rounded-circle mb-3" alt="" />
              <h3 class="card-title mb-3">Mekdem Alemu</h3>
              <p class="card-text">
                I am a painter with an eye for detail, color and texture. 
                I take great pride in my work and strive to create beautiful artwork that captures the essence of what is being portrayed.
                My specializes lie in landscapes and still life paintings, but I am always open to new ideas.
               I approach each piece with dedication and creativity, ensuring that the finished product will be something to be cherished.
              </p>
              <a href="#"><i class="bi bi-twitter text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-facebook text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-linkedin text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-instagram text-dark mx-1"></i></a>
            </div>
          </div>
        </div>

        <div class="col-md-6 col-lg-3">
          <div class="card bg-light">
            <div class="card-body text-center">
              <img :src="require('../assets/img/miki.jpg')"  style="width:180px;height:180px;overflow:hidden;border-radius:50%;" class="rounded-circle mb-3" alt="" />
              <h3 class="card-title mb-3">Micheal Getahun</h3>
              <p class="card-text">
                I am a painter who values creating artwork that resonates with people's emotions and imaginations.
                Creating beautiful works of art gives me joy, and I enjoy exploring new techniques and materials to
                craft unique creations. My favorite style is realism, but I have also experimented in abstract and
                surrealism. Art making is my passion, my life's purpose, and I feel grateful to be able to share it with
                the world.
              </p>
              <a href="#"><i class="bi bi-twitter text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-facebook text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-linkedin text-dark mx-1"></i></a>
              <a href="#"><i class="bi bi-instagram text-dark mx-1"></i></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

<!-- artworks section -->

  <section id="artwork" class="p-5">
    <div class="container">
      <h2 class="text-center text-black">Categories</h2>
      <p class="lead text-center text-black mb-5">
        Artists in our Website , all are creative and exprienced
      </p>
      <div class="row text-center g-4">

        <div class="col-md">
          <div class="card bg-dark text-light">
            <div class="card-body text-center">
              <div class="h1 mb-3">
                <img class="img-fluid w-40 d-none d-sm-block" :src="require('../assets/img/face.jpg')" style="width:400px;height:300px;overflow:hidden;" alt="">
              </div>
              <h3 class="card-title mb-3">Paintings</h3>
              <p class="card-text">
                Paintings are artworks created by applying various mediums—pigments, oil paint, inks, watercolors,
                etc.—onto a two-dimensional surface such as a canvas, paper, or board. Paintings range from
                representational and abstract works of art to religious imagery. The goal of a painting is to express
                ideas and emotions that the artist has.
              </p>
                <router-link class="btn btn-success" to="/artworks">See more</router-link>
            </div>
          </div>
        </div>

        <div class="col-md">
          <div class="card bg-dark text-light">
            <div class="card-body text-center">
              <div class="h1 mb-3">
                <img class="img-fluid w-40 d-none d-sm-block" :src="require('../assets/img/imana.jpg')" style="width:400px;height:300px;overflow:hidden;" alt="">
                <!--<i class="bi bi-person-square"></i>-->
              </div>
              <h3 class="card-title mb-3">Cultural</h3>
              <p class="card-text">
                Cultural paintings are artwork that depict the culture of a particular time or place. These works can
                include traditional art forms such as murals, illustrations, sketches, and popular art. Cultural
                paintings often feature images of people, events, customs, values, ideas, and symbols associated with
                that specific tribe or country.
              </p>
              <router-link class="btn btn-success" to="/artworks">See more</router-link>
            </div>
          </div>
        </div>

        <div class="col-md">
          <div class="card bg-dark text-light">
            <div class="card-body text-center">
              <div class="h1 mb-3">
                <img class="img-fluid w-40 d-none d-sm-block" :src="require('../assets/img/body-painting.jpg')"
                style="width:400px;height:300px;overflow:hidden;" alt="">
                <!--<i class="bi bi-people"></i>-->
              </div>
              <h3 class="card-title mb-3">Artistic</h3>
              <p class="card-text">
                Artistic painting is an expression of emotions, ideas, and experiences created with visual media. It may
                involve the use of different painting materials such as oil paints, watercolors, acrylics, inks, colored
                pencils, pastels and other mixed media. Artistic painting may also involve abstract or representational
                elements as well as creative expression.
              </p>
              <router-link class="btn btn-success" to="/artworks">See more</router-link>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <section id="questions" class="p-5">
    <div class="container">
      <h2 class="text-center mb-4">Frequently Asked Questions</h2>
      <div class="accordion accordion-flush" id="questions">
        <!-- Item 1 -->
        <div class="accordion-item">
          <h2 class="accordion-header">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#question-one">
              How do I purchase artwork from your gallery?
            </button>
          </h2>
          <div id="question-one" class="accordion-collapse collapse" data-bs-parent="#questions">
            <div class="accordion-body">
              You can purchase artwork from our gallery by navigating to the artwork page, selecting a work of art you
              would like to purchase, and then following the on-screen instructions. If you need help, please contact us
              and one of our team members will be happy to help.
            </div>
          </div>
        </div>
        <!-- Item 2 -->
        <div class="accordion-item">
          <h2 class="accordion-header">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#question-two">
              Does your online art gallery offer returns?
            </button>
          </h2>
          <div id="question-two" class="accordion-collapse collapse" data-bs-parent="#questions">
            <div class="accordion-body">
              Yes, we offer 30-day returns on any artwork purchased directly from our website. Should you wish to return
              an item, please contact us within 30 days of receiving your order with your reason for return and we will
              be more than happy to assist.
            </div>
          </div>
        </div>
        <!-- Item 3 -->
        <div class="accordion-item">
          <h2 class="accordion-header">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#question-three">
              How Do I sign up?
            </button>
          </h2>
          <div id="question-three" class="accordion-collapse collapse" data-bs-parent="#questions">
            <div class="accordion-body">
              To sign up, first you will need to locate the application form or website for the service or product you
              are interested in. After that, fill out the required information and follow any instructions set forth by
              the application. Once you have completed all of the steps, submit your application to get registered and
              receive your login credentials.
            </div>
          </div>
        </div>
<!-- item 5-->
        <div class="accordion-item">
          <h2 class="accordion-header">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#question-four">
              How is the artwork shipped and what are the shipping costs?
            </button>
          </h2>
          <div id="question-four" class="accordion-collapse collapse" data-bs-parent="#questions">
            <div class="accordion-body">
              Artwork is carefully packaged and shipped via a trusted carrier such as FedEx or UPS. 
              Shipping costs are calculated based on the size, weight, and destination of the artwork.
               You can find shipping costs for each artwork on its product page.
            </div>
          </div>
        </div>
   <!-- Item 6 -->
        <div class="accordion-item">
          <h2 class="accordion-header">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#question-five">
              Do you offer custom framing for your artwork?
            </button>
          </h2>
          <div id="question-five" class="accordion-collapse collapse" data-bs-parent="#questions">
            <div class="accordion-body">
              Yes, we offer custom framing for many of our artworks.
               You can select the framing option on the artwork's product page and choose from a variety of frames and matting options.
               If you have any specific framing requests or questions, please contact our customer support team.
            </div>
          </div>
        </div>
        <!-- Item 7 -->
        <div class="accordion-item">
          <h2 class="accordion-header">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
              data-bs-target="#question-six">
              Where are you located ?
            </button>
          </h2>
          <div id="question-six" class="accordion-collapse collapse" data-bs-parent="#questions">
            <div class="accordion-body">
              We are located in Addis ababa, bole sheger house 3rd floor.
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="p-5 bg-dark text-white text-center position-relative">
    <div class="container">
      <p class="lead">Copyright &copy; 2023 Sheba Online Art Gallery</p>

      <a href="#" class="position-absolute bottom-0 end-0 p-5">
        <i class="bi bi-arrow-up-circle h1"></i>
      </a>
    </div>
  </footer>

</template>

<script>

export default {
  name: 'HomeView',
//class="img-fluid w-40 d-none d-sm-block" <img v-if="imageVisible" :alt="imageAltText" :src="imageSource"
}
</script>

<style>
/* Set height to full screen */
body {
  height: 100%;
}


/* Set text color and padding */
/* .overlay {
  color: black;
  padding: 300px 0;
}*/
</style>