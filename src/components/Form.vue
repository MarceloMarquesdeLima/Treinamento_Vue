<template>
    <div>
        <form action="">
            <h1>Meu Formulário</h1>
            <div>
                <InputText />
            </div> <br />
            <div>
                <InputText />
            </div> <br />
            <div>
                <Submit />
            </div>
        </form>
    </div>
</template>

<script>
    import InputText from './form/inputText.vue'
    import Submit from './form/Submit.vue'

    export default {
        name: 'Form',
        components: {
            InputText,
            Submit
        }
    }
</script>