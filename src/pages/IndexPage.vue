
<!---->
<template>
  <q-page class="bg-gray-200">
    <div class="text-red-600 text-2xl text-bold ml-10 py-5">
      Upcoming Product
    </div>
    <div class="flex row gap-0 mx-10">

  <!--first card-->
  <q-card class="my-card col-3 flex px-3 pt-3 bg-slate-950 " label="Card" @click="card1 = true" >
      <img class="w-full h-48 object-cover" src="~src/assets/1.jpeg">

      <q-card-section class="text-white">
        <div class="text-h6">White Chinese Cat</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none text-white">
        <p>The Chinese mountain cat, also known as Chinese desert cat and Chinese steppe cat, is a small wild Felis species with sand-coloured fur, faint dark stripes on the face and legs and black tipped ears. It is endemic to the Tibetan Plateau of western China, where it lives in grassland above elevations of 2,500 m.</p>
      </q-card-section>
  </q-card>

  <!--second card-->
  <q-card class="my-card col-3 flex px-3 pt-3 bg-slate-950" label="Card" @click="card2 = true" >
      <img class="w-full h-48 object-cover" src="~src/assets/2.jpeg">

      <q-card-section class="text-white">
        <div class="text-h6">White Chinese Cat</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none text-white">
        <p>The Chinese mountain cat, also known as Chinese desert cat and Chinese steppe cat, is a small wild Felis species with sand-coloured fur, faint dark stripes on the face and legs and black tipped ears. It is endemic to the Tibetan Plateau of western China, where it lives in grassland above elevations of 2,500 m.</p>
      </q-card-section>
  </q-card>

  <!--third card-->
  <q-card class="my-card col-3 flex px-3 pt-3 bg-slate-950" label="Card" @click="card3 = true" >
      <img class="w-full h-48 object-cover" src="~src/assets/3.jpeg">

      <q-card-section class="text-white">
        <div class="text-h6">White Chinese Cat</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none text-white">
        <p>The Chinese mountain cat, also known as Chinese desert cat and Chinese steppe cat, is a small wild Felis species with sand-coloured fur, faint dark stripes on the face and legs and black tipped ears. It is endemic to the Tibetan Plateau of western China, where it lives in grassland above elevations of 2,500 m.</p>
      </q-card-section>
  </q-card>

  <!--fourth card-->
  <q-card class="my-card col-3 flex px-3 pt-3 bg-slate-950" label="Card" @click="card4 = true" >
      <img class="w-full h-48 object-cover" src="~src/assets/4.jpeg">

      <q-card-section class="text-white">
        <div class="text-h6">White Chinese Cat</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none text-white">
        <p>The Chinese mountain cat, also known as Chinese desert cat and Chinese steppe cat, is a small wild Felis species with sand-coloured fur, faint dark stripes on the face and legs and black tipped ears. It is endemic to the Tibetan Plateau of western China, where it lives in grassland above elevations of 2,500 m.</p>
      </q-card-section>
  </q-card>

  <!--fifth card-->
  <q-card class="my-card col-3 flex px-3 pt-3 bg-slate-950" label="Card" @click="card5 = true" >
      <img class="w-full h-48 object-cover" src="~src/assets/5.jpeg">

      <q-card-section class="text-white">
        <div class="text-h6">White Chinese Cat</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none text-white">
        <p>The Chinese mountain cat, also known as Chinese desert cat and Chinese steppe cat, is a small wild Felis species with sand-coloured fur, faint dark stripes on the face and legs and black tipped ears. It is endemic to the Tibetan Plateau of western China, where it lives in grassland above elevations of 2,500 m.</p>
      </q-card-section>
  </q-card>

  <!--sixth card-->
  <q-card class="my-card col-3 flex px-3 pt-3 bg-slate-950" label="Card" @click="card6 = true" >
      <img class="w-full h-48 object-cover" src="~src/assets/6.jpeg">

      <q-card-section class="text-white">
        <div class="text-h6">White Chinese Cat</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none text-white">
        <p>The Chinese mountain cat, also known as Chinese desert cat and Chinese steppe cat, is a small wild Felis species with sand-coloured fur, faint dark stripes on the face and legs and black tipped ears. It is endemic to the Tibetan Plateau of western China, where it lives in grassland above elevations of 2,500 m.</p>
      </q-card-section>
  </q-card>

  <!--seventh card-->
  <q-card class="my-card col-3 flex px-3 pt-3 bg-slate-950" label="Card" @click="card7 = true" >
      <img class="w-full h-48 object-cover" src="~src/assets/7.jpeg">

      <q-card-section class="text-white">
        <div class="text-h6">White Chinese Cat</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>

      <q-card-section class="q-pt-none text-white">
        <p>The Chinese mountain cat, also known as Chinese desert cat and Chinese steppe cat, is a small wild Felis species with sand-coloured fur, faint dark stripes on the face and legs and black tipped ears. It is endemic to the Tibetan Plateau of western China, where it lives in grassland above elevations of 2,500 m.</p>
      </q-card-section>
  </q-card>
</div>

     <!--card1-->
    <q-dialog v-model="card1">
      <q-card class="my-card w-[1200px] bg-slate-900">
        <div class="q-pa-md">
    <q-carousel
      swipeable
      animated
      v-model="slide"
      thumbnails
      infinite
    >
      <q-carousel-slide :name="1" img-src="~src/assets/1.jpeg" />
      <q-carousel-slide :name="2" img-src="~src/assets/2.jpeg" />
      <q-carousel-slide :name="3" img-src="~src/assets/3.jpeg" />
      <q-carousel-slide :name="4" img-src="~src/assets/4.jpeg" />
    </q-carousel>
  </div>

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%);"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">
              White Chinese Cat
            </div>
            <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">
            $45
          </div>
          <div class="text-caption text-grey">
            Color: Black, White, Yellow.
          </div>
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
        <q-img  src="~src/assets/2.jpeg" />

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%);"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">
              White Chinese Cat
            </div>
            <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">
            $45
          </div>
          <div class="text-caption text-grey">
            Color: Black, White, Yellow.
          </div>
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
        <q-img  src="~src/assets/3.jpeg" />

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%);"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">
              White Chinese Cat
            </div>
            <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">
            $45
          </div>
          <div class="text-caption text-grey">
            Color: Black, White, Yellow.
          </div>
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
        <q-img src="~src/assets/4.jpeg" />

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%);"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">
              White Chinese Cat
            </div>
            <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">
            $45
          </div>
          <div class="text-caption text-grey">
            Color: Black, White, Yellow.
          </div>
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
        <q-img src="~src/assets/5.jpeg" />

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%);"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">
              White Chinese Cat
            </div>
            <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">
            $45
          </div>
          <div class="text-caption text-grey">
            Color: Black, White, Yellow.
          </div>
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
        <q-img src="~src/assets/6.jpeg" />

        <q-card-section>
          <q-btn
            fab
            color="primary"
            icon="place"
            class="absolute"
            style="top: 0; right: 12px; transform: translateY(-50%);"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">
              White Chinese Cat
            </div>
            <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">
            $45
          </div>
          <div class="text-caption text-grey">
            Color: Black, White, Yellow.
          </div>
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
            style="top: 0; right: 12px; transform: translateY(-50%);"
          />

          <div class="row no-wrap items-center">
            <div class="col text-h6 ellipsis text-white">
              White Chinese Cat
            </div>
            <div class="col-auto text-grey text-caption q-pt-md row no-wrap items-center">
              <q-icon name="place" />
              China
            </div>
          </div>

          <q-rating v-model="stars" :max="5" size="32px" />
        </q-card-section>

        <q-card-section class="q-pt-none text-white">
          <div class="text-subtitle1">
            $45
          </div>
          <div class="text-caption text-grey">
            Color: Black, White, Yellow.
          </div>
        </q-card-section>

        <q-separator />

        <q-card-actions align="right">
          <q-btn v-close-popup flat color="primary" label="close" />

        </q-card-actions>
      </q-card>
    </q-dialog>

  </q-page>

</template>

<script>
import { defineComponent } from "vue";
import { ref } from 'vue';

export default ({
  name: "IndexPage",

  setup () {
    return {
      carousel: ref(false),
      
      card1: ref(false),
      card2: ref(false),
      card3: ref(false),
      card4: ref(false),
      card5: ref(false),
      card6: ref(false),
      card7: ref(false),

      sliders: ref(false),

      slide: ref(1),
      lorem: 'Lorem ipsum dolor sit amet consectetur, adipisicing elit. Natus, ratione eum minus fuga, quasi dicta facilis corporis magnam, suscipit at quo nostrum!',

      stars: ref(3),

      slideVol: ref(39),
      slideAlarm: ref(56),
      slideVibration: ref(63)
    }
  }
});
</script>

<style>
@import "tailwindcss/base";
@import "tailwindcss/components";
@import "tailwindcss/utilities";
</style>
