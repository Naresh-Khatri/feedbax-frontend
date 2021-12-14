<template>
    <router-link to="/feedback">
  <div class="item">
      <div class="item-content">
        <div class="text-h6 item-title">{{ title }}</div>
        <div class="text-caption item-description">{{ description }}</div>
      </div>
      <div class="item-image">
        <img
          width="150"
          src="https://avataaars.io/?avatarStyle=Transparent&topType=LongHairStraight&accessoriesType=Blank&hairColor=BrownDark&facialHairType=Blank&clotheType=BlazerShirt&eyeType=Default&eyebrowType=Default&mouthType=Default&skinColor=Light"
          alt=""
        />
      </div>
  </div>
    </router-link>
</template>

<script>
export default {
  data() {
    return {
      title: "How to stay safe on the internet",
      description: "Rahul kumar",
    };
  },
};
</script>

<style>
.item {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
  margin: 20px;
  color: white;
  border-radius: 20px;
  background: linear-gradient(to right, #222222, #2b0047);
}
a{
    text-decoration: none;
}
</style>
