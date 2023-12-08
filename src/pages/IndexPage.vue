<template>
  <q-page class="bg-gray-100">
    <!--cover pic-->
    <q-carousel
      animated
      v-model="slide"
      navigation
      infinite
      :autoplay="true"
      :timeout="2000"
      arrows
      transition-prev="slide-right"
      transition-next="slide-left"
      @mouseenter="autoplay = false"
      @mouseleave="autoplay = true"
    >
      <q-carousel-slide
        :name="1"
        img-src="https://i.pinimg.com/originals/4d/e8/b3/4de8b3f6309e6563671312ec443c09c1.jpg"
        alt="Slide 1"
      />
      <q-carousel-slide
        :name="2"
        img-src="https://shavershianfitness.com/cdn/shop/files/C_J-2080.jpg?v=1688722731"
        alt="Slide 2"
      />
      <q-carousel-slide
        :name="3"
        img-src="https://ae01.alicdn.com/kf/H98d2bcd137d44da0899751681ce7c5531.jpg_640x640Q90.jpg_.webp"
        alt="Slide 3"
      />
      <q-carousel-slide
        :name="4"
        img-src="https://i.pinimg.com/736x/05/28/b2/0528b24c24526cbdbb28ba1031108491.jpg"
        alt="Slide 4"
      />
    </q-carousel>
    <!--cover pic finish-->
    <div
      class="bg-orange-700 text-2xl text-bold text-center py-3"
      id="color-changing-text"
    >
      Get Unlimited Offer
    </div>

    <div class="flex row mx-2 my-4 gap-1">
      <div class="col">
        <div class="my-card h-[90px] w-[90px] rounded-full flip-card">
          <div class="flip-card-inner">
            <img
              class="flip-card-front relative h-[90px] w-[90px] rounded-full overflow-hidden"
              src="https://5.imimg.com/data5/SELLER/Default/2023/1/RR/KJ/UE/102058255/shimak-casual-shirts-printed-full-sleeve-500x500.jpeg"
              alt="Front Image"
            />

            <div class="flip-card-back absolute rounded-full">
              <div class="back-content">
                <p>30% OFF!</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="my-card h-[90px] w-[90px] rounded-full flip-card">
          <div class="flip-card-inner">
            <img
              class="flip-card-front relative h-[90px] w-[90px] rounded-full overflow-hidden"
              src="https://images.pexels.com/photos/428311/pexels-photo-428311.jpeg?cs=srgb&dl=pexels-spencer-selover-428311.jpg&fm=jpg"
              alt="Front Image"
            />

            <div class="flip-card-back absolute rounded-full">
              <div class="back-content">
                <p>10% OFF!</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="col">
        <div class="my-card h-[90px] w-[90px] rounded-full flip-card">
          <div class="flip-card-inner">
            <img
              class="flip-card-front relative h-[90px] w-[90px] rounded-full overflow-hidden"
              src="https://masculine.com.bd/cdn/shop/files/WhatsAppImage2023-08-23at4.00.28PM_533x.jpg?v=1692789842"
              alt="Front Image"
            />

            <div class="flip-card-back absolute rounded-full">
              <div class="back-content">
                <p>15% OFF!</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="col">
        <div class="my-card h-[90px] w-[90px] rounded-full flip-card">
          <div class="flip-card-inner">
            <img
              class="flip-card-front relative h-[90px] w-[90px] rounded-full overflow-hidden"
              src="https://pbs.twimg.com/media/Cwgdk57WEAAo3LP.jpg:large"
              alt="Front Image"
            />

            <div class="flip-card-back absolute rounded-full">
              <div class="back-content">
                <p>20% OFF!</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="q-gutter-md row items-start"></div>
    <!--cover pic-->

    <div
      class="text-white text-center text-2xl animate-pulse mx-14 rounded-full mb-4 md:ml-10 py-3 bg-lime-600 mt-3"
    >
      catafories
    </div>
    <!--all categoeies decorated here-->
    <div class="flex overflow-x-auto flex-row-reverse">
      <!-- Your existing code for each item goes here -->

      <!-- Repeat the above div for other items -->
    </div>

    <div class="grid grid-cols-3 gap-2 mx-2 md:mx-10">
      <!--first card-->
      <q-card
        class="my-card col flex md:px-3 bg-slate-200 shadow-box"
        label="Card"
        @click="card1 = true"
      >
        <img
          class="w-full h-48 object-cover diamond-image"
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS1kbigyXlXl-xIuQ2_ITwiDFLgvuTNEELh5A&usqp=CAU"
        />

        <div class="text-slate-600 py-2">
          <div class="text-sm mx-2">Calvin Klein</div>
          <div class="text-subtitle2 mx-2">$19</div>
        </div>
      </q-card>

      <!--second card-->
      <q-card
        class="my-card col flex md:px-3 bg-slate-200 shadow-box"
        label="Card"
        @click="card2 = true"
      >
        <img class="w-full h-48 object-cover" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQV2Ax-bQL5OYxJrLktkukBXHYxsBg-tLvdjA42RRv5RtGP4WY2LKHCqoqM6EtyVZxKDX4&usqp=CAU" />
" />

        <div class="text-slate-600 py-2">
          <div class="text-sm mx-2">Calvin Klein</div>
          <div class="text-subtitle2 mx-2">$19</div>
        </div>
      </q-card>

      <!--third card-->
      <q-card
        class="my-card col flex md:px-3 bg-slate-200 shadow-box"
        label="Card"
        @click="card2 = true"
      >
        <img class="w-full h-48 object-cover" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR6OHfPCu7hf92ap8nkwpGvDb4OKF1tNM8NWg&usqp=CAU" />

        <div class="text-slate-600 py-2">
          <div class="text-sm mx-2">Calvin Klein</div>
          <div class="text-subtitle2 mx-2">$19</div>
        </div>
      </q-card>

      <!--fourth card-->
      <q-card
        class="my-card col flex md:px-3 bg-slate-200 shadow-box"
        label="Card"
        @click="card2 = true"
      >
        <img class="w-full h-48 object-cover" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQeSgeTCTDhBmWipolZWujtE4zWDvZlVEwdsA&usqp=CAU" />

        <div class="text-slate-600 py-2">
          <div class="text-sm mx-2">Calvin Klein</div>
          <div class="text-subtitle2 mx-2">$19</div>
        </div>
      </q-card>

      <!--fifth card-->
      <q-card
        class="my-card col flex md:px-3 bg-slate-200 shadow-box"
        label="Card"
        @click="card2 = true"
      >
        <img class="w-full h-48 object-cover" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSPKILlD0_n1Am5clRQxRefZ9prZxu3VX65hA&usqp=CAU" />

        <div class="text-slate-600 py-2">
          <div class="text-sm mx-2">Calvin Klein</div>
          <div class="text-subtitle2 mx-2">$19</div>
        </div>
      </q-card>

      <!--sixth card-->
      <q-card
        class="my-card col flex md:px-3 bg-slate-200 shadow-box"
        label="Card"
        @click="card2 = true"
      >
        <img class="w-full h-48 object-cover" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSPKILlD0_n1Am5clRQxRefZ9prZxu3VX65hA&usqp=CAU" />

        <div class="text-slate-600 py-2">
          <div class="text-sm mx-2">Calvin Klein</div>
          <div class="text-subtitle2 mx-2">$19</div>
        </div>
      </q-card>

      <!--seventh card-->
      <q-card
        class="my-card col flex md:px-3 bg-slate-200 shadow-box"
        label="Card"
        @click="card2 = true"
      >
        <img class="w-full h-48 object-cover" src="~src/assets/2.jpeg" />

        <div class="text-slate-600 py-2">
          <div class="text-sm mx-2">Calvin Klein</div>
          <div class="text-subtitle2 mx-2">$19</div>
        </div>
      </q-card>

      <!---->
    </div>

    <!--card1-->
    <q-dialog v-model="card1">
      <q-card class="my-card w-[1200px] bg-slate-900">
        <div class="q-pa-md">
          <q-carousel swipeable animated v-model="slide" thumbnails infinite>
            <q-carousel-slide
              :name="1"
              img-src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS1kbigyXlXl-xIuQ2_ITwiDFLgvuTNEELh5A&usqp=CAU"
            />
            <q-carousel-slide
              :name="2"
              img-src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQKPUPO5Onv8DQRRvl8wmDjqqjbrIq-1d6uTQ&usqp=CAU"
            />
            <q-carousel-slide
              :name="3"
              img-src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT9lc8wFy9XMiWW9eVr6jFGgOFnhvyn5NhI7g&usqp=CAU"
            />
            <q-carousel-slide
              :name="4"
              img-src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTecfvaeGiqESEjMiijxF9aTHe9H_k1d0nEAQ&usqp=CAU"
            />
          </q-carousel>
        </div>

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%)"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">Calvin Kleine</div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="place" />
              USA
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">$45</div>
          <div class="text-caption text-grey">Color: Black, White, Yellow.</div>
        </q-card-section>

        <q-separator />

        <q-card-actions align="right">
          <q-btn v-close-popup flat color="primary" label="close" />
        </q-card-actions>
      </q-card>
    </q-dialog>

    <!--card2-->
    <q-dialog v-model="card2">
      <q-card class="my-card w-[1200px] bg-slate-900">
        <q-img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQV2Ax-bQL5OYxJrLktkukBXHYxsBg-tLvdjA42RRv5RtGP4WY2LKHCqoqM6EtyVZxKDX4&usqp=CAU" />

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%)"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">Calvin Kleine</div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="place" />
              Bangladesh
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">$45</div>
          <div class="text-caption text-grey">Color: Black, White, Yellow.</div>
        </q-card-section>

        <q-separator />

        <q-card-actions align="right">
          <q-btn v-close-popup flat color="primary" label="close" />
        </q-card-actions>
      </q-card>
    </q-dialog>

    <!--card3-->
    <q-dialog v-model="card3">
      <q-card class="my-card w-[1200px] bg-slate-900">
        <q-img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR6OHfPCu7hf92ap8nkwpGvDb4OKF1tNM8NWg&usqp=CAU" />

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%)"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">White Chinese Cat</div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">$45</div>
          <div class="text-caption text-grey">Color: Black, White, Yellow.</div>
        </q-card-section>

        <q-separator />

        <q-card-actions align="right">
          <q-btn v-close-popup flat color="primary" label="close" />
        </q-card-actions>
      </q-card>
    </q-dialog>

    <!--card4-->
    <q-dialog v-model="card4">
      <q-card class="my-card w-[1200px] bg-slate-900">
        <q-img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQeSgeTCTDhBmWipolZWujtE4zWDvZlVEwdsA&usqp=CAU" />

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%)"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">White Chinese Cat</div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">$45</div>
          <div class="text-caption text-grey">Color: Black, White, Yellow.</div>
        </q-card-section>

        <q-separator />

        <q-card-actions align="right">
          <q-btn v-close-popup flat color="primary" label="close" />
        </q-card-actions>
      </q-card>
    </q-dialog>

    <!--card5-->
    <q-dialog v-model="card5">
      <q-card class="my-card w-[1200px] bg-slate-900">
        <q-img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSPKILlD0_n1Am5clRQxRefZ9prZxu3VX65hA&usqp=CAU" />

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%)"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">White Chinese Cat</div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">$45</div>
          <div class="text-caption text-grey">Color: Black, White, Yellow.</div>
        </q-card-section>

        <q-separator />

        <q-card-actions align="right">
          <q-btn v-close-popup flat color="primary" label="close" />
        </q-card-actions>
      </q-card>
    </q-dialog>

    <!--card6-->
    <q-dialog v-model="card6">
      <q-card class="my-card w-[1200px] bg-slate-900">
        <q-img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSPKILlD0_n1Am5clRQxRefZ9prZxu3VX65hA&usqp=CAU" />

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%)"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">White Chinese Cat</div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">$45</div>
          <div class="text-caption text-grey">Color: Black, White, Yellow.</div>
        </q-card-section>

        <q-separator />

        <q-card-actions align="right">
          <q-btn v-close-popup flat color="primary" label="close" />
        </q-card-actions>
      </q-card>
    </q-dialog>

    <!--card7-->
    <q-dialog v-model="card7">
      <q-card class="my-card w-[1200px] bg-slate-900">
        <q-img src="~src/assets/7.jpeg" />

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%)"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">White Chinese Cat</div>
            <div
              class="col-auto text-grey text-caption q-pt-md row no-wrap items-center"
            >
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">$45</div>
          <div class="text-caption text-grey">Color: Black, White, Yellow.</div>
        </q-card-section>

        <q-separator />

        <q-card-actions align="right">
          <q-btn v-close-popup flat color="primary" label="close" />
        </q-card-actions>
      </q-card>
    </q-dialog>

    <!--footer-->
    <footer class="bg-gray-800 text-white py-8">
  <div class="container mx-auto grid grid-cols-4 gap-8">
    <!-- Solutions -->
    <div class="mb-4 pl-3">
      <h3 class="text-xl font-bold mb-2">Solutions</h3>
      <ul>
        <li><a href="#">Marketing</a></li>
        <li><a href="#">Analytics</a></li>
        <li><a href="#">Commerce</a></li>
        <!-- Add more solution links as needed -->
      </ul>
    </div>

    <!-- Support -->
    <div class="mb-4">
      <h3 class="text-xl font-bold mb-2">Support</h3>
      <ul>
        <li><a href="#">Insights</a></li>
        <li><a href="#">Support</a></li>
        <!-- Add more support links as needed -->
      </ul>
    </div>

    <!-- Company -->
    <div class="mb-4">
      <h3 class="text-xl font-bold mb-2">Company</h3>
      <ul>
        <li><a href="#">About</a></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">Jobs</a></li>
        <!-- Add more company links as needed -->
      </ul>
    </div>

    <!-- Legal -->
    <div class="mb-4">
      <h3 class="text-xl font-bold mb-2">Legal</h3>
      <ul>
        <li><a href="#">Privacy</a></li>
        <li><a href="#">Terms</a></li>
        <li><a href="#">Claim</a></li>
        <!-- Add more legal links as needed -->
      </ul>
    </div>
  </div>

  <!-- Newsletter -->
  <div class="text-center mt-8">
    <h3 class="text-xl font-bold mb-2">Subscribe to our newsletter</h3>
    <p class="mb-4">The latest news, articles, and resources, sent to your inbox weekly.</p>
    <form class="flex items-center justify-center">
      <input type="email" class="py-2 px-4 mr-2 border border-gray-600 rounded focus:outline-none" placeholder="Enter your email">
      <button type="submit" class="bg-blue-500 text-white py-2 px-4 rounded hover:bg-blue-600 focus:outline-none">Subscribe</button>
    </form>
  </div>
</footer>



  </q-page>
</template>

<script>
import { defineComponent } from "vue";
import { ref } from "vue";

export default {
  name: "MyHorizontalScrollComponent",
  name: "IndexPage",

  setup() {
    return {
      slide: ref(1),

      carousel: ref(false),

      card1: ref(false),
      card2: ref(false),
      card3: ref(false),
      card4: ref(false),
      card5: ref(false),
      card6: ref(false),
      card7: ref(false),

      sliders: ref(false),

      //slide: ref(1),
      lorem:
        "Lorem ipsum dolor sit amet consectetur, adipisicing elit. Natus, ratione eum minus fuga, quasi dicta facilis corporis magnam, suscipit at quo nostrum!",

      stars: ref(3),

      slideVol: ref(39),
      slideAlarm: ref(56),
      slideVibration: ref(63),
      fitModes: ["cover"],
    };
  },
  data() {
    return {};
  },
};
</script>

<style lang="sass" scoped>



.example-item
  height: 290px
  width: 290px
</style>

<style>
@import "tailwindcss/base";
@import "tailwindcss/components";
@import "tailwindcss/utilities";

/*text color*/
@keyframes colorChange {
  0% {
    color: #48ff00; /* Start color (e.g., blue) */
  }
  50% {
    color: #ffc002; /* Middle color (e.g., orange) */
  }
  100% {
    color: #ffffff; /* End color (e.g., green) */
  }
}

#color-changing-text {
  animation: colorChange 2s infinite alternate; /* Adjust the duration and other properties as needed */
}
/*finish*/

@keyframes flip {
  from {
    transform: rotateY(0deg);
  }
  to {
    transform: rotateY(180deg);
  }
}

.flip-card {
  width: 90px;
  height: 90px;
}

.flip-card-inner {
  width: 100%;
  height: 100%;
  transform-style: preserve-3d;
  animation: flip 3s infinite alternate; /* Adjust the duration and other properties as needed */
}

.flip-card-front,
.flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
}

.flip-card-back {
  transform: rotateY(180deg);
}

.back-content {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 100%;
  background: linear-gradient(
    90deg,
    #010027,
    #6d87db
  ); /* Adjust background color as needed */
  border-radius: 50%;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.3); /* Add shadow for better visibility */
}

.back-content p {
  font-size: 14px; /* Adjust font size as needed */
  color: #fff700; /* Adjust text color as needed */
  font-weight: bold;
}
</style>
