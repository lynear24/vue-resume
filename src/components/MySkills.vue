<template>
    <div id="my-skills">
        <div class="container">
            <div class="alert alert-dark" role="alert">
                <h1 class="display-5">{{ msg }}</h1>

                <ul class="list-group">
                    <li class="list-group-item">Computer Programming (C++, Python, Java)</li>
                    <li class="list-group-item">Web Development (HTML, CSS, Javascript, Vue, Bootstrap)</li>
                    <li class="list-group-item">Art</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'my-skills',
    data () {
        return {
            msg: 'Skillset'
        }
    }
}
</script>