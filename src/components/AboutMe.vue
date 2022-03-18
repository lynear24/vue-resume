<template>
    <div id="about-me" class="mb-5">
        <div class="card mx-auto" style="width: 400px;">
            <img src="../assets/profile.png" alt="" class="card-img-">
            <div class="card-body">
                <h5 class="card-title display-6 mb-3">{{ msg }}</h5>
                
                <p class="card-text"></p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'about-me',
    data () {
        return {
            msg: "Hi, I'm Nyle, a BS IT undergrad specializing in Web Development."
        }
    }
}
</script>