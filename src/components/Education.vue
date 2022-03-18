<template>
    <div id="education">
        <div class="container">
            <div class="alert alert-success" role="alert">
                <h1 class="display-5">{{ msg }}</h1>
                
                <br>
                
                <h2 class="display-6">Philipine Science High School - Central Luzon Campus</h2>
                <p>STEM Strand (Specialization in Computer Science)</p>

                <br>

                <h2 class="display-6">Holy Angel University</h2>
                <p>Bachelor of Science in Information Technology - Web Development</p>

            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'education',
    data () {
        return {
            msg: 'Educational Background'
        }
    }
}
</script>