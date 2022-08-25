class Furthersteps(player:Player){
  
  var board = new Array[String](9)
  def fill:Unit{
    if(board(position-1)== null)
    {
      board(position-2) = sign1
      print("Updated")
    }
    else
    print("Not Empty")
  }
}



class win(arr:Int){
  if(arr(0)==arr(1) && arr(1)=arr(2))
    print ("Player x Won")
  else if(arr(3)==arr(4) && arr(3)=arr(5))
    print ("Player x Won")
  else if(arr(6)==arr(7) && arr(6)=arr(8))
    print ("Player x Won")
  else if(arr(0)==arr(3) && arr(0)=arr(7))
    print ("Player x Won")
  else if(arr(1)==arr(4) && arr(1)=arr(7))
    print ("Player x Won")
  else if(arr(2)==arr(5) && arr(2)=arr(8))
    print ("Player x Won")
  else if(arr(0)==arr(4) && arr(0)=arr(8))
    print ("Player x Won")
  else if(arr(2)==arr(4) && arr(2)=arr(6))
    print ("Player x Won")
  
}
