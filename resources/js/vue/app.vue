<template>
  <div class="todoListContainer">
  	 <div class="heading">
  	   <h2 id = "title">
       hello
        <add-item-form/>
      </h2>
      	<list-view/>
     </div>

    
  </div>
</template>

<script>
import 	AddItemForm from './AddItemForm.vue'
import 	ListView from './ListView.vue'
export default {  
  components:{
  			AddItemForm,
  			ListView
  			}
}
</script>

<style>
.example {
  todoListContainer: red;
}
</style>