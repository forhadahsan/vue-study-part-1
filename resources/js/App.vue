 <template>
  <div>
    <h5>HI, Friends</h5>

    <button @click="show = !show">Add Button</button>

    <div v-if="show">
      <p>👉 এটা হাইড করা কনটেন্ট, এখন দেখা যাচ্ছে!</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      show: false
    }
  }
};
</script>
