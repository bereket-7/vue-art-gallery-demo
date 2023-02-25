<template>
<section class="h-100 h-custom" style="background-color: #eee;">
  <div class="container py-5 h-100">
    <div class="row d-flex justify-content-center align-items-center h-100">
      <div class="col">
        <div class="card">
          <div class="card-body p-4">

            <div class="row">

              <div class="col-lg-7">
                <h5 class="mb-3"> <router-link class="text-success" to="/artworks"><i
                      class="fas fa-long-arrow-alt-left me-2 text-success"></i>Continue shopping</router-link></h5>
                <hr>

                <div class="d-flex justify-content-between align-items-center mb-5">
                  <div>
                    <p class="mb-2">Shopping cart</p>
                    <p class="mb-0">You have 4 items in your cart</p>
                  </div>

                  <div class="dropdown">
                        <a class="btn btn-success dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Sort By:
                        </a>

                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">price</a></li>
                                <li><a class="dropdown-item" href="#">alphabet</a></li>
                                <li><a class="dropdown-item" href="#">time</a></li>
                            </ul>
                    </div>

                </div>

                <div class="card mb-3">
                  <div class="card-body">
                    <div class="d-flex justify-content-between">
                      <div class="d-flex flex-row align-items-center">
                        <div>
                          <img
                            :src="require('../assets/img/girl.jpg')"
                            class="img-fluid rounded-3" alt="Shopping item" style="width: 65px;">
                        </div>
                        <div class="ms-3">
                          <h5>Textile</h5>
                          <p class="small mb-0">abstract girl face </p>
                        </div>
                      </div>
                      <div class="d-flex flex-row align-items-center">
                        <div style="width: 50px;">
                          <h5 class="fw-normal mb-0">2</h5>
                        </div>
                        <div style="width: 80px;">
                          <h5 class="mb-0">9000</h5>
                        </div>
                        <a href="#!" style="color: #cecece;"><i class="fas fa-trash-alt" style="color:red;"></i></a>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="card mb-3">
                  <div class="card-body">
                    <div class="d-flex justify-content-between">
                      <div class="d-flex flex-row align-items-center">
                        <div>
                          <img
                          :src="require('../assets/img/face.jpg')"
                            class="img-fluid rounded-3" alt="Shopping item" style="width: 65px;">
                        </div>
                        <div class="ms-3">
                          <h5>Photography</h5>
                          <p class="small mb-0">abstact face</p>
                        </div>
                      </div>
                      <div class="d-flex flex-row align-items-center">
                        <div style="width: 50px;">
                          <h5 class="fw-normal mb-0">1</h5>
                        </div>
                        <div style="width: 80px;">
                          <h5 class="mb-0">9500</h5>
                        </div>
                        <a href="#!" style="color: #cecece;"><i class="fas fa-trash-alt" style="color:red;"></i></a>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="card mb-3">
                  <div class="card-body">
                    <div class="d-flex justify-content-between">
                      <div class="d-flex flex-row align-items-center">
                        <div>
                          <img
                           :src="require('../assets/img/steel.jpg')"
                            class="img-fluid rounded-3" alt="Shopping item" style="width: 65px;">
                        </div>
                        <div class="ms-3">
                          <h5>steel work</h5>
                          <p class="small mb-0">artistic steel work</p>
                        </div>
                      </div>
                      <div class="d-flex flex-row align-items-center">
                        <div style="width: 50px;">
                          <h5 class="fw-normal mb-0">1</h5>
                        </div>
                        <div style="width: 80px;">
                          <h5 class="mb-0">5500</h5>
                        </div>
                        <a href="#!" style="color: #cecece;"><i class="fas fa-trash-alt" style="color:red;"></i></a>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="card mb-3 ">
                  <div class="card-body">
                    <div class="d-flex justify-content-between">
                      <div class="d-flex flex-row align-items-center">
                        <div>
                          <img
                          :src="require('../assets/img/monaliza.jpg')"
                            class="img-fluid rounded-3" alt="Shopping item" style="width: 65px;">
                        </div>
                        <div class="ms-3">
                            <h5>Monaliza</h5>
                          <p class="small mb-0">painting</p>
                        </div>
                      </div>
                    
                      <div class="d-flex flex-row align-items-center">
                        <div style="width: 50px;">
                          <h5 class="fw-normal mb-0">1</h5>
                        </div>
                
                        <div style="width: 80px;">
                          <h5 class="mb-0">10000</h5>
                        </div>
                        <a href="#!" style="color: #cecece;"><i class="fas fa-trash-alt" style="color:red;"></i></a>
                        </div>
                  </div>
                  </div>
                </div>


              </div>


              <div class="col-lg-5">
                <div class="card bg-dark text-white rounded-3">
                  <div class="card-body">
                    <div class="d-flex justify-content-between align-items-center mb-4">
                      <h5 class="mb-0">Card details</h5>
                      <img :src="require('../assets/img/bini.jpg')"
                        class="img-fluid rounded-3" style="width: 45px;" alt="Avatar">
                    </div>

                    <p class="small mb-2">Card type</p>
                    <a href="#!" type="submit" class="text-white"><i
                        class="fab fa-cc-mastercard fa-2x me-2"></i></a>
                    <a href="#!" type="submit" class="text-white"><i
                        class="fab fa-cc-visa fa-2x me-2"></i></a>
                    <a href="#!" type="submit" class="text-white"><i
                        class="fab fa-cc-amex fa-2x me-2"></i></a>
                    <a href="#!" type="submit" class="text-white"><i class="fab fa-cc-paypal fa-2x"></i></a>

                    <form class="mt-4">
                      <div class="form-outline form-white mb-4">
                        <input type="text" id="typeName" class="form-control form-control-lg" size="17"
                          placeholder="Cardholder's Name" />
                      </div>

                      <div class="form-outline form-white mb-4">
                        <input type="text" id="typeText" class="form-control form-control-lg" size="17"
                          placeholder="Card number" minlength="19" maxlength="19" />
                      </div>

                      <div class="row mb-4">
                        <div class="col-md-6">
                          <div class="form-outline form-white">
                            <input type="text" id="typeExp" class="form-control form-control-lg"
                              placeholder="MM/YYYY" size="7" minlength="7" maxlength="7" />
                          </div>
                        </div>
                        <div class="col-md-6">
                          <div class="form-outline form-white">
                            <input type="password" id="typeText" class="form-control form-control-lg"
                              placeholder="&#9679;&#9679;&#9679;&#9679;" size="1" minlength="4" maxlength="4" />
                          </div>
                        </div>
                      </div>

                    </form>

                    <hr class="my-4">

                    <div class="d-flex justify-content-between">
                      <p class="mb-2">Subtotal</p>
                      <p class="mb-2">ETB15798.00</p>
                    </div>

                    <div class="d-flex justify-content-between">
                      <p class="mb-2">Shipping</p>
                      <p class="mb-2">ETB500.00</p>
                    </div>

                    <div class="d-flex justify-content-between mb-4">
                      <p class="mb-2">Total(Incl. taxes)</p>
                      <p class="mb-2">ETB16278.00</p>
                    </div>

                    <button type="button" class="btn btn-success btn-block btn-lg">
                      <div class="d-flex justify-content-between">
                        <span>ETB16278.00</span>
                        <span>Checkout <i class="fas fa-long-arrow-alt-right ms-2"></i></span>
                      </div>
                    </button>

                  </div>
                </div>

              </div>

            </div>

          </div>
        </div>
      </div>
    </div>
  </div>
</section>



</template>

<script>
import ShippingCart from '@/components/ShippingCart.vue';
export default {
    name:'CartView',
    component:{
        ShippingCart
    }

}
</script>

<style scoped>
    
</style>