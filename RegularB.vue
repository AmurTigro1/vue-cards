<template>
   
    <div :class="type">
        <!-- {{title}} -->
        <p class="title">{{ title }}</p>
    </div>
</template>

<script>

export default {
    props: {
        title: String,
        type: String //primary, danger, warning, success
    }
}

</script>

<style scoped>
/* .title {
    margin-top: 500px;
} */
.regular {
    background-color: #2686e7;
    border-color: #06386a;
}
.angry {
    background-color: #e72636;
    border-color: #6a0609;
}
.sad {
    background-color: #E9B824;
    border-color: #fbc729;
}
.happy {
    background-color: #11c839;
    border-color: #045e22;
}
div {
    padding: 10px;
  
    border-radius: 4px;
    
    margin: 8px 0;
    text-align: center;
}
.regM {
    background-color: #2686e7;
    border-color: #06386a;
    width: 434px;
    height: 150px;
}
.hapM {
   background-color: #E9B824;
    border-color: #fbc729;
    width: 434px;
    height: 150px;
}
.sadM {
    background-color: #11c839;
    border-color: #045e22;
    width: 434px;
    height: 150px;
}
.angM {
    background-color: #e72636;
    border-color: #6a0609;
    width: 434px;
    height: 150px;
}

</style>