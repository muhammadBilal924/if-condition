<template>
    <div>
      <h1>Conditional Rending in vue js</h1>  
    </div>
</template>
<script>
export default  {
      name:'if-condition',
      props:{
          data:String,
          msg:String,
      },data()
      {
          return{show:true}
      },
      methods:{
      display()
      {
          this.show=!this.show
      }
      }  
    
}
</script>