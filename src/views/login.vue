<template >
    <div class="center">

        <v-row>
            <v-col cols="10" offset="1" sm="6" offset-sm="3" md="4" offset-md="4">
                <v-avatar color="surface-variant" rounded="0" size="100">
                    <v-img src="@/assets/logo.png"></v-img></v-avatar>
                <v-text-field label="Email address" placeholder="johndoe@gmail.com" type="email"
                    v-model="username"></v-text-field>
                <v-text-field label="password" type="password" v-model="password"></v-text-field>
                < <v-btn block @click="authenticate()" class="base-inverted">
                    Login
                    </v-btn>
            </v-col>
        </v-row>
    </div>
</template>

<script>
export default {
    data() {
        return {
            username: "",
            password: ""
        }
    },
    methods: {
        authenticate() {
            alert("Login clicked");

        }
    },
}
</script>

<style lang="scss" scoped></style>