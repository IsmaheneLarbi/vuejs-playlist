<template>
  <div>
      <footer>
          <p>{{copyright}} {{title}}</p>
      </footer>
  </div>
</template>

<script>

export default {
    props:{
        title:{
            type:String,
        },
    },
  data () {
    return {
        copyright:'Copyright of ',
    };
  },
}
</script>

<style scoped>
footer{
    background: #222;
    padding: 6px;
}
p{
    color:lightgreen;
    text-align: center;
}
</style>
