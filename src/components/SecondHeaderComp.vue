<template>
    <div class="container d-flex">
        <div>
            <img src="./../assets/images/MasterStudy.svg" alt="">
        </div>
        <div>
            <p>Category</p>
        </div>
        <div class="input-group mb-3">
            <input type="text" class="form-control" placeholder="Recipient's username" aria-label="Recipient's username" aria-describedby="basic-addon2">
            <span class="input-group-text" id="basic-addon2">cerca</span>
        </div>
        <div class="d-flex">
            <p>Become an Instructor</p>
            <p>For Enterprise</p>
        </div>
        <div>
            <p>Log in</p>
        </div>
        <div>
            <button type="button" class="btn c-coral-red">Sign Up</button>
        </div>

    </div>
</template>

<script>
export default {
  name: 'SecondHeaderComp'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

    .c-coral-red{
        background-color: #ff4550;
    }
</style>