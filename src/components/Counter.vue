<template>
    <div>
        <button class="btn btn-primary" @click="increment">Increment</button>
        <button class="btn btn-primary" @click="decrement">Decrement</button>
    </div>
</template>

<script>
    
    import { mapMutations } from 'vuex';
    
    export default {
        
        methods: {
            
            ...mapMutations ([
                
                'increment',
                'decrement'
                
            ])
            
            //increment() {
                
                //this.$store.commit('increment');
                
                ////this.$store.state.counter++;
                
            //},
            
            //decrement() {
                
                //this.$store.commit('decrement');
                
                ////this.$store.state.counter--;
                
            //}
            
        }
        
    }
    
</script>