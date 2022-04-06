<templated>
  <h3>{{ counter }}</h3>
</templated>

<script>
export default {
    computed: {
        counter() {
            return this.$store.state.counter;
        },
    },
};
</script>
