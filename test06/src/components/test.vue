<template>
    <h1>{{msg}}</h1>
</template>
<script>
/*eslint-disable*/
export default{
    name:'test',
    props:{
        msg:String,
          title: String,
  likes: Number,
  isPublished: Boolean,
  commentIds: Array,
  author: Object,
  callback: Function,
  contactsPromise: Promise
    }
    
}
</script>
