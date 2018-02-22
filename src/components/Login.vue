<template>
<div class="container">
    <div class="row justify-content-center">

        <div class="card border-primary mb-3" >
            <div class="card-header">Login</div>
            <div class="card-body text-primary">
                <form>
                    <div class="form-group">
                        <input type="text" v-model="username" class="form-control" placeholder="Username">
                    </div>
                    <div class="form-group">
                        <input type="password" v-model="password" class="form-control" placeholder="Password">
                    </div>
                    <div class="form-group">
                        <button class="btn btn-raised btn-primary" v-on:click="doLogin">Login</button>
                    </div>
                </form>
            </div>
        </div>
    </div>
</div>
        
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  methods: {
    doLogin (): void {
      alert('ok!')
    }
  }
})
</script>


