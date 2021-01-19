<template>
  <div class="todoListContainer">
  	 <div class="heading">
  	 <h2 id = "title">
      Todo List
       </h2>
        <add-item-form/>
      
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
  align : center;
}
.heading{
	width: 100%;
    height: 50%;
    background-color: gray;
    color: aquamarine;

}
</style>