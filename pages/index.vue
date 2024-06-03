<template>
  <v-app class="bg-grey-darken-2">
    <section class="pb-10">
      <v-app-bar :elevation="2" title="sleep" class="bg-red-darken-3">
        <v-btn to="/">Home</v-btn>
        <v-btn to="/about">about</v-btn>
      </v-app-bar>
    </section>
    <section class="py-10">
      <v-container>
        <!-- <div class="d-flex justify-center justify-space-between">
            <div class="bg-red div"></div>
            <div class="bg-pink div"></div>
          </div>
        
           
            <v-col></v-col>
            <v-col></v-col> -->

        <v-row align="center">
          <v-col cols="12" md="6">
            <v-img
              height="600"
              cover
              rounded
              src="https://i.pinimg.com/736x/2d/e1/64/2de1640eac60c7ac03be2b195fb68567.jpg"
            ></v-img>
          </v-col>
          <v-col cols="12" md="6">
            <h1>Trainer Profile ID</h1>
            <p>
              <p class="pt-5 pb-5">Name: RaiTheB0ar <br>Age: 16 <br>badges: 10 <br> No. of pokemon in party: six <br>
              Region orgion: Hoenn <br></p><p class="pt-10 pb-10"> Lorem ipsum dolor sit amet
              consectetur adipisicing elit. Doloribus deleniti tenetur maxime
              libero unde molestiae. Veritatis fugit molestiae vitae laboriosam
              voluptatem, autem nemo blanditiis deserunt ex, culpa quidem
              ratione odio.</p>
            </p>
            <v-btn to="/about" class="bg-red-darken-3">
              <v-icon>mdi-bed </v-icon>More</v-btn
            >
          </v-col>
        </v-row>
      </v-container>
    </section>
    <!-- card -->
    <section>
      <v-container>
        <v-row
          ><v-col cols="4">
            <v-card class="mx-auto" hover>
              <v-img
                class="align-end text-white"
                height="400"
                src="https://i.pinimg.com/236x/f5/7b/52/f57b524dc28954718fa40ef551f375c1.jpg"
                cover
              >
                <v-card-title
                  >Top 10 Australian beaches without the eac</v-card-title
                >
              </v-img>

              <v-card-subtitle class="pt-4 bg-black">
                its all Sam
              </v-card-subtitle>

              <v-card-text class="bg-black">
                <div>Whitehaven Beach without the each</div>

                <div>Its all Sam laming</div>
              </v-card-text>

              <v-card-actions class="bg-black">
                <v-btn color="red" text="Share"></v-btn>
                <v-btn color="red" text="Actually no he's mine"></v-btn>
              </v-card-actions>
            </v-card>
          </v-col>

          <v-col cols="4">
            <v-card class="mx-auto" hover>
              <v-img
                class="align-end text-white"
                height="400"
                src="https://i.pinimg.com/236x/35/78/71/357871e05af1cb83311c915c6dbcd5e8.jpg"
                cover
              >
                <v-card-title
                  >Top 10 Australian beaches without the eac</v-card-title
                >
              </v-img>

              <v-card-subtitle class="pt-4 bg-black">
                its all Sam
              </v-card-subtitle>

              <v-card-text class="bg-black">
                <div>Whitehaven Beach without the each</div>

                <div>Its all Sam laming</div>
              </v-card-text>

              <v-card-actions class="bg-black">
                <v-btn color="red" text="Share"></v-btn>
                <v-btn color="red" text="Actually no he's mine"></v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col cols="4">
            <v-card class="mx-auto" hover>
              <v-img
                class="align-end text-white"
                height="400"
                src="https://i.pinimg.com/236x/f2/80/4f/f2804f48cec276f685ec15de973e1858.jpg"
                cover
              >
                <v-card-title
                  >Top 10 Australian beaches without the eac</v-card-title
                >
              </v-img>

              <v-card-subtitle class="pt-4 bg-black">
                its all Sam
              </v-card-subtitle>

              <v-card-text class="bg-black">
                <div>Whitehaven Beach without the each</div>

                <div>Its all Sam laming</div>
              </v-card-text>

              <v-card-actions class="bg-black">
                <v-btn color="red" text="Share"></v-btn>
                <v-btn color="red" text="Actually no he's mine"></v-btn>
              </v-card-actions>
            </v-card>
          </v-col>

          <v-col cols="4">
            <v-card class="mx-auto" hover>
              <v-img
                class="align-end text-white"
                height="400"
                src="https://i.pinimg.com/236x/80/90/03/80900392221b7d5a47b726b8742e8b96.jpg"
                cover
              >
                <v-card-title
                  >Top 10 Australian beaches without the eac</v-card-title
                >
              </v-img>

              <v-card-subtitle class="pt-4 bg-black">
                its all Sam
              </v-card-subtitle>

              <v-card-text class="bg-black">
                <div>Whitehaven Beach without the each</div>

                <div>Its all Sam laming</div>
              </v-card-text>

              <v-card-actions class="bg-black">
                <v-btn color="red" text="Share"></v-btn>
                <v-btn color="red" text="Actually no he's mine"></v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col cols="4 ">
            <v-card class="mx-auto" hover>
              <v-img
                class="align-end text-white"
                height="400"
                src="https://i.pinimg.com/236x/4e/0b/1f/4e0b1f58ecd75ed3461ad57efc26729f.jpg"
                cover
              >
                <v-card-title
                  >Top 10 Australian beaches without the eac</v-card-title
                >
              </v-img>

              <v-card-subtitle class="pt-4 bg-black">
                its all Sam
              </v-card-subtitle>

              <v-card-text class="bg-black">
                <div>Whitehaven Beach without the each</div>

                <div>Its all Sam laming</div>
              </v-card-text>

              <v-card-actions class="bg-black">
                <v-btn color="red" text="Share"></v-btn>
                <v-btn color="red" text="Actually no he's mine"></v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col cols="4">
            <v-card class="mx-auto" hover>
              <v-img
                class="align-end text-white"
                height="400"
                src="https://i.pinimg.com/236x/2b/57/e1/2b57e1b8b49944e1b853493f34daeb22.jpg"
                cover
              >
                <v-card-title
                  >Top 10 Australian beaches without the eac</v-card-title
                >
              </v-img>

              <v-card-subtitle class="pt-4 bg-black">
                its all Sam
              </v-card-subtitle>

              <v-card-text class="bg-black">
                <div>Whitehaven Beach without the each</div>

                <div>Its all Sam laming</div>
              </v-card-text>

              <v-card-actions class="bg-black">
                <v-btn color="red" text="Share"></v-btn>
                <v-btn color="red" text="Actually no he's mine"></v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </section>
  </v-app>
</template>

<script setup>
</script>

<style scoped>
.div {
  height: 100px;
  width: 100px;
}
.everything {
  background-color: black;
}
</style>