# My-functions

1.- - - - - - - - - - - - - - - - - - - - - - - - - - - -my bind- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

function bind(obj, fn){
 return function(){
     let newproto = Object.assign({}, obj)
     newproto.fn = fn
     return(newproto.fn())
  }
}



- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
