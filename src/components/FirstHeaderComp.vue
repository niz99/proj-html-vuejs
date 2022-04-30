<template>
    <div class="border-bottom">
        <div class="container d-flex justify-content-between c-grey">
            <div class="d-flex">
                <p class="me-2">English</p>
                <p>></p>
            </div>
            <div>
                <ul class="d-flex">
                    <li class="me-2">Home</li>
                    <li class="me-2">Pages</li>
                    <li class="me-2">Course Formats</li>
                    <li class="me-2">Courses</li>
                    <li class="me-2">Demos</li>
                </ul>
            </div>
        </div>
    </div>
    
</template>

<script>
export default {
  name: 'FirstHeaderComp'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

    li{
        list-style: none;
    }

    .c-grey{
        color: #c4c4c5
    }

</style>