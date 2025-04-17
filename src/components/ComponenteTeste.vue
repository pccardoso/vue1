<template>
    <div>
        <label for="forNome">Nome do Usuário:</label> <br>
        <input type="text" v-model="formNome"> <br> <br>

        <button @click="eventoPai">Clique Aqui</button>
    </div>
</template>

<script>

    export default {
        name: "ComponenteTeste",
        data(){
            return{
                nome: "Paulo Cesar",
                formNome: ""
            }
        },
        methods:{

            eventoPai(){
                this.$emit("update-message", this.formNome)
            }

        }
    }

</script>