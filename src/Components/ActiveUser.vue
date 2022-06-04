<template>
    <section>
        <header>
            <h1>{{ username}}</h1>
            <h3>{{ userage}} Years</h3>
        </header>
    </section>
</template>

<script>

export default {

props : {
    
    username : {
        type : String,
        required : true
    },
    userage : {
        type : Number,
        required : true
    },
}

  
}

</script>



