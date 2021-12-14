<template>
  <q-page class="text-white">
    <div class="q-pa-md flex row">
      <img
        class="col"
        style="
          width: 100px;
          height: 100px;
          border-radius: 50%;
          margin-right: 20px;
        "
        width="150"
        src="https://avataaars.io/?avatarStyle=Transparent&topType=LongHairStraight&accessoriesType=Blank&hairColor=BrownDark&facialHairType=Blank&clotheType=BlazerShirt&eyeType=Default&eyebrowType=Default&mouthType=Default&skinColor=Light"
        alt=""
      />
      <div class="col text-h4">Rate this speaker</div>
    </div>
    <q-card>
      <q-card-section class="bg-dark">
        <div class="text-h5"> Did you understand the basic idea? </div>
        <q-rating
          v-model="rating1"
          max="5"
          size="3em"
          color="yellow"
          icon="star_border"
          icon-selected="star"
          icon-half="star_half"
          no-dimming
        />
      </q-card-section>
      <q-card-section class="bg-dark">
        <div class="text-h5"> Slides </div>
        <q-rating
          v-model="rating1"
          max="5"
          size="3em"
          color="yellow"
          icon="star_border"
          icon-selected="star"
          icon-half="star_half"
          no-dimming
        />
      </q-card-section>
      <q-card-section class="bg-dark">
        <div class="text-h5"> Fluency </div>
        <q-rating
          v-model="rating2"
          max="5"
          size="3em"
          color="yellow"
          icon="star_border"
          icon-selected="star"
          icon-half="star_half"
          no-dimming
        />
      </q-card-section>
      <q-card-section class="bg-dark">
        <div class="text-h5"> Slides </div>
        <q-rating
          v-model="rating1"
          max="5"
          size="3em"
          color="yellow"
          icon="star_border"
          icon-selected="star"
          icon-half="star_half"
          no-dimming
        />
      </q-card-section>
    </q-card>
  </q-page>
</template>

<script>
export default {
  name: "PageIndex",
  components: {},
  data() {
    return {
      rating1: 0,
      rating2: 0,
      rating3: 0,
      rating4: 0,
    };
  },
};
</script>
