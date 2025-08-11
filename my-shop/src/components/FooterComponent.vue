<template>
<div>
<h2>@2025 Всі права захищено</h2>
<ul>
<li>{{ email }} </li>
<li>{{ phone }} </li>
</ul>
<ul>
<li><a>{{ about }} </a></li>
<li><a> {{ delivery }} </a></li>
</ul>
</div>
</template>
<script>
export default {
    props: {
        email: String,
        phone: Number,
        about: String,
        delivery: String
    }
}
</script>