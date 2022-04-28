<template> 
  <div>
    <label for="todo-item">Token</label>
    <input type="text" name="tokeName" v-model="tokenName">
    
  </div>
</template>
<script>
  export default {
    name: 'SilentPublish',
    data() {
      return {
        tokenName: '',
      }
    }   
  };
</script>